## Hi there 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Alzabi — Portfolio</title>
  <meta name="description" content="Portfolio of Alzabi — young innovator, web developer, and aspiring pilot & IT professor." />
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#7c5cff;
      --glass: rgba(255,255,255,0.04);
      --radius:12px;
      color-scheme: dark;
      color: #e6eef8;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#081028,#071224);}
    .container{max-width:980px;margin:36px auto;padding:28px}

    header{display:flex;gap:18px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:18px;background:linear-gradient(135deg,var(--accent),#4ec5ff);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:#021024;box-shadow:0 6px 18px rgba(0,0,0,0.6)}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    main{margin-top:22px;display:grid;grid-template-columns:1fr 320px;gap:20px}
    .card{background:var(--card);padding:18px;border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6);}

    .section{margin-bottom:14px}
    .section h2{margin:0 0 8px;font-size:16px}
    ul{margin:0;padding-left:18px;color:var(--muted)}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-size:13px;margin:6px 6px 0 0}

    .skills{display:flex;flex-wrap:wrap}
    .projects .project{border-radius:10px;padding:12px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);margin-bottom:10px}

    aside .card{position:sticky;top:28px}
    .contact a{display:inline-block;margin-right:10px;text-decoration:none;color:var(--accent);}

    footer{margin-top:20px;text-align:center;color:var(--muted);font-size:13px}

    /* Responsive */
    @media (max-width:880px){main{grid-template-columns:1fr;}
      aside .card{position:static}
      .avatar{width:76px;height:76px;font-size:22px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">A</div>
      <div>
        <h1>Alzabi</h1>
        <p class="lead">Young innovator • Web developer (beginner) • Grade 9 student at ABS Global School, Trikaripur, Kerala</p>
      </div>
    </header>

    <main>
      <section>
        <div class="card">
          <div class="section">
            <h2>About Me</h2>
            <p style="color:var(--muted);margin:8px 0 0;">I am <strong>Alzabi</strong>, a curious and driven Grade 9 student who loves technology, building websites, and exploring innovative ideas. I’m passionate about aviation and computer science, and I aim to become both a pilot and an IT professor.</p>
          </div>

          <div class="section">
            <h2>What I Do</h2>
            <ul>
              <li>Build simple, responsive websites using HTML &amp; CSS.</li>
              <li>Experiment with small tech prototypes and learn new tools.</li>
              <li>Study software, gadgets, and aviation systems.</li>
            </ul>
          </div>

          <div class="section">
            <h2>Ambitions</h2>
            <ul>
              <li>Become a professional <strong>pilot</strong> — love for flight and aviation systems.</li>
              <li>Become an <strong>IT professor</strong> — teach, research, and guide future technologists.</li>
            </ul>
