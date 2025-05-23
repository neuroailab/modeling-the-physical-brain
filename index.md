---
layout: default
title: Home
---

# Modeling the Physical Brain  
**Spatial Organization and Biophysical Constraints**

<!-- Your event description here -->
Lorem ipsum dolor sit amet…

--
## Organizers

<div class="organizers-grid">
  {% for org in site.data.organizers %}
    <div class="organizer-card">
      <img src="{{ org.photo | relative_url }}" alt="{{ org.name }}" />
      <p>{{ org.name }}</p>
    </div>
  {% endfor %}
</div>