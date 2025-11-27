<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mandeep Ray — Full-Stack Developer & AI Engineer</title>
  <meta name="description" content="Mandeep Ray — Full-Stack Developer & AI Engineer crafting intelligent, scalable, and user-centric applications." />
  <style>
    :root{
      --bg:#0b1020;
      --card:#0f1724;
      --muted:#9aa6bf;
      --accent:#ffd166;
      --glass: rgba(255,255,255,0.03);
      --radius:12px;
      --container:1100px;
      --mono: "Courier New", monospace;
      --sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:var(--sans);
      background:linear-gradient(180deg,#071029 0%, #071a2a 100%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding:32px 18px;
      display:flex;
      justify-content:center;
    }
    .wrap{
      width:100%;
      max-width:var(--container);
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:16px;
      padding:28px;
      box-shadow: 0 6px 30px rgba(2,6,23,0.7);
      border:1px solid rgba(255,255,255,0.03);
    }
    .center {text-align:center}
    h1{font-size:1.6rem;margin:0}
    .intro p{margin:8px 0;color:var(--muted)}
    .badges a{margin:6px 6px 6px 0;display:inline-block}
    .section{margin-top:22px;padding-top:14px;border-top:1px dashed rgba(255,255,255,0.03)}
    .section h2{font-size:1.05rem;margin:0 0 8px 0;color:#fff}
    .whatido ul{list-style:none;padding:0;margin:0;display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:8px}
    .whatido li{background:var(--glass);padding:10px;border-radius:10px;color:var(--muted)}
    .techstack{display:flex;flex-wrap:wrap;gap:8px;justify-content:center}
    .techstack img{height:34px;border-radius:8px;box-shadow:0 3px 10px rgba(3,6,23,0.6)}
    .projects table{width:100%;border-collapse:collapse;margin-top:10px}
    .projects td{vertical-align:top;padding:12px;border-radius:10px}
    .projects h3{margin:0 0 6px 0}
    .projects p{margin:6px 0;color:var(--muted)}
    .meta a{color:var(--accent);text-decoration:none;font-weight:600;margin-right:12px}
    .codes{font-family:var(--mono);background:rgba(255,255,255,0.02);padding:6px 8px;border-radius:6px;color:#cfe9ff}
    .stats{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px;justify-content:center}
    .ach table{width:100%;border-collapse:collapse}
    .ach td{padding:10px 12px;vertical-align:top}
    .footer{margin-top:18px;text-align:center;color:var(--muted);font-size:0.95rem}
    .contact-row{display:flex;gap:12px;justify-content:center;align-items:center;flex-wrap:wrap;margin-top:8px}
    .emoji{font-size:1.05rem;margin-right:6px}
    @media (max-width:860px){
      .intro h1 img{display:none}
      .whatido ul{grid-template-columns:1fr}
      .projects td{display:block;width:100%}
      .center{text-align:center}
    }
  </style>
</head>
<body>
  <div class="wrap" role="main">
    <div class="center intro">
      <h1>
        <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" alt="wave"/>
        &nbsp;Hey, I'm <strong style="color:var(--accent)">Mandeep Ray</strong>!
      </h1>
      <p><strong>A Full-Stack Developer & AI Engineer crafting intelligent, scalable, and user-centric applications.</strong></p>
      <p>I transform complex problems into elegant solutions, blending machine learning with robust backend and frontend technologies. Currently exploring the frontier of Generative AI with LangChain, RAG, and local LLMs.</p>

      <div class="badges" style="margin-top:12px">
        <a href="https://mandeepportfolio.vercel.app/" target="_blank" rel="noopener">
          <img src="https://img.shields.io/badge/-Portfolio-FFD700?style=for-the-badge&logo=google-chrome&logoColor=black" alt="Portfolio">
        </a>
        <a href="https://www.linkedin.com/in/mandeep-ray-b5535627b/" target="_blank" rel="noopener">
          <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
        </a>
        <a href="mailto:mandycodekarega@gmail.com" target="_blank" rel="noopener">
          <img src="https://img.shields.io/badge/-Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
        </a>
      </div>
    </div>

    <!-- Work Experience -->
    <div class="section">
      <h2>🧑‍💻 Work Experience</h2>
      <div style="display:flex;gap:18px;flex-wrap:wrap;align-items:flex-start">
        <div style="flex:1;min-width:260px">
          <strong>Full-Stack Developer — Kurators</strong> <span style="color:var(--muted)">(2024–Present)</span><br>
          <span style="color:var(--muted)">React.js · PHP · Composer · jQuery · Automation</span>
        </div>
        <div style="flex:2;min-width:320px">
          <ul style="margin:6px 0 0 18px;color:var(--muted)">
            <li>Built production-ready modules for an artisan marketplace including dashboards, workflow automation, and product management systems.</li>
            <li>Developed reusable and scalable UI components in React, improving development efficiency and user experience.</li>
            <li>Automated backend processes using <strong>PHP + Composer</strong>, reducing manual operational workload by <strong>40%</strong>.</li>
            <li>Strengthened the digital presence of artisans by improving product visibility, storytelling, and platform engagement.</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- What I Do -->
    <div class="section">
      <h2>🚀 What I Do</h2>
      <div class="whatido">
        <ul>
          <li>🧠 <strong>AI & Machine Learning:</strong> Architecting & deploying end-to-end ML pipelines, building intelligent agents with <strong>LangChain/LangGraph</strong>, running local inference with <strong>Ollama</strong>.</li>
          <li>💻 <strong>Full-Stack Development:</strong> Building performant, responsive web apps with <strong>Next.js/React</strong>, backed by robust Node.js/Express services.</li>
          <li>🛠️ <strong>Data-Driven Apps & Viz:</strong> Transforming raw data into interactive apps & dashboards with <strong>Streamlit</strong>, Plotly, and Power BI.</li>
          <li>☁️ <strong>DevOps & Tooling:</strong> Linux/Bash, Git, containerization concepts for smooth development & deployment.</li>
        </ul>
      </div>
    </div>

    <!-- Tech Stack -->
    <div class="section">
      <h2>🛠️ My Tech Stack</h2>
      <p align="center" style="margin:6px 0 12px 0;color:var(--muted)">A snapshot of technologies I use daily</p>
      <div class="techstack" role="list" aria-label="Tech badges">
        <!-- row 1 -->
        <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
        <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
        <img alt="React" src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
        <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white">
        <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
        <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
        <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
        <!-- row 2 -->
        <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white">
        <img alt="Express" src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">
        <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">
        <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
        <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
        <img alt="LangChain" src="https://img.shields.io/badge/LangChain-00865D?style=for-the-badge&logo=python&logoColor=white">
        <img alt="Ollama" src="https://img.shields.io/badge/Ollama-6A0DAD?style=for-the-badge&logo=robotframework&logoColor=white">
        <img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white">
        <!-- row 3 -->
        <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
        <img alt="Ubuntu" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">
        <img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img alt="Power BI" src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black">
        <img alt="Azure" src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white">
      </div>
    </div>

    <!-- Featured Projects -->
    <div class="section projects">
      <h2>✨ Featured Projects</h2>
      <table>
        <tr>
          <td width="50%">
            <h3>🧠 NeuroHire - AI Resume Analyzer</h3>
            <p><em>An NLP-powered application that screens resumes, matches candidates to jobs, and provides visual feedback using BERT embeddings and FAISS.</em></p>
            <p class="meta">
              <a href="https://airecruiterapp.streamlit.app/" target="_blank" rel="noopener">Live Demo</a> |
              <a href="https://github.com/Mandy1200/NeuroHire" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1fUyFEpyaUV-0_jNrH8iwpqu49uVSiVjE/view" target="_blank" rel="noopener">Video</a>
            </p>
            <p class="codes">Streamlit · scikit-learn · BERT · FAISS · Python</p>
          </td>
          <td width="50%">
            <h3>🧘 Claravita - WellNess Predictor</h3>
            <p><em>An AI platform predicting burnout and stress by analyzing lifestyle data. Includes explainable AI (SHAP) and personalized health scores.</em></p>
            <p class="meta">
              <a href="https://wellnesspredictor.streamlit.app/" target="_blank" rel="noopener">Live Demo</a> |
              <a href="https://github.com/Mandy1200/Claravita" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1EQ9oInLqA_UwrnioxuD4o7bATXx5-ZnG/view" target="_blank" rel="noopener">Video</a>
            </p>
            <p class="codes">Streamlit · Plotly · SHAP · scikit-learn · Python</p>
          </td>
        </tr>

        <tr>
          <td width="50%">
            <h3>🚁 Swift Relief - Disaster Response Drone System</h3>
            <p><em>Autonomous drone system for delivering medical supplies in disaster-hit areas, with real-time GPS navigation and obstacle avoidance.</em></p>
            <p class="meta">
              <a href="https://drive.google.com/file/d/1XpAXIpqPRXEEkD6LdGJiPgZuMMRt0PRZ/view" target="_blank" rel="noopener">Website Demo</a> |
              <a href="#" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1xTaSlHYdTSghmXeoqn8IEBQdCkk1jbAn/view" target="_blank" rel="noopener">Hardware Demo</a>
            </p>
            <p class="codes">Hardware · IoT · Python · GPS · React</p>
          </td>
          <td width="50%">
            <h3>💻 CodeZen - Collaborative Coding Platform</h3>
            <p><em>Real-time collaborative coding platform with AI assistants, live previews, and team workflows, built for project-based learning.</em></p>
            <p class="meta">
              <a href="https://codezens.vercel.app/" target="_blank" rel="noopener">Website</a> |
              <a href="#" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1yNA6DLjq4LI18qtK6LMFCmdzCEvoSwaN/view" target="_blank" rel="noopener">Video Demo</a>
            </p>
            <p class="codes">React · WebSockets · Node.js · AI/LLM API · Next.js</p>
          </td>
        </tr>

        <tr>
          <td width="50%">
            <h3>🐝 SmartBloom - Automated Pollination Robot</h3>
            <p><em>Custom robotic system using Arduino and Edge Impulse to automate cross-pollination and agricultural automation.</em></p>
            <p class="meta">
              <a href="https://www.smartbloom.in/" target="_blank" rel="noopener">Website</a> |
              <a href="https://github.com/Mandy1200/SmartBloom" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1V7WFyE7MrIIydIWNiFPmf09DVzyNkLeV/view" target="_blank" rel="noopener">Video</a>
            </p>
            <p class="codes">Robotics · Edge Impulse · Arduino · C++ · ML</p>
          </td>
          <td width="50%">
            <h3>🗣️ SilentSpeak - Assistive Communication Device</h3>
            <p><em>AI-driven device using Morse code and haptics for non-verbal communication, with multilingual output and emergency features.</em></p>
            <p class="meta">
              <a href="https://silent-speaks.netlify.app/" target="_blank" rel="noopener">Website</a> |
              <a href="https://github.com/Mandy1200/silentspeak2.0" target="_blank" rel="noopener">GitHub Repo</a> |
              <a href="https://drive.google.com/file/d/1wq6qSjO54d20EM_EO7LFaKoE7DCLq-8m/view" target="_blank" rel="noopener">Video</a>
            </p>
            <p class="codes">AI/ML · Hardware · IoT · Python · React</p>
          </td>
        </tr>
      </table>
    </div>

    <!-- GitHub Stats -->
    <div class="section center">
      <h2>📊 GitHub Stats</h2>
      <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mandy1200&layout=compact&theme=radical&hide_border=true&border_radius=12&langs_count=8" alt="Top Languages" style="max-width:48%;width:48%;min-width:260px;border-radius:10px">
        <img src="https://streak-stats.demolab.com?user=Mandy1200&theme=radical&hide_border=true&border_radius=12" alt="GitHub Streak" style="max-width:48%;width:48%;min-width:260px;border-radius:10px">
      </div>
    </div>

    <!-- Achievements -->
    <div class="section ach">
      <h2>🏆 Achievements & Recognition</h2>
      <table>
        <tr>
          <td width="28%"><h3>🗣️ SilentSpeak</h3></td>
          <td>
            <strong>AWS Credit Program Selection</strong><br>
            <em>Selected at the prestigious PITCH ‘n’ WIN event at IIT Bhubaneswar for innovation and potential.</em>
          </td>
        </tr>
        <tr>
          <td><h3>🐝 SmartBloom</h3></td>
          <td>
            <strong>Multi-Hackathon Champion (5x Winner)</strong><br>
            <em>Wins at IIIT D3 Fest, Silicon SparkUp Summit, TechTronics 2024, Utkarsh 2024 (StartUp Odisha), and MSME IDEA Hackathon 4.0.</em>
          </td>
        </tr>
        <tr>
          <td><h3>💻 CodeZen</h3></td>
          <td>
            <strong>Dual Hackathon Winner</strong><br>
            <em>Top positions for collaborative features at IIIT BBSR Invento Expo Advaita & ELYSIUM 2025 KODLAMA (AI Hackathon).</em>
          </td>
        </tr>
      </table>
    </div>

    <!-- Collaboration -->
    <div class="section">
      <h2>🤝 Let's Collaborate!</h2>
      <p style="color:var(--muted)">I'm always excited to connect with new people and explore opportunities. Currently open to:</p>
      <ul style="color:var(--muted)">
        <li>AI/ML Research Internships (Remote or In-Person)</li>
        <li>Open-Source Contributions in ML, GenAI, or Frontend tools</li>
        <li>Freelance/Contract Roles focused on AI-driven web applications</li>
        <li>Collaborations on innovative tech projects</li>
      </ul>
    </div>

    <div class="footer">
      <div class="contact-row">
        <div>Made with ❤️ and a lot of ☕</div>
        <div>•</div>
        <div><strong>Mandeep Ray</strong> — <a href="mailto:mandycodekarega@gmail.com" style="color:var(--accent);text-decoration:none">mandycodekarega@gmail.com</a></div>
      </div>
    </div>
  </div>
</body>
</html>