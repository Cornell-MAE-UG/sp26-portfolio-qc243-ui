---
layout: default
title: Projects
permalink: /projects/
---

<style>
body,
h1,
p,
a {
  font-family: "Times New Roman", Times, serif;
}

body {
  background-color: #fff5f8;
}

h1 {
  text-align: center;
  color: #b85c7a;
  font-size: 3rem;
  margin-bottom: 2rem;
}

.gallery-container {
  max-width: 700px;
  margin: 0 auto;
  padding: 2rem;
}

.project-gallery {
  display: flex;
  justify-content: center;
}

.gallery-item {
  background: #ffe8ef;
  border-radius: 18px;
  overflow: hidden;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  width: 100%;
  max-width: 500px;
}

.gallery-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
}

.gallery-item img {
  width: 100%;
  height: auto;
  display: block;
}

.gallery-item p {
  text-align: center;
  padding: 1rem;
  margin: 0;
  color: #8a3d5d;
  font-size: 1.4rem;
  font-weight: bold;
}

.gallery-item a {
  text-decoration: none;
}
</style>

<h1>Projects</h1>

<div class="gallery-container">
  <div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>