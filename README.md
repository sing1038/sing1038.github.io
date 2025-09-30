theme: Kahana
title: Kahana's Management Team
description: Kahana's Management Team

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Khaana — Management Team</title>

  <!-- Inline CSS to keep everything in one file (allowed for the project) -->
  <style>
    body {
      font-family: "Helvetica Neue", Arial, sans-serif;
      margin: 24px;
      line-height: 1.6;
      background: #fffaf6;
      color: #222;
    }

    header {
      border-bottom: 3px solid #e6cfa1;
      padding-bottom: 12px;
      margin-bottom: 18px;
    }

    h1 {
      font-family: Georgia, "Times New Roman", serif; /* font style #1 */
      font-size: 32px;
      margin: 0;
      color: #2b5d34; /* color #1 (green) */
    }

    .tagline {
      font-family: "Courier New", Courier, monospace; /* font style #2 */
      font-size: 14px; /* smaller font size option */
      color: #a33a3a; /* color #2 (red) */
      margin-top: 6px;
      font-style: italic; /* italics requirement */
    }

    .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 18px;
      margin-top: 18px;
    }

    .card {
      background: #fff;
      border-radius: 8px;
      padding: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.06);
      border: 1px solid #efe2d1;
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 6px;
      border-bottom: 3px solid #f2e8de;
    }

    .name {
      font-size: 18px; /* second font size */
      font-weight: bold; /* bold requirement */
      margin: 8px 0 2px 0;
    }

    .title {
      font-size: 14px;
      margin-bottom: 8px;
      color: #555;
      text-decoration: underline; /* underline requirement */
    }

    .bio {
      font-size: 13px;
      margin-bottom: 8px;
    }

    .responsibilities, .awards {
      margin: 0 0 8px 0;
      padding-left: 20px;
    }

    .contact {
      margin-top: 12px;
      font-size: 14px;
    }

    footer {
      margin-top: 26px;
      border-top: 1px dashed #ddd;
      padding-top: 10px;
      font-size: 13px;
      color: #333;
    }

    /* small visual note (italic + color) */
    .fun {
      font-style: italic;
      color: #2b5d34;
    }
  </style>
</head>
<body>
  <header>
    <h1>Khaana — Management Team</h1>
    <div class="tagline">Allergy-safe foodservice solutions — founded to serve everyone at the table.</div>
  </header>

  <section>
    <p>
      <span style="font-size:16px; color:#2b5d34;"><strong>About this page:</strong></span>
      <span style="font-size:14px; color:#a33a3a;">
        This page introduces Khaana's leadership and people who design, operate, and support our allergy-safe foodservice products and services.
      </span>
    </p>

    <!-- unordered list (requirement) -->
    <h2 style="font-family: Georgia, serif; font-size:20px;">Our Management Highlights</h2>
    <ul>
      <li><strong>Mission-centered</strong> leadership focused on safety & inclusion.</li>
      <li><em>Cross-functional</em> teams combining food science, operations, and UX.</li>
      <li>Customer-first processes that center allergy safety in design.</li>
    </ul>

    <!-- team cards with images and bios (more than just a list) -->
    <div class="team-grid">
      <!-- Card 1 -->
      <article class="card" id="manager-1">
        <img src="assets/manager1.jpg" alt="Portrait of Priya Sharma — Founder & CEO" />
        <div class="name">Priya Sharma</div>
        <div class="title">Founder &amp; CEO</div>
        <p class="bio">
          <span style="font-family: 'Courier New', monospace;">Priya</span> founded Khaana after managing large institutional kitchens and seeing an urgent need for standardized allergen-safe procedures.
          She leads strategy, partnerships with suppliers, and research into hypoallergenic menu design.
        </p>

        <div>
          <strong>Key responsibilities:</strong>
          <!-- unordered sub-list of responsibilities -->
          <ul class="responsibilities">
            <li>Vision &amp; product strategy</li>
            <li>Supplier &amp; partner relationships</li>
            <li>Regulatory &amp; safety compliance oversight</li>
          </ul>
        </div>

        <div class="fun">Fun fact: Priya is a certified pastry chef and designs allergen-free desserts for our test kitchen.</div>
      </article>

      <!-- Card 2 -->
      <article class="card" id="manager-2">
        <img src="assets/manager2.jpg" alt="Portrait of Marcus Lee — Head of Product" />
        <div class="name">Marcus Lee</div>
        <div class="title">Head of Product</div>
        <p class="bio">
          Marcus translates customer needs into product features — from kitchen labeling systems to staff-training microlearning modules.
        </p>

        <div>
          <strong>Top projects (ordered)</strong>
          <!-- ordered list (requirement) -->
          <ol class="awards">
            <li>Allergen-Safe Prep Flow (pilot)</li>
            <li>LabelScan™ handheld scanner integration</li>
            <li>Kitchen Staff Microlearning Series</li>
          </ol>
        </div>

        <div class="contact">
          <strong>Contact Marcus:</strong> <a href="mailto:marcus.khaana@example.com">marcus.khaana@example.com</a>
        </div>
      </article>

      <!-- Card 3 -->
      <article class="card" id="manager-3">
        <img src="assets/manager3.jpg" alt="Portrait of Elena Rodriguez — Director of Operations" />
        <div class="name">Elena Rodriguez</div>
        <div class="title">Director of Operations</div>
        <p class="bio">
          Elena oversees rollout at partner foodservice locations, training, and quality audits. She focuses on process reliability at scale.
        </p>

        <div>
          <strong>Responsibilities:</strong>
          <ul class="responsibilities">
            <li>Implementation & site onboarding</li>
            <li>Quality assurance & audits</li>
            <li>Data collection for continuous improvement</li>
          </ul>
        </div>

        <div class="fun">Fun fact: Elena runs an annual "Safe Chef" workshop and mentors kitchen staff in cross-contact prevention.</div>
      </article>
    </div> <!-- /.team-grid -->

    <!-- short section describing more people beyond managers: advisors, support, interns -->
    <section style="margin-top:20px;">
      <h3 style="font-size:18px;">Extended Team</h3>
      <p class="bio">
        Khaana's success is supported by product designers, food scientists, QA auditors, training specialists, and a rotating group of student interns.
      </p>

      <strong>Roles that keep Khaana running:</strong>
      <ul>
        <li>Food Safety Analysts — research cross-contact mitigation.</li>
        <li>UX Designers — design labeling and kitchen signage for clarity.</li>
        <li>Customer Success & Training Specialists — on-site training and support.</li>
      </ul>
    </section>

    <!-- Downloadable file (requirement) -->
    <section style="margin-top:18px;">
      <h3 style="font-size:18px;">Download — Team Brochure</h3>
      <p>
        <a href="assets/Khaana_Team_Brochure.pdf" download="Khaana_Team_Brochure.pdf">
          Download our Team Brochure (PDF)
        </a>
        — contains org chart, quick bios, and compliance highlights.
      </p>
    </section>

    <!-- External hyperlink (requirement: outside link, opens in new window) -->
    <section style="margin-top:14px;">
      <p>
        Learn more about allergy labeling best practices at the
        <a href="https://www.foodallergy.org" target="_blank" rel="noopener noreferrer">Food Allergy Research & Education (FARE)</a>.
      </p>
    </section>

    <!-- Link back to the team frameset/home (counts as a link within the allowed three) -->
    <p>
      <a href="team_home.html">Return to Team Home</a>
    </p>
  </section>

  <footer>
    <!-- Last modified date: automatically inserted via JS -->
    <div id="last-modified">Date last modified: <span id="modified-date">Loading...</span></div>
    <div style="margin-top:6px; font-size:12px;">
      Page author: <strong>Reva Singh</strong> &mdash; <a href="mailto:reva.khaana@example.com">reva.khaana@example.com</a>
    </div>
  </footer>

  <script>
    // Show the document last modified date. If document.lastModified is empty (some hosts),
    // fall back to the current date so the page still displays an automatic date.
    (function () {
      function formatDate(d) {
        try {
          const options = { year: "numeric", month: "long", day: "numeric" };
          return new Date(d).toLocaleDateString(undefined, options);
        } catch (e) {
          return d;
        }
      }

      var raw = document.lastModified || "";
      var out;
      if (raw && raw !== "") {
        // Some browsers return a timestamp string; try to parse it
        out = formatDate(raw);
      } else {
        // fallback: use current date
        out = formatDate(new Date());
      }

      document.getElementById("modified-date").textContent = out;
    })();
  </script>
</body>
</html>
