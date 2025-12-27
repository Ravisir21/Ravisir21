<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raviprakash Mishra - AI/ML Engineer & Full-Stack Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0a0e27 0%, #1a1f3a 50%, #0f1419 100%);
            color: #e6e6e6;
            overflow-x: hidden;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }

        .star {
            position: absolute;
            background: white;
            border-radius: 50%;
            animation: twinkle 3s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 1; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
            position: relative;
            z-index: 1;
        }

        .hero {
            text-align: center;
            padding: 80px 20px;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 600px;
            height: 600px;
            background: radial-gradient(circle, rgba(0, 255, 255, 0.1) 0%, transparent 70%);
            animation: pulse 4s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: translate(-50%, -50%) scale(1); opacity: 0.5; }
            50% { transform: translate(-50%, -50%) scale(1.2); opacity: 0.8; }
        }

        .hero h1 {
            font-size: 4em;
            font-weight: 900;
            background: linear-gradient(135deg, #00ffff 0%, #00d4ff 50%, #0099ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 20px;
            animation: slideDown 1s ease-out;
            text-shadow: 0 0 40px rgba(0, 255, 255, 0.3);
        }

        @keyframes slideDown {
            from { opacity: 0; transform: translateY(-50px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .hero .subtitle {
            font-size: 1.8em;
            color: #00ffff;
            margin-bottom: 30px;
            animation: slideUp 1s ease-out 0.3s both;
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.5);
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .hero .tagline {
            font-size: 1.2em;
            color: #a0a0a0;
            max-width: 800px;
            margin: 0 auto 40px;
            line-height: 1.8;
            animation: fadeIn 1s ease-out 0.6s both;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
            animation: fadeIn 1s ease-out 0.9s both;
        }

        .social-btn {
            padding: 15px 35px;
            background: rgba(0, 255, 255, 0.1);
            border: 2px solid #00ffff;
            border-radius: 50px;
            color: #00ffff;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .social-btn::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            background: rgba(0, 255, 255, 0.3);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }

        .social-btn:hover::before {
            width: 300px;
            height: 300px;
        }

        .social-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0, 255, 255, 0.4);
        }

        .section {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 50px;
            margin: 40px 0;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            animation: fadeInUp 0.8s ease-out both;
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .section:nth-child(even) {
            animation-delay: 0.2s;
        }

        .section h2 {
            font-size: 2.5em;
            margin-bottom: 30px;
            background: linear-gradient(135deg, #00ffff 0%, #ffffff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            display: inline-block;
            position: relative;
        }

        .section h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, #00ffff 0%, transparent 100%);
            animation: expand 1s ease-out;
        }

        @keyframes expand {
            from { width: 0; }
            to { width: 100%; }
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }

        .card {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(0, 255, 255, 0.2);
            border-radius: 15px;
            padding: 30px;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 255, 255, 0.1), transparent);
            transition: left 0.6s;
        }

        .card:hover::before {
            left: 100%;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: #00ffff;
            box-shadow: 0 15px 40px rgba(0, 255, 255, 0.3);
        }

        .card h3 {
            color: #00ffff;
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        .card p {
            color: #b0b0b0;
            line-height: 1.6;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 30px;
        }

        .tech-badge {
            background: rgba(0, 255, 255, 0.1);
            border: 1px solid rgba(0, 255, 255, 0.3);
            padding: 10px 20px;
            border-radius: 25px;
            font-size: 0.9em;
            color: #00ffff;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .tech-badge:hover {
            background: rgba(0, 255, 255, 0.2);
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(0, 255, 255, 0.4);
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .stat-card {
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.1) 0%, rgba(0, 100, 255, 0.1) 100%);
            border: 2px solid rgba(0, 255, 255, 0.3);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .stat-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: conic-gradient(from 0deg, transparent, rgba(0, 255, 255, 0.2), transparent 30%);
            animation: rotate 4s linear infinite;
        }

        @keyframes rotate {
            100% { transform: rotate(360deg); }
        }

        .stat-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 50px rgba(0, 255, 255, 0.4);
        }

        .stat-number {
            font-size: 3em;
            font-weight: 900;
            color: #00ffff;
            position: relative;
            z-index: 1;
        }

        .stat-label {
            color: #b0b0b0;
            margin-top: 10px;
            position: relative;
            z-index: 1;
        }

        .floating {
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .gradient-text {
            background: linear-gradient(135deg, #00ffff 0%, #00d4ff 50%, #0099ff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .glow {
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.5),
                         0 0 20px rgba(0, 255, 255, 0.3),
                         0 0 30px rgba(0, 255, 255, 0.2);
        }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5em; }
            .hero .subtitle { font-size: 1.3em; }
            .section { padding: 30px 20px; }
            .social-links { flex-direction: column; align-items: center; }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <div class="hero">
            <h1 class="glow">RAVIPRAKASH MISHRA</h1>
            <div class="subtitle">AI/ML Engineer & Full-Stack Developer</div>
            <p class="tagline">
                Building intelligent, scalable systems at the intersection of deep learning, 
                generative AI, and modern web development. Transforming complex challenges 
                into elegant, user-friendly solutions.
            </p>
            <div class="social-links">
                <a href="https://linkedin.com/in/ravisir21" class="social-btn" target="_blank">
                    <span style="position: relative; z-index: 1;">LinkedIn</span>
                </a>
                <a href="https://instagram.com/shree_raviprakash" class="social-btn" target="_blank">
                    <span style="position: relative; z-index: 1;">Instagram</span>
                </a>
                <a href="https://github.com/Ravisir21" class="social-btn" target="_blank">
                    <span style="position: relative; z-index: 1;">GitHub</span>
                </a>
            </div>
        </div>

        <div class="section">
            <h2>🚀 Current Focus</h2>
            <div class="grid">
                <div class="card floating">
                    <h3>AI/ML Innovation</h3>
                    <p>Developing cutting-edge semantic RAG systems, algorithmic trading solutions, and enterprise-scale ML models</p>
                </div>
                <div class="card floating" style="animation-delay: 0.3s;">
                    <h3>Full-Stack Development</h3>
                    <p>Building scalable applications with React.js, Next.js, and cloud-native architectures</p>
                </div>
                <div class="card floating" style="animation-delay: 0.6s;">
                    <h3>Creative Engineering</h3>
                    <p>Merging technical depth with exceptional UI/UX design for memorable user experiences</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>💡 Expertise</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <div class="stat-number gradient-text">AI/ML</div>
                    <div class="stat-label">Deep Learning & Generative AI</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number gradient-text">Full-Stack</div>
                    <div class="stat-label">React, Next.js, FastAPI, Flask</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number gradient-text">Cloud</div>
                    <div class="stat-label">AWS, GCP, Azure Deployments</div>
                </div>
                <div class="stat-card">
                    <div class="stat-number gradient-text">LLMOps</div>
                    <div class="stat-label">Prompt Engineering & Fine-tuning</div>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🎯 Collaboration Interests</h2>
            <div class="grid">
                <div class="card">
                    <h3>Open Source</h3>
                    <p>AI tools, frameworks, and libraries that push the boundaries of what's possible</p>
                </div>
                <div class="card">
                    <h3>Fintech Innovation</h3>
                    <p>Trading platforms, financial analysis tools, and blockchain applications</p>
                </div>
                <div class="card">
                    <h3>Creative Tech</h3>
                    <p>Design-driven applications that blend aesthetics with functionality</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🔬 Currently Exploring</h2>
            <div class="tech-stack">
                <div class="tech-badge">Advanced LLMOps</div>
                <div class="tech-badge">Algorithmic Trading</div>
                <div class="tech-badge">Prompt Engineering</div>
                <div class="tech-badge">Secure Backend Auditing</div>
                <div class="tech-badge">Cloud-Native Architecture</div>
                <div class="tech-badge">Real-time AI Systems</div>
            </div>
        </div>

        <div class="section">
            <h2>💻 Technology Arsenal</h2>
            <div class="tech-stack">
                <div class="tech-badge">Python</div>
                <div class="tech-badge">JavaScript/TypeScript</div>
                <div class="tech-badge">React & Next.js</div>
                <div class="tech-badge">PyTorch & TensorFlow</div>
                <div class="tech-badge">FastAPI & Flask</div>
                <div class="tech-badge">Node.js & Express</div>
                <div class="tech-badge">MongoDB & PostgreSQL</div>
                <div class="tech-badge">Docker & Kubernetes</div>
                <div class="tech-badge">AWS & GCP</div>
                <div class="tech-badge">Three.js</div>
                <div class="tech-badge">TailwindCSS</div>
                <div class="tech-badge">Git & CI/CD</div>
            </div>
        </div>

        <div class="section" style="text-align: center;">
            <h2>⚡ Fun Fact</h2>
            <p style="font-size: 1.2em; line-height: 1.8; color: #b0b0b0; max-width: 800px; margin: 30px auto;">
                I thrive at the intersection of <span class="gradient-text" style="font-weight: 700;">technical rigor</span> 
                and <span class="gradient-text" style="font-weight: 700;">creative design</span> — whether it's architecting 
                a trading bot dashboard with real-time analytics or crafting an artist's portfolio that tells a compelling story.
            </p>
        </div>
    </div>

    <script>
        // Create animated stars
        const starsContainer = document.getElementById('stars');
        for (let i = 0; i < 100; i++) {
            const star = document.createElement('div');
            star.className = 'star';
            star.style.width = Math.random() * 3 + 'px';
            star.style.height = star.style.width;
            star.style.left = Math.random() * 100 + '%';
            star.style.top = Math.random() * 100 + '%';
            star.style.animationDelay = Math.random() * 3 + 's';
            starsContainer.appendChild(star);
        }

        // Animate cards on scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, { threshold: 0.1 });

        document.querySelectorAll('.section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(40px)';
            section.style.transition = 'all 0.8s ease-out';
            observer.observe(section);
        });

        // Add parallax effect to hero
        document.addEventListener('mousemove', (e) => {
            const hero = document.querySelector('.hero');
            const x = (e.clientX / window.innerWidth - 0.5) * 20;
            const y = (e.clientY / window.innerHeight - 0.5) * 20;
            hero.style.transform = `translate(${x}px, ${y}px)`;
        });
    </script>
</body>
</html>
