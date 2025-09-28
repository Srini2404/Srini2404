<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Srinivasan M | AI & ML Researcher</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        /* Reset & Fonts */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Inter', sans-serif; line-height: 1.6; background: #f5f6fa; color: #333; }
        a { text-decoration: none; color: inherit; }
        img { max-width: 100%; display: block; }

        /* Container */
        .container { max-width: 1000px; margin: auto; padding: 2rem; }

        /* Header */
        header { text-align: center; margin-bottom: 3rem; }
        header h1 { font-size: 3rem; color: #0e75b6; }
        header h3 { font-weight: 400; margin-top: 1rem; color: #555; }

        /* Profile Views */
        .profile-views { margin-top: 1rem; }

        /* Roles Section */
        .roles { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1rem; margin: 3rem 0; }
        .role-card { background: #fff; padding: 1.5rem; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.05); transition: transform 0.3s; }
        .role-card:hover { transform: translateY(-5px); }
        .role-card a { color: #0e75b6; font-weight: 600; }

        /* Info Section */
        .info { display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 3rem; }
        .info div { flex: 1; min-width: 200px; padding: 1rem; background: #fff; border-radius: 12px; box-shadow: 0 6px 20px rgba(0,0,0,0.05); }

        /* Socials */
        .socials { text-align: center; margin: 2rem 0; }
        .socials a { display: inline-block; margin: 0 0.5rem; font-size: 1.5rem; color: #0e75b6; transition: color 0.3s; }
        .socials a:hover { color: #ff4757; }

        /* Tech Stack */
        .tech-stack { display: flex; flex-wrap: wrap; gap: 1rem; justify-content: center; margin-bottom: 3rem; }
        .tech-stack code { display: flex; align-items: center; justify-content: center; flex-direction: column; background: #fff; padding: 0.5rem; border-radius: 10px; box-shadow: 0 6px 15px rgba(0,0,0,0.05); transition: transform 0.3s; width: 70px; }
        .tech-stack code:hover { transform: translateY(-5px); }
        .tech-stack img { width: 40px; height: 40px; margin-bottom: 0.3rem; }

        /* Stats */
        .stats { text-align: center; margin-bottom: 3rem; }
        .stats img { border-radius: 12px; margin: 0.5rem 0; }

        /* Footer */
        footer { text-align: center; padding: 2rem 0; font-size: 0.9rem; color: #777; border-top: 1px solid #ddd; }

        /* Responsive */
        @media(max-width: 768px){
            header h1 { font-size: 2.2rem; }
            header h3 { font-size: 1rem; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi 👋, I'm Srinivasan</h1>
            <h3>Final year student IIIT Bangalore. I’m an <strong>AI and Machine Learning researcher</strong>, currently at <strong>SUTD Singapore</strong> after a rewarding stint with <strong>IBM Research</strong>. I’m passionate about making AI <strong>smarter, safer, and human-aligned</strong>. When not coding, you’ll find me <strong>hiking or behind a camera</strong>.</h3>
            <div class="profile-views">
                <img src="https://komarev.com/ghpvc/?username=srini2404&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views">
            </div>
        </header>

        <section class="roles">
            <div class="role-card"><strong>Visiting Student</strong> - <a href="https://www.sutd.edu.sg/">SUTD Singapore</a></div>
            <div class="role-card"><strong>Ex-Research Intern</strong> - <a href="https://research.ibm.com/">IBM Research</a></div>
            <div class="role-card"><strong>Ex-Marketing Lead</strong> - <a href="https://www.tedxiiitbangalore.in/">TEDxIIITB</a></div>
            <div class="role-card"><strong>Ex-Member</strong> - <a href="https://github.com/ComputX-research-group">ComputX</a></div>
            <div class="role-card"><strong>Ex-Member</strong> - <a href="https://www.instagram.com/chhayachitra_iiitb/">Chhayachitra</a></div>
            <div class="role-card"><strong>Teaching Assistant</strong> - IIIT Bangalore</div>
        </section>

        <section class="info">
            <div><strong>Currently Working On:</strong> Machine Learning</div>
            <div><strong>Exploring:</strong> Recommendation Systems & Image Segmentation</div>
            <div><strong>Projects:</strong> <a href="https://github.com/Srini2404">GitHub</a></div>
            <div><strong>Ask me about:</strong> Spring, React, PyTorch</div>
            <div><strong>Contact:</strong> m.srinivasan@iiitb.ac.in</div>
            <div><strong>Experiences:</strong> <a href="https://www.overleaf.com/project/64131d76edab08cf121bc187">Overleaf</a></div>
            <div><strong>Fun Fact:</strong> Love to talk about aviation!</div>
        </section>

        <section class="socials">
            <a href="https://www.linkedin.com/in/srinivasan-m-668154228" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://instagram.com/srinivasan_2404" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://discord.gg/srinivasan1490" target="_blank"><i class="fab fa-discord"></i></a>
        </section>

        <section class="tech-stack">
            <code><img src="https://user-images.githubusercontent.com/25181517/192107854-765620d7-f909-4953-a6da-36e1ef69eea6.png" alt="HTTP"/><span>HTTP</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/192107858-fe19f043-c502-4009-8c47-476fc89718ad.png" alt="REST"/><span>REST</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png" alt="Git"/><span>Git</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png" alt="GitHub"/><span>GitHub</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="Jupyter"/><span>Jupyter</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/183897015-94a058a6-b86e-4e42-a37e-bf92061753e5.png" alt="React"/><span>React</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/183568594-85e280a7-0d7e-4d1a-9028-c8c2209e073c.png" alt="Node.js"/><span>Node.js</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML"/><span>HTML</span></code>
            <code><img src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS"/><span>CSS</span></code>
        </section>

        <section class="stats">
            <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=srini2404&theme=radical&hide_border=true&include_all_commits=false&count_private=true" alt="GitHub Stats">
            <br>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=srini2404&theme=radical&hide_border=true" alt="GitHub Streak">
        </section>

        <footer>
            &copy; 2025 Srinivasan M. | Made with ❤️ using GitHub Pages
        </footer>
    </div>
</body>
</html>
