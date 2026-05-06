---
title: Private BlurCam - Private Health & Diet Camera
permalink: /marketing/
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
}
.pbc-page { color: var(--ink); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; line-height: 1.55; }
.pbc-page * { box-sizing: border-box; }
.pbc-page a { color: var(--teal); font-weight: 750; }
.pbc-hero {
  min-height: 76vh;
  display: grid;
  align-items: end;
  margin: -22px calc(50% - 50vw) 0;
  padding: clamp(28px, 5vw, 72px);
  background:
    linear-gradient(90deg, rgba(16, 25, 24, .88), rgba(16, 25, 24, .6), rgba(16, 25, 24, .14)),
    url("https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=1800&q=80") center/cover;
}
.pbc-wrap { max-width: 1160px; margin: 0 auto; width: 100%; }
.pbc-kicker { color: #b9f0d5; font-size: .82rem; font-weight: 850; letter-spacing: .08em; text-transform: uppercase; }
.pbc-hero h1 { color: #fff; max-width: 900px; margin: 10px 0 16px; font-size: clamp(2.35rem, 7vw, 5.8rem); line-height: .96; letter-spacing: 0; }
.pbc-hero p { color: rgba(255,255,255,.9); max-width: 700px; font-size: clamp(1.04rem, 2vw, 1.34rem); }
.pbc-actions { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 26px; }
.pbc-button { display: inline-flex; align-items: center; min-height: 48px; border-radius: 8px; padding: 12px 18px; text-decoration: none; background: #fff; color: var(--ink) !important; font-weight: 850; }
.pbc-button.secondary { background: rgba(255,255,255,.14); color: #fff !important; border: 1px solid rgba(255,255,255,.36); }
.pbc-band { margin: 0 calc(50% - 50vw); padding: clamp(38px, 6vw, 76px) clamp(20px, 5vw, 72px); }
.pbc-band.soft { background: var(--soft); }
.pbc-band.dark { background: #16231d; color: #f6fbf8; }
.pbc-eyebrow { color: var(--mint); font-weight: 850; text-transform: uppercase; font-size: .78rem; letter-spacing: .08em; }
.pbc-band.dark .pbc-eyebrow { color: #9ce3c0; }
.pbc-grid { display: grid; gap: 18px; }
.pbc-grid.two { grid-template-columns: repeat(2, minmax(0, 1fr)); align-items: center; }
.pbc-grid.three { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.pbc-card { background: #fff; border: 1px solid var(--line); border-radius: 8px; padding: 22px; }
.pbc-band.dark .pbc-card { background: rgba(255,255,255,.08); border-color: rgba(255,255,255,.16); }
.pbc-card h3 { margin: 0 0 8px; }
.pbc-card p, .pbc-card li { color: var(--muted); }
.pbc-band.dark .pbc-card p, .pbc-band.dark .pbc-card li { color: rgba(246,251,248,.82); }
.pbc-photo { width: 100%; min-height: 360px; border-radius: 8px; object-fit: cover; border: 1px solid var(--line); }
.pbc-stat { font-size: clamp(2rem, 4vw, 3.6rem); line-height: 1; font-weight: 900; color: var(--mint); }
.pbc-table { width: 100%; border-collapse: collapse; background: #fff; border: 1px solid var(--line); border-radius: 8px; overflow: hidden; }
.pbc-table th, .pbc-table td { padding: 14px; border-bottom: 1px solid var(--line); text-align: left; vertical-align: top; }
.pbc-table th { background: #e6f2ec; }
.pbc-steps { counter-reset: step; display: grid; gap: 14px; }
.pbc-step { display: grid; grid-template-columns: 42px 1fr; gap: 14px; align-items: start; }
.pbc-step:before { counter-increment: step; content: counter(step); width: 42px; height: 42px; border-radius: 8px; display: grid; place-items: center; background: #dff1e7; color: var(--mint); font-weight: 900; }
.pbc-note { color: var(--muted); font-size: .92rem; }
@media (max-width: 780px) {
  .pbc-hero { min-height: 74vh; padding: 28px 20px; }
  .pbc-grid.two, .pbc-grid.three { grid-template-columns: 1fr; }
  .pbc-photo { min-height: 250px; }
  .pbc-table { display: block; overflow-x: auto; }
}
</style>

<main class="pbc-page">
  <section class="pbc-hero">
    <div class="pbc-wrap">
      <div class="pbc-kicker">Private BlurCam</div>
      <h1>A privacy camera for real-life health and diet recording.</h1>
      <p>Capture meal logs, progress clips, grocery notes, interviews, and family routine videos with real-time face blur before you save or share.</p>
      <div class="pbc-actions">
        <a class="pbc-button" href="{{ site.baseurl }}/">Support and FAQ</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/privacy/">Privacy details</a>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Market reality</div>
      <h2>People want health evidence, but they do not want accidental exposure.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <div class="pbc-stat">41.9%</div>
          <h3>adult obesity prevalence</h3>
          <p>CDC data shows obesity affects more than 2 in 5 U.S. adults. Many people use photos and short videos to review habits, meals, and progress.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">20</div>
          <h3>studies reviewed by USDA</h3>
          <p>USDA's evidence review found diet and weight self-monitoring can help in behavioral weight management programs, with adherence and frequency mattering.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">89%</div>
          <h3>worry about children’s privacy</h3>
          <p>Pew reports broad concern about social platforms knowing children's personal information. Face blur is especially relevant for family health content.</p>
        </article>
      </div>
      <p class="pbc-note">Sources: <a href="https://www.cdc.gov/obesity/adult-obesity-facts/index.html">CDC Adult Obesity Facts</a>, <a href="https://nesr.usda.gov/what-relationship-between-use-diet-and-body-weight-self-monitoring-strategies-and-body-weight">USDA Nutrition Evidence Systematic Review</a>, <a href="https://www.pewresearch.org/internet/2023/10/18/how-americans-view-data-privacy/">Pew Research Center data privacy report</a>.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <div>
        <div class="pbc-eyebrow">Positioning</div>
        <h2>Private BlurCam is not another calorie counter.</h2>
        <p>It solves the part most health apps ignore: how to safely capture the visual evidence around your routine. Use it before a nutrition appointment, while tracking meal prep, documenting walking routes, recording a workout form check, or sharing a grocery label with a coach.</p>
        <div class="pbc-steps">
          <div class="pbc-step"><div><strong>Open the private camera.</strong><br>Start in video or photo mode with face blur on by default.</div></div>
          <div class="pbc-step"><div><strong>Record the useful context.</strong><br>Meals, portions, kitchen setup, movement, or a short explanation.</div></div>
          <div class="pbc-step"><div><strong>Save or share with less leakage.</strong><br>Use Pro controls for metadata removal, voice protection, and higher-quality export.</div></div>
        </div>
      </div>
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1490818387583-1baba5e638af?auto=format&fit=crop&w=1300&q=80" alt="Healthy ingredients and fruit on a kitchen table">
    </div>
  </section>

  <section class="pbc-band dark">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Competitive proof</div>
      <h2>The privacy-camera category is real. Health and diet is an under-served wedge.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <h3>Direct competitors</h3>
          <p>Anonymous Camera and FaceHider both promote local/on-device anonymization. That validates demand, but most positioning is broad creator/privacy language.</p>
        </article>
        <article class="pbc-card">
          <h3>Indirect competitors</h3>
          <p>Calorie trackers and food diaries help with logging, but they usually do not solve bystander faces, home privacy, voice identity, or share-safe video capture.</p>
        </article>
        <article class="pbc-card">
          <h3>Native alternatives</h3>
          <p>iOS editing can help after capture, but it is manual and photo-oriented. Private BlurCam's stronger pitch is privacy applied during recording.</p>
        </article>
      </div>
      <p class="pbc-note">Competitor references: <a href="https://apps.apple.com/us/app/anonymous-camera/id1504102584">Anonymous Camera on the App Store</a>, <a href="https://apps.apple.com/us/app/facehider-blur-video-face/id6758146143">FaceHider on the App Store</a>.</p>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Free vs Pro</div>
      <h2>Start with basic privacy. Upgrade when quality and sharing controls matter.</h2>
      <table class="pbc-table">
        <thead>
          <tr><th>Feature</th><th>Free</th><th>Pro</th><th>Why health and diet users care</th></tr>
        </thead>
        <tbody>
          <tr><td>Real-time face blur</td><td>Included</td><td>Included</td><td>Protects family, bystanders, gym members, restaurant staff, and people in the background.</td></tr>
          <tr><td>Recording quality</td><td>480p</td><td>Full HD, 2K, 4K</td><td>Higher quality makes meal details, labels, movement form, and progress clips easier to review.</td></tr>
          <tr><td>Metadata removal</td><td>Off</td><td>On</td><td>Reduces hidden location, device, and capture details before sharing.</td></tr>
          <tr><td>Voice protection</td><td>Off</td><td>On</td><td>Useful when a clip includes personal narration or another person's voice.</td></tr>
          <tr><td>Watermark</td><td>Off</td><td>On</td><td>Adds attribution for creators, coaches, or progress-account content.</td></tr>
          <tr><td>Smooth Skin</td><td>Off</td><td>On</td><td>Optional appearance control for personal progress clips without changing the core privacy purpose.</td></tr>
        </tbody>
      </table>
      <p class="pbc-note">Private BlurCam is a consumer camera utility for personal use. It does not provide nutrition advice, medical advice, diagnosis, treatment, or guaranteed health outcomes.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=1300&q=80" alt="Person practicing yoga in a bright studio">
      <div>
        <div class="pbc-eyebrow">Best-fit users</div>
        <h2>Built for people who record health context in public or shared spaces.</h2>
        <ul>
          <li>Parents documenting family meals without posting children's faces.</li>
          <li>Diet and fitness creators who film in gyms, parks, restaurants, or grocery stores.</li>
          <li>People sharing progress clips with a coach, friend, or accountability group.</li>
          <li>Caregivers who need a personal record but want to avoid exposing family identity.</li>
          <li>Privacy-conscious users who prefer local processing and no cloud render queue.</li>
        </ul>
        <div class="pbc-actions">
          <a class="pbc-button" href="{{ site.baseurl }}/privacy/">Review privacy policy</a>
          <a class="pbc-button secondary" style="color: var(--ink) !important; border-color: var(--line);" href="mailto:private.blur.cam@outlook.com">Contact support</a>
        </div>
      </div>
    </div>
  </section>
</main>
