# Hi there! 👋 I'm Ragul Balaji

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vCenter=true&width=500&lines=Welcome+to+my+GitHub+Profile!;Computer+Science+Student;AI+%7C+Cybersecurity+%7C+Blockchain+Explorer;Python+%7C+C%2FC%2B%2B+%7C+SQL+Developer;Always+learning%2C+always+innovating!" alt="Typing SVG" />
</div>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ragul Balaji - Cyber Profile</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Orbitron:wght@400;700;900&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #0a0a0a;
            color: #00ff41;
            font-family: 'JetBrains Mono', monospace;
            overflow-x: hidden;
            min-height: 100vh;
        }

        .matrix-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -2;
            background: linear-gradient(135deg, #0f0f0f 0%, #1a1a1a 50%, #0f0f0f 100%);
        }

        .matrix-rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.1;
        }

        .hacker-gif {
            position: fixed;
            top: 50%;
            right: 5%;
            transform: translateY(-50%);
            width: 300px;
            height: auto;
            opacity: 0.15;
            filter: sepia(100%) hue-rotate(90deg) saturate(200%);
            z-index: -1;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            position: relative;
            z-index: 1;
        }

        .terminal-window {
            background: rgba(0, 0, 0, 0.9);
            border: 2px solid #00ff41;
            border-radius: 10px;
            box-shadow: 
                0 0 20px rgba(0, 255, 65, 0.3),
                inset 0 0 20px rgba(0, 255, 65, 0.1);
            overflow: hidden;
            backdrop-filter: blur(10px);
        }

        .terminal-header {
            background: linear-gradient(90deg, #00ff41, #00cc33);
            color: #000;
            padding: 0.5rem 1rem;
            display: flex;
            align-items: center;
            font-weight: bold;
        }

        .terminal-dots {
            display: flex;
            gap: 5px;
            margin-right: 1rem;
        }

        .dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #000;
        }

        .terminal-body {
            padding: 2rem;
            background: rgba(0, 0, 0, 0.95);
        }

        .prompt {
            color: #00ff41;
            margin-bottom: 1rem;
        }

        .prompt::before {
            content: "root@ragul:~$ ";
            color: #ff6b35;
            font-weight: bold;
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
        }

        .glitch-title {
            font-family: 'Orbitron', monospace;
            font-size: 3rem;
            font-weight: 900;
            color: #00ff41;
            text-shadow: 
                0 0 10px #00ff41,
                0 0 20px #00ff41,
                0 0 30px #00ff41;
            margin-bottom: 0.5rem;
            animation: glitchText 2s infinite;
        }

        @keyframes glitchText {
            0%, 90%, 100% { transform: translateX(0); }
            20% { transform: translateX(-2px); }
            40% { transform: translateX(2px); }
            60% { transform: translateX(-1px); }
            80% { transform: translateX(1px); }
        }

        .subtitle {
            color: #ff6b35;
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        .ascii-art {
            color: #00cc33;
            font-size: 0.8rem;
            white-space: pre;
            text-align: center;
            margin: 2rem 0;
            line-height: 1;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .info-block {
            background: rgba(0, 255, 65, 0.05);
            border: 1px solid #00ff41;
            border-radius: 8px;
            padding: 1.5rem;
            position: relative;
            overflow: hidden;
        }

        .info-block::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, #00ff41, transparent);
            animation: scanLine 3s infinite;
        }

        @keyframes scanLine {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .info-title {
            color: #ff6b35;
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .info-title::before {
            content: '>';
            color: #00ff41;
            font-weight: bold;
        }

        .info-content {
            line-height: 1.6;
        }

        .tag {
            display: inline-block;
            background: rgba(255, 107, 53, 0.2);
            color: #ff6b35;
            padding: 0.2rem 0.8rem;
            border-radius: 20px;
            font-size: 0.9rem;
            margin: 0.2rem;
            border: 1px solid #ff6b35;
        }

        .status-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(0, 255, 65, 0.1);
            border: 1px solid #00ff41;
            border-radius: 5px;
            padding: 1rem;
            margin: 2rem 0;
        }

        .status-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .status-icon {
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background: #00ff41;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        .command-output {
            margin: 1rem 0;
            padding: 1rem;
            background: rgba(0, 0, 0, 0.5);
            border-left: 3px solid #00ff41;
            font-family: 'JetBrains Mono', monospace;
        }

        .typewriter {
            overflow: hidden;
            border-right: 2px solid #00ff41;
            white-space: nowrap;
            animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #00ff41; }
        }

        .matrix-char {
            position: absolute;
            color: #00ff41;
            font-family: 'JetBrains Mono', monospace;
            font-size: 14px;
            animation: matrixFall linear infinite;
        }

        @keyframes matrixFall {
            0% {
                transform: translateY(-100vh);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh);
                opacity: 0;
            }
        }

        @media (max-width: 768px) {
            .glitch-title { font-size: 2rem; }
            .hacker-gif { display: none; }
            .info-grid { grid-template-columns: 1fr; }
            .status-bar { flex-direction: column; gap: 1rem; }
        }
    </style>
</head>
<body>
    <div class="matrix-bg"></div>
    <div class="matrix-rain" id="matrixRain"></div>
    
    <img src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" alt="Hacker Coding" class="hacker-gif">
    
    <div class="container">
        <div class="terminal-window">
            <div class="terminal-header">
                <div class="terminal-dots">
                    <div class="dot"></div>
                    <div class="dot"></div>
                    <div class="dot"></div>
                </div>
                <span>cyber_profile.exe - ACTIVE SESSION</span>
            </div>
            
            <div class="terminal-body">
                <div class="prompt typewriter">whoami</div>
                
                <div class="header">
                    <h1 class="glitch-title">RAGUL BALAJI</h1>
                    <div class="subtitle">[CYBER_WARRIOR] | [CODE_BREAKER] | [DIGITAL_ARCHITECT]</div>
                </div>

                <div class="ascii-art">
    ██████╗  █████╗  ██████╗ ██╗   ██╗██╗     
    ██╔══██╗██╔══██╗██╔════╝ ██║   ██║██║     
    ██████╔╝███████║██║  ███╗██║   ██║██║     
    ██╔══██╗██╔══██║██║   ██║██║   ██║██║     
    ██║  ██║██║  ██║╚██████╔╝╚██████╔╝███████╗
    ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝  ╚═════╝ ╚══════╝
                </div>

                <div class="status-bar">
                    <div class="status-item">
                        <div class="status-icon"></div>
                        <span>SYSTEM: ONLINE</span>
                    </div>
                    <div class="status-item">
                        <div class="status-icon"></div>
                        <span>LOCATION: COIMBATORE, TN</span>
                    </div>
                    <div class="status-item">
                        <div class="status-icon"></div>
                        <span>STATUS: LEARNING_MODE</span>
                    </div>
                </div>

                <div class="prompt">cat /home/ragul/profile.cfg</div>
                
                <div class="info-grid">
                    <div class="info-block">
                        <div class="info-title">🎯 CURRENT_MISSION</div>
                        <div class="info-content">
                            <strong>Primary Objective:</strong> Computer Science Student @ CIT<br>
                            <strong>Secondary Ops:</strong> Tech Enthusiast & Future Innovator<br>
                            <strong>Mission Statement:</strong> "Learning today, leading tomorrow!"
                        </div>
                    </div>

                    <div class="info-block">
                        <div class="info-title">🔥 ACTIVE_PROTOCOLS</div>
                        <div class="info-content">
                            <div class="tag">AI & Machine Learning</div>
                            <div class="tag">Cybersecurity</div>
                            <div class="tag">Blockchain Technology</div>
                            <div class="tag">Linux Systems</div>
                            <div class="tag">React Development</div>
                        </div>
                    </div>

                    <div class="info-block">
                        <div class="info-title">⚡ WEAPON_ARSENAL</div>
                        <div class="info-content">
                            <strong>Core Languages:</strong><br>
                            <div class="tag">Python</div>
                            <div class="tag">C/C++</div>
                            <div class="tag">SQL</div>
                            <br><strong>Reconnaissance Tools:</strong><br>
                            <div class="tag">Linux Terminal</div>
                            <div class="tag">React Framework</div>
                        </div>
                    </div>

                    <div class="info-block">
                        <div class="info-title">🚀 SYSTEM_STATUS</div>
                        <div class="info-content">
                            <strong>🎓 EDUCATION_MODULE:</strong> Running at CIT<br>
                            <strong>🤖 AI_LEARNING:</strong> Deep dive in progress...<br>
                            <strong>🔐 SECURITY_SCAN:</strong> Mastering fundamentals<br>
                            <strong>⛓️ BLOCKCHAIN_SYNC:</strong> Exploring distributed systems<br>
                            <strong>💻 PROJECT_BUILD:</strong> Python & React deployment active
                        </div>
                    </div>
                </div>

                <div class="command-output">
                    <div class="prompt">./connect_with_ragul.sh</div>
                    <div style="color: #00ff41; margin-top: 0.5rem;">
                        [SUCCESS] Connection established!<br>
                        [INFO] Thanks for scanning my profile!<br>
                        [INVITE] Let's collaborate and hack the future together! 🚀<br>
                        [STATUS] Ready for next command...
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Matrix rain effect
        function createMatrixRain() {
            const container = document.getElementById('matrixRain');
            const chars = '01アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン';
            
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const char = document.createElement('div');
                    char.className = 'matrix-char';
                    char.textContent = chars[Math.floor(Math.random() * chars.length)];
                    char.style.left = Math.random() * 100 + 'vw';
                    char.style.animationDuration = (Math.random() * 3 + 2) + 's';
                    char.style.animationDelay = Math.random() * 2 + 's';
                    container.appendChild(char);
                    
                    setTimeout(() => {
                        if (char.parentNode) {
                            char.parentNode.removeChild(char);
                        }
                    }, 5000);
                }, i * 200);
            }
        }

        // Start matrix rain
        createMatrixRain();
        setInterval(createMatrixRain, 3000);

        // Add typing effect to prompts
        document.addEventListener('DOMContentLoaded', function() {
            const prompts = document.querySelectorAll('.prompt');
            prompts.forEach((prompt, index) => {
                setTimeout(() => {
                    prompt.style.animation = 'typing 2s steps(40, end), blink-caret 0.75s step-end infinite';
                }, index * 1000);
            });
        });
    </script>
</body>
</html>

## 🛠️ Tech Arsenal

<div align="center">

### Programming Languages
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### Technologies & Frameworks
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

### Specialized Areas
![Artificial Intelligence](https://img.shields.io/badge/AI-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-000000?style=for-the-badge&logo=hackaday&logoColor=white)
![Blockchain](https://img.shields.io/badge/Blockchain-121D33?style=for-the-badge&logo=blockchain-dot-com&logoColor=white)

</div>

## 📊 GitHub Statistics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ragulbalaji&show_icons=true&theme=radical&include_all_commits=true&count_private=true&border_radius=10"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ragulbalaji&layout=compact&langs_count=8&theme=radical&border_radius=10"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ragulbalaji&theme=radical&border_radius=10" alt="GitHub Streak" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=ragulbalaji&label=Profile%20Views&color=brightgreen&style=for-the-badge" alt="Profile Views" />
  
  <br>
  
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake eating contributions" />
</div>

---

<div align="center">
  <h3>⭐️ From <a href="https://github.com/ragulbalaji">Ragul Balaji</a> with ❤️</h3>
  <p><em>Happy Coding! 🚀</em></p>
</div>
