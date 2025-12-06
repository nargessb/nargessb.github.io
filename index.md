---
layout: home
author_profile: true
---

Hi, This is Narges Babadi, a PhD researcher in Electrical and Software Engineering.My research focuses on AI Security, Adversarial Machine Learning, and Vision–Language Models.  

---

# Latest Projects

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
