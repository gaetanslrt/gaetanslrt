<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Gaetan — EPITA · Scribocracy · Aerospace</title>
  <meta name="description" content="Profil GitHub de Gaetan — étudiant EPITA, passionné d'aérospatiale, créateur de Scribocracy. Compétences en CS, physique, finance." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#7c3aed; --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.02);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;color:#e6eef8;background:linear-gradient(180deg,var(--bg),#071028);}
    a{color:inherit;text-decoration:none}
    .container{max-width:980px;margin:40px auto;padding:24px}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#0ea5a4);display:flex;align-items:center;justify-content:center;color:white;font-weight:800;font-size:28px;box-shadow:0 10px 30px rgba(0,0,0,0.6)}

    h1{margin:0;font-size:28px}
    h2{margin:6px 0;color:var(--muted);font-weight:400}

    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge img{height:34px;display:block}

    .grid{display:grid;grid-template-columns:1fr 340px;gap:20px;margin-top:26px}
    .card{background:linear-gradient(180deg,var(--card),var(--glass));border-radius:12px;padding:18px;box-shadow:0 6px 20px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}

    .about p{color:var(--muted);margin:0 0 10px}

    .skills{display:grid;grid-template-columns:repeat(auto-fill,minmax(120px,1fr));gap:10px}
    .skill{display:flex;gap:10px;align-items:center;padding:8px;border-radius:8px;background:var(--glass-2);border:1px solid rgba(255,255,255,0.02)}
    .skill img{width:28px;height:28px}
    .skill span{font-weight:600;font-size:13px}

    .projects{display:grid;gap:12px}
    .project{display:flex;flex-direction:column;gap:8px;padding:12px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);border:1px solid rgba(255,255,255,0.025)}
    .project a{font-weight:700}
    .project small{color:var(--muted)}

    .contact{display:flex;gap:8px;flex-wrap:wrap}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:8px 12px;border-radius:10px;background:var(--glass);border:1px solid rgba(255,255,255,0.03)}

    footer{color:var(--muted);font-size:13px;margin-top:20px;text-align:center}

    /* Responsive */
    @media (max-width:900px){
      .grid{grid-template-columns:1fr}
      header{flex-direction:column;align-items:flex-start}
      .avatar{width:84px;height:84px;border-radius:12px;font-size:20px}
    }
  </style>
</head>
<body>
  <main class="container">
    <header>
      <div class="avatar">GS</div>
      <div>
        <h1>Gaetan — étudiant à <a href="https://epita.fr/" target="_blank" rel="noopener">EPITA</a></h1>
        <h2>🤖 Informatique · Physique · Finance · Passion aérospatiale</h2>

        <div class="badges" aria-hidden>
          <!-- Badges: reuse original shields -->
          <div class="badge"><img src="https://img.shields.io/badge/GNU%20Bash-4EAA25.svg?style=for-the-badge&logo=GNU-Bash&logoColor=white" alt="Bash"></div>
          <div class="badge"><img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" alt="Python"></div>
          <div class="badge"><img src="https://img.shields.io/badge/Rust-000000.svg?style=for-the-badge&logo=Rust&logoColor=white" alt="Rust"></div>
          <div class="badge"><img src="https://img.shields.io/badge/C-A8B9CC.svg?style=for-the-badge&logo=C&logoColor=black" alt="C"></div>
          <div class="badge"><img src="https://img.shields.io/badge/Flutter-02569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter"></div>
        </div>
      </div>
    </header>

    <section class="grid" aria-label="Profil principal">
      <div>
        <div class="card about">
          <h3>À propos</h3>
          <p>Étudiant à EPITA, je mixe l'informatique, la physique et la finance — et j'adore l'aérospatial. Je construis des outils simples, rapides et élégants (ex. <a href="https://scribocracy.com/" target="_blank" rel="noopener">Scribocracy</a>).</p>
          <p>J'aime prototyper : apps Flutter, outils web statiques, scripts Rust/C/Python et projets ops sur Linux/OVH/Cloudflare.</p>

          <h4>Compétences clés</h4>
          <div class="skills" role="list">
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat-square&logo=HTML5&logoColor=white" alt="HTML"><span>HTML &amp; CSS</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/JavaScript-323330.svg?style=flat-square&logo=javascript&logoColor=white" alt="JS"><span>JS / Node</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat-square&logo=Python&logoColor=white" alt="Python"><span>Python</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/C-A8B9CC.svg?style=flat-square&logo=C&logoColor=black" alt="C"><span>C &amp; systèmes</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/Rust-000000.svg?style=flat-square&logo=Rust&logoColor=white" alt="Rust"><span>Rust</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/OCaml-EC6813.svg?style=flat-square&logo=OCaml&logoColor=white" alt="OCaml"><span>OCaml</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/Flutter-02569B.svg?style=flat-square&logo=Flutter&logoColor=white" alt="Flutter"><span>Flutter / Dart</span></div>
            <div class="skill" role="listitem"><img src="https://img.shields.io/badge/DevOps-2F855A.svg?style=flat-square&logo=cloudflare&logoColor=white" alt="DevOps"><span>Cloud &amp; Ops</span></div>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>Projets récents</h3>
          <div class="projects">
            <div class="project">
              <a href="https://scribocracy.com/" target="_blank" rel="noopener">Scribocracy</a>
              <small>La prise de notes minimaliste que j'ai créée — rapide, sans distractions.</small>
            </div>

            <div class="project">
              <a href="https://whitesloth-search.pages.dev" target="_blank" rel="noopener">WhiteSloth Search</a>
              <small>Moteur de recherche "lazy" — expérience personnelle et optimisée.</small>
            </div>

            <div class="project">
              <a href="https://horizonapp.pages.dev" target="_blank" rel="noopener">Horizon</a>
              <small>Application météo moderne : UI claire, info utile rapidement.</small>
            </div>

            <div class="project">
              <a href="https://meditrackpro.pages.dev" target="_blank" rel="noopener">MediTrackPro</a>
              <small>Générateur de documents d'état médical (utilitaire).</small>
            </div>

            <div class="project">
              <a href="https://alphazuluspotting.pages.dev" target="_blank" rel="noopener">AlphaZuluSpotting</a>
              <small>Site de planespotting (photos gérées par un photographe privé).</small>
            </div>
          </div>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3>Contact &amp; réseaux</h3>
          <p class="contact">
            <a class="btn" href="https://x.com/gaetanslrt" target="_blank" rel="noopener">X / Twitter</a>
            <a class="btn" href="https://www.linkedin.com/in/gaetan-suillerot/" target="_blank" rel="noopener">LinkedIn</a>
            <a class="btn" href="mailto:hello@example.com">Email</a>
          </p>

          <h4 style="margin-top:12px">Intérêts</h4>
          <p class="about"><small class="muted">Aérospatiale, propulsion, safetly-critical systems, finance quant, signal processing.</small></p>

          <h4 style="margin-top:10px">Statut</h4>
          <p class="about"><small class="muted">Étudiant @ EPITA — développement actif de projets personnels et contributions open-source.</small></p>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>Liens utiles</h3>
          <ul style="padding-left:18px;margin:8px 0 0;color:var(--muted)">
            <li><a href="https://scribocracy.com/">Scribocracy</a></li>
            <li><a href="https://whitesloth-search.pages.dev">WhiteSloth Search</a></li>
            <li><a href="https://horizonapp.pages.dev">Horizon</a></li>
          </ul>
        </div>
      </aside>
    </section>

    <footer>
      <small>Crée par Gaetan — <a href="https://scribocracy.com/">Scribocracy</a> · <em>Forkez / personnalisez</em></small>
    </footer>
  </main>
</body>
</html>
