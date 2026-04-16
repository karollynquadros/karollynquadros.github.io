---
layout: page
title: Home
---

# {{ site.data.profile.name }}

**{{ site.data.profile.position }}**

{{ site.data.profile.location }} | [{{ site.data.profile.email }}](mailto:{{ site.data.profile.email }}) | {{ site.data.profile.phone }}

---

## About Me

{{ site.data.profile.bio }}

---

## Education

{% for edu in site.data.profile.education %}
### {{ edu.degree }}
**{{ edu.institution }}** | {{ edu.year }}
- {{ edu.details }}

{% endfor %}

---

## Research Interests

{% for interest in site.data.profile.research_interests %}
- {{ interest }}
{% endfor %}

---

## Technical Skills

{% for skill in site.data.profile.technical_skills %}
- {{ skill }}
{% endfor %}

---

## Languages

{% for lang in site.data.profile.languages %}
- {{ lang }}
{% endfor %}

---

## 🏆 Honors & Awards

- **Gold Medal** - UFPR (2024) - First place in class at graduation ceremony
- **Scientific Initiation Award** - UFPR (2023) - Internal Waves Research
- **Maximum Grade in Capstone Project** - UFPR (2024) - Final Projects I & II
- **Conference Award** - SBRH (2023) - Floating Photovoltaic Panels Research
---

## Connect

- [GitHub](https://github.com/{{ site.data.profile.social.github }})
- [LinkedIn](https://linkedin.com/in/{{ site.data.profile.social.linkedin }})
- [Email](mailto:{{ site.data.profile.social.email }})
