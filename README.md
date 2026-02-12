<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Template</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
        }
        
        .panel {
            background: white;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            overflow: auto;
        }
        
        h1 {
            color: #24292f;
            margin-bottom: 20px;
            font-size: 24px;
            border-bottom: 2px solid #d0d7de;
            padding-bottom: 10px;
        }
        
        .markdown-code {
            background: #f6f8fa;
            border: 1px solid #d0d7de;
            border-radius: 6px;
            padding: 16px;
            font-family: 'Courier New', monospace;
            font-size: 13px;
            line-height: 1.6;
            white-space: pre-wrap;
            word-wrap: break-word;
            color: #24292f;
            max-height: 80vh;
            overflow-y: auto;
        }
        
        .preview {
            max-height: 80vh;
            overflow-y: auto;
        }
        
        .preview h2 {
            color: #24292f;
            margin: 20px 0 10px 0;
            font-size: 20px;
        }
        
        .preview h3 {
            color: #24292f;
            margin: 15px 0 8px 0;
            font-size: 16px;
        }
        
        .preview p {
            color: #57606a;
            line-height: 1.6;
            margin: 10px 0;
        }
        
        .preview img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
        
        .preview ul {
            margin: 10px 0;
            padding-left: 30px;
        }
        
        .preview li {
            color: #57606a;
            margin: 5px 0;
        }
        
        .preview a {
            color: #0969da;
            text-decoration: none;
        }
        
        .preview a:hover {
            text-decoration: underline;
        }
        
        .badge-container {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            margin: 10px 0;
        }
        
        .badge {
            display: inline-block;
        }
        
        .stats-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin: 15px 0;
        }
        
        .header-section {
            text-align: center;
            padding: 20px 0;
            border-bottom: 1px solid #d0d7de;
            margin-bottom: 20px;
        }
        
        .header-section h1 {
            border: none;
            font-size: 32px;
            margin-bottom: 10px;
        }
        
        .copy-btn {
            background: #2da44e;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
            margin-top: 10px;
        }
        
        .copy-btn:hover {
            background: #2c974b;
        }
        
        @media (max-width: 968px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="panel">
            <h1>📝 Markdown Code</h1>
            <div class="markdown-code" id="markdown-content">&lt;!-- Replace 'YourUsername' with your GitHub username --&gt;

&lt;div align="center"&gt;
  &lt;img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2E9EF7&center=true&vCenter=true&width=435&lines=Hi+%F0%9F%91%8B+I'm+Your+Name;Full+Stack+Developer;Open+Source+Enthusiast" alt="Typing SVG" /&gt;
&lt;/div&gt;

## 🚀 About Me

I'm a passionate developer who loves building innovative solutions and contributing to open source. Currently focusing on web development and cloud technologies.

- 🔭 I'm currently working on **[Your Project Name]**
- 🌱 I'm currently learning **[Technology/Framework]**
- 👯 I'm looking to collaborate on **Open Source Projects**
- 💬 Ask me about **JavaScript, React, Node.js**
- 📫 How to reach me: **your.email@example.com**
- ⚡ Fun fact: **I debug with console.log() and I'm not ashamed!**

## 🛠️ Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)

### Database
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Tools & Platforms
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

## 📊 GitHub Stats

&lt;div align="center"&gt;
  &lt;img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=radical" alt="GitHub Stats" height="165"&gt;
  &lt;img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YourUsername&layout=compact&theme=radical" alt="Top Languages" height="165"&gt;
&lt;/div&gt;

&lt;div align="center"&gt;
  &lt;img src="https://github-readme-streak-stats.herokuapp.com/?user=YourUsername&theme=radical" alt="GitHub Streak" /&gt;
&lt;/div&gt;

## 🏆 GitHub Trophies

&lt;div align="center"&gt;
  &lt;img src="https://github-profile-trophy.vercel.app/?username=YourUsername&theme=radical&no-frame=true&no-bg=false&margin-w=4&row=1" alt="GitHub Trophies" /&gt;
&lt;/div&gt;

## 📈 Contribution Graph

&lt;div align="center"&gt;
  &lt;img src="https://github-readme-activity-graph.vercel.app/graph?username=YourUsername&theme=react-dark&hide_border=true" alt="Contribution Graph" /&gt;
&lt;/div&gt;

## 🔥 Featured Projects

### [Project Name 1](https://github.com/YourUsername/project1)
A brief description of your amazing project. What problem does it solve?

**Tech Stack:** React, Node.js, MongoDB

### [Project Name 2](https://github.com/YourUsername/project2)
Another awesome project description here.

**Tech Stack:** Python, Django, PostgreSQL

## 📫 Connect With Me

&lt;div align="center"&gt;
  &lt;a href="https://linkedin.com/in/yourusername"&gt;
    &lt;img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /&gt;
  &lt;/a&gt;
  &lt;a href="https://twitter.com/yourusername"&gt;
    &lt;img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /&gt;
  &lt;/a&gt;
  &lt;a href="mailto:your.email@example.com"&gt;
    &lt;img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /&gt;
  &lt;/a&gt;
  &lt;a href="https://yourwebsite.com"&gt;
    &lt;img src="https://img.shields.io/badge/-Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" /&gt;
  &lt;/a&gt;
&lt;/div&gt;

---

&lt;div align="center"&gt;
  &lt;img src="https://komarev.com/ghpvc/?username=YourUsername&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile Views" /&gt;
&lt;/div&gt;

&lt;div align="center"&gt;
  ⭐️ From [YourUsername](https://github.com/YourUsername)
&lt;/div&gt;</div>
            <button class="copy-btn" onclick="copyToClipboard()">📋 Copy Markdown</button>
        </div>
        
        <div class="panel">
            <h1>👁️ Preview</h1>
            <div class="preview">
                <div class="header-section">
                    <h1>Hi 👋 I'm Your Name</h1>
                    <p style="color: #2E9EF7; font-size: 18px;">Full Stack Developer | Open Source Enthusiast</p>
                </div>
                
                <h2>🚀 About Me</h2>
                <p>I'm a passionate developer who loves building innovative solutions and contributing to open source. Currently focusing on web development and cloud technologies.</p>
                
                <ul>
                    <li>🔭 I'm currently working on <strong>[Your Project Name]</strong></li>
                    <li>🌱 I'm currently learning <strong>[Technology/Framework]</strong></li>
                    <li>👯 I'm looking to collaborate on <strong>Open Source Projects</strong></li>
                    <li>💬 Ask me about <strong>JavaScript, React, Node.js</strong></li>
                    <li>📫 How to reach me: <strong>your.email@example.com</strong></li>
                    <li>⚡ Fun fact: <strong>I debug with console.log() and I'm not ashamed!</strong></li>
                </ul>
                
                <h2>🛠️ Tech Stack</h2>
                
                <h3>Languages</h3>
                <div class="badge-container">
                    <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
                    <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
                    <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
                    <img src="https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white" alt="Java">
                </div>
                
                <h3>Frontend</h3>
                <div class="badge-container">
                    <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
                    <img src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white" alt="Vue.js">
                    <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
                    <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
                    <img src="https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
                </div>
                
                <h2>📊 GitHub Stats</h2>
                <div class="stats-container">
                    <img src="https://github-readme-stats.vercel.app/api?username=YourUsername&show_icons=true&theme=radical" alt="GitHub Stats" style="width: 100%;">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=YourUsername&theme=radical" alt="GitHub Streak" style="width: 100%;">
                </div>
                
                <h2>📫 Connect With Me</h2>
                <div class="badge-container">
                    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                    <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
                    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                    <img src="https://img.shields.io/badge/-Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
                </div>
            </div>
        </div>
    </div>
    
    <script>
        function copyToClipboard() {
            const markdown = document.getElementById('markdown-content').textContent;
            navigator.clipboard.writeText(markdown).then(() => {
                const btn = document.querySelector('.copy-btn');
                btn.textContent = '✅ Copied!';
                setTimeout(() => {
                    btn.textContent = '📋 Copy Markdown';
                }, 2000);
            });
        }
    </script>
</body>
</html>
