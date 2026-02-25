---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek C Margoor | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        :root { 
            --primary: #2563eb; 
            --primary-dark: #1e40af;
            --text-main: #0f172a; 
            --text-muted: #64748b; 
            --bg-light: #f8fafc; 
        }

        body { 
            font-family: 'Inter', sans-serif; 
            background: var(--bg-light);
            /* Subtle Data-Centric Background */
            background-image: 
                radial-gradient(at 0% 0%, rgba(37, 99, 235, 0.07) 0px, transparent 50%),
                radial-gradient(at 100% 100%, rgba(37, 99, 235, 0.07) 0px, transparent 50%);
            color: var(--text-main); 
            line-height: 1.6; 
            margin: 0; 
            min-height: 100vh;
        }

        /* Header Section */
        .header { 
            background: white; 
            text-align: center; 
            padding: 80px 20px; 
            border-bottom: 1px solid #e2e8f0;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }
        .header h1 { font-size: 3rem; margin: 0; color: #0f172a; font-weight: 800; letter-spacing: -0.025em; }
        .header p { font-size: 1.25rem; color: var(--text-muted); margin: 15px 0 25px; }
        
        .links { margin-bottom: 30px; }
        .links a { margin: 0 12px; text-decoration: none; color: var(--primary); font-weight: 600; transition: color 0.2s; }
        .links a:hover { color: var(--primary-dark); }

        /* Resume Button */
        .btn-resume {
            display: inline-block;
            background: var(--primary);
            color: white !important;
            padding: 12px 28px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 700;
            transition: all 0.2s ease;
            box-shadow: 0 10px 15px -3px rgba(37, 99, 235, 0.3);
        }
        .btn-resume:hover { 
            background: var(--primary-dark); 
            transform: translateY(-2px);
            box-shadow: 0 12px 20px -3px rgba(37, 99, 235, 0.4);
        }

        .container { max-width: 900px; margin: 0 auto; padding: 60px 20px; }
        
        .section-title { 
            font-size: 1.8rem; 
            font-weight: 700;
            border-left: 6px solid var(--primary); 
            padding-left: 20px; 
            margin: 50px 0 30px; 
            color: #0f172a;
        }

        /* Project Cards */
        .project-card { 
            background: #fff; 
            border: 1px solid #e2e8f0;
            border-radius: 16px; 
            padding: 35px; 
            margin-bottom: 35px; 
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }
        .project-card:hover { 
            transform: translateY(-8px); 
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
            border-color: var(--primary);
        }
        
        .project-title { font-size: 1.5rem; color: #0f172a; font-weight: 700; margin-bottom: 12px; display: block; }
        
        .tech-stack { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 20px; }
        .tech-pill { 
            background: #eff6ff; 
            color: var(--primary); 
            padding: 6px 14px; 
            border-radius: 20px; 
            font-size: 0.8rem; 
            font-weight: 600; 
        }

        .view-link { 
            color: var(--primary); 
            text-decoration: none; 
            font-weight: 700; 
            display: inline-flex; 
            align-items: center;
        }
        .view-link::after { content: ' →'; transition: margin-left 0.2s; }
        .view-link:hover::after { margin-left: 8px; }

        /* Skills Section */
        .skill-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 15px; }
        .skill-tag { background: white; border: 1px solid #e2e8f0; padding: 12px; border-radius: 10px; text-align: center; font-weight: 600; font-size: 0.9rem; transition: border-color 0.2s; }
        .skill-tag:hover { border-color: var(--primary); color: var(--primary); }

        footer { text-align: center; padding: 40px; color: var(--text-muted); font-size: 0.9rem; }
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
    <a href="YOUR_RESUME_FILENAME.pdf" class="btn-resume" target="_blank">📄 Download Full Resume</a>
</div>

<div class="container">
    <h2 class="section-title">🚀 Featured Projects</h2>

    <div class="project-card">
        <span class="project-title">FinSight AI: Agentic Market Reasoning</span>
        <div class="tech-stack">
            <span class="tech-pill">Gemini 1.5 Flash</span>
            <span class="tech-pill">LangChain</span>
            <span class="tech-pill">PySpark</span>
            <span class="tech-pill">Kafka</span>
            <span class="tech-pill">AWS</span>
        </div>
        <p>Architected an autonomous agent system bridging quantitative market signals with qualitative global sentiment. Reduced data latency by 40%.</p>
        <a href="https://github.com/Abhishek-C-Margoor/FinSight-AI" class="view-link">View Repository</a>
    </div>

    <div class="project-card">
        <span class="project-title">Intelligent Motor Vehicle Insurance Claim System</span>
        <div class="tech-stack">
            <span class="tech-pill">YOLOv8</span>
            <span class="tech-pill">LLaMA</span>
            <span class="tech-pill">RAG (FAISS)</span>
            <span class="tech-pill">Explainable AI</span>
        </div>
        <p>Automated claim evaluation using Computer Vision for damage assessment. Built an Explainable AI layer to provide policy-grounded justifications, improving speed by 65%.</p>
        <a href="https://github.com/Abhishek-C-Margoor/Insurance-Claim-System" class="view-link">View Repository</a>
    </div>

    <div class="project-card">
        <span class="project-title">Nutrisist: AI Dietary Recommendation</span>
        <div class="tech-stack">
            <span class="tech-pill">Django REST</span>
            <span class="tech-pill">Google Fit API</span>
            <span class="tech-pill">PostgreSQL</span>
        </div>
        <p>Personalized nutrition engine adapting to real-time wearable activity data. Optimized for 1,000+ dynamic recipe mappings with sub-second latency.</p>
        <a href="https://github.com/Abhishek-C-Margoor/Nutrisist" class="view-link">View Repository</a>
    </div>

    <h2 class="section-title">🛠️ Core Technical Skills</h2>
    <div class="skill-grid">
        <div class="skill-tag">Agentic RAG</div>
        <div class="skill-tag">Computer Vision</div>
        <div class="skill-tag">PySpark & Kafka</div>
        <div class="skill-tag">LLM Fine-tuning</div>
        <div class="skill-tag">FastAPI & Django</div>
        <div class="skill-tag">AWS Cloud</div>
        <div class="skill-tag">Docker Containerization</div>
        <div class="skill-tag">PostgreSQL / MongoDB</div>
    </div>
</div>

<footer>
    <p>&copy; 2026 Abhishek C Margoor. Built with ❤️ and GitHub Pages.</p>
</footer>

</body>
</html>
