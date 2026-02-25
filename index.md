---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek C Margoor | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        :root { --primary: #007bff; --text: #333; --bg: #f4f7f9; }
        body { font-family: 'Inter', sans-serif; background-color: var(--bg); color: var(--text); line-height: 1.6; margin: 0; padding: 0; }
        .container { max-width: 900px; margin: 0 auto; padding: 40px 20px; }
        
        /* Header */
        .header { text-align: center; padding: 60px 20px; background: white; border-bottom: 1px solid #e1e4e8; }
        .header h1 { margin: 0; font-size: 2.5rem; color: #1a1a1a; }
        .header p { font-size: 1.2rem; color: #666; margin: 10px 0 20px; }
        .links a { margin: 0 15px; text-decoration: none; color: var(--primary); font-weight: 600; }

        /* Project Cards */
        .section-title { font-size: 1.8rem; margin: 40px 0 25px; border-left: 5px solid var(--primary); padding-left: 15px; }
        .project-card { background: white; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); transition: transform 0.2s; }
        .project-card:hover { transform: translateY(-5px); box-shadow: 0 8px 15px rgba(0,0,0,0.1); }
        .project-card h3 { margin-top: 0; color: var(--primary); }
        .tech-pill { display: inline-block; background: #e7f3ff; color: #0056b3; padding: 4px 12px; border-radius: 20px; font-size: 0.8rem; font-weight: 600; margin-right: 5px; margin-bottom: 10px; }
        .view-btn { display: inline-block; margin-top: 15px; color: var(--primary); text-decoration: none; font-weight: 600; }

        /* Skills */
        .skill-tag { display: inline-block; background: #fff; border: 1px solid #ddd; padding: 8px 16px; margin: 5px; border-radius: 8px; font-size: 0.9rem; font-weight: 500; }
    </style>
</head>
<body>

<div class="header">
    <h1>Abhishek C Margoor</h1>
    <p>Data Scientist | ML Engineer | GenAI Specialist</p>
    <div class="links">
        <a href="https://www.linkedin.com/in/abhishek-c-margoor-3a9967280">LinkedIn</a>
        <a href="https://github.com/Abhishek-C-Margoor">GitHub</a>
        <a href="mailto:abhishekcmargoor@gmail.com">Email</a>
    </div>
</div>

<div class="container">
    <h2 class="section-title">🚀 Featured Projects</h2>

    <div class="project-card">
        <h3>FinSight AI: Agentic Market Reasoning</h3>
        <div>
            <span class="tech-pill">Gemini 1.5 Flash</span>
            <span class="tech-pill">LangChain</span>
            <span class="tech-pill">PySpark</span>
            <span class="tech-pill">Kafka</span>
            <span class="tech-pill">AWS</span>
        </div>
        <p>Architected an autonomous agent system bridging quantitative market signals with qualitative global sentiment. Reduced data latency by 40% using a high-throughput pipeline.</p>
        <a class="view-btn" href="https://github.com/Abhishek-C-Margoor/FinSight-AI">View Repository →</a>
    </div>

    <div class="project-card">
        <h3>Intelligent Motor Vehicle Insurance Claim System</h3>
        <div>
            <span class="tech-pill">YOLOv8</span>
            <span class="tech-pill">LLaMA</span>
            <span class="tech-pill">RAG (FAISS)</span>
            <span class="tech-pill">XAI</span>
        </div>
        <p>Automated claim evaluation using Computer Vision for damage assessment. Built an Explainable AI (XAI) layer to provide human-readable justifications, improving speed by 65%.</p>
        <a class="view-btn" href="https://github.com/Abhishek-C-Margoor/Insurance-Claim-System">View Repository →</a>
    </div>

    <div class="project-card">
        <h3>Nutrisist: AI Dietary Recommendation</h3>
        <div>
            <span class="tech-pill">Django REST</span>
            <span class="tech-pill">Google Fit API</span>
            <span class="tech-pill">PostgreSQL</span>
        </div>
        <p>Personalized nutrition engine adapting to real-time wearable activity data. Optimized for 1,000+ dynamic recipe mappings with sub-second latency.</p>
        <a class="view-btn" href="https://github.com/Abhishek-C-Margoor/Nutrisist">View Repository →</a>
    </div>

    <h2 class="section-title">🛠️ Technical Skills</h2>
    <div style="margin-bottom: 50px;">
        <span class="skill-tag">Agentic RAG</span>
        <span class="skill-tag">Computer Vision (YOLO)</span>
        <span class="skill-tag">Distributed Computing (PySpark)</span>
        <span class="skill-tag">FastAPI & Django</span>
        <span class="skill-tag">AWS & Docker</span>
        <span class="skill-tag">SQL & MongoDB</span>
    </div>

    <h2 class="section-title">📜 Certifications</h2>
    <ul style="list-style: none; padding: 0;">
        <li style="background: white; padding: 15px; border-radius: 8px; margin-bottom: 10px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
            <strong>SkilloVilla:</strong> Certified Data Scientist (ID: E7700TUY)
        </li>
        <li style="background: white; padding: 15px; border-radius: 8px; margin-bottom: 10px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
            <strong>AWS Academy:</strong> GenAI Foundations & Data Engineering
        </li>
        <li style="background: white; padding: 15px; border-radius: 8px; margin-bottom: 10px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
            <strong>C-DAC:</strong> PG Diploma in Big Data Analytics
        </li>
    </ul>
</div>

</body>
</html>
