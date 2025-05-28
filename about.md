---
layout: page
title: About
permalink: /about/
---

<div class="about-hero">
  <h1>About Me</h1>
  <p class="lead">Bridging the worlds of sound engineering, artificial intelligence, and forensic science</p>
</div>

<div class="about-content">
  <section class="bio-section">
    <h2>Professional Journey</h2>
    <p>
      My career represents a unique intersection of technology, science, and justice. As a Forensic Acoustics Expert with Colombia's Fiscalía General de la Nación, I apply cutting-edge signal processing and AI techniques to solve complex cases involving audio evidence.
    </p>
    
    <p>
      What drives me is the potential to use technology for meaningful impact—whether it's enhancing audio evidence that helps deliver justice, developing new tools for forensic analysis, or advancing the field through research and education.
    </p>
  </section>

  <section class="education-section">
    <h2>Education & Continuous Learning</h2>
    <div class="education-grid">
      <div class="education-item">
        <h3>Master's in Electronic Engineering</h3>
        <p><strong>Pontificia Universidad Javeriana</strong> (In Progress)</p>
        <p>Specializing in audio manipulation detection for forensic applications</p>
      </div>
      
      <div class="education-item">
        <h3>Master's in Artificial Intelligence</h3>
        <p><strong>Completed with Academic Excellence</strong></p>
        <p>Recognized for outstanding thesis quality</p>
      </div>
      
      <div class="education-item">
        <h3>Sound Engineering Degree</h3>
        <p>Foundation in audio technology and signal processing</p>
      </div>
    </div>
  </section>

  <section class="expertise-section">
    <h2>Areas of Expertise</h2>
    <div class="expertise-grid">
      <div class="expertise-item">
        <h3>🔍 Forensic Audio Analysis</h3>
        <ul>
          <li>Audio enhancement and restoration</li>
          <li>Speaker recognition and verification</li>
          <li>Audio authenticity assessment</li>
          <li>Voice comparison analysis</li>
        </ul>
      </div>
      
      <div class="expertise-item">
        <h3>🤖 AI & Signal Processing</h3>
        <ul>
          <li>Machine learning for audio applications</li>
          <li>Digital signal processing algorithms</li>
          <li>Audio manipulation detection</li>
          <li>Pattern recognition in audio signals</li>
        </ul>
      </div>
      
      <div class="expertise-item">
        <h3>🎓 Education & Training</h3>
        <ul>
          <li>University-level course instruction</li>
          <li>Professional training programs</li>
          <li>Conference presentations</li>
          <li>Research supervision</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="philosophy-section">
    <h2>Research Philosophy</h2>
    <p>
      I believe in the power of interdisciplinary research. By combining sound engineering principles with artificial intelligence and forensic science, we can develop more robust, accurate, and reliable tools for audio analysis. My work focuses on practical applications that can make a real difference in forensic investigations while advancing our scientific understanding of audio processing.
    </p>
  </section>

  <section class="collaboration-section">
    <h2>Collaboration & Future Goals</h2>
    <p>
      I'm passionate about collaborative research and always open to working with fellow researchers, institutions, and organizations on projects that advance the field of forensic acoustics and AI applications in audio processing.
    </p>
    
    <p>
      Whether you're interested in research collaboration, consulting on forensic audio cases, or discussing the latest developments in AI and audio processing, I'd love to connect.
    </p>
    
    <div class="contact-cta">
      <a href="mailto:{{ site.author.email }}" class="btn btn-primary">Let's Connect</a>
    </div>
  </section>
</div>

<style>
.about-hero {
  text-align: center;
  padding: 3rem 0;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin-bottom: 3rem;
}

.about-hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: 300;
}

.lead {
  font-size: 1.2rem;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto;
}

.about-content {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 2rem;
}

.about-content section {
  margin-bottom: 3rem;
}

.about-content h2 {
  color: #333;
  margin-bottom: 1.5rem;
  font-size: 1.8rem;
}

.education-grid, .expertise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.education-item, .expertise-item {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.education-item h3, .expertise-item h3 {
  color: #667eea;
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

.expertise-item ul {
  list-style: none;
  padding: 0;
}

.expertise-item li {
  padding: 0.5rem 0;
  border-bottom: 1px solid #eee;
  position: relative;
  padding-left: 1.5rem;
}

.expertise-item li:before {
  content: "→";
  position: absolute;
  left: 0;
  color: #667eea;
  font-weight: bold;
}

.philosophy-section {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  border-left: 4px solid #667eea;
}

.contact-cta {
  text-align: center;
  margin-top: 2rem;
}

.btn {
  display: inline-block;
  padding: 0.75rem 2rem;
  background: #667eea;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
  transition: all 0.3s ease;
}

.btn:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .about-hero h1 {
    font-size: 2rem;
  }
  
  .education-grid, .expertise-grid {
    grid-template-columns: 1fr;
  }
  
  .about-content {
    padding: 0 1rem;
  }
}
</style>
