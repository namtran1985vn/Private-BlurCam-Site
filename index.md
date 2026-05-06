---
title: Private BlurCam Support
permalink: /
---

<style>
:root {
  --ink: #15211c;
  --muted: #5a6861;
  --line: #d9e4de;
  --paper: #fbfdfb;
  --soft: #eef6f1;
  --mint: #2f7d5c;
  --teal: #0d6f7c;
  --amber: #b96f24;
  --rose: #b84b5f;
}
.pbc-page {
  color: var(--ink);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  line-height: 1.55;
}
.pbc-page * { box-sizing: border-box; }
.pbc-page a { color: var(--teal); font-weight: 700; }
.pbc-hero {
  min-height: 78vh;
  display: grid;
  align-items: end;
  padding: clamp(28px, 5vw, 72px);
  margin: -22px calc(50% - 50vw) 0;
  background:
    linear-gradient(90deg, rgba(12, 25, 20, .86), rgba(12, 25, 20, .58), rgba(12, 25, 20, .18)),
    url("https://images.unsplash.com/photo-1498837167922-ddd27525d352?auto=format&fit=crop&w=1800&q=80") center/cover;
}
.pbc-hero-inner { max-width: 1160px; margin: 0 auto; width: 100%; }
.pbc-kicker {
  color: #b9f0d5;
  font-size: .82rem;
  font-weight: 800;
  letter-spacing: .08em;
  text-transform: uppercase;
}
.pbc-hero h1 {
  max-width: 850px;
  margin: 10px 0 16px;
  color: #fff;
  font-size: clamp(2.35rem, 7vw, 5.8rem);
  line-height: .96;
  letter-spacing: 0;
}
.pbc-hero p {
  max-width: 680px;
  color: rgba(255,255,255,.9);
  font-size: clamp(1.04rem, 2vw, 1.34rem);
}
.pbc-actions { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 26px; }
.pbc-button {
  display: inline-flex;
  align-items: center;
  min-height: 48px;
  padding: 12px 18px;
  border-radius: 8px;
  text-decoration: none;
  background: #fff;
  color: var(--ink) !important;
  font-weight: 800;
}
.pbc-button.secondary {
  background: rgba(255,255,255,.14);
  color: #fff !important;
  border: 1px solid rgba(255,255,255,.36);
}
.pbc-band { margin: 0 calc(50% - 50vw); padding: clamp(38px, 6vw, 76px) clamp(20px, 5vw, 72px); }
.pbc-band.soft { background: var(--soft); }
.pbc-band.dark { background: #16231d; color: #f6fbf8; }
.pbc-wrap { max-width: 1160px; margin: 0 auto; }
.pbc-eyebrow { color: var(--mint); font-weight: 800; text-transform: uppercase; font-size: .78rem; letter-spacing: .08em; }
.pbc-band.dark .pbc-eyebrow { color: #9ce3c0; }
.pbc-grid { display: grid; gap: 18px; }
.pbc-grid.two { grid-template-columns: repeat(2, minmax(0, 1fr)); align-items: center; }
.pbc-grid.three { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.pbc-card {
  background: #fff;
  border: 1px solid var(--line);
  border-radius: 8px;
  padding: 22px;
}
.pbc-band.dark .pbc-card { background: rgba(255,255,255,.08); border-color: rgba(255,255,255,.16); }
.pbc-stat { font-size: clamp(2rem, 4vw, 3.6rem); line-height: 1; font-weight: 900; color: var(--mint); }
.pbc-band.dark .pbc-stat { color: #b9f0d5; }
.pbc-card h3 { margin: 10px 0 8px; font-size: 1.15rem; }
.pbc-card p, .pbc-card li { color: var(--muted); }
.pbc-band.dark .pbc-card p, .pbc-band.dark .pbc-card li { color: rgba(246,251,248,.82); }
.pbc-photo {
  width: 100%;
  min-height: 360px;
  border-radius: 8px;
  object-fit: cover;
  border: 1px solid var(--line);
}
.pbc-feature-list { display: grid; gap: 12px; margin-top: 18px; }
.pbc-feature {
  display: grid;
  grid-template-columns: 34px 1fr;
  gap: 12px;
  align-items: start;
}
.pbc-icon {
  display: grid;
  place-items: center;
  width: 34px;
  height: 34px;
  border-radius: 8px;
  background: #dff1e7;
  color: var(--mint);
  font-weight: 900;
}
.pbc-table { width: 100%; border-collapse: collapse; overflow: hidden; border-radius: 8px; background: #fff; }
.pbc-table th, .pbc-table td { padding: 14px; border-bottom: 1px solid var(--line); text-align: left; vertical-align: top; }
.pbc-table th { background: #e6f2ec; }
.pbc-note { font-size: .92rem; color: var(--muted); }
@media (max-width: 780px) {
  .pbc-hero { min-height: 74vh; padding: 28px 20px; }
  .pbc-grid.two, .pbc-grid.three { grid-template-columns: 1fr; }
  .pbc-photo { min-height: 250px; }
  .pbc-table { display: block; overflow-x: auto; }
}
</style>

<main class="pbc-page">
  <section class="pbc-hero">
    <div class="pbc-hero-inner">
      <div class="pbc-kicker">Private camera for personal health and diet logs</div>
      <h1>Record your routine without exposing everyone around you.</h1>
      <p>Private BlurCam helps you capture meals, workouts, body-progress check-ins, grocery finds, and family health moments with automatic on-device face blur, optional metadata removal, and no cloud video processing.</p>
      <div class="pbc-actions">
        <a class="pbc-button" href="{{ site.baseurl }}/marketing/">See the health use cases</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/privacy/">Read privacy policy</a>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Why this matters</div>
      <h2>Health tracking is useful. Health media is sensitive.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <div class="pbc-stat">2 in 5+</div>
          <h3>U.S. adults live with obesity</h3>
          <p>The CDC reports obesity is common and costly in the U.S. Visual food and routine logs can support self-review, but they should not force people to expose private surroundings.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">Moderate</div>
          <h3>evidence for self-monitoring</h3>
          <p>USDA evidence reviews connect diet or weight self-monitoring, inside broader behavior programs, with improved weight-loss outcomes. The app is a private capture tool, not a diet plan.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">70%</div>
          <h3>low trust in AI companies</h3>
          <p>Pew found many Americans have little or no trust in companies using AI responsibly. Private BlurCam keeps face detection and blur rendering on the iPhone.</p>
        </article>
      </div>
      <p class="pbc-note">Sources: <a href="https://www.cdc.gov/obesity/adult-obesity-facts/index.html">CDC Adult Obesity Facts</a>, <a href="https://nesr.usda.gov/what-relationship-between-use-diet-and-body-weight-self-monitoring-strategies-and-body-weight">USDA Nutrition Evidence Systematic Review</a>, <a href="https://www.pewresearch.org/short-reads/2023/10/18/key-findings-about-americans-and-data-privacy/">Pew Research Center data privacy findings</a>.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?auto=format&fit=crop&w=1300&q=80" alt="Colorful meal ingredients on a table">
      <div>
        <div class="pbc-eyebrow">Everyday health use cases</div>
        <h2>Use your camera as a private memory aid.</h2>
        <div class="pbc-feature-list">
          <div class="pbc-feature"><div class="pbc-icon">1</div><div><strong>Meal review</strong><br>Film grocery hauls, meal prep, restaurant plates, or pantry swaps without showing children, friends, or strangers in the background.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">2</div><div><strong>Progress check-ins</strong><br>Capture short personal clips for your own review while reducing accidental exposure of faces, room details, and location metadata.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">3</div><div><strong>Coach or family sharing</strong><br>Share a useful clip while keeping bystanders, family members, and audio identity better protected.</div></div>
        </div>
      </div>
    </div>
  </section>

  <section class="pbc-band dark">
    <div class="pbc-wrap pbc-grid two">
      <div>
        <div class="pbc-eyebrow">What the app actually does</div>
        <h2>Privacy tools built into the capture flow.</h2>
        <div class="pbc-feature-list">
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Automatic real-time face blur</strong><br>Faces are detected locally with Apple Vision and blurred before the clip is saved.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Offline recording workflow</strong><br>Camera processing does not need an upload, account, or cloud render queue.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Pro privacy controls</strong><br>Higher resolution, metadata removal, voice protection, watermarking, social export quality, and Smooth Skin controls.</div></div>
        </div>
      </div>
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1518611012118-696072aa579a?auto=format&fit=crop&w=1300&q=80" alt="Person stretching on a mat indoors">
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Support</div>
      <h2>Common questions</h2>
      <div class="pbc-grid two">
        <article class="pbc-card">
          <h3>Is this a medical or diet app?</h3>
          <p>No. Private BlurCam does not diagnose, treat, prescribe, count calories, or replace professional advice. It is a private camera utility for personal recording and sharing.</p>
        </article>
        <article class="pbc-card">
          <h3>Do my videos upload for AI processing?</h3>
          <p>No. Face detection, blur rendering, metadata removal, and voice protection are designed to run locally on your device.</p>
        </article>
        <article class="pbc-card">
          <h3>What does Free include?</h3>
          <p>Free includes basic face blur at 480p. Pro unlocks Full HD, 2K, 4K, Untraceable Mode, Voice Protection, metadata removal, Smooth Skin, watermarking, and export controls.</p>
        </article>
        <article class="pbc-card">
          <h3>How do I get help?</h3>
          <p>Email <a href="mailto:private.blur.cam@outlook.com">private.blur.cam@outlook.com</a> for support, privacy questions, or subscription help.</p>
        </article>
      </div>
    </div>
  </section>
</main>
