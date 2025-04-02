---
layout: default
title: Fuse - Project 1999 Guild
---

<div class="hero">
  <img src="{{ '/assets/images/fuse-logo.png' | relative_url }}" alt="Fuse Guild Logo" class="logo-image">
  <h1>Welcome to Fuse</h1>
  <p class="subtitle">A Project 1999 Guild</p>
</div>

<div class="content">
  <section class="about">
    <h2>About Us</h2>
    <p>Fuse is a dedicated guild on Project 1999, focused on creating a welcoming and supportive environment for all players. We value teamwork, respect, and the classic EverQuest experience.</p>
  </section>

  <section class="recruitment">
    <h2>Recruitment</h2>
    <p>Thank you for your interest in joining Fuse! Below you'll find our requirements, application process, and important information for prospective members.</p>
    
    <div class="requirements">
      <h3>Core Requirements</h3>
      <ul>
        <li>Magic Resist of at least 150 unbuffed</li>
        <li>Leatherfoot Raider's Skullcap (WC Cap)†</li>
        <li>2x + 10 Dose Wort Potion (Do not use the last charge)</li>
        <li>Worker Sledgemallet (OT Hammer)</li>
        <li>Vial of Velium Vapors (Thurg Pot)</li>
        <li>Crystallized Pumice or other means to dispell</li>
        <li>Forlorn Totem of Rolfron Zek (stun totem) * †</li>
        <li>2x + Thin Bone Wands * †</li>
        <li>Reaper of the Dead</li>
      </ul>

      <h3>Class-Specific Requirements</h3>
      <ul>
        <li>All casters must have a GCD (Global Cooldown Reset)</li>
        <li>Have the ability to increase run speed</li>
        <li>Have the ability to levitate</li>
        <li>Have the ability to shrink (except Gnomes/Halflings)</li>
        <li>Have the ability to instantly invisibility</li>
        <li>Have at least one clickable instant junk buff</li>
      </ul>

      <h3>Suggested Items (Not Required)</h3>
      <ul>
        <li>Bracer of the Hidden</li>
        <li>Black and Green Flower of Functionality</li>
        <li>Star of Eyes</li>
        <li>1 Stack of Peridots and/or Pearls</li>
        <li>2x + Stalking Probes * †</li>
        <li>1 Stack of Batwings (for classes that can cast levitate)</li>
      </ul>

      <div class="notes">
        <h3>Important Notes</h3>
        <ul>
          <li>All items marked with † can be recharged at guild recharge sessions</li>
          <li>Forlorn Totem of Rolfron Zek, Thin Bone Wands and Stalking Probes are commonly used during pulls and tags</li>
          <li>Porters are encouraged to keep one of these fully charged for easy recharging</li>
        </ul>
      </div>
    </div>

    <div class="application-process">
      <h3>Application Process</h3>
      <ol>
        <li>Review Requirements
          <ul>
            <li>Ensure you meet all the necessary criteria</li>
            <li>Gather required items</li>
          </ul>
        </li>
        <li>Submit Application
          <ul>
            <li>Fill out our application form at: <a href="https://forms.gle/7eqF1EyUjeHd17uZ6" target="_blank">Application Form</a></li>
            <li>Be thorough and honest in your responses</li>
          </ul>
        </li>
        <li>Next Steps
          <ul>
            <li>Our recruitment team will review your application</li>
            <li>You'll be contacted via Discord if we have any questions</li>
            <li>Successful applications will be invited to join as recruits</li>
          </ul>
        </li>
      </ol>
    </div>

    <div class="important-documents">
      <h3>Important Documents</h3>
      <ul>
        <li><a href="#">Constitution/Rules</a></li>
        <li><a href="#">Raid Expectations</a></li>
        <li><a href="#">DKP Rules</a></li>
      </ul>
    </div>

    <div class="application-note">
      <p><strong>Note:</strong> Please do not ping officers or recruiters about your application status. We review applications as quickly as possible and will contact you when ready.</p>
    </div>
  </section>

  <section class="contact">
    <h2>How to Join</h2>
    <p>To apply to Fuse, please contact one of our officers in-game:</p>
    <ul>
      <li>Officer1 (Main Contact)</li>
      <li>Officer2</li>
      <li>Officer3</li>
    </ul>
    <p>Or reach out to us on our Discord server: [Discord Link]</p>
  </section>
</div>

<style>
.hero {
  text-align: center;
  padding: 40px 20px;
  background: #2c3e50;
  color: white;
}

.logo-image {
  max-width: 200px;
  height: auto;
  margin-bottom: 20px;
}

.subtitle {
  font-size: 1.5em;
  margin-top: 10px;
}

.content {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

section {
  margin: 40px 0;
}

h2 {
  color: #2c3e50;
  border-bottom: 2px solid #2c3e50;
  padding-bottom: 10px;
}

h3 {
  color: #2c3e50;
  margin-top: 20px;
}

.requirements, .application-process, .important-documents {
  background: #f5f5f5;
  padding: 20px;
  border-radius: 5px;
  margin: 20px 0;
}

.notes {
  background: #fff3cd;
  padding: 15px;
  border-radius: 5px;
  margin: 15px 0;
}

.application-note {
  background: #d4edda;
  padding: 15px;
  border-radius: 5px;
  margin: 15px 0;
}

ul, ol {
  list-style-type: none;
  padding: 0;
  margin: 10px 0;
}

li {
  padding: 5px 0;
  padding-left: 20px;
  position: relative;
}

ul li:before {
  content: "•";
  color: #2c3e50;
  position: absolute;
  left: 0;
}

ol {
  counter-reset: item;
}

ol li {
  counter-increment: item;
  margin-bottom: 10px;
}

ol li:before {
  content: counter(item) ".";
  color: #2c3e50;
  position: absolute;
  left: 0;
}

a {
  color: #2c3e50;
  text-decoration: none;
  font-weight: bold;
}

a:hover {
  text-decoration: underline;
}
</style> 