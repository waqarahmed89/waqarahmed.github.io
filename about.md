---
layout: default
title: About
---

<div class="about-page">
    <h1>About</h1>
    
    <div class="about-content">
        <h2>📌 About This Blog</h2>
        <p>AI and high-performance computing are evolving faster than ever. This blog is my space to share <strong>research and hands-on learnings</strong> across:</p>
        
        <ul>
            <li><strong>Large Language Models (LLMs):</strong> Architecture, training, and scaling strategies</li>
            <li><strong>Computer Vision (CV):</strong> Advanced image and video processing with real-world deployment strategies</li>
            <li><strong>FPGA Architecture:</strong> Hardware flexibility for AI workloads</li>
            <li><strong>GPU Acceleration & Kernel Optimization:</strong> Deep dive into parallel computing and performance engineering</li>
        </ul>

        <p>The mission: <strong>decode complexity, share practical insights, and push the boundaries of speed and scalability.</strong></p>

        <h2>🎯 Purpose</h2>
        <p>This blog serves as a <strong>knowledge hub</strong> for:</p>
        <ul>
            <li>Advanced concepts in AI and compute-intensive systems</li>
            <li>Practical implementations and optimization strategies</li>
            <li>Performance tuning tips for real-world workloads</li>
        </ul>

        <h2>📬 Contact & Collaboration</h2>
        
        <div class="contact-grid">
            <div class="contact-item">
                <strong>🔗 LinkedIn:</strong> 
                <a href="{{ site.author.linkedin }}" target="_blank">{{ site.author.linkedin }}</a>
            </div>
            <div class="contact-item">
                <strong>🐙 GitHub:</strong> 
                <a href="{{ site.author.github }}" target="_blank">{{ site.author.github }}</a>
            </div>
            <div class="contact-item">
                <strong>📚 Google Scholar:</strong> 
                <a href="{{ site.author.scholar }}" target="_blank">{{ site.author.scholar }}</a>
            </div>
            <div class="contact-item">
                <strong>✉️ Email:</strong> 
                <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
            </div>
        </div>

        <h2>⚠️ Disclaimer</h2>
        <p>All opinions expressed here are <strong>my own</strong> and do <strong>not represent AMD</strong>.</p>
    </div>
</div>

<style>
.about-content {
    max-width: 700px;
}

.contact-grid {
    display: grid;
    gap: 1rem;
    margin: 2rem 0;
}

.contact-item {
    padding: 1rem;
    background: #f8f9fa;
    border-radius: 8px;
    border-left: 4px solid #3182ce;
}

.contact-item a {
    word-break: break-all;
}
</style>