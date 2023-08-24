---
layout: page
title: Home
id: home
permalink: /
---



<p style="padding: 3em 1em; background: #505050; border-radius: 4px;">
  <em>Smoke and steam rise from mining vents as the city wakes up. Soon, rolling mountaintop fog shrouds the morning commute, turning the flickering electroplasm lanterns into haunting distant sprites. Foot, boat, and carriage traffic dances around the caldera and its seven bridges. Plots, schemes, and ambitions drip through the city from its tallest spire to the deepest depths of the mines below. The city endures; too valuable to be backwater, too distant to be relevant:</em>
<br><br>
<strong>Welcome to Cloudspire.</strong>
</p>

![whisper.jpg](/assets/whisper.jpg)


# [[Table of Contents]]

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>


<style>
  .wrapper {
    max-width: 46em;
  }
</style>
