<div align="center">

<!-- Animated Gradient Header -->
<svg width="100%" height="200">
  <defs>
    <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00F7F7;stop-opacity:1">
        <animate attributeName="offset" values="0;1;0" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#7B68EE;stop-opacity:1">
        <animate attributeName="offset" values=".5;1;.5" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#FF1493;stop-opacity:1">
        <animate attributeName="offset" values="1;0;1" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <rect width="100%" height="100%" fill="url(#gradient)"/>
  <text x="50%" y="50%" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="white" text-anchor="middle" dy=".3em">🚀 Raviprakash Mishra</text>
</svg>

<br/>

<!-- Animated Typing Effect with Glow -->
<div style="position: relative; display: inline-block;">
  <div style="
    font-size: 28px;
    font-weight: 600;
    font-family: 'Fira Code', monospace;
    background: linear-gradient(90deg, #00F7F7, #7B68EE, #FF1493);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    animation: gradientShift 3s ease infinite;
    text-shadow: 0 0 20px rgba(0, 247, 247, 0.3);
  ">
    <span class="typing-text"></span>
    <span class="cursor" style="
      display: inline-block;
      width: 3px;
      background-color: #00F7F7;
      animation: blink 1s infinite;
      margin-left: 2px;
      height: 1.2em;
      vertical-align: middle;
    "></span>
  </div>
</div>

<!-- Animated 3D Cube -->
<div style="position: relative; width: 100px; height: 100px; margin: 20px auto; perspective: 1000px;">
  <div style="
    width: 100%;
    height: 100%;
    position: relative;
    transform-style: preserve-3d;
    animation: rotateCube 10s infinite linear;
  ">
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #00F7F7, #7B68EE); opacity: 0.8; transform: rotateY(0deg) translateZ(50px);"></div>
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #7B68EE, #FF1493); opacity: 0.8; transform: rotateY(90deg) translateZ(50px);"></div>
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #FF1493, #00F7F7); opacity: 0.8; transform: rotateY(180deg) translateZ(50px);"></div>
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #00F7F7, #7B68EE); opacity: 0.8; transform: rotateY(-90deg) translateZ(50px);"></div>
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #7B68EE, #FF1493); opacity: 0.8; transform: rotateX(90deg) translateZ(50px);"></div>
    <div style="position: absolute; width: 100px; height: 100px; background: linear-gradient(45deg, #FF1493, #00F7F7); opacity: 0.8; transform: rotateX(-90deg) translateZ(50px);"></div>
  </div>
</div>

<!-- Animated Particle Background -->
<div style="position: relative; width: 100%; height: 200px; overflow: hidden;">
  <canvas id="particleCanvas" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></canvas>
  <div style="position: relative; z-index: 1; padding: 40px;">
    <h1 style="color: white; font-size: 42px; text-shadow: 0 0 20px rgba(0, 247, 247, 0.5);">AI/ML Engineer & Full-Stack Developer</h1>
    <p style="color: #ddd; font-size: 18px;">Building the future with intelligent systems</p>
  </div>
</div>

</div>

<!-- Animated Cards Section -->
<div align="center">

## 🌟 Core Expertise

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 40px 0;">

<!-- Card 1 -->
<div style="
  background: linear-gradient(135deg, rgba(0, 247, 247, 0.1), rgba(123, 104, 238, 0.1));
  border: 1px solid rgba(0, 247, 247, 0.2);
  border-radius: 15px;
  padding: 25px;
  transition: all 0.3s ease;
  position: relative;
  overflow: hidden;
  animation: float 6s ease-in-out infinite;
">
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(45deg, transparent, rgba(0, 247, 247, 0.1), transparent); transform: translateX(-100%); animation: shimmer 2s infinite;"></div>
  <h3 style="color: #00F7F7; margin-top: 0;">🧠 Artificial Intelligence</h3>
  <ul style="text-align: left; color: #ddd;">
    <li>Deep Learning & Neural Networks</li>
    <li>Generative AI & LLMs</li>
    <li>Computer Vision</li>
    <li>Natural Language Processing</li>
  </ul>
</div>

<!-- Card 2 -->
<div style="
  background: linear-gradient(135deg, rgba(123, 104, 238, 0.1), rgba(255, 20, 147, 0.1));
  border: 1px solid rgba(123, 104, 238, 0.2);
  border-radius: 15px;
  padding: 25px;
  transition: all 0.3s ease;
  animation: float 6s ease-in-out infinite;
  animation-delay: 0.5s;
">
  <h3 style="color: #7B68EE; margin-top: 0;">🌐 Full-Stack Development</h3>
  <ul style="text-align: left; color: #ddd;">
    <li>React.js & Next.js</li>
    <li>Node.js & FastAPI</li>
    <li>Microservices Architecture</li>
    <li>Real-time Systems</li>
  </ul>
</div>

<!-- Card 3 -->
<div style="
  background: linear-gradient(135deg, rgba(255, 20, 147, 0.1), rgba(0, 247, 247, 0.1));
  border: 1px solid rgba(255, 20, 147, 0.2);
  border-radius: 15px;
  padding: 25px;
  transition: all 0.3s ease;
  animation: float 6s ease-in-out infinite;
  animation-delay: 1s;
">
  <h3 style="color: #FF1493; margin-top: 0;">☁️ Cloud & DevOps</h3>
  <ul style="text-align: left; color: #ddd;">
    <li>AWS & Azure</li>
    <li>Kubernetes & Docker</li>
    <li>CI/CD Pipelines</li>
    <li>Infrastructure as Code</li>
  </ul>
</div>

</div>

</div>

<!-- Animated Skills Graph -->
<div align="center">

## 📊 Skills Proficiency

<div style="position: relative; width: 100%; max-width: 800px; margin: 40px auto; background: rgba(255, 255, 255, 0.05); border-radius: 15px; padding: 30px;">

<!-- Python -->
<div style="margin: 20px 0;">
  <div style="display: flex; justify-content: space-between; margin-bottom: 5px;">
    <span style="color: #ddd;">Python</span>
    <span style="color: #00F7F7;">95%</span>
  </div>
  <div style="height: 10px; background: rgba(255, 255, 255, 0.1); border-radius: 5px; overflow: hidden;">
    <div style="width: 95%; height: 100%; background: linear-gradient(90deg, #00F7F7, #7B68EE); border-radius: 5px; animation: fillBar 2s ease-out;"></div>
  </div>
</div>

<!-- JavaScript/TypeScript -->
<div style="margin: 20px 0;">
  <div style="display: flex; justify-content: space-between; margin-bottom: 5px;">
    <span style="color: #ddd;">JavaScript/TypeScript</span>
    <span style="color: #00F7F7;">90%</span>
  </div>
  <div style="height: 10px; background: rgba(255, 255, 255, 0.1); border-radius: 5px; overflow: hidden;">
    <div style="width: 90%; height: 100%; background: linear-gradient(90deg, #7B68EE, #FF1493); border-radius: 5px; animation: fillBar 2s ease-out 0.2s;"></div>
  </div>
</div>

<!-- AI/ML Frameworks -->
<div style="margin: 20px 0;">
  <div style="display: flex; justify-content: space-between; margin-bottom: 5px;">
    <span style="color: #ddd;">AI/ML Frameworks</span>
    <span style="color: #00F7F7;">92%</span>
  </div>
  <div style="height: 10px; background: rgba(255, 255, 255, 0.1); border-radius: 5px; overflow: hidden;">
    <div style="width: 92%; height: 100%; background: linear-gradient(90deg, #FF1493, #00F7F7); border-radius: 5px; animation: fillBar 2s ease-out 0.4s;"></div>
  </div>
</div>

<!-- Cloud Platforms -->
<div style="margin: 20px 0;">
  <div style="display: flex; justify-content: space-between; margin-bottom: 5px;">
    <span style="color: #ddd;">Cloud Platforms</span>
    <span style="color: #00F7F7;">88%</span>
  </div>
  <div style="height: 10px; background: rgba(255, 255, 255, 0.1); border-radius: 5px; overflow: hidden;">
    <div style="width: 88%; height: 100%; background: linear-gradient(90deg, #00F7F7, #7B68EE); border-radius: 5px; animation: fillBar 2s ease-out 0.6s;"></div>
  </div>
</div>

</div>

</div>

<!-- Live GitHub Stats with Animation -->
<div align="center">

## 📈 Real-time GitHub Analytics

<!-- Animated Stats Container -->
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin: 40px 0;">

<!-- Commits -->
<div style="
  background: linear-gradient(135deg, rgba(0, 247, 247, 0.1), rgba(0, 247, 247, 0.2));
  border-radius: 15px;
  padding: 20px;
  border: 1px solid rgba(0, 247, 247, 0.3);
  position: relative;
  overflow: hidden;
">
  <div style="font-size: 48px; font-weight: bold; color: #00F7F7; animation: countUp 2s ease-out;">
    <span class="counter" data-target="1500">0</span>+
  </div>
  <div style="color: #ddd; font-size: 14px;">Total Commits</div>
</div>

<!-- Repositories -->
<div style="
  background: linear-gradient(135deg, rgba(123, 104, 238, 0.1), rgba(123, 104, 238, 0.2));
  border-radius: 15px;
  padding: 20px;
  border: 1px solid rgba(123, 104, 238, 0.3);
  position: relative;
  overflow: hidden;
">
  <div style="font-size: 48px; font-weight: bold; color: #7B68EE; animation: countUp 2s ease-out 0.2s;">
    <span class="counter" data-target="50">0</span>+
  </div>
  <div style="color: #ddd; font-size: 14px;">Repositories</div>
</div>

<!-- Technologies -->
<div style="
  background: linear-gradient(135deg, rgba(255, 20, 147, 0.1), rgba(255, 20, 147, 0.2));
  border-radius: 15px;
  padding: 20px;
  border: 1px solid rgba(255, 20, 147, 0.3);
  position: relative;
  overflow: hidden;
">
  <div style="font-size: 48px; font-weight: bold; color: #FF1493; animation: countUp 2s ease-out 0.4s;">
    <span class="counter" data-target="40">0</span>+
  </div>
  <div style="color: #ddd; font-size: 14px;">Technologies</div>
</div>

<!-- Projects -->
<div style="
  background: linear-gradient(135deg, rgba(0, 247, 247, 0.1), rgba(123, 104, 238, 0.2));
  border-radius: 15px;
  padding: 20px;
  border: 1px solid rgba(0, 247, 247, 0.3);
  position: relative;
  overflow: hidden;
">
  <div style="font-size: 48px; font-weight: bold; color: #00F7F7; animation: countUp 2s ease-out 0.6s;">
    <span class="counter" data-target="25">0</span>+
  </div>
  <div style="color: #ddd; font-size: 14px;">Completed Projects</div>
</div>

</div>

</div>

<!-- Animated Timeline -->
<div align="center">

## 🗓️ Current Focus Timeline

<div style="position: relative; max-width: 800px; margin: 40px auto; padding: 20px;">

<!-- Timeline Item 1 -->
<div style="display: flex; align-items: center; margin: 40px 0; position: relative;">
  <div style="
    width: 20px;
    height: 20px;
    background: linear-gradient(45deg, #00F7F7, #7B68EE);
    border-radius: 50%;
    margin-right: 20px;
    position: relative;
    z-index: 2;
    animation: pulse 2s infinite;
  "></div>
  <div style="flex: 1; background: rgba(0, 247, 247, 0.1); padding: 20px; border-radius: 10px; border-left: 3px solid #00F7F7;">
    <h4 style="color: #00F7F7; margin: 0 0 10px 0;">🔬 Semantic RAG Systems</h4>
    <p style="color: #ddd; margin: 0;">Advanced Retrieval-Augmented Generation for enterprise knowledge bases</p>
  </div>
</div>

<!-- Timeline Item 2 -->
<div style="display: flex; align-items: center; margin: 40px 0; position: relative;">
  <div style="
    width: 20px;
    height: 20px;
    background: linear-gradient(45deg, #7B68EE, #FF1493);
    border-radius: 50%;
    margin-right: 20px;
    position: relative;
    z-index: 2;
    animation: pulse 2s infinite 0.5s;
  "></div>
  <div style="flex: 1; background: rgba(123, 104, 238, 0.1); padding: 20px; border-radius: 10px; border-left: 3px solid #7B68EE;">
    <h4 style="color: #7B68EE; margin: 0 0 10px 0;">📈 Algorithmic Trading Bots</h4>
    <p style="color: #ddd; margin: 0;">Machine learning models for quantitative finance and trading</p>
  </div>
</div>

<!-- Timeline Item 3 -->
<div style="display: flex; align-items: center; margin: 40px 0; position: relative;">
  <div style="
    width: 20px;
    height: 20px;
    background: linear-gradient(45deg, #FF1493, #00F7F7);
    border-radius: 50%;
    margin-right: 20px;
    position: relative;
    z-index: 2;
    animation: pulse 2s infinite 1s;
  "></div>
  <div style="flex: 1; background: rgba(255, 20, 147, 0.1); padding: 20px; border-radius: 10px; border-left: 3px solid #FF1493;">
    <h4 style="color: #FF1493; margin: 0 0 10px 0;">⚡ LLMOps Infrastructure</h4>
    <p style="color: #ddd; margin: 0;">Scalable deployment and monitoring for large language models</p>
  </div>
</div>

</div>

</div>

<!-- Animated Contact Section -->
<div align="center">

## 📬 Let's Build Something Amazing Together

<!-- Animated Contact Cards -->
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 20px; margin: 40px 0;">

<!-- LinkedIn -->
<a href="https://linkedin.com/in/ravisir21" style="text-decoration: none;">
  <div style="
    background: linear-gradient(135deg, rgba(0, 119, 181, 0.2), rgba(0, 119, 181, 0.3));
    border: 1px solid rgba(0, 119, 181, 0.4);
    border-radius: 15px;
    padding: 20px;
    transition: all 0.3s ease;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    animation: bounce 2s infinite;
  ">
    <div style="font-size: 24px;">💼</div>
    <div style="color: #fff; margin-top: 10px;">LinkedIn</div>
  </div>
</a>

<!-- GitHub -->
<a href="https://github.com/Ravisir21" style="text-decoration: none;">
  <div style="
    background: linear-gradient(135deg, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.2));
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 15px;
    padding: 20px;
    transition: all 0.3s ease;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    animation: bounce 2s infinite 0.2s;
  ">
    <div style="font-size: 24px;">🐙</div>
    <div style="color: #fff; margin-top: 10px;">GitHub</div>
  </div>
</a>

<!-- Email -->
<a href="mailto:myoffice1212.0@gmail.com" style="text-decoration: none;">
  <div style="
    background: linear-gradient(135deg, rgba(220, 53, 69, 0.2), rgba(220, 53, 69, 0.3));
    border: 1px solid rgba(220, 53, 69, 0.4);
    border-radius: 15px;
    padding: 20px;
    transition: all 0.3s ease;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    animation: bounce 2s infinite 0.4s;
  ">
    <div style="font-size: 24px;">✉️</div>
    <div style="color: #fff; margin-top: 10px;">Email</div>
  </div>
</a>

<!-- Portfolio -->
<a href="#" style="text-decoration: none;">
  <div style="
    background: linear-gradient(135deg, rgba(0, 247, 247, 0.2), rgba(0, 247, 247, 0.3));
    border: 1px solid rgba(0, 247, 247, 0.4);
    border-radius: 15px;
    padding: 20px;
    transition: all 0.3s ease;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    animation: bounce 2s infinite 0.6s;
  ">
    <div style="font-size: 24px;">🌐</div>
    <div style="color: #fff; margin-top: 10px;">Portfolio</div>
  </div>
</a>

</div>

</div>

<!-- Animated Footer -->
<div align="center" style="margin-top: 60px; padding: 40px; background: linear-gradient(135deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.7)); border-radius: 20px; position: relative; overflow: hidden;">

<!-- Floating Elements -->
<div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  <div style="position: absolute; width: 50px; height: 50px; background: rgba(0, 247, 247, 0.1); border-radius: 50%; top: 20%; left: 10%; animation: float 10s infinite ease-in-out;"></div>
  <div style="position: absolute; width: 30px; height: 30px; background: rgba(123, 104, 238, 0.1); border-radius: 50%; top: 60%; left: 20%; animation: float 8s infinite ease-in-out reverse;"></div>
  <div style="position: absolute; width: 40px; height: 40px; background: rgba(255, 20, 147, 0.1); border-radius: 50%; top: 30%; left: 80%; animation: float 12s infinite ease-in-out;"></div>
</div>

<h2 style="color: #fff; position: relative; z-index: 1;">Ready to Innovate? 🚀</h2>
<p style="color: #ddd; max-width: 600px; margin: 20px auto; position: relative; z-index: 1;">
  Let's collaborate on cutting-edge AI solutions and build the future together. Whether it's research, development, or consultation, I'm excited to tackle challenging problems.
</p>

<div style="
  display: inline-block;
  background: linear-gradient(45deg, #00F7F7, #7B68EE, #FF1493);
  background-size: 200% 200%;
  animation: gradientShift 3s ease infinite;
  padding: 15px 30px;
  border-radius: 50px;
  color: white;
  font-weight: bold;
  margin-top: 20px;
  cursor: pointer;
  transition: transform 0.3s ease;
  position: relative;
  z-index: 1;
  text-decoration: none;
" onmouseover="this.style.transform='scale(1.05)'" onmouseout="this.style.transform='scale(1)'">
  ✨ Start a Conversation
</div>

</div>

<!-- CSS Animations -->
<style>
@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0; }
}

@keyframes rotateCube {
  0% { transform: rotateX(0) rotateY(0); }
  100% { transform: rotateX(360deg) rotateY(360deg); }
}

@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

@keyframes shimmer {
  100% { transform: translateX(100%); }
}

@keyframes fillBar {
  0% { width: 0%; }
}

@keyframes countUp {
  0% { opacity: 0; transform: translateY(20px); }
  100% { opacity: 1; transform: translateY(0); }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-5px); }
}
</style>

<!-- JavaScript for Interactive Elements -->
<script>
// Typing Effect
const texts = [
  "AI/ML Engineer 🧠",
  "Full-Stack Developer 💻",
  "Generative AI Specialist ✨",
  "Cloud Architecture Expert ☁️",
  "Tech Innovator 🚀"
];
let textIndex = 0;
let charIndex = 0;
let isDeleting = false;
let typingSpeed = 100;

function typeEffect() {
  const currentText = texts[textIndex];
  const typingElement = document.querySelector('.typing-text');
  
  if (isDeleting) {
    typingElement.textContent = currentText.substring(0, charIndex - 1);
    charIndex--;
    typingSpeed = 50;
  } else {
    typingElement.textContent = currentText.substring(0, charIndex + 1);
    charIndex++;
    typingSpeed = 100;
  }
  
  if (!isDeleting && charIndex === currentText.length) {
    isDeleting = true;
    typingSpeed = 1500;
  } else if (isDeleting && charIndex === 0) {
    isDeleting = false;
    textIndex = (textIndex + 1) % texts.length;
    typingSpeed = 500;
  }
  
  setTimeout(typeEffect, typingSpeed);
}

// Counter Animation
function animateCounters() {
  const counters = document.querySelectorAll('.counter');
  counters.forEach(counter => {
    const target = +counter.getAttribute('data-target');
    const duration = 2000;
    const step = target / (duration / 16);
    let current = 0;
    
    const updateCounter = () => {
      current += step;
      if (current < target) {
        counter.textContent = Math.ceil(current);
        requestAnimationFrame(updateCounter);
      } else {
        counter.textContent = target;
      }
    };
    
    updateCounter();
  });
}

// Initialize when page loads
document.addEventListener('DOMContentLoaded', () => {
  typeEffect();
  
  // Start counters when in viewport
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        animateCounters();
        observer.unobserve(entry.target);
      }
    });
  });
  
  const statsSection = document.querySelector('[style*="Real-time GitHub Analytics"]');
  if (statsSection) {
    observer.observe(statsSection);
  }
});

// Particle System
function initParticles() {
  const canvas = document.getElementById('particleCanvas');
  if (!canvas) return;
  
  const ctx = canvas.getContext('2d');
  const particles = [];
  const particleCount = 50;
  
  canvas.width = canvas.offsetWidth;
  canvas.height = canvas.offsetHeight;
  
  class Particle {
    constructor() {
      this.x = Math.random() * canvas.width;
      this.y = Math.random() * canvas.height;
      this.size = Math.random() * 3 + 1;
      this.speedX = Math.random() * 1 - 0.5;
      this.speedY = Math.random() * 1 - 0.5;
      this.color = `rgba(${Math.random() * 100 + 155}, ${Math.random() * 100 + 155}, 255, 0.8)`;
    }
    
    update() {
      this.x += this.speedX;
      this.y += this.speedY;
      
      if (this.x > canvas.width) this.x = 0;
      else if (this.x < 0) this.x = canvas.width;
      if (this.y > canvas.height) this.y = 0;
      else if (this.y < 0) this.y = canvas.height;
    }
    
    draw() {
      ctx.fillStyle = this.color;
      ctx.beginPath();
      ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
      ctx.fill();
    }
  }
  
  for (let i = 0; i < particleCount; i++) {
    particles.push(new Particle());
  }
  
  function animateParticles() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    
    for (let i = 0; i < particles.length; i++) {
      particles[i].update();
      particles[i].draw();
      
      for (let j = i + 1; j < particles.length; j++) {
        const dx = particles[i].x - particles[j].x;
        const dy = particles[i].y - particles[j].y;
        const distance = Math.sqrt(dx * dx + dy * dy);
        
        if (distance < 100) {
          ctx.beginPath();
          ctx.strokeStyle = `rgba(0, 247, 247, ${0.2 * (1 - distance / 100)})`;
          ctx.lineWidth = 0.5;
          ctx.moveTo(particles[i].x, particles[i].y);
          ctx.lineTo(particles[j].x, particles[j].y);
          ctx.stroke();
        }
      }
    }
    
    requestAnimationFrame(animateParticles);
  }
  
  animateParticles();
  
  // Handle resize
  window.addEventListener('resize', () => {
    canvas.width = canvas.offsetWidth;
    canvas.height = canvas.offsetHeight;
  });
}

// Initialize particles
if (document.getElementById('particleCanvas')) {
  initParticles();
}
</script>

<div align="center" style="margin-top: 40px; padding: 20px; color: #888; font-size: 14px;">
  <p>✨ Built with passion and cutting-edge web technologies • Last updated: <span id="currentDate"></span></p>
  <script>
    document.getElementById('currentDate').textContent = new Date().toLocaleDateString('en-US', {
      year: 'numeric',
      month: 'long',
      day: 'numeric'
    });
  </script>
</div>
