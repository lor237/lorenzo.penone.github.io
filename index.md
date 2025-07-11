---
layout: default
title: Home
permalink: /
---

<!-- Hero -->
# Hello, I’m **Lorenzo**  
_Evolutionary biologist & no-code enthusiast._

![Profile photo](/assets/me.jpg){: style="width:150px;border-radius:50%" }

---

<!-- About Me -->
## About Me  
I’m a researcher in evolutionary biology with experience in bioinformatics and science communication.  

---

<!-- Key Projects -->
## Key Projects  
- **EvoMap** – A platform for mapping phylogenetic relationships.  
- **GenomeViz** – A genomic visualization tool.  
- **Science Blog** – Articles on evolution and genetics.

---

<!-- Blog Preview -->
## Latest from the Blog  
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[→ Visit the blog](/blog/)  

---

<!-- Contact -->
## Contact  
- 📫 Email: lorenzo@example.com  
- 🔗 GitHub: [@your-username](https://github.com/your-username)  
- 🐦 Twitter: [@your_handle](https://twitter.com/your_handle)
