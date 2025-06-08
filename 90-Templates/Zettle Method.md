---
title: <% tp.file.title %>
note_type: zettel
zettel_id: <% tp.date.now("YYYYMMDDHHmmss") %>
topic: 
tags: 
related_cards: 
created: <% tp.date.now("YYYY-MM-DD") %>
---
- <% tp.frontmatter.title %> (Card ID: <% tp.frontmatter.zettel_id %>)

- 🧭 Topic: <% tp.frontmatter.topic %>  
- 🧩 Related Cards:
	<%* tp.frontmatter.related_cards?.forEach(card => {
	  tR += `- [[${card}]]\n`
	}) %>

---

# 🧠 Idea Content

- (Write your thoughts, interpretations, or conceptual rephrasing here)

# ❓ Questions & Reasoning

- What does this imply?
- How does it relate to other concepts?
- Are there alternative views or contradictions?

# 🔄 Next Step (Optional)

- Should this card be developed into an article?
- Should it link to a Cornell note or atomic note?
