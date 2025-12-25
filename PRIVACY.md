<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Privacy Policy - Zealth</title>
  <meta name="description" content="Privacy Policy for the Zealth mobile application." />
  <meta name="robots" content="index,follow" />

  <!-- Open Graph (social previews) -->
  <meta property="og:title" content="Privacy Policy - Zealth" />
  <meta property="og:description" content="Privacy Policy for the Zealth mobile application." />
  <meta property="og:type" content="website" />

  <!-- Theme color (mobile browsers) -->
  <meta name="theme-color" content="#2b6cb0" />

  <style>
    :root{
      --bg:#ffffff;
      --text:#111111;
      --muted:#555555;
      --card:#f6f7f9;
      --border:#e6e8ee;
      --accent:#2b6cb0;
      --shadow: 0 10px 26px rgba(0,0,0,.06);
      --radius: 16px;
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }

    body{
      margin:0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a{
      color: var(--accent);
      text-decoration: none;
    }
    a:hover{ text-decoration: underline; }

    /* Layout */
    .wrap{
      max-width: 960px;
      margin: 0 auto;
      padding: 0 16px;
    }

    header{
      position: sticky;
      top: 0;
      background: rgba(255,255,255,.92);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--border);
      z-index: 10;
    }

    .topbar{
      padding: 18px 0;
      display:flex;
      align-items:flex-start;
      justify-content: space-between;
      gap: 12px;
    }

    h1{
      margin:0;
      font-size: 26px;
      letter-spacing: -0.2px;
    }

    .meta{
      margin-top: 6px;
      font-size: 13px;
      color: var(--muted);
    }

    .badge{
      display:inline-block;
      font-size: 12px;
      color: #0f172a;
      border: 1px solid var(--border);
      background: #fff;
      padding: 6px 10px;
      border-radius: 999px;
      white-space: nowrap;
    }

    main{
      padding: 22px 0 28px;
    }

    .lead{
      background: linear-gradient(180deg, #ffffff 0%, #fafbff 100%);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 18px;
      box-shadow: var(--shadow);
    }

    .grid{
      display: grid;
      grid-template-columns: 1fr;
      gap: 16px;
      margin-top: 16px;
    }

    section{
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 18px;
      box-shadow: var(--shadow);
    }

    h2{
      margin: 0 0 10px 0;
      font-size: 18px;
    }
    h3{
      margin: 14px 0 8px 0;
      font-size: 15px;
    }
    p{ margin: 10px 0; }
    ul{ margin: 10px 0 0 20px; }
    li{ margin: 6px 0; }

    .note{
      margin-top: 12px;
      border-left: 4px solid var(--accent);
      padding: 10px 12px;
      background: #ffffff;
      border-radius: 12px;
      border: 1px solid var(--border);
      color: #0f172a;
    }

    /* Contact cards */
    .fields{
      display:grid;
      grid-template-columns: 1fr;
      gap: 10px;
      margin-top: 10px;
    }
    .field{
      background:#fff;
      border:1px solid var(--border);
      border-radius: 14px;
      padding: 12px;
    }
    .label{
      font-size: 12px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 4px;
    }

    footer{
      border-top: 1px solid var(--border);
      padding: 16px 0;
      color: var(--muted);
      font-size: 13px;
    }

    /* Desktop enhancements */
    @media (min-width: 900px){
      .grid{
        grid-template-columns: 1fr 1fr;
      }
      section.full{
        grid-column: 1 / -1;
      }
      .fields{
        grid-template-columns: 1fr 1fr;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="wrap">
      <div class="topbar">
        <div>
          <h1>Privacy Policy</h1>
          <div class="meta">
            App: <strong>Zealth</strong> &nbsp;•&nbsp; Effective Date: <strong>January 1, 2025</strong>
          </div>
        </div>
        <div class="badge">Hosted on GitHub Pages</div>
      </div>
    </div>
  </header>

  <main>
    <div class="wrap">
      <div class="lead">
        <p>
          Zealth (“we”, “our”, or “us”) respects your privacy and is committed to protecting your personal information.
          This Privacy Policy explains how information is collected, used, and safeguarded when you use the Zealth
          mobile application (“the App”).
        </p>
      </div>

      <div class="grid">

        <section>
          <h2>1. Information We Collect</h2>

          <h3>Information You Provide</h3>
          <ul>
            <li>Basic health inputs (height, weight, age, pregnancy details)</li>
            <li>Symptoms entered for AI health guidance</li>
            <li>Preferences and app settings</li>
          </ul>

          <div class="note">
            Zealth does <strong>not</strong> require account creation and does <strong>not</strong>
            collect names, email addresses, or phone numbers.
          </div>

          <h3>Automatically Collected Information</h3>
          <ul>
            <li>Device type and Android version</li>
            <li>App usage statistics</li>
            <li>Approximate location (only if permission is granted)</li>
          </ul>

          <h3>Location Information</h3>
          <p>
            Location data is used only to show nearby health facilities while the app is in use
            and is not stored or shared.
          </p>
        </section>

        <section>
          <h2>2. How We Use Your Information</h2>
          <ul>
            <li>Provide health-related tools and insights</li>
            <li>Display nearby hospitals and clinics</li>
            <li>Improve app performance and reliability</li>
            <li>Maintain app security</li>
          </ul>
        </section>

        <section>
          <h2>3. Health Data Disclaimer</h2>
          <ul>
            <li>Health data is processed locally or temporarily</li>
            <li>No health data is sold or used for advertising</li>
            <li>This app does not replace professional medical advice</li>
          </ul>
        </section>

        <section>
          <h2>4. Data Sharing</h2>
          <p>
            We do not sell, rent, or trade user data. Limited data may be shared only if legally required
            or necessary to operate essential app features.
          </p>
        </section>

        <section>
          <h2>5. Data Security</h2>
          <p>
            We use reasonable safeguards to protect your information, but no system can be guaranteed
            to be completely secure.
          </p>
        </section>

        <section>
          <h2>6. Children’s Privacy</h2>
          <p>
            Zealth is not intended for children under 13 and does not knowingly collect their data.
          </p>
        </section>

        <section>
          <h2>7. Your Rights</h2>
          <ul>
            <li>Control permissions via device settings</li>
            <li>Request data deletion where applicable</li>
          </ul>
        </section>

        <section>
          <h2>8. Third-Party Services</h2>
          <p>
            The app may use Google Maps and Android system services,
            each governed by their own privacy policies.
          </p>
        </section>

        <section>
          <h2>9. Changes to This Policy</h2>
          <p>
            This Privacy Policy may be updated periodically. Changes will be reflected on this page and in the app.
          </p>
        </section>

        <section class="full">
          <h2>10. Contact Us</h2>
          <p>If you have questions or concerns about this Privacy Policy, contact us at:</p>

          <div class="fields">
            <div class="field">
              <div class="label">Email</div>
              <div><a href="mailto:cyph3rzw@gmail.com">cyph3rzw@gmail.com</a></div>
            </div>
            <div class="field">
              <div class="label">App Name</div>
              <div>Zealth</div>
            </div>
            <div class="field">
              <div class="label">Developer</div>
              <div>cyph3r (independent developer)</div>
            </div>
          </div>
        </section>

      </div>
    </div>
  </main>

  <footer>
    <div class="wrap">
      © <span id="year"></span> Zealth. All rights reserved.
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
