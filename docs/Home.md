# Sanguis et Harena
<style>
:root {
  --c-bg: #141009;
  --c-surface: #1e1712;
  --c-ink: #ece0c4;
  --c-muted: #a89878;
  --c-accent: #c9a227;
  --c-border: #3a2e20;
}
/* Landing page: break out of the wiki shell (no sidebar column, no topbar, no footer) */
.shell { display: block !important; }
.sidebar, .nav-toggle, .breadcrumb, header.topbar, footer { display: none !important; }
.content > h1:first-child { display: none; }
main.content { max-width: 1120px; margin: 0 auto; padding-left: 1.5rem; padding-right: 1.5rem; }
.sh-hero {
  display: grid; grid-template-columns: 1.1fr 0.9fr; gap: 3rem;
  align-items: center; padding: 3rem 0 4rem;
}
@media (max-width: 800px) { .sh-hero { grid-template-columns: 1fr; } }
.sh-kicker {
  color: var(--c-accent); letter-spacing: 0.35em; font-size: 0.8rem;
  text-transform: uppercase; margin-bottom: 1rem;
}
.sh-title {
  font-family: Georgia, 'Times New Roman', serif;
  font-size: clamp(2.6rem, 6vw, 4.2rem); line-height: 1.05; margin: 0 0 1rem;
  color: var(--c-accent);
}
.sh-tagline { font-size: 1.3rem; font-style: italic; color: var(--c-ink); margin-bottom: 2rem; }
.sh-cta {
  display: inline-block; background: var(--c-accent); color: #141009;
  font-weight: bold; padding: 0.9rem 2.4rem; text-decoration: none;
  border-radius: 0.3rem; font-size: 1.1rem;
}
.sh-cta:hover { filter: brightness(1.1); }
.sh-price { margin-top: 0.8rem; color: var(--c-muted); font-size: 0.95rem; }
.sh-cover img { width: 100%; border-radius: 0.5rem; box-shadow: 0 20px 60px rgba(0,0,0,0.6); }
.sh-section { padding: 3rem 0; border-top: 1px solid var(--c-border); }
.sh-section h2 {
  font-family: Georgia, serif; color: var(--c-accent); text-align: center;
  font-size: 2rem; margin-bottom: 2rem; border: none;
}
.sh-steps { display: flex; justify-content: center; gap: 0.6rem; flex-wrap: wrap; margin-bottom: 1.5rem; }
.sh-step {
  background: var(--c-surface); border: 1px solid var(--c-border);
  padding: 0.7rem 1.2rem; border-radius: 0.3rem; font-weight: bold;
  letter-spacing: 0.12em; color: var(--c-accent);
}
.sh-arrow { align-self: center; color: var(--c-muted); }
.sh-body { max-width: 720px; margin: 0 auto; line-height: 1.7; }
.sh-champs { display: grid; grid-template-columns: repeat(4, 1fr); gap: 1.2rem; }
@media (max-width: 900px) { .sh-champs { grid-template-columns: repeat(2, 1fr); } }
@media (max-width: 520px) { .sh-champs { grid-template-columns: 1fr; } }
.sh-champ {
  background: var(--c-surface); border: 1px solid var(--c-border);
  border-radius: 0.5rem; overflow: hidden;
}
.sh-champ img { width: 100%; display: block; }
.sh-champ .sh-cbody { padding: 1rem 1.1rem 1.2rem; }
.sh-champ h3 { margin: 0 0 0.2rem; color: var(--c-accent); font-family: Georgia, serif; }
.sh-champ .sh-role { font-style: italic; color: var(--c-muted); font-size: 0.9rem; margin-bottom: 0.6rem; }
.sh-champ .sh-ability { font-size: 0.92rem; margin-bottom: 0.6rem; }
.sh-champ .sh-quote { font-size: 0.85rem; font-style: italic; color: var(--c-muted); }
.sh-gallery { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.2rem; }
@media (max-width: 700px) { .sh-gallery { grid-template-columns: 1fr; } }
.sh-gallery img { width: 100%; border-radius: 0.4rem; }
.sh-buybox {
  background: var(--c-surface); border: 1px solid var(--c-accent);
  border-radius: 0.5rem; padding: 2rem; text-align: center; max-width: 640px; margin: 0 auto;
}
.sh-buybox .sh-big { font-size: 2rem; color: var(--c-accent); font-weight: bold; margin: 0.5rem 0; }
.sh-note { max-width: 720px; margin: 2rem auto 0; font-size: 0.85rem; color: var(--c-muted); }
.sh-freerules { text-align: center; margin-top: 1.4rem; color: var(--c-muted); }
.sh-freerules a { color: var(--c-accent); }
</style>

<div class="sh-hero">
<div>
<div class="sh-kicker">Wicked Combo presents</div>
<div class="sh-title">Sanguis<br>et Harena</div>
<p class="sh-tagline">A tactical card game of timing, positioning, and nerve.</p>
<a class="sh-cta" href="https://www.drivethrurpg.com/en/product/588027/sanguis-harena">Get the Game on DriveThruRPG</a>
<p class="sh-price">36-card print-and-play deck &mdash; $14.99 &middot; rulebook PDF included</p>
</div>
<div class="sh-cover"><img src=".attachments/cover.jpg" alt="Sanguis et Harena cover art"></div>
</div>

<div class="sh-section">
<h2>The System</h2>
<div class="sh-steps">
<span class="sh-step">CHOOSE</span><span class="sh-arrow">&rarr;</span>
<span class="sh-step">SHOW</span><span class="sh-arrow">&rarr;</span>
<span class="sh-step">ACT</span><span class="sh-arrow">&rarr;</span>
<span class="sh-step">BURN</span><span class="sh-arrow">&rarr;</span>
<span class="sh-step">REPEAT</span>
</div>
<div class="sh-body">
<p>Each round runs six seconds. Every second, you secretly choose one card and reveal it together with your opponents &mdash; then resolve everything live on your burn-down track. Cards slide down each second; when they burn off, you pay their water and score their glory.</p>
<p><strong>Water</strong> fuels every card. <strong>Glory</strong> rewards bold play. <strong>Positioning</strong> decides every exchange. Most glory after six rounds wins &mdash; unless you finish your rivals first.</p>
</div>
</div>

<div class="sh-section">
<h2>The Champions</h2>
<div class="sh-champs">
<div class="sh-champ">
<img src=".attachments/champion-rufus.jpg" alt="Rufus the Ox">
<div class="sh-cbody">
<h3>Rufus the Ox</h3>
<div class="sh-role">Brute, built like a siege engine.</div>
<div class="sh-ability">Once per round, Stab as an additional action.</div>
<div class="sh-quote">&ldquo;Rufus once headbutted a gate. The gate apologized.&rdquo;</div>
</div>
</div>
<div class="sh-champ">
<img src=".attachments/champion-drusa.jpg" alt="Drusa the Wall">
<div class="sh-cbody">
<h3>Drusa the Wall</h3>
<div class="sh-role">Veteran. Twenty rounds of bad decisions survived.</div>
<div class="sh-ability">Once per round, Parry as an additional action.</div>
<div class="sh-quote">&ldquo;Twenty rounds. Four scars. Zero apologies.&rdquo;</div>
</div>
</div>
<div class="sh-champ">
<img src=".attachments/champion-cassius.jpg" alt="Cassius the Peacock">
<div class="sh-cbody">
<h3>Cassius the Peacock</h3>
<div class="sh-role">Showman. The crowd is his second weapon.</div>
<div class="sh-ability">Once per round, gain +1 glory for a flourish.</div>
<div class="sh-quote">&ldquo;The crowd didn't come to see him win. They came to see him.&rdquo;</div>
</div>
</div>
<div class="sh-champ">
<img src=".attachments/champion-vela.jpg" alt="Vela the Eel">
<div class="sh-cbody">
<h3>Vela the Eel</h3>
<div class="sh-role">She moves like a reed in the wind.</div>
<div class="sh-ability">Once per round, move as an additional action.</div>
<div class="sh-quote">&ldquo;You can't hit what already left.&rdquo;</div>
</div>
</div>
</div>
</div>

<div class="sh-section">
<h2>The Cards</h2>
<div class="sh-gallery">
<img src=".attachments/card-back.jpg" alt="Card back">
<img src=".attachments/cards.jpg" alt="Action cards">
<img src=".attachments/arena.jpg" alt="Hex arena">
</div>
</div>

<div class="sh-section">
<div class="sh-buybox">
<h2 style="margin-top:0;">Get in the Arena</h2>
<p>36 poker-size cards &middot; 10-page full-color rulebook &middot; 2&ndash;6 players, ages 12+</p>
<div class="sh-big">$14.99</div>
<a class="sh-cta" href="https://www.drivethrurpg.com/en/product/588027/sanguis-harena">Get the Game on DriveThruRPG</a>
</div>
<p class="sh-freerules">Just want the rules? <a href=".attachments/sanguis-et-harena-rulebook.pdf">Download the free rulebook (PDF)</a></p>
<p class="sh-note">Card art is AI-generated placeholder art, disclosed per DriveThruRPG policy. Wicked Combo is commissioning human artists for future printings &mdash; this release funds that work.</p>
</div>

