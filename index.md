---
layout: default
title: Home
---
<div class="maincontent">
  <p> Hello there! Welcome to my web portfolio, here you can find detailed information about my professional and personal experience, as well as some information about myself.</p>

  <h1>Professional Projects</h1>

  <div class="projectviewer">
    <ul>
      {% for project in site.projects %}
        {% if project.type == "professional" %}
        <li>
          <div class="projectcontainer" onclick="window.location='{{ project.url | relative_url }}'">
            <img src="{{ project.imageurl | relative_url }}" class="projectimage">
            <div class="projectpreview">
              <div>
                <h2><a href="{{ project.url | relative_url }}">{{ project.name }}</a></h2>
                <!-- <h3>{{ project.type }}</h3> -->
                <p>Release: {{ project.release_date }}</p>
                <p> {{ project.summary }} </p>
              </div>
            </div>
          </div>
        </li>
        {% endif %}
      {% endfor %}
    </ul>
  </div>

  <h1>Personal Projects</h1>

  <div class="projectviewer">
    <ul>
      {% for project in site.projects %}
        {% if project.type == "personal" %}
        <li>
          <div class="projectcontainer" onclick="window.location='{{ project.url | relative_url }}'">
            <img src="{{ project.imageurl | relative_url }}" class="projectimage">
            <div class="projectpreview">
              <div>
                <h2><a href="{{ project.url | relative_url }}">{{ project.name }}</a></h2>
                <!-- <h3>{{ project.type }}</h3> -->
                <p>Release date: {{ project.release_date }}</p>
                <p> {{ project.summary }} </p>
              </div>
            </div>
          </div>
        </li>
        {% endif %}
      {% endfor %}
    </ul>
  </div>
</div>