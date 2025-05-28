---
layout: page
title: Projects
permalink: /projects/
---

<div class="projects-header">
  <h1>My Projects</h1>
  <p>Explore my work in forensic acoustics, AI applications, and audio processing research.</p>
</div>

<div class="projects-grid">
  {% for project in site.projects %}
  <div class="project-card">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
    {% if project.technologies %}
    <div class="technologies">
      {% for tech in project.technologies %}
        <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
    {% endif %}
  </div>
  {% endfor %}
</div>

{% if site.projects.size == 0 %}
<div class="empty-state">
  <h3>🚧 Projects Coming Soon</h3>
  <p>I'm currently working on documenting my research projects and tools. Check back soon for updates on:</p>
  <ul>
    <li>Forensic audio analysis tools</li>
    <li>AI-powered audio authentication systems</li>
    <li>Signal processing applications</li>
    <li>Speaker recognition algorithms</li>
  </ul>
</div>
{% endif %}

<style>
.projects-header {
  text-align: center;
  margin-bottom: 3rem;
  padding: 2rem 0;
}

.projects-header h1 {
  color: #333;
  margin-bottom: 1rem;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.project-card {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 20px rgba(0,0,0,0.15);
}

.project-card h3 {
  margin-bottom: 1rem;
}

.project-card h3 a {
  color: #667eea;
  text-decoration: none;
}

.project-card h3 a:hover {
  text-decoration: underline;
}

.technologies {
  margin-top: 1rem;
}

.tech-tag {
  display: inline-block;
  background: #667eea;
  color: white;
  padding: 0.25rem 0.5rem;
  border-radius: 4px;
  font-size: 0.8rem;
  margin: 0.25rem 0.25rem 0 0;
}

.empty-state {
  text-align: center;
  padding: 3rem;
  background: #f8f9fa;
  border-radius: 8px;
  margin: 2rem 0;
}

.empty-state h3 {
  color: #667eea;
  margin-bottom: 1rem;
}

.empty-state ul {
  text-align: left;
  max-width: 400px;
  margin: 0 auto;
}

.empty-state li {
  padding: 0.5rem 0;
}
</style>
