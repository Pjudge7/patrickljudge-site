<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="referrer" content="strict-origin-when-cross-origin" />
  <meta http-equiv="Permissions-Policy" content="camera=(), microphone=(), geolocation=(), payment=(), usb=(), interest-cohort=()" />
  <title>Patrick L. Judge | Executive Digital Business Card</title>
  <meta name="description" content="Patrick L. Judge — Chief AI Strategy & Digital Transformation (CSDO). Executive advisory, governance, digital transformation, board advisory and operational model design." />
  <meta property="og:title" content="Patrick L. Judge | Executive Digital Business Card" />
  <meta property="og:description" content="Executive digital business card for Patrick L. Judge. AI strategic planning, governance & compliance, digital & enterprise transformation, board advisory and operational model design." />
  <meta property="og:image" content="https://www.patrickljudge.com/card/assets/patrick-l-judge-business-card.png" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://www.patrickljudge.com/card/" />
  <meta name="theme-color" content="#071a2d" />
  <style>
    :root {
      --navy:#071a2d;
      --navy-2:#0d2742;
      --navy-3:#102f4e;
      --gold:#b88a3d;
      --gold-soft:#d7b173;
      --ink:#edf2f8;
      --muted:#c0ccda;
      --line:rgba(255,255,255,.12);
      --panel:rgba(10,24,42,.78);
      --shadow:0 28px 70px rgba(0,0,0,.28);
      --radius:28px;
    }
    * { box-sizing:border-box; }
    html { scroll-behavior:smooth; }
    body {
      margin:0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color:var(--ink);
      background:
        radial-gradient(circle at top left, rgba(184,138,61,.14), transparent 28%),
        radial-gradient(circle at bottom right, rgba(50,110,180,.12), transparent 24%),
        linear-gradient(135deg, #06121f 0%, #0a1f36 52%, #071a2d 100%);
      min-height:100vh;
    }
    .page { max-width:1280px; margin:0 auto; padding:42px 22px 28px; }
    .wrap {
      display:grid;
      grid-template-columns:minmax(0,1.18fr) minmax(320px,.82fr);
      gap:30px;
      align-items:center;
    }
    .card-stage {
      position:relative;
      padding:12px;
      border-radius:32px;
      background:linear-gradient(180deg, rgba(255,255,255,.07), rgba(255,255,255,.03));
      border:1px solid rgba(255,255,255,.08);
      box-shadow:var(--shadow);
      overflow:hidden;
    }
    .card-stage::before {
      content:"";
      position:absolute; inset:-25% auto auto -10%;
      width:220px; height:220px; border-radius:50%;
      background:radial-gradient(circle, rgba(184,138,61,.22), transparent 68%);
      pointer-events:none;
      filter:blur(12px);
    }
    .card-img {
      width:100%; display:block; border-radius:24px; background:#fff;
      box-shadow:0 20px 48px rgba(0,0,0,.2);
    }
    .panel {
      position:relative;
      background:var(--panel);
      border:1px solid rgba(255,255,255,.10);
      border-radius:var(--radius);
      padding:34px;
      box-shadow:var(--shadow);
      backdrop-filter:blur(14px) saturate(140%);
    }
    .panel::after {
      content:"";
      position:absolute; inset:0;
      border-radius:inherit;
      padding:1px;
      background:linear-gradient(135deg, rgba(184,138,61,.34), rgba(255,255,255,.04), rgba(184,138,61,.18));
      -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
      -webkit-mask-composite: xor;
      mask-composite: exclude;
      pointer-events:none;
    }
    .eyebrow {
      display:inline-flex; align-items:center; gap:8px;
      color:var(--gold-soft); text-transform:uppercase; letter-spacing:.16em;
      font-size:.78rem; font-weight:800; margin-bottom:14px;
    }
    .eyebrow::before { content:""; width:28px; height:1px; background:currentColor; display:inline-block; }
    h1 {
      margin:0; color:#fff; font-family: Georgia, "Times New Roman", serif;
      font-size:clamp(2.25rem, 5vw, 3.75rem); line-height:.98;
    }
    .title { margin:14px 0 6px; color:var(--gold-soft); font-weight:700; font-size:1.08rem; }
    .company { margin:0; color:var(--muted); line-height:1.55; font-size:1rem; }
    .divider { height:1px; background:linear-gradient(90deg, rgba(184,138,61,.55), rgba(255,255,255,.08)); margin:22px 0; }
    .summary {
      margin:0; color:#e7edf5; line-height:1.65; font-size:.98rem;
    }
    .button-grid {
      display:grid; grid-template-columns:1fr 1fr; gap:12px; margin:24px 0 22px;
    }
    .button {
      display:flex; align-items:center; justify-content:center;
      min-height:50px; padding:12px 14px; border-radius:999px;
      text-decoration:none; font-weight:800; letter-spacing:.01em;
      transition:transform .16s ease, box-shadow .16s ease, border-color .16s ease;
      box-shadow:0 8px 20px rgba(0,0,0,.15);
    }
    .button:hover, .button:focus-visible { transform:translateY(-1px); outline:none; }
    .button.primary {
      color:#081a2c;
      background:linear-gradient(90deg, #34c6f3 0%, #8c84f4 100%);
    }
    .button.secondary {
      color:#f3f7fb; background:rgba(255,255,255,.03);
      border:1px solid rgba(255,255,255,.12);
    }
    .button.secondary:hover, .button.secondary:focus-visible { border-color:rgba(184,138,61,.5); box-shadow:0 12px 24px rgba(0,0,0,.18); }
    .section-title {
      margin:0 0 12px; color:#fff; font-size:1rem; font-weight:800;
    }
    .chips { display:flex; flex-wrap:wrap; gap:10px; }
    .chip {
      border:1px solid rgba(255,255,255,.10);
      background:rgba(255,255,255,.04);
      color:#f0f4f9; border-radius:999px;
      padding:10px 13px; font-size:.92rem; line-height:1;
      box-shadow:inset 0 0 0 1px rgba(255,255,255,.02);
    }
    .info-grid {
      display:grid; grid-template-columns:1fr; gap:12px; margin-top:22px;
    }
    .info-item {
      display:flex; gap:10px; align-items:flex-start;
      padding:12px 14px; border-radius:18px;
      background:rgba(255,255,255,.03);
      border:1px solid rgba(255,255,255,.08);
    }
    .info-label { min-width:86px; color:var(--gold-soft); font-weight:800; }
    .info-value, .info-value a { color:#f3f7fb; text-decoration:none; word-break:break-word; }
    .info-value a:hover, .info-value a:focus-visible { color:#fff; text-decoration:underline; }
    .note {
      margin-top:18px; color:var(--muted); font-size:.9rem; line-height:1.55;
      padding:14px 16px; border-radius:18px;
      background:rgba(255,255,255,.03); border:1px dashed rgba(184,138,61,.26);
    }
    footer {
      text-align:center; color:#91a2b6; font-size:.82rem; padding:18px 0 0;
    }
    @media (max-width: 980px) {
      .wrap { grid-template-columns:1fr; }
      .panel { padding:28px 22px; }
      .page { padding:24px 14px 20px; }
    }
    @media (max-width: 560px) {
      .button-grid { grid-template-columns:1fr; }
      .info-item { flex-direction:column; gap:4px; }
      .info-label { min-width:auto; }
    }
  </style>
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Person",
    "name":"Patrick L. Judge",
    "jobTitle":"Chief AI Strategy & Digital Transformation (CSDO)",
    "url":"https://www.patrickljudge.com/card/",
    "email":"mailto:pjudge@pljca.com",
    "telephone":"+1-404-421-7252",
    "address":{
      "@type":"PostalAddress",
      "addressLocality":"Atlanta",
      "addressRegion":"GA",
      "addressCountry":"US"
    },
    "sameAs":["https://www.linkedin.com/in/patrickljudge","https://www.patrickljudge.com/"],
    "worksFor":{
      "@type":"Organization",
      "name":"PLJ Consulting, Advisory & Fractional Executive Leadership"
    }
  }
  </script>
</head>
<body>
  <main class="page">
    <section class="wrap" aria-label="Patrick L. Judge digital business card">
      <div class="card-stage">
        <img class="card-img" src="assets/patrick-l-judge-business-card.png" alt="Patrick L. Judge business card with photo, contact details, services, and an embedded QR code to save contact information" />
      </div>

      <aside class="panel">
        <div class="eyebrow">Executive Digital Card</div>
        <h1>Patrick L. Judge</h1>
        <p class="title">Chief AI Strategy &amp; Digital Transformation (CSDO)</p>
        <p class="company">PLJ Consulting, Advisory &amp; Fractional Executive Leadership</p>
        <div class="divider" aria-hidden="true"></div>
        <p class="summary">Helping organizations shape AI strategy, strengthen governance, accelerate transformation, and improve operating models with executive-level clarity and measurable business outcomes.</p>

        <div class="button-grid" aria-label="Primary contact actions">
          <a class="button primary" href="patrick-l-judge.vcf" download>Save Contact</a>
          <a class="button secondary" href="mailto:pjudge@pljca.com">Email</a>
          <a class="button secondary" href="tel:+14044217252">Call</a>
          <a class="button secondary" href="https://www.linkedin.com/in/patrickljudge" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        </div>

        <section aria-labelledby="services-title">
          <h2 class="section-title" id="services-title">Core Advisory Services</h2>
          <div class="chips">
            <span class="chip">AI Strategic Planning</span>
            <span class="chip">Governance &amp; Compliance</span>
            <span class="chip">Digital &amp; Enterprise Transformation</span>
            <span class="chip">Board Advisory</span>
            <span class="chip">Operational Model Design</span>
          </div>
        </section>

        <div class="info-grid" aria-label="Contact details">
          <div class="info-item"><div class="info-label">Email</div><div class="info-value"><a href="mailto:pjudge@pljca.com">pjudge@pljca.com</a></div></div>
          <div class="info-item"><div class="info-label">Phone</div><div class="info-value"><a href="tel:+14044217252">+1 (404) 421-7252</a></div></div>
          <div class="info-item"><div class="info-label">Website</div><div class="info-value"><a href="https://www.patrickljudge.com" target="_blank" rel="noopener noreferrer">www.patrickljudge.com</a></div></div>
          <div class="info-item"><div class="info-label">LinkedIn</div><div class="info-value"><a href="https://www.linkedin.com/in/patrickljudge" target="_blank" rel="noopener noreferrer">linkedin.com/in/patrickljudge</a></div></div>
        </div>

        <p class="note">The QR code is embedded directly on the card for a clean, single-QR experience. Visitors can either scan the card or tap <strong>Save Contact</strong>.</p>
      </aside>
    </section>
    <footer>© Patrick L. Judge. All rights reserved.</footer>
  </main>
</body>
</html>
