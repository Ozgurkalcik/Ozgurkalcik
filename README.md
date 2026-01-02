<div align="center">
  <br/><br/>
</div>

<div align="center">
<svg width="100%" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#050a14;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0a192f;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#020c1b;stop-opacity:1" />
    </linearGradient>
    
<filter id="neonGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

<pattern id="circuitPattern" x="0" y="0" width="50" height="50" patternUnits="userSpaceOnUse">
      <path d="M10 10 L40 10 L40 40 L10 40 Z" fill="none" stroke="#112240" stroke-width="1"/>
      <circle cx="10" cy="10" r="2" fill="#233554"/>
      <circle cx="40" cy="40" r="2" fill="#233554"/>
    </pattern>
  </defs>

  <rect width="800" height="300" fill="url(#bgGradient)" rx="15" />
  <rect width="800" height="300" fill="url(#circuitPattern)" opacity="0.3" rx="15" />

  <path d="M50 150 L100 150 L120 100 L200 100" stroke="#64ffda" stroke-width="2" fill="none" filter="url(#neonGlow)" opacity="0.6">
    <animate attributeName="stroke-dasharray" from="0,1000" to="1000,0" dur="3s" repeatCount="indefinite" />
  </path>
  <path d="M50 160 L90 160 L110 200 L200 200" stroke="#00f2ff" stroke-width="2" fill="none" filter="url(#neonGlow)" opacity="0.6">
    <animate attributeName="stroke-dasharray" from="0,500" to="500,0" dur="4s" repeatCount="indefinite" />
  </path>

  <path d="M750 150 L700 150 L680 100 L600 100" stroke="#ff0055" stroke-width="2" fill="none" filter="url(#neonGlow)" opacity="0.6">
    <animate attributeName="stroke-dasharray" from="0,1000" to="1000,0" dur="3s" repeatCount="indefinite" />
  </path>
  <path d="M750 160 L710 160 L690 200 L600 200" stroke="#bd34fe" stroke-width="2" fill="none" filter="url(#neonGlow)" opacity="0.6">
    <animate attributeName="stroke-dasharray" from="0,500" to="500,0" dur="4s" repeatCount="indefinite" />
  </path>

  <polygon points="400,80 450,110 450,190 400,220 350,190 350,110" fill="none" stroke="#64ffda" stroke-width="3" filter="url(#neonGlow)">
    <animateTransform attributeName="transform" type="rotate" from="0 400 150" to="360 400 150" dur="20s" repeatCount="indefinite" />
  </polygon>
  
  <polygon points="400,95 435,115 435,185 400,205 365,185 365,115" fill="none" stroke="#00f2ff" stroke-width="2" opacity="0.8">
     <animateTransform attributeName="transform" type="rotate" from="360 400 150" to="0 400 150" dur="15s" repeatCount="indefinite" />
  </polygon>

  <text x="400" y="145" text-anchor="middle" font-family="monospace" font-size="28" fill="#ffffff" font-weight="bold" letter-spacing="4" filter="url(#neonGlow)">
    OZGUR KALCIK
  </text>
  <text x="400" y="175" text-anchor="middle" font-family="monospace" font-size="14" fill="#64ffda" letter-spacing="2">
    &lt; 1st-Year Computer Engineering Student /&gt;
  </text>
   <text x="400" y="280" text-anchor="middle" font-family="monospace" font-size="14" fill="#64ffda" letter-spacing="2">
    &lt; Hi! /&gt;
  </text>
  
  <rect x="20" y="20" width="10" height="10" fill="#64ffda" />
  <rect x="770" y="20" width="10" height="10" fill="#64ffda" />
  <rect x="20" y="270" width="10" height="10" fill="#64ffda" />
  <rect x="770" y="270" width="10" height="10" fill="#64ffda" />
  
  <rect x="0" y="0" width="800" height="300" fill="url(#circuitPattern)" opacity="0.1">
    <animate attributeName="y" from="-300" to="300" dur="5s" repeatCount="indefinite" />
  </rect>

</svg>
</div>

<br/>
<div align="center">
<table width="90%" style="background-color: #0d1117; border: 1px solid #30363d; border-radius: 6px; font-family: 'Fira Code', monospace; color: #8b949e; font-size: 12px;">
  <tr>
    <td style="padding: 10px; border-bottom: 1px solid #30363d; background-color: #161b22;">
        <span style="color: #ff5f56">●</span> <span style="color: #ffbd2e">●</span> <span style="color: #27c93f">●</span> &nbsp;&nbsp; <b>ozgur@mainframe:~</b>
    </td>
  </tr>
  <tr>
    <td style="padding: 15px;">
        <p style="margin: 2px;">$ sudo ./init_profile.sh --verbose</p>
        <p style="margin: 2px; color: #27c93f;">> [SUCCESS] BIOS Integrity Check Passed.</p>
        <p style="margin: 2px; color: #27c93f;">> [SUCCESS] Loading User Module: STUDENT_YEAR_1</p>
        <p style="margin: 2px; color: #58a6ff;">> [INFO] Detect Interest: ARTIFICIAL_INTELLIGENCE (Confidence: 99.9%)</p>
        <p style="margin: 2px; color: #58a6ff;">> [INFO] Detect Interest: CYBER_SECURITY (Confidence: 98.5%)</p>
        <p style="margin: 2px; color: #58a6ff;">> [INFO] Detect Hardware: NVIDIA_RTX_TARGET_ACQUIRED</p>
        <p style="margin: 2px; color: #e3b341;">> [WARN] Sleep Deprivation Detected. Suggestion: Coffee.exe</p>
        <p style="margin: 2px; color: #27c93f;">> [SUCCESS] Mounting "Github Repositories"... Done.</p>
        <p style="margin: 2px; color: #27c93f;">> [SUCCESS] System Ready. Welcome, Ozgur.</p>
        <br/>
        <p style="margin: 2px;">$ _<span style="animation: blink 1s infinite;">█</span></p>
    </td>
  </tr>
</table>
</div>


</code></pre>
</td>
</tr>
</table>
</div>

---

<h2 align="center">🛠️ /usr/bin/skill_metrics</h2>
<p align="center"><i>Quantified analysis of technical capabilities.</i></p>

<div align="center">
<table width="95%" style="border-spacing: 20px; border-collapse: separate;">
  <tr>
    <td width="50%" valign="top" style="background-color: #161b22; padding: 20px; border-radius: 10px; border: 1px solid #30363d;">
      <h3 align="center" style="color: #58a6ff;">&lt; Programming Languages /&gt;</h3>
      
<div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>Python (AI & Scripting)</span>
          <span>90%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 90%; background: linear-gradient(90deg, #3776AB, #64ffda); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

 <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>C++ (Algorithms & Systems)</span>
          <span>75%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 75%; background: linear-gradient(90deg, #00599C, #64ffda); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

 <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>C (Embedded / Kernel)</span>
          <span>70%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 70%; background: linear-gradient(90deg, #A8B9CC, #64ffda); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

<div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>Java (OOP)</span>
          <span>60%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 60%; background: linear-gradient(90deg, #ED8B00, #64ffda); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

 <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>JavaScript (Web)</span>
          <span>65%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 65%; background: linear-gradient(90deg, #F7DF1E, #64ffda); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>
    </td>

<td width="50%" valign="top" style="background-color: #161b22; padding: 20px; border-radius: 10px; border: 1px solid #30363d;">
      <h3 align="center" style="color: #ff7b72;">&lt; Frameworks & CyberSec /&gt;</h3>
      
  <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>TensorFlow / Pandas / NumPy</span>
          <span>80%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 80%; background: linear-gradient(90deg, #FF6F00, #ff7b72); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

<div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>Kali Linux & Bash Scripting</span>
          <span>85%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 85%; background: linear-gradient(90deg, #000000, #ff7b72); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

 <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>Wireshark / Nmap / OSI Model</span>
          <span>70%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 70%; background: linear-gradient(90deg, #1679A7, #ff7b72); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>

 <div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>React & Node.js</span>
          <span>50%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 50%; background: linear-gradient(90deg, #61DAFB, #ff7b72); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>
      
<div style="margin-bottom: 15px;">
        <div style="display: flex; justify-content: space-between; color: #c9d1d9; font-family: monospace; font-size: 14px;">
          <span>Git / Docker / VS Code</span>
          <span>95%</span>
        </div>
        <div style="width: 100%; background-color: #30363d; height: 8px; border-radius: 4px; margin-top: 5px;">
          <div style="width: 95%; background: linear-gradient(90deg, #F05032, #ff7b72); height: 100%; border-radius: 4px;"></div>
        </div>
      </div>
    </td>
  </tr>
</table>
</div>

---

    

</div>


</div>

---

<h2 align="center">📊 /proc/stats/github</h2>

<div align="center">
  <a href="https://github.com/Ozgurkalcik">
    <img src="https://github-readme-stats.vercel.app/api?username=Ozgurkalcik&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&bg_color=0d1117&title_color=64ffda&icon_color=00f2ff" height="180px" alt="Ozgur Kalcik Stats" />
  </a>
  <a href="https://github.com/Ozgurkalcik">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ozgurkalcik&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=64ffda" height="180px" alt="Top Languages" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Ozgurkalcik&theme=tokyonight&hide_border=true&background=0D1117&ring=00f2ff&fire=ff0055&currStreakNum=ffffff" alt="Streak Stats" />
</div>

<br/>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ozgurkalcik&theme=tokyonight" alt="Profile Summary" />
</div>

---

<h2 align="center">🐍 /bin/run_snake.py</h2>
<p align="center">
  <img src="https://github.com/Ozgurkalcik/Ozgurkalcik/blob/output/github-contribution-grid-snake.svg" alt="Snake Animation" width="100%" />
</p>

---

<div align="center">
  
  <br/>
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Quote"/>
  <br/><br/>
  
  <h3 align="center">📫 Initiate Communication Protocol</h3>
  
  <p>
    <a href="mailto:ozgurkalx@gmail.com"><img src="https://img.shields.io/badge/EMAIL-ozgurkalx%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
    <a href="https://linkedin.com/in/ozgurkalcik"><img src="https://img.shields.io/badge/LINKEDIN-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
    <a href="https://instagram.com/"><img src="https://img.shields.io/badge/INSTAGRAM-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
    <a href="https://discord.com/"><img src="https://img.shields.io/badge/DISCORD-Chat-5865F2?style=for-the-badge&logo=discord&logoColor=white"/></a>
    <a href="https://medium.com/"><img src="https://img.shields.io/badge/MEDIUM-Read_Blogs-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  </p>

  <br/>

  <svg width="100%" height="50" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="25" x2="100%" y2="25" stroke="#30363d" stroke-width="2" />
    <circle cx="50%" cy="25" r="10" fill="#0d1117" stroke="#64ffda" stroke-width="2" />
    <circle cx="50%" cy="25" r="4" fill="#64ffda">
      <animate attributeName="opacity" values="1;0;1" dur="2s" repeatCount="indefinite" />
    </circle>
  </svg>
  
  <p style="font-family: monospace; color: #8b949e; font-size: 10px;">
    SYSTEM ID: OZ-2025-ENG <br/>
    LOCATION: TURKIYE // STATUS: ACTIVE <br/>
    © 2025 Ozgur Kalcik. All rights reserved.
  </p>
</div>
