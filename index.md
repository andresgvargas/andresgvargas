---
layout: default
---

<div class="hero-section">
  <div class="hero-content">
    <h1 class="hero-title">Hi there! 👋 I'm {{ site.author.name }}</h1>
    <p class="hero-subtitle">Forensic Acoustics Expert | AI & Audio Processing Researcher | Sound Engineer</p>
    
    <div class="contact-info">
      <p>🔍 <strong>Location:</strong> {{ site.author.location }}</p>
      <p>📧 <strong>Email:</strong> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></p>
      <p>🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank">{{ site.author.linkedin }}</a></p>
      <p>💻 <strong>GitHub:</strong> <a href="https://github.com/{{ site.author.github }}" target="_blank">{{ site.author.github }}</a></p>
    </div>
  </div>
</div>

<div class="content-sections">
  <section class="about-section">
    <h2>🎓 Academic Background</h2>
    <p>I hold degrees in Sound Engineering and have recently completed a Master's in Artificial Intelligence. Currently, I am pursuing another Master's in Electronic Engineering at Pontificia Universidad Javeriana, focusing on audio manipulation detection in forensic cases.</p>
  </section>

  <section class="experience-section">
    <h2>👨‍💼 Professional Experience</h2>
    <p>As a Forensic Acoustics Expert with the Fiscalía General de la Nación in Colombia, I specialize in audio enhancement, speaker recognition, and audio authenticity assessments. My work includes national training and research in audio engineering.</p>
  </section>

  <section class="research-section">
    <h2>🔬 Research and Innovation</h2>
    <p>My research interests lie in signal processing and AI applications in forensic audio. I have developed tools used in my laboratory for forensic analysis.</p>
  </section>

  <section class="honors-section">
    <h2>🏅 Honors</h2>
    <p>Awarded for my master's thesis's academic quality, I've also been recognized for my achievements in judicial police training.</p>
  </section>

  <section class="teaching-section">
    <h2>🧑‍🏫 Teaching Experience</h2>
    <p>I've taught various courses in the Sound Engineering program at Universidad de San Buenaventura, including programming languages and applied audio programming.</p>
  </section>

  <section class="speaking-section">
    <h2>📢 Speaking Engagements</h2>
    <p>I've presented on Forensic Acoustics across various national platforms, sharing insights and developments in the field.</p>
  </section>

  <section class="skills-section">
    <h2>👨‍🔧 Skills</h2>
    <div class="skills-grid">
      <div class="skill-category">
        <h3>Programming</h3>
        <ul>
          <li>Python</li>
          <li>MATLAB</li>
          <li>LabVIEW</li>
        </ul>
      </div>
      <div class="skill-category">
        <h3>Audio Tools</h3>
        <ul>
          <li>Adobe CC</li>
          <li>MaxMSP</li>
          <li>Sound Processing Tools</li>
        </ul>
      </div>
      <div class="skill-category">
        <h3>Specializations</h3>
        <ul>
          <li>Signal Processing</li>
          <li>AI Applications</li>
          <li>Forensic Audio Analysis</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="collaboration-section">
    <h2>🤝 Let's Collaborate</h2>
    <p>I'm always looking to collaborate on projects involving sound technology and AI. If you have an idea or a project that aligns with my skills, don't hesitate to reach out!</p>
    <div class="cta-buttons">
      <a href="mailto:{{ site.author.email }}" class="btn btn-primary">Get In Touch</a>
      <a href="/projects" class="btn btn-secondary">View Projects</a>
    </div>
  </section>
</div>

<style>
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 4rem 0;
  text-align: center;
  margin-bottom: 3rem;
}

.hero-content {
  max-width: 800px;
  margin: 0 auto;
  padding: 0 2rem;
}

.hero-title {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: 300;
}

.hero-subtitle {
  font-size: 1.2rem;
  margin-bottom: 2rem;
  opacity: 0.9;
}

.contact-info {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.contact-info p {
  margin: 0.5rem 0;
}

.contact-info a {
  color: #fff;
  text-decoration: none;
  border-bottom: 1px solid rgba(255,255,255,0.3);
}

.contact-info a:hover {
  border-bottom-color: #fff;
}

.content-sections {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 2rem;
}

.content-sections section {
  margin-bottom: 3rem;
  padding: 2rem;
  background: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.content-sections h2 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  margin-top: 1rem;
}

.skill-category h3 {
  color: #667eea;
  margin-bottom: 0.5rem;
}

.skill-category ul {
  list-style: none;
  padding: 0;
}

.skill-category li {
  padding: 0.25rem 0;
  border-bottom: 1px solid #eee;
}

.cta-buttons {
  margin-top: 1.5rem;
  text-align: center;
}

.btn {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  margin: 0 0.5rem;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 600;
  transition: all 0.3s ease;
}

.btn-primary {
  background: #667eea;
  color: white;
}

.btn-primary:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
}

.btn-secondary {
  background: transparent;
  color: #667eea;
  border: 2px solid #667eea;
}

.btn-secondary:hover {
  background: #667eea;
  color: white;
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .hero-title {
    font-size: 2rem;
  }
  
  .hero-subtitle {
    font-size: 1rem;
  }
  
  .contact-info {
    grid-template-columns: 1fr;
  }
  
  .content-sections {
    padding: 0 1rem;
  }
  
  .content-sections section {
    padding: 1.5rem;
  }
}
</style>
