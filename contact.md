---
layout: page
title: Contact
permalink: /contact/
---

<div class="contact-hero">
  <h1>Get In Touch</h1>
  <p>Let's discuss forensic acoustics, AI research, or potential collaborations</p>
</div>

<div class="contact-content">
  <div class="contact-grid">
    <div class="contact-info">
      <h2>Contact Information</h2>
      
      <div class="contact-item">
        <div class="contact-icon">📧</div>
        <div class="contact-details">
          <h3>Email</h3>
          <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
        </div>
      </div>
      
      <div class="contact-item">
        <div class="contact-icon">🔍</div>
        <div class="contact-details">
          <h3>Location</h3>
          <p>{{ site.author.location }}</p>
        </div>
      </div>
      
      <div class="contact-item">
        <div class="contact-icon">🔗</div>
        <div class="contact-details">
          <h3>LinkedIn</h3>
          <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank">{{ site.author.linkedin }}</a>
        </div>
      </div>
      
      <div class="contact-item">
        <div class="contact-icon">💻</div>
        <div class="contact-details">
          <h3>GitHub</h3>
          <a href="https://github.com/{{ site.author.github }}" target="_blank">{{ site.author.github }}</a>
        </div>
      </div>
    </div>
    
    <div class="contact-form-section">
      <h2>Areas of Collaboration</h2>
      
      <div class="collaboration-areas">
        <div class="area-item">
          <h3>🔬 Research Collaboration</h3>
          <p>Joint research projects in forensic acoustics, AI applications in audio processing, and signal analysis.</p>
        </div>
        
        <div class="area-item">
          <h3>🎓 Academic Partnerships</h3>
          <p>Teaching opportunities, student supervision, and academic program development.</p>
        </div>
        
        <div class="area-item">
          <h3>🏢 Consulting Services</h3>
          <p>Forensic audio analysis, expert witness testimony, and technical consulting for legal cases.</p>
        </div>
        
        <div class="area-item">
          <h3>📢 Speaking Engagements</h3>
          <p>Conference presentations, workshops, and training sessions on forensic acoustics and AI.</p>
        </div>
        
        <div class="area-item">
          <h3>💡 Technology Development</h3>
          <p>Collaborative development of new tools and technologies for audio analysis and processing.</p>
        </div>
        
        <div class="area-item">
          <h3>📚 Publications & Research</h3>
          <p>Co-authoring research papers, technical articles, and contributing to academic publications.</p>
        </div>
      </div>
    </div>
  </div>
  
  <div class="contact-note">
    <h3>📝 Note</h3>
    <p>
      When reaching out, please include details about your project, research interests, or collaboration goals. 
      I'm particularly interested in projects that combine AI with audio processing, forensic applications, 
      and interdisciplinary research opportunities.
    </p>
    
    <p>
      <strong>Response Time:</strong> I typically respond to emails within 24-48 hours during business days.
    </p>
  </div>
  
  <div class="quick-contact">
    <h3>Quick Contact</h3>
    <p>For immediate inquiries or urgent forensic consulting needs:</p>
    <a href="mailto:{{ site.author.email }}?subject=Urgent Inquiry - Forensic Acoustics" class="btn btn-primary">
      Send Urgent Email
    </a>
  </div>
</div>

<style>
.contact-hero {
  text-align: center;
  padding: 3rem 0;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  margin-bottom: 3rem;
}

.contact-hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  font-weight: 300;
}

.contact-hero p {
  font-size: 1.2rem;
  opacity: 0.9;
  max-width: 600px;
  margin: 0 auto;
}

.contact-content {
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 2rem;
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 3rem;
  margin-bottom: 3rem;
}

.contact-info h2, .contact-form-section h2 {
  color: #333;
  margin-bottom: 2rem;
  font-size: 1.8rem;
}

.contact-item {
  display: flex;
  align-items: center;
  margin-bottom: 2rem;
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.contact-icon {
  font-size: 2rem;
  margin-right: 1.5rem;
  min-width: 60px;
  text-align: center;
}

.contact-details h3 {
  margin: 0 0 0.5rem 0;
  color: #667eea;
  font-size: 1.1rem;
}

.contact-details p, .contact-details a {
  margin: 0;
  color: #666;
  text-decoration: none;
}

.contact-details a:hover {
  color: #667eea;
  text-decoration: underline;
}

.collaboration-areas {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.area-item {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.area-item:hover {
  transform: translateY(-3px);
}

.area-item h3 {
  color: #667eea;
  margin-bottom: 1rem;
  font-size: 1rem;
}

.area-item p {
  font-size: 0.9rem;
  line-height: 1.6;
  color: #666;
}

.contact-note {
  background: #e3f2fd;
  padding: 2rem;
  border-radius: 8px;
  border-left: 4px solid #667eea;
  margin-bottom: 2rem;
}

.contact-note h3 {
  color: #667eea;
  margin-bottom: 1rem;
}

.contact-note p {
  margin-bottom: 1rem;
  line-height: 1.6;
}

.quick-contact {
  text-align: center;
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  margin-bottom: 2rem;
}

.quick-contact h3 {
  color: #333;
  margin-bottom: 1rem;
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
  margin-top: 1rem;
}

.btn:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .contact-hero h1 {
    font-size: 2rem;
  }
  
  .contact-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .contact-item {
    flex-direction: column;
    text-align: center;
  }
  
  .contact-icon {
    margin-right: 0;
    margin-bottom: 1rem;
  }
  
  .collaboration-areas {
    grid-template-columns: 1fr;
  }
  
  .contact-content {
    padding: 0 1rem;
  }
}
</style>
