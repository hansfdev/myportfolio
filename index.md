---
layout: default
title: Home
---

<h1>Professional Projects</h1>

<div class="projectviewer">
  <ul>
    {% for project in site.projects %}
      <li>
        <div>
          <h2><a href="{{ project.url | relative_url }}">{{ project.name }}</a></h2>
          <h3>{{ project.type }}</h3>
          <p>Release date: {{ project.release_date }}</p>
          <p> {{ project.summary }} </p>
        </div>
      </li>
    {% endfor %}
  </ul>
</div>
