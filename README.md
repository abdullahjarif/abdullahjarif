<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdullah Jarif | Full Stack Developer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: white;
        }

        header {
            text-align: center;
            margin-top: 50px;
        }

        header h1 {
            font-size: 2.5em;
            color: #61DAFB;
        }

        header h4 {
            font-size: 1.5em;
            color: #E34F26;
        }

        .intro {
            font-size: 1.1em;
            margin-top: 20px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .social-links a {
            color: #ffffff;
            text-decoration: none;
            padding: 10px;
            font-size: 1.3em;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }

        .social-links a:hover {
            background-color: #444444;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .tech-stack img {
            width: 50px;
            height: 50px;
            transition: transform 0.3s ease;
        }

        .tech-stack img:hover {
            transform: scale(1.2);
        }

        .github-stats {
            display: flex;
            justify-content: center;
            gap: 50px;
            margin-top: 40px;
        }

        .github-stats img {
            border-radius: 8px;
            border: 2px solid #444;
            padding: 10px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            header h4 {
                font-size: 1.2em;
            }
            .social-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>💫 Hi Pals, It's me Abdullah Jarif</h1>
        <h4>🔭 Frontend Fanatic | Code Explorer | Learning for Tomorrow</h4>
        <p class="intro">
            🌱 A passionate learner and full stack developer currently diving deep into
            <strong>React</strong>, <strong>AngularJS</strong>, and <strong>Node.js</strong>. <br>
            💬 Ask me about Frontend => JavaScript, React, Nodejs <br>
            🔭 I’m currently working on: TechWisdom Web Solution LTD. as Full Stack Developer
        </p>
    </header>

    <section>
        <h3 align="center">🌐 How to Reach Me</h3>
        <div class="social-links">
            <a href="https://discord.gg/8eTa6d6u" target="_blank">Discord</a>
            <a href="https://facebook.com/mustakim.jarif.393" target="_blank">Facebook</a>
            <a href="https://linkedin.com/in/abdullah-jarif-28414a24a" target="_blank">LinkedIn</a>
            <a href="mailto:22-46386-1@student.aiub.edu" target="_blank">Email</a>
        </div>
    </section>

    <section class="tech-stack">
        <h3 align="center">💻 Tech Stack</h3>
        <img src="https://img.shields.io/badge/React-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB" alt="React">
        <img src="https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
        <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
    </section>

    <section class="github-stats">
        <div>
            <img src="https://github-readme-stats.vercel.app/api?username=abdullahjarif&theme=dark&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats">
        </div>
        <div>
            <img src="https://nirzak-streak-stats.vercel.app/?user=abdullahjarif&theme=dark&hide_border=false" alt="GitHub Streak">
        </div>
    </section>
</body>
</html>
