---
title: <% tp.file.title %>
note_type: atomic
topic: 
summary: 
source: 
tags: []
related_project: []
created: <% tp.date.now("YYYY-MM-DD") %>
---
# <% tp.frontmatter.title %>

- 🧠 Summary: <% tp.frontmatter.summary %>

- 📚 Source: <% tp.frontmatter.source %>

- 📂 Related Projects:
		<%* tp.frontmatter.related_project?.forEach(project => {
	  tR += `- [[${project}]]\n`
		}) %>

---

# 💡 Core Idea

- (Express the meaning of this idea in your own words)

# 🔗 Extended Links (Optional)

