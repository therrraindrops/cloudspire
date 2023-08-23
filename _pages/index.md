---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to Cloudspire.

<p style="padding: 3em 1em; background: #505050; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Table of Contents]]</span> to get started.
</p>

![whisper.jpg](/assets/whisper.jpg)

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
