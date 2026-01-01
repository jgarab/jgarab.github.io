---
layout: default
title: Home
---

# József Garab

<span class="badge">University Lecturer</span>
<span class="badge">Simulation / FEA</span>
<span class="badge">Wood & Timber Engineering</span>
<span class="badge">Quality Management</span>

I am an associate professor at the University of Sopron (Hungary). Currently, I serve as a Head of Institute of the Institute of the Applied Sciences at the University of Sopron. 
My work focuses on numerical simulation (FEA) in wood-based materials and structures, and data-driven analytics for manufacturing related fields (e.g.: manufacturing, quality management, industrial engineering, management decision support)

**Interests:** structural mechanics, anisotropic materials, timber structures, data analysis

- Email: `garab.jozsef@uni-sopron.hu`
- LinkedIn: <https://www.linkedin.com/in/jozsefgarab/>
- GitHub: <https://github.com/jgarab>
- University of Sopron: <https://international.uni-sopron.hu/home>
- 

---

## Quick links
- [CV](/cv)
- [Publications](/publications)
- [Teaching](/teaching)
- [Projects](/projects)

---

## Latest posts
{% for post in site.posts limit:5 %}
- **{{ post.date | date: "%Y-%m-%d" }}:** [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
