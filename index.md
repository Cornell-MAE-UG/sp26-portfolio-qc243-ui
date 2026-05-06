---
layout: default
title: Lisa Chen
---
<style>

body,
h1,
h2,
p,
a {
  font-family: "Times New Roman", Times, serif;
}

body {
  background-color: #fff7fa;
  line-height: 1.8;
}

.profile-container {
  max-width: 1000px;
  margin: 3rem auto;
  background: #fff0f5;
  border-radius: 20px;
  padding: 3rem;
  box-shadow: 0 4px 18px rgba(0,0,0,0.08);
}

.profile-header {
  text-align: center;
  margin-bottom: 2rem;
}

.profile-header h1 {
  color: #b85c7a;
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.profile-content {
  display: flex;
  align-items: center;
  gap: 3rem;
  flex-wrap: wrap;
  justify-content: center;
}

.profile-image {
  width: 280px;
  height: 280px;
  object-fit: cover;
  border-radius: 18px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.12);
}

.bio-text {
  flex: 1;
  min-width: 280px;
}

.bio-text p {
  font-size: 1.1rem;
  color: #333;
}

.links {
  margin-top: 1.5rem;
}

.links a {
  display: inline-block;
  margin-right: 1rem;
  padding: 0.7rem 1.2rem;
  background-color: #f5cad8;
  color: #8a3d5d;
  border-radius: 10px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.2s ease;
}

.links a:hover {
  background-color: #efb7ca;
  transform: translateY(-2px);
}
</style>

<div class="profile-container">

  <div class="profile-header">
    <h1>Lisa Chen</h1>
  </div>

  <div class="profile-content">

<img 
    src="{{ 'assets/images/profile_pic.PNG'}}" 
    alt="Profile Picture"
    class="profile-image"
>

    <div class="bio-text">

My name is {{ site.name }}, and I am a motivated and curious individual with a strong interest in problem-solving, innovation, and continuous learning.

I’m passionate about turning ideas into practical solutions and enjoy combining analytical thinking with creativity to tackle real-world challenges. Whether working independently or collaborating with a team, I value clear communication, thoughtful design, and meaningful impact.

I’m always eager to expand my knowledge, take on new challenges, and contribute in ways that make a difference.

<div class="links">
  <a href="{{ '/projects/' | relative_url }}">my projects</a>
  <a href="{{ '/cv/' | relative_url }}">CV</a>
</div>

    </div>
  </div>
</div>