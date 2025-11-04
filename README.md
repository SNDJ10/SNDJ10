<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sanjay D — Portfolio & Resume</title>
  <meta name="description" content="Sanjay D — Java Full Stack Developer | Portfolio, projects, resume and contact." />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#6ee7b7;--muted:#94a3b8;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:linear-gradient(180deg,#081126 0%,#071026 60%);color:#e6eef6;-webkit-font-smoothing:antialiased}
    .wrap{max-width:980px;margin:48px auto;padding:28px;border-radius:18px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 30px rgba(2,6,23,0.6);}
    header{display:flex;gap:18px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:16px;flex:0 0 96px;background:linear-gradient(135deg,#0b1220,#0c1b2b);display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent);font-size:28px;}
    h1{margin:0;font-size:26px}
    h2{margin:0;font-size:14px;color:var(--muted);font-weight:600}
    .top-right{margin-left:auto;text-align:right}
    .badge{display:inline-block;margin-top:8px;padding:6px 10px;border-radius:999px;background:var(--glass);font-weight:600;color:var(--accent);border:1px solid rgba(110,231,183,0.08)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:22px;margin-top:22px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));padding:18px;border-radius:14px;border:1px solid rgba(255,255,255,0.03)}
    .section-title{font-size:13px;color:var(--muted);letter-spacing:0.6px;margin-bottom:10px}
    .about p{margin:0 0 12px 0;color:#cfe8ff}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .chip{padding:8px 10px;border-radius:999px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02);font-weight:600;font-size:13px;color:#d8f7ef}
    .contact-list{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:8px}
    .contact-list a{color:#dbeefd;text-decoration:none;font-weight:600}
    .projects{display:flex;flex-direction:column;gap:12px}
    .project{padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.005));border:1px solid rgba(255,255,255,0.02)}
    .project h3{margin:0;font-size:15px}
    .project p{margin:6px 0 0 0;color:var(--muted);font-size:13px}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    .download{display:inline-block;margin-top:12px;padding:10px 14px;border-radius:12px;background:linear-gradient(90deg,var(--accent),#4fd1c5);color:#012; font-weight:800;text-decoration:none;border:0}
    .meta{font-size:13px;color:var(--muted)}
    @media(max-width:860px){.grid{grid-template-columns:1fr;}.top-right{text-align:left;margin-left:0}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">SD</div>
      <div>
        <h1>Sanjay D</h1>
        <h2>Java Full Stack Developer • Computer Science Engineer (VTU)</h2>
        <div class="meta">Graduate 2025 — Shree Devi Institute of Technology, Mangalore</div>
      </div>
      <div class="top-right">
        <div class="badge">Seeking: Full-time / Internship — Java Full Stack</div>
        <div style="margin-top:8px" class="meta">Currently: Xworkz (Java Full Stack Developer)</div>
      </div>
    </header>

    <div class="grid">
      <!-- Left column -->
      <div>
        <section class="card about">
          <div class="section-title">About</div>
          <p>Hi — I'm Sanjay, a passionate and detail-focused Java Full Stack Developer. I build clean, maintainable web applications using Java on the backend and modern frontend practices. I love turning ideas into polished, user-friendly products.</p>
          <p>My work combines strong object-oriented fundamentals with practical full-stack experience. I enjoy collaborating in teams, learning new tools, and improving code quality every day.</p>
          <a class="download" href="#" onclick="alert('Resume download placeholder - replace with real link')">Download Resume (PDF)</a>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Key Skills</div>
          <div class="skills">
            <span class="chip">Java</span>
            <span class="chip">Spring Boot</span>
            <span class="chip">REST APIs</span>
            <span class="chip">HTML • CSS • JavaScript</span>
            <span class="chip">React (basics)</span>
            <span class="chip">SQL • MySQL</span>
            <span class="chip">Git • GitHub</span>
            <span class="chip">Unit Testing</span>
            <span class="chip">OOP • Data Structures</span>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Selected Projects</div>
          <div class="projects">
            <div class="project">
              <h3>Project A — E-Commerce Backend</h3>
              <p>Design and implementation of a RESTful microservice using Spring Boot, JWT authentication, and MySQL. Focused on maintainability and clean API design.</p>
            </div>
            <div class="project">
              <h3>Project B — Portfolio Website</h3>
              <p>Responsive single-page portfolio showcasing projects, blog links, and contact form. Built with HTML/CSS and lightweight JS.</p>
            </div>
            <div class="project">
              <h3>Project C — Task Manager (Team)</h3>
              <p>Collaborative task manager with role-based access, implemented using Spring Boot and React. Practiced CI and code reviews.</p>
            </div>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Experience</div>
          <div style="display:flex;flex-direction:column;gap:8px">
            <div>
              <strong>Xworkz</strong> — Java Full Stack Developer (Current)
              <div class="meta">Worked on backend services, integrated APIs, and collaborated with frontend teams to ship features.</div>
            </div>
          </div>
        </section>

      </div>

      <!-- Right column -->
      <aside>
        <section class="card">
          <div class="section-title">Contact</div>
          <ul class="contact-list">
            <li><strong>Phone:</strong> <a href="tel:+918618793041">+91 86187 93041</a></li>
            <li><strong>Email:</strong> <a href="mailto:sanjaysanji700@gmail.com">sanjaysanji700@gmail.com</a></li>
            <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sanjay-d-61457b229" target="_blank" rel="noopener">linkedin.com/in/sanjay-d-61457b229</a></li>
            <li><strong>Instagram:</strong> <a href="https://instagram.com/thename_is_sanjay" target="_blank" rel="noopener">@thename_is_sanjay</a></li>
            <li><strong>Location:</strong> Mangalore, India</li>
          </ul>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Education</div>
          <div><strong>Shree Devi Institute of Technology — B.E. Computer Science</strong>
            <div class="meta">Visvesvaraya Technological University (VTU) — Graduating 2025</div>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <div class="section-title">Quick Links</div>
          <div style="display:flex;flex-direction:column;gap:8px">
            <a href="#" class="chip">GitHub: github.com/your-username</a>
            <a href="#" class="chip">Projects & Demos</a>
            <a href="#" class="chip">Blog / Articles</a>
          </div>
        </section>

      </aside>
    </div>

    <footer>
      <div>Thanks for visiting — feel free to clone this README, customize it, and host it on GitHub Pages.</div>
    </footer>
  </div>
</body>
</html>
