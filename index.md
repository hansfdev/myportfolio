---
layout: default
title: Home
---
<div>
  <h1>{{ "Hello World!"}}</h1>

  <ul>
    {% for project in site.projects %}
      <li>
        <h2><a href="{{ project.url | relative_url }}">{{ project.name }}</a></h2>
        <h3>{{ project.type }}</h3>
        <p>Release date: {{ project.release_date }}</p>
        <p> {{ project.summary }} </p>
      </li>
    {% endfor %}
  </ul>
</div>