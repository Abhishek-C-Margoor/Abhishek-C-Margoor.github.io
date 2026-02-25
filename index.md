---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek C Margoor | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root { --primary: #2563eb; --primary-light: #eff6ff; --text-dark: #1f2937; --text-light: #6b7280; --bg: #f8fafc; }
        body { font-family: 'Inter', sans-serif; background-color: var(--bg); color: var(--text-dark); line-height: 1.6; margin: 0; }
        
        /* Header Section */
        .header { background: white; border-bottom: 1px solid #e5e7eb; padding: 80px 20px; text-align: center; }
        .header h1 { font-size: 2.8rem; font-weight: 700; margin: 0; color: #111827; letter-spacing: -0.025em; }
        .header p { font-size: 1.25rem; color: var(--text-light); margin: 15px 0 25px; }
        .links a { margin: 0 12px; text-decoration: none; color: var(--primary); font-weight: 600; transition: opacity 0.2s; }
        .links a:hover { opacity: 0.7; }

        /* Container & Sections */
        .container { max-width: 850px; margin: 0 auto; padding: 50px 20px; }
        .section-title { font-size: 1.75rem; font-weight: 700; margin: 40px 0 25px; display: flex; align-items: center; gap: 10px; }
        
        /* Project Cards */
        .project-card { background: white; border: 1px solid #e5e7eb; border-radius: 12px; padding: 32px; margin-bottom: 24px; box-shadow: 0 1px 3px rgba(0,0,0,0.05); transition: all 0.3s ease; }
        .project-card:hover { transform: translateY(-4px); box-shadow: 0 12px 20px rgba(0,0,0,0.08); border-color: var(--primary); }
        .project-card h3 { margin: 0 0 12px; font-size: 1.4rem; color: #111827; }
        .tech-stack { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 16px; }
        .tech-pill { background: var(--primary-light); color: var(--primary); padding: 4px 12px; border-radius: 6px; font-size: 0.8rem; font-weight: 600; }
        .project-card p { color: var(--text-light); margin-bottom: 20px; }
        .repo-link { display: inline-flex; align-items: center; color: var(--primary); text-decoration: none; font-weight: 600; font-size: 0.95rem; }

        /* Skills & Certs */
        .skill-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(180px, 1fr)); gap: 12px; }
        .skill-item { background: white; border: 1px solid #e5e7eb; padding: 12px 16px; border-radius: 8px; font-weight: 500; font-size: 0.9rem; text-align: center; }
        .cert-list { list-style: none; padding: 0; }
        .cert-item { background: white; padding: 16px; border-radius: 8px; border: 1px solid #e5e7eb; margin-bottom: 10px; display: flex; justify-content: space-between; align-items: center; }
    </style>
</head>
<body>

<header class="header">
    <h1>Abhishek C Margoor</h1>
    <p>Data Scientist | ML Engineer | GenAI Specialist</p>
    <div class="links">
        <a href="https://www.linkedin.com/in/abhishek-c-margoor-3a9967280">LinkedIn</a>
        <a href="https://github.com/Abhishek-C-Margoor">GitHub</a>
        <a href="mailto:abhishekcmargoor@gmail.com">Email</a>
    </div>
</header>

<main class="container">
    <h2 class="section-title">🚀 Featured Projects</h2>

    <div class="project-card">
        <h3>FinSight AI: Agentic Market Reasoning</h3>
        <div class="tech-stack">
            <span class="tech-pill">Gemini 1.5 Flash</span>
            <span class="tech-pill">LangChain</span>
            <span class="tech-pill">PySpark</span>
            <span class="tech-pill">Kafka</span>
            <span class="tech-pill">AWS</span>
        </div>
        <p>Architected an autonomous agent system bridging quantitative market signals with qualitative global sentiment. Achieved a 40% reduction in data latency using a high-throughput pipeline.</p>
        <a href="https://github.com/Abhishek-C-Margoor/FinSight-AI" class="repo-link">View Source Code →</a>
    </div>

    <div class="project-card">
        <h3>Intelligent Insurance Claim System</h3>
        <div class="tech-stack">
            <span class="tech-pill">YOLOv8</span>
            <span class="tech-pill">LLaMA</span>
            <span class="tech-pill">RAG (FAISS)</span>
            <span class="tech-pill">Explainable AI</span>
        </div>
        <p>Automated claim evaluation using YOLO-based CNNs for damage assessment and an XAI layer for human-readable justifications. Improved processing speed by 65%.</p>
        <a href="https://github.com/Abhishek-C-Margoor/Insurance-Claim-System" class="repo-link">View Source Code →</a>
    </div>

    <div class="project-card">
        <h3>Nutrisist: AI Dietary Recommendation</h3>
        <div class="tech-stack">
            <span class="tech-pill">Django REST</span>
            <span class="tech-pill">Google Fit API</span>
            <span class="tech-pill">PostgreSQL</span>
        </div>
        <p>Developed a personalized nutrition engine that syncs with wearable data. Supported 1,000+ dynamic recipe mappings with optimized sub-second latency.</p>
        <a href="https://github.com/Abhishek-C-Margoor/Nutrisist" class="repo-link">View Source Code →</a>
    </div>

    <h2 class="section-title">🛠️ Technical Expertise</h2>
    <div class="skill-grid">
        <div class="skill-item">Agentic RAG</div>
        <div class="skill-item">Computer Vision</div>
        <div class="skill-item">Big Data (PySpark)</div>
        <div class="skill-item">FastAPI / Django</div>
        <div class="skill-item">Docker & AWS</div>
        <div class="skill-item">SQL & NoSQL</div>
    </div>

    <h2 class="section-title">📜 Certifications</h2>
    <div class="cert-list">
        <div class="cert-item">
            <span><strong>SkilloVilla:</strong> Certified Data Scientist</span>
            <span style="color: var(--text-light); font-size: 0.85rem;">ID: E7700TUY</span>
        </div>
        <div class="cert-item">
            <span><strong>AWS Academy:</strong> GenAI Foundations & Data Engineering</span>
        </div>
        <div class="cert-item">
            <span><strong>C-DAC:</strong> PG Diploma in Big Data Analytics</span>
        </div>
    </div>
</main>

</body>
</html>
