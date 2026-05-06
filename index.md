---
title: Private BlurCam Support
permalink: /
---

<style>
:root {
  --ink: #141716;
  --muted: #5d6663;
  --line: #dfe7e4;
  --paper: #fbfcfb;
  --soft: #f0f6f3;
  --deep: #111817;
  --mint: #2f7d5c;
  --cyan: #126d78;
  --gold: #ad7a29;
}
.pbc-page { color: var(--ink); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; line-height: 1.55; }
.pbc-page * { box-sizing: border-box; }
.pbc-page a { color: var(--cyan); font-weight: 750; }
.pbc-hero {
  min-height: 78vh;
  display: grid;
  align-items: end;
  margin: -22px calc(50% - 50vw) 0;
  padding: clamp(28px, 5vw, 72px);
  background:
    linear-gradient(90deg, rgba(10, 14, 14, .9), rgba(10, 14, 14, .68), rgba(10, 14, 14, .18)),
    url("https://images.unsplash.com/photo-1492684223066-81342ee5ff30?auto=format&fit=crop&w=1800&q=82") center/cover;
}
.pbc-wrap { max-width: 1160px; margin: 0 auto; width: 100%; }
.pbc-kicker { color: #a9e8cd; font-size: .82rem; font-weight: 850; letter-spacing: .08em; text-transform: uppercase; }
.pbc-hero h1 { color: #fff; max-width: 920px; margin: 10px 0 16px; font-size: clamp(2.25rem, 7vw, 5.7rem); line-height: .96; letter-spacing: 0; }
.pbc-hero p { color: rgba(255,255,255,.9); max-width: 720px; font-size: clamp(1.04rem, 2vw, 1.34rem); }
.pbc-actions { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 26px; }
.pbc-button { display: inline-flex; align-items: center; min-height: 48px; padding: 12px 18px; border-radius: 8px; text-decoration: none; background: #fff; color: var(--ink) !important; font-weight: 850; }
.pbc-button.secondary { background: rgba(255,255,255,.14); color: #fff !important; border: 1px solid rgba(255,255,255,.36); }
.pbc-button.store {
  min-height: 56px;
  padding: 14px 22px;
  background: linear-gradient(135deg, #f7c948, #f59e0b);
  color: #111817 !important;
  border: 1px solid rgba(255,255,255,.72);
  box-shadow: 0 14px 34px rgba(245, 158, 11, .34), 0 0 0 5px rgba(247, 201, 72, .18);
  transform: translateY(-1px);
}
.pbc-button.store::before {
  content: "★";
  margin-right: 8px;
  font-size: 1rem;
}
.pbc-band { margin: 0 calc(50% - 50vw); padding: clamp(38px, 6vw, 76px) clamp(20px, 5vw, 72px); }
.pbc-band.soft { background: var(--soft); }
.pbc-band.dark { background: var(--deep); color: #f7fbf9; }
.pbc-eyebrow { color: var(--mint); font-weight: 850; text-transform: uppercase; font-size: .78rem; letter-spacing: .08em; }
.pbc-band.dark .pbc-eyebrow { color: #a9e8cd; }
.pbc-grid { display: grid; gap: 18px; }
.pbc-grid.two { grid-template-columns: repeat(2, minmax(0, 1fr)); align-items: center; }
.pbc-grid.three { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.pbc-card { background: #fff; border: 1px solid var(--line); border-radius: 8px; padding: 22px; }
.pbc-band.dark .pbc-card { background: rgba(255,255,255,.08); border-color: rgba(255,255,255,.16); }
.pbc-card h3 { margin: 0 0 8px; font-size: 1.15rem; }
.pbc-card p, .pbc-card li { color: var(--muted); }
.pbc-band.dark .pbc-card p, .pbc-band.dark .pbc-card li { color: rgba(247,251,249,.82); }
.pbc-stat { font-size: clamp(2rem, 4vw, 3.5rem); line-height: 1; font-weight: 900; color: var(--mint); }
.pbc-photo { width: 100%; min-height: 360px; border-radius: 8px; object-fit: cover; border: 1px solid var(--line); }
.pbc-shot-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 18px; margin-top: 22px; }
.pbc-shot { overflow: hidden; background: #fff; border: 1px solid var(--line); border-radius: 8px; }
.pbc-shot img { display: block; width: 100%; aspect-ratio: 9 / 16; object-fit: cover; object-position: top center; }
.pbc-shot div { padding: 16px; }
.pbc-shot h3 { margin: 0 0 6px; font-size: 1.02rem; }
.pbc-shot p { margin: 0; color: var(--muted); font-size: .95rem; }
.pbc-feature-list { display: grid; gap: 12px; margin-top: 18px; }
.pbc-feature { display: grid; grid-template-columns: 36px 1fr; gap: 12px; align-items: start; }
.pbc-icon { display: grid; place-items: center; width: 36px; height: 36px; border-radius: 8px; background: #dff1e7; color: var(--mint); font-weight: 900; }
.pbc-note { color: var(--muted); font-size: .92rem; }
@media (max-width: 780px) {
  .pbc-hero { min-height: 74vh; padding: 28px 20px; }
  .pbc-grid.two, .pbc-grid.three { grid-template-columns: 1fr; }
  .pbc-shot-grid { grid-template-columns: 1fr; }
  .pbc-photo { min-height: 250px; }
}
</style>

<main class="pbc-page">
  <section class="pbc-hero">
    <div class="pbc-wrap">
      <div class="pbc-kicker">Private camera for pseudonymous creators</div>
      <h1>Make polished content without giving away more than you choose.</h1>
      <p>Private BlurCam helps creators record previews, collabs, behind-the-scenes clips, and private-channel media with faces hidden, offline processing, 4K export, voice protection, metadata removal, watermarking, and social-ready quality controls.</p>
      <div class="pbc-actions">
        <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/marketing/">See creator use cases</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/privacy/">Read privacy policy</a>
      </div>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">App screenshots</div>
      <h2>See the privacy workflow before you film.</h2>
      <div class="pbc-shot-grid">
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/faces-stay-hidden.jpg" alt="Private BlurCam screenshot showing faces stay hidden while recording">
          <div>
            <h3>Capture videos. Faces stay hidden.</h3>
            <p>Record groups, shared rooms, and background people with automatic face blur applied to the saved clip.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/private-by-design.jpg" alt="Private BlurCam screenshot showing processed on your device">
          <div>
            <h3>Private by design</h3>
            <p>On-device processing helps avoid uploading raw creator media to a cloud blur service.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/4k-export.jpg" alt="Private BlurCam screenshot showing 4K export and video quality selector">
          <div>
            <h3>Ultra-sharp 4K export</h3>
            <p>Pro resolution options support cleaner previews, promo edits, and higher-quality private-channel posts.</p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Why creators need it</div>
      <h2>Audience growth increases privacy risk.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <div class="pbc-stat">41%</div>
          <h3>online harassment is common</h3>
          <p>Pew reports 41% of U.S. adults have personally experienced online harassment. Creators with public audiences carry more exposure than casual users.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">25%</div>
          <h3>severe incidents are rising</h3>
          <p>Pew also found 25% of U.S. adults have faced more severe harassment, including stalking, threats, or sustained harassment.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">Public</div>
          <h3>creator work changes the threat model</h3>
          <p>USENIX creator-safety research notes that creators weigh emotional, physical, relational, and financial safety across platforms and audiences.</p>
        </article>
      </div>
      <p class="pbc-note">Sources: <a href="https://www.pewresearch.org/internet/2021/01/13/the-state-of-online-harassment/">Pew Research Center online harassment report</a>, <a href="https://www.usenix.org/conference/usenixsecurity23/presentation/samermit">USENIX digital-safety needs of creators</a>.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=1300&q=82" alt="Camera and production gear on a dark desk">
      <div>
        <div class="pbc-eyebrow">Creator workflow</div>
        <h2>Built for the moments a normal camera is too risky.</h2>
        <div class="pbc-feature-list">
          <div class="pbc-feature"><div class="pbc-icon">1</div><div><strong>Keep faces out of the file.</strong><br>Record in shared rooms, studios, events, hotels, or public spaces while faces are blurred in real time before saving.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">2</div><div><strong>Reduce location clues.</strong><br>Use Pro metadata controls before exporting clips that could otherwise reveal device, capture, or location details.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">3</div><div><strong>Protect the brand layer.</strong><br>Add a custom watermark, use higher resolution, tune sharpness and saturation, and keep quality stronger for social uploads.</div></div>
        </div>
      </div>
    </div>
  </section>

  <section class="pbc-band dark">
    <div class="pbc-wrap pbc-grid two">
      <div>
        <div class="pbc-eyebrow">Source-backed features</div>
        <h2>The app protects the capture pipeline, not just the edit afterward.</h2>
        <div class="pbc-feature-list">
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Always-on face blur.</strong><br>The Settings screen states face blur is always enabled; photos and videos are automatically blurred.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Protected-save receipt.</strong><br>After saving, the app confirms faces were blurred before saving and that no unblurred video was created or saved.</div></div>
          <div class="pbc-feature"><div class="pbc-icon">✓</div><div><strong>Private by design.</strong><br>The in-app trust banner says on-device face blur with no media uploads or AI training.</div></div>
        </div>
      </div>
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1300&q=82" alt="Minimal private studio workspace with warm lighting">
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Creator feature checklist</div>
      <h2>Everything that helps keep creator work controlled.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <h3>Real-time face blur</h3>
          <p>Faces are blurred while filming, so collaborators, guests, mirrors, crowds, and background people are less likely to appear clearly in the saved file.</p>
        </article>
        <article class="pbc-card">
          <h3>Metadata removal</h3>
          <p>Pro exports can strip location and device details that creators often forget are hidden inside media files.</p>
        </article>
        <article class="pbc-card">
          <h3>Voice protection</h3>
          <p>Mask narration or background voices when the clip needs personality without exposing a real-world voice identity.</p>
        </article>
        <article class="pbc-card">
          <h3>Watermarking</h3>
          <p>Add a creator name, brand, or handle to saved videos so previews and reposted clips still carry attribution.</p>
        </article>
        <article class="pbc-card">
          <h3>High-quality export</h3>
          <p>Pro unlocks Full HD, 2K, 4K, and a social quality option for sharper previews, promo clips, and private-channel posts.</p>
        </article>
        <article class="pbc-card">
          <h3>Privacy receipt</h3>
          <p>After saving, the app confirms which protections were active, including face blur, metadata removal, voice protection, and watermarking.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Support</div>
      <h2>Common questions</h2>
      <div class="pbc-grid two">
        <article class="pbc-card">
          <h3>Is this for private-channel creators?</h3>
          <p>Yes. The page stays platform-neutral, but the app is useful for creators who want to separate public identity, private brand identity, collaborators, and bystanders.</p>
        </article>
        <article class="pbc-card">
          <h3>Do clips upload for processing?</h3>
          <p>No. Face detection, blur rendering, metadata removal, and voice protection are designed to run locally on your device.</p>
        </article>
        <article class="pbc-card">
          <h3>What is included in Free?</h3>
          <p>Free includes basic face blur at 480p. Pro unlocks Full HD, 2K, 4K, metadata removal, voice protection, watermarking, Smooth Skin, and export controls.</p>
        </article>
        <article class="pbc-card">
          <h3>How do I get help?</h3>
          <p>Email <a href="mailto:private.blur.cam@outlook.com">private.blur.cam@outlook.com</a> for support, privacy questions, or subscription help.</p>
        </article>
      </div>
      <div class="pbc-actions">
        <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
      </div>
    </div>
  </section>
</main>
