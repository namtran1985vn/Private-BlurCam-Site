---
title: Private BlurCam - Creator Privacy Camera
permalink: /marketing/
---

<style>
:root {
  --ink: #141716;
  --muted: #5d6663;
  --line: #dfe7e4;
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
  min-height: 76vh;
  display: grid;
  align-items: end;
  margin: -22px calc(50% - 50vw) 0;
  padding: clamp(28px, 5vw, 72px);
  background:
    linear-gradient(90deg, rgba(11, 15, 15, .9), rgba(11, 15, 15, .64), rgba(11, 15, 15, .14)),
    url("https://images.unsplash.com/photo-1516280440614-37939bbacd81?auto=format&fit=crop&w=1800&q=82") center/cover;
}
.pbc-wrap { max-width: 1160px; margin: 0 auto; width: 100%; }
.pbc-kicker { color: #a9e8cd; font-size: .82rem; font-weight: 850; letter-spacing: .08em; text-transform: uppercase; }
.pbc-hero h1 { color: #fff; max-width: 920px; margin: 10px 0 16px; font-size: clamp(2.25rem, 7vw, 5.7rem); line-height: .96; letter-spacing: 0; }
.pbc-hero p { color: rgba(255,255,255,.9); max-width: 720px; font-size: clamp(1.04rem, 2vw, 1.34rem); }
.pbc-actions { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 26px; }
.pbc-button { display: inline-flex; align-items: center; min-height: 48px; border-radius: 8px; padding: 12px 18px; text-decoration: none; background: #fff; color: var(--ink) !important; font-weight: 850; }
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
.pbc-card h3 { margin: 0 0 8px; }
.pbc-card p, .pbc-card li { color: var(--muted); }
.pbc-band.dark .pbc-card p, .pbc-band.dark .pbc-card li { color: rgba(247,251,249,.82); }
.pbc-photo { width: 100%; min-height: 360px; border-radius: 8px; object-fit: cover; border: 1px solid var(--line); }
.pbc-stat { font-size: clamp(2rem, 4vw, 3.5rem); line-height: 1; font-weight: 900; color: var(--mint); }
.pbc-demo-band { background: radial-gradient(circle at 72% 18%, rgba(122, 84, 255, .26), transparent 34%), #111817; }
.pbc-demo-intro { display: grid; grid-template-columns: minmax(0, 1fr) minmax(300px, 420px); gap: clamp(28px, 6vw, 72px); align-items: center; }
.pbc-demo-copy { max-width: 680px; }
.pbc-demo-copy h2 { margin: 10px 0 14px; padding: 0; border: 0; font-size: clamp(2rem, 4vw, 3.55rem); line-height: 1.03; letter-spacing: 0; }
.pbc-demo-copy p { max-width: 620px; color: rgba(247,251,249,.82); font-size: 1.06rem; }
.pbc-proof-list { display: grid; gap: 10px; margin-top: 22px; }
.pbc-proof { display: grid; grid-template-columns: 42px 1fr; gap: 14px; align-items: start; padding: 14px; border: 1px solid rgba(255,255,255,.14); border-radius: 8px; background: rgba(255,255,255,.06); }
.pbc-proof .pbc-icon { background: #dff1e7; color: var(--mint); }
.pbc-proof strong { display: block; color: #fff; margin-bottom: 2px; }
.pbc-proof span { color: rgba(247,251,249,.76); }
.pbc-demo-frame { justify-self: center; width: min(100%, 390px); padding: 10px; border-radius: 12px; background: linear-gradient(180deg, rgba(255,255,255,.14), rgba(255,255,255,.04)); box-shadow: 0 24px 70px rgba(0,0,0,.42); }
.pbc-demo-image { display: block; width: 100%; max-height: 690px; object-fit: cover; object-position: top center; border-radius: 8px; background: #090817; }
.pbc-shot-grid { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 18px; margin-top: 22px; }
.pbc-shot { overflow: hidden; background: #fff; border: 1px solid var(--line); border-radius: 8px; }
.pbc-shot img { display: block; width: 100%; aspect-ratio: 9 / 16; object-fit: cover; object-position: top center; }
.pbc-shot div { padding: 16px; }
.pbc-shot h3 { margin: 0 0 6px; font-size: 1.02rem; }
.pbc-shot p { margin: 0; color: var(--muted); font-size: .95rem; }
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
  .pbc-demo-intro { grid-template-columns: 1fr; }
  .pbc-demo-frame { width: min(100%, 360px); }
  .pbc-demo-image { max-height: 640px; }
  .pbc-shot-grid { grid-template-columns: 1fr; }
  .pbc-photo { min-height: 250px; }
  .pbc-table { display: block; overflow-x: auto; }
}
</style>

<main class="pbc-page">
  <section class="pbc-hero">
    <div class="pbc-wrap">
      <div class="pbc-kicker">Private BlurCam</div>
      <h1>The creator camera for identity-safe filming.</h1>
      <p>Record private previews, social teasers, collabs, behind-the-scenes clips, and faceless brand content with hidden faces, offline processing, metadata controls, voice protection, watermarking, and 4K export.</p>
      <div class="pbc-actions">
        <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/">Support and FAQ</a>
        <a class="pbc-button secondary" href="{{ site.baseurl }}/privacy/">Privacy details</a>
      </div>
    </div>
  </section>

  <section class="pbc-band dark pbc-demo-band">
    <div class="pbc-wrap pbc-demo-intro">
      <div class="pbc-demo-copy">
        <div class="pbc-eyebrow">Lead demo</div>
        <h2>Real-time face blurring with zero original videos saved.</h2>
        <p>The strongest creator value is simple: film the moment, keep faces hidden, and save only the protected output. Private BlurCam applies blur during capture so privacy is part of production, not a cleanup task after something risky is already recorded.</p>
        <div class="pbc-proof-list">
          <div class="pbc-proof"><div class="pbc-icon">✓</div><div><strong>Only protected video is saved</strong><span>The app's receipt confirms faces were blurred before saving and no unblurred video was created or saved.</span></div></div>
          <div class="pbc-proof"><div class="pbc-icon">✓</div><div><strong>Collaborator privacy by default</strong><span>Keep guests, partners, staff, clients, and background people out of the identifiable final clip.</span></div></div>
          <div class="pbc-proof"><div class="pbc-icon">✓</div><div><strong>Built for repeat production</strong><span>Use the same privacy workflow for previews, collabs, behind-the-scenes clips, and social teasers.</span></div></div>
        </div>
      </div>
      <figure class="pbc-demo-frame">
        <img class="pbc-demo-image" src="{{ site.baseurl }}/assets/screenshots/zero-originals-demo.jpg" alt="Private BlurCam demo showing real-time face blurring with zero originals stored">
      </figure>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Screenshots</div>
      <h2>The app is built around the exact risks creators care about.</h2>
      <div class="pbc-shot-grid">
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/private-by-design.jpg" alt="Private BlurCam screenshot showing private by design and processed on your device">
          <div>
            <h3>Private by design</h3>
            <p>Process creator media on-device with no cloud blur workflow for raw source clips.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/faces-stay-hidden.jpg" alt="Private BlurCam screenshot showing faces hidden during video capture">
          <div>
            <h3>Faces stay hidden</h3>
            <p>Film groups, mirrors, rooms, and shared spaces while faces are blurred before saving.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/untraceable-mode.jpg" alt="Private BlurCam screenshot showing Untraceable Mode">
          <div>
            <h3>Untraceable Mode</h3>
            <p>Use maximum privacy settings for clips that should not carry location, device, time, or camera clues.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/voice-protection.jpg" alt="Private BlurCam screenshot showing Voice Protection">
          <div>
            <h3>Voice Protection</h3>
            <p>Mask narration and background voices when real-world identity needs separation from creator persona.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/prevent-quality-loss.jpg" alt="Private BlurCam screenshot showing Prevent Quality Loss and watermark settings">
          <div>
            <h3>Post without quality loss</h3>
            <p>Prepare clips for social posting, add a watermark, and keep creator previews sharper after recompression.</p>
          </div>
        </article>
        <article class="pbc-shot">
          <img src="{{ site.baseurl }}/assets/screenshots/4k-export.jpg" alt="Private BlurCam screenshot showing 4K export">
          <div>
            <h3>Ultra-sharp 4K export</h3>
            <p>Upgrade from 480p to Full HD, 2K, or 4K for polished promos and higher-value content drops.</p>
          </div>
        </article>
      </div>
      <div class="pbc-actions">
        <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Market reality</div>
      <h2>Private creators need capture tools, not just editing tools.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <div class="pbc-stat">41%</div>
          <h3>experienced online harassment</h3>
          <p>Pew found 41% of U.S. adults have personally experienced online harassment. Public creator accounts increase the surface area for unwanted attention.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">25%</div>
          <h3>experienced severe harassment</h3>
          <p>Severe forms include stalking, sustained harassment, or physical threats. Privacy controls are a risk-reduction workflow, not decoration.</p>
        </article>
        <article class="pbc-card">
          <div class="pbc-stat">4</div>
          <h3>safety dimensions</h3>
          <p>USENIX research on creators describes emotional, physical, relational, and financial safety as part of modern creator threat models.</p>
        </article>
      </div>
      <p class="pbc-note">Sources: <a href="https://www.pewresearch.org/internet/2021/01/13/the-state-of-online-harassment/">Pew Research Center online harassment report</a>, <a href="https://www.usenix.org/conference/usenixsecurity23/presentation/samermit">USENIX digital-safety needs of creators</a>.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <div>
        <div class="pbc-eyebrow">Positioning</div>
        <h2>Private BlurCam is for creators who separate persona from real life.</h2>
        <p>Most camera apps assume you can fix privacy later. Private BlurCam is built around capture-time protection: face blur is always on, the preview is processed live, and the app confirms when protected media is saved.</p>
        <div class="pbc-steps">
          <div class="pbc-step"><div><strong>Open the private camera.</strong><br>Choose photo or video, frame the scene, pinch to zoom, tap to focus, and keep face blur active.</div></div>
          <div class="pbc-step"><div><strong>Record without overexposing the room.</strong><br>Hide collaborators, clients, friends, strangers, mirrors, crowds, or accidental background faces.</div></div>
          <div class="pbc-step"><div><strong>Export for the platform.</strong><br>Use Pro for metadata removal, voice protection, watermarking, social-quality export, and up to 4K resolution.</div></div>
        </div>
      </div>
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1497015289639-54688650d173?auto=format&fit=crop&w=1300&q=82" alt="Creator editing media in a private workspace">
    </div>
  </section>

  <section class="pbc-band dark">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Creator use cases</div>
      <h2>Discreet language. Direct value.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <h3>Faceless previews</h3>
          <p>Film teasers or short clips where the setting matters but full identity does not. Face blur is automatic.</p>
        </article>
        <article class="pbc-card">
          <h3>Collabs and shared spaces</h3>
          <p>Protect people who did not agree to be part of the final file, especially in studios, venues, homes, and events.</p>
        </article>
        <article class="pbc-card">
          <h3>Persona-safe posting</h3>
          <p>Reduce hidden metadata, disguise voice when needed, and apply a watermark for attribution before posting or sending.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Important features</div>
      <h2>The feature set creators actually need before posting.</h2>
      <div class="pbc-grid three">
        <article class="pbc-card">
          <h3>Automatic face privacy</h3>
          <p>Always-on face blur helps protect your real-world identity, collaborators, clients, friends, and bystanders before the media is saved.</p>
        </article>
        <article class="pbc-card">
          <h3>No raw-media upload</h3>
          <p>Camera processing is designed to run on-device, so you do not need to send unprotected source clips to a cloud blur tool.</p>
        </article>
        <article class="pbc-card">
          <h3>Metadata hygiene</h3>
          <p>Pro metadata removal reduces hidden clues such as location, device, timestamp, and camera information before a clip leaves your phone.</p>
        </article>
        <article class="pbc-card">
          <h3>Voice masking</h3>
          <p>Voice Protection helps separate creator persona from real-world voice identity, especially for narration, room audio, and short previews.</p>
        </article>
        <article class="pbc-card">
          <h3>Brand watermark</h3>
          <p>Burn a creator name, brand, or handle into saved videos so preview clips retain attribution after sharing or reposting.</p>
        </article>
        <article class="pbc-card">
          <h3>Social-ready quality</h3>
          <p>Use Full HD, 2K, 4K, sharpness, saturation, and Prevent Quality Loss to keep creator clips cleaner through platform recompression.</p>
        </article>
        <article class="pbc-card">
          <h3>Photo and video modes</h3>
          <p>Switch between quick protected photos and longer recorded clips without changing apps or rebuilding the privacy workflow.</p>
        </article>
        <article class="pbc-card">
          <h3>Smooth Skin</h3>
          <p>Optional Pro beauty pass helps creator media look more polished while keeping the core identity-protection workflow intact.</p>
        </article>
        <article class="pbc-card">
          <h3>Protected-save receipt</h3>
          <p>The app shows which protections were applied after saving, giving creators a final confidence check before publishing or sending.</p>
        </article>
      </div>
      <div class="pbc-actions">
        <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
      </div>
    </div>
  </section>

  <section class="pbc-band soft">
    <div class="pbc-wrap">
      <div class="pbc-eyebrow">Free vs Pro</div>
      <h2>Start with basic privacy. Upgrade when content quality and identity control matter.</h2>
      <table class="pbc-table">
        <thead>
          <tr><th>Feature</th><th>Free</th><th>Pro</th><th>Creator value</th></tr>
        </thead>
        <tbody>
          <tr><td>Real-time face blur</td><td>Included</td><td>Included</td><td>Protects you, collaborators, bystanders, and background faces before saving.</td></tr>
          <tr><td>Recording quality</td><td>480p</td><td>Full HD, 2K, 4K</td><td>Sharper clips for paid feeds, previews, and promo cuts.</td></tr>
          <tr><td>Metadata removal</td><td>Off</td><td>On</td><td>Reduces hidden location, device, timestamp, and camera details before sharing.</td></tr>
          <tr><td>Voice protection</td><td>Off</td><td>On</td><td>Useful for narration, background voices, and persona separation.</td></tr>
          <tr><td>Prevent Quality Loss</td><td>Off</td><td>On</td><td>Helps preserve detail through social platform recompression.</td></tr>
          <tr><td>Watermark</td><td>Off</td><td>On</td><td>Adds creator name, brand, or handle in the lower-left of saved videos.</td></tr>
          <tr><td>Smooth Skin</td><td>Off</td><td>On</td><td>Optional real-time beauty pass for polished creator clips.</td></tr>
        </tbody>
      </table>
      <p class="pbc-note">Private BlurCam reduces common privacy leaks during capture and export. It cannot guarantee anonymity, stop screen recording, prevent reposts, or make content impossible to copy.</p>
    </div>
  </section>

  <section class="pbc-band">
    <div class="pbc-wrap pbc-grid two">
      <img class="pbc-photo" src="https://images.unsplash.com/photo-1497366811353-6870744d04b2?auto=format&fit=crop&w=1300&q=82" alt="Private creative studio with desk and camera setup">
      <div>
        <div class="pbc-eyebrow">Best-fit users</div>
        <h2>For creators who treat privacy as part of production quality.</h2>
        <ul>
          <li>Pseudonymous creators who keep stage identity separate from real identity.</li>
          <li>Faceless creators who still need expressive photo and video content.</li>
          <li>Creators filming in rented rooms, hotels, studios, venues, or public areas.</li>
          <li>Small teams capturing collabs, promo clips, and behind-the-scenes footage.</li>
          <li>Anyone who wants local processing instead of uploading raw media to a blur service.</li>
        </ul>
        <div class="pbc-actions">
          <a class="pbc-button store" href="https://apps.apple.com/vn/app/private-blurcam/id6760446756">Available on App Store</a>
          <a class="pbc-button secondary" style="color: var(--ink) !important; border-color: var(--line);" href="{{ site.baseurl }}/privacy/">Review privacy policy</a>
          <a class="pbc-button secondary" style="color: var(--ink) !important; border-color: var(--line);" href="mailto:private.blur.cam@outlook.com">Contact support</a>
        </div>
      </div>
    </div>
  </section>
</main>
