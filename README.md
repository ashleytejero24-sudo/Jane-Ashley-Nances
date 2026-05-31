
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jane Ashley Nances | UTS v2.0</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
:root {
--primary: #3b82f6;
--secondary: #a855f7;
--success: #22c55e;
--bg-dark: #020617;
--card-bg: #ffffff;
}

* { box-sizing: border-box; scroll-behavior: smooth; }

body {
font-family: 'Inter', -apple-system, sans-serif;
margin: 0;
background-color: #f1f5f9;
color: #1e293b;
}

/* Clean Navigation [Requirement: Clean layout and navigation] */
nav {
background: rgba(255, 255, 255, 0.8);
backdrop-filter: blur(12px);
padding: 1.2rem 10%;
display: flex;
justify-content: space-between;
align-items: center;
position: sticky;
top: 0;
z-index: 1000;
border-bottom: 1px solid rgba(0,0,0,0.05);
}

.nav-logo { font-weight: 900; color: var(--primary); font-size: 1.2rem; }

nav ul { display: flex; list-style: none; gap: 30px; margin: 0; padding: 0; }

nav a {
text-decoration: none; color: #64748b;
font-weight: 700; font-size: 0.75rem; text-transform: uppercase;
}

/* Home (Introduction) [Requirement: Suggested Section Home] */
.hero {
height: 70vh;
background: linear-gradient(135deg, var(--bg-dark) 0%, #1e293b 100%);
color: white;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
text-align: center;
padding: 0 10%;
}

.hero h1 { font-size: 4rem; margin: 0; letter-spacing: -3px; }

.system-status {
background: rgba(255,255,255,0.1);
padding: 8px 20px;
border-radius: 50px;
font-family: monospace;
font-size: 0.9rem;
margin-bottom: 25px;
color: var(--success);
border: 1px solid rgba(34, 197, 94, 0.3);
}

.identity-icon {
width: 130px;
height: 130px;
border-radius: 50%;
border: 4px solid var(--primary);
margin-bottom: 25px;
box-shadow: 0 0 30px rgba(59, 130, 246, 0.3);
}

.container { max-width: 1100px; margin: -50px auto 50px; padding: 20px; position: relative; z-index: 10; }

/* Section Layouts [Requirement: The 3 sections are required] */
section {
background: var(--card-bg);
padding: 60px;
border-radius: 40px;
margin-bottom: 60px;
box-shadow: 0 15px 35px rgba(0,0,0,0.03);
border: 1px solid #e2e8f0;
}

h2 { font-size: 2.2rem; margin-bottom: 40px; color: var(--bg-dark); border-left: 6px solid var(--primary); padding-left: 20px; }

.grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }

.card {
padding: 35px;
background: #f8fafc;
border-radius: 25px;
border: 1px solid #f1f5f9;
transition: transform 0.3s ease;
}

.card:hover { transform: translateY(-8px); border-color: var(--primary); }

.card i { font-size: 2rem; color: var(--secondary); margin-bottom: 25px; display: block; }

/* Future IT Progress [Requirement 7, 8] */
.progress-container { margin-top: 20px; }
.progress-label { display: flex; justify-content: space-between; font-weight: 800; font-size: 0.75rem; margin-bottom: 8px; }
.progress-bar { height: 10px; background: #e2e8f0; border-radius: 10px; overflow: hidden; }
.progress-fill { height: 100%; background: linear-gradient(90deg, var(--primary), var(--secondary)); }

/* Letter Section [Requirement 10] */
.letter-wrap {
background: var(--bg-dark);
color: #f1f5f9;
padding: 50px;
border-radius: 35px;
font-style: italic;
position: relative;
line-height: 2;
}

footer { text-align: center; padding: 60px; color: #94a3b8; font-size: 0.75rem; letter-spacing: 1px; }

@media (max-width: 768px) {
.hero h1 { font-size: 2.5rem; }
nav ul { display: none; }
section { padding: 40px 20px; }
}
</style>
</head>
<body>

<nav>
<div class="nav-logo">JANE ASHLEY NANCES</div>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#holistic">Holistic Reflection</a></li>
<li><a href="#future">IT Identity</a></li>
<li><a href="#plan">Upgrade Plan</a></li>
</ul>
</nav>

<header class="hero" id="home">

<img src="https://static.wikia.nocookie.net/deathbattle/images/8/8f/Portrait.makima.png" alt="Persona Icon" class="identity-icon">
<span style="color: var(--primary); font-weight: 800; letter-spacing: 2px;">JANE ASHLEY NANCES | BSIT</span>
<h1>Ashley : version 2.0</h1>

</header>

<div class="container">

<section id="holistic">
<h2>01. Me Holistically</h2>
<div class="grid">
<div class="card">
<i class="fas fa-user-circle"></i>
<h3>Physical Self</h3>
<p>I’m still figuring out my body image. Some days I feel okay, other days I compare myself to people on TikTok and Instagram. My self-esteem isn’t only about looks, but lack of sleep from coding definitely makes me feel worse. I’m trying to eat better, move a bit more, and stop treating sleep like it’s optional during midterms. When I feel physically okay, I think clearer and debug faster.</p>
</div>
<div class="card">
<i class="fas fa-wallet"></i>
<h3>Material & Economic</h3>
<p>As a student, my main possessions are my laptop, phone, and a lot of free software. My lifestyle is pretty simple: budget meals, secondhand clothes, and spending only on things that help with school. Money’s tight right now, but I see it as temporary. I’m using what I have now to build skills for better opportunities later.</p>
</div>
<div class="card">
<i class="fas fa-star"></i>
<h3>Spiritual & Sexual</h3>
<p>I’m not super religious, but I hold onto values like honesty, responsibility, and doing the right thing even when no one’s watching. For me, meaning comes from learning and helping others through tech. Even a small project that makes someone’s life easier feels worth it. Those values keep me grounded when school gets overwhelming.</p>
</div>
<div class="card">
<i class="fas fa-laptop-code"></i>
<h3>Digital Self</h3>
<p>Online, I’m more confident and curious. I post my projects, ask questions in group chats, and follow developers I look up to. Offline, I’m quieter and take time to open up. BSIT is pushing me to speak up more in class and group work. I want my online and offline selves to match — someone who’s learning and not afraid to say “I don’t know yet.”</p>
</div>
</div>
</section>

<section id="future">
<h2>02. Future IT Professional</h2>
<div class="grid">
<div class="card">
<h3>Dream Career</h3>
<p>Aiming to become a <strong>Cybersecurity Analyst</strong>. I aspire to build and secure digital fortresses for an evolving world.</p>
<div class="progress-container">
<div class="progress-label"><span>SKILL DEVELOPMENT</span><span>75%</span></div>
<div class="progress-bar"><div class="progress-fill" style="width: 75%;"></div></div>
</div>
</div>
<div class="card">
<h3>Ethical Responsibility</h3>
As someone in IT, I’ll have access to data and systems people trust me with. That means protecting privacy, not misusing access, and speaking up against shady practices. I want to build things that are secure by design, not just functional. Ethics matter when one mistake can leak someone’s information.
</p>
</div>
</div>
</section>

<section id="plan">
<h2>03. Version 2.0 Plan</h2>
<div class="grid">
<div class="card">
<h3>Personal Goals</h3>
<p><strong>Short-term:</strong> Pass this semester without burning out, finish one personal project, and get comfortable with Git.<br><strong>Long-term:</strong> Graduate with a solid portfolio, get an internship by 3rd year, and be confident in one IT specialization.
</p>
</div>
<div class="card">
<h3>Concrete Action Plan</h3>
<p>I will dedicate 1 hour daily to coding projects and engage in technical communities to "upgrade" my social-technical skills.</p>
</div>

<div class="card">
<h3>Areas for improvement</h3>
<p>Time management, asking for help earlier, and cutting down on procrastination disguised as “research.” I also need to speak up more in group work.</p>
</div>

<div class="card">
<h3>How I will upgrade myself</h3>
<p>Treat learning like a skill I need to practice daily. Get feedback often and reflect at the end of each semester on what worked and what didn’t. Take care of my health so I don’t burn out. Surround myself with people who push me to be better.</p>
</div>
</div>

<div class="letter-wrap" style="margin-top: 50px;">
<i class="fas fa-quote-left" style="font-size: 2rem; color: var(--primary); margin-bottom: 20px; display: block;"></i>
<h3 style="color: var(--primary); font-style: normal; margin-top: 0;">Letter to My Present Self</h3>
"Dear Jane Ashley, I know things feel messy right now. You’re tired, stressed, and sometimes you wonder if you picked the right course. But you’re still here, and that already means a lot.

It’s okay to struggle with code. It’s okay to ask questions. Don’t forget to eat and sleep — you code worse when you’re exhausted.

Future you is grateful you didn’t quit. This semester is just one chapter. Keep going"

<p style="text-align: right; font-weight: 800; font-style: normal; margin-top: 30px;">— Jane Ashley, v2.0</p>
</div>
</section>

</div>

<footer>
<p>FINAL REQUIREMENT IN UNDERSTANDING THE SELF (UTS)</p>
<p>JANE ASHLEY NANCES | BSIT STUDENT | MAY 2026</p>
</footer>

</body>
</html>


