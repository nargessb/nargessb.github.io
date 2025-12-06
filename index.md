---
layout: home
title: "Narges Babadi"
author_profile: true
header:
  overlay_color: "#000"
  overlay_filter: "0.15"
---

# 👋 About Me

I am **Narges Babadi**, a PhD researcher in **AI Security, Adversarial Machine Learning, Explainability, and Vision–Language Models**.  
My research focuses on *explainability attacks, robustness, multimodal reasoning*, and *secure AI systems*.

---

# 🔬 Latest Projects

{% for post in site.categories.projects limit: 3 %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.excerpt }}
{% endfor %}

[➡️ View all projects](/projects/)

---

# 📚 Latest Publications

{% for post in site.categories.publications limit: 3 %}
- **{{ post.title }}**  
  *{{ post.venue }}*  
{% endfor %}

[➡️ View all publications](/publications/)
