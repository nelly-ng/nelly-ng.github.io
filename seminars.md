---
title: Seminars
permalink: /seminars/
---

## inQlings Seminar Series

Our seminar series explores topics related to quantum information, thermodynamics, and the foundations of physics.

### Watch the full playlist

<iframe width="900" height="506"
src="https://www.youtube.com/embed/videoseries?list=PL3z0iE0Y9E06T93AZBhWuL21oWS0DK6F9"
frameborder="0"
allowfullscreen>
</iframe>

---

### Latest seminars

{% for talk in site.data.talks %}
- **{{ talk.title }}**  
  {{ talk.speaker }}  
  {{ talk.date }}

  <iframe width="560" height="315"
  src="https://www.youtube.com/embed/{{ talk.youtube }}"
  frameborder="0"
  allowfullscreen></iframe>

{% endfor %}
