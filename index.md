---
title:  ""
---

- ✉️ [vit@kutny.cz](mailto:vit@kutny.cz)
- 📱 [+420 605 531 830](tel:+420605531830)

---

- 💼 [LinkedIn](https://www.linkedin.com/in/vitkutny)
- 📖 [Facebook](https://facebook.com/vitkutny)
- 📷 [Instagram](https://www.instagram.com/vitkutny)

---

{% for post in site.posts %} - `{{ post.date | date: "%Y-%m-%d" }}` [{{ post.title }}]({{ post.url }})
{% endfor %}
