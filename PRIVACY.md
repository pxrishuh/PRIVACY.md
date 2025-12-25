<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Privacy Policy - Zealth</title>

  <style>
    :root{
      --bg:#ffffff;
      --text:#111111;
      --muted:#555555;
      --card:#f6f7f9;
      --border:#e6e8ee;
      --accent:#2b6cb0;
    }
    body{
      margin:0;
      font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Arial,sans-serif;
      background:var(--bg);
      color:var(--text);
      line-height:1.55;
    }
    header{
      padding:28px 18px;
      border-bottom:1px solid var(--border);
      background:#fafbfc;
    }
    .wrap{
      max-width:900px;
      margin:0 auto;
    }
    h1{ margin:0 0 8px; font-size:28px; }
    .meta{ color:var(--muted); font-size:14px; }

    main{ padding:18px; }
    section{
      margin:18px 0;
      padding:18px;
      background:var(--card);
      border:1px solid var(--border);
      border-radius:14px;
    }
    h2{ margin:0 0 10px; font-size:18px; }
    h3{ margin:14px 0 8px; font-size:15px; }
    p{ margin:10px 0; }
    ul{ margin:10px 0 0 20px; }
    li{ margin:6px 0; }

    .note{
      border-left:4px solid var(--accent);
      padding:10px 12px;
      background:#fff;
      border-radius:10px;
      border:1px solid var(--border);
    }

    footer{
      padding:18px;
      border-top:1px solid var(--border);
      color:var(--muted);
      font-size:13px;
      text-align:center;
    }

    .fields{
      display:grid;
      grid-template-columns:1fr;
      gap:10px;
    }
    .field{
      background:#fff;
      border:1px solid var(--border);
      border-radius:12px;
      padding:12px;
    }
    .label{
      font-size:12px;
      color:var(--muted);
      text-transform:uppercase;
      letter-spacing:0.5px;
    }
    @media (min-width:720px){
      .fields{ grid-template-columns:1fr 1fr; }
    }
  </style>
</head>

<body>

<header>
  <div class="wrap">
    <h1>Privacy Policy</h1>
    <div class="meta">
      App: Zealth • Effective Date: January 1, 2025
    </div>
  </div>
</header>

<main>
  <div class="wrap">

    <p>
      Zealth (“we”, “our”, or “us”) respects your privacy and is committed to protecting your personal information.
      This Privacy Policy explains how information is collected, used, and safeguarded when you use the Zealth
      mobile application (“the App”).
    </p>

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
        This Privacy Policy may be updated periodically. Changes will be reflected in the app.
      </p>
    </section>

    <section>
      <h2>10. Contact Us</h2>
      <div class="fields">
        <div class="field">
          <div class="label">Email</div>
          <div>cyph3rzw@gmail.com</div>
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
</main>

<footer>
  © <span id="year"></span> Zealth. All rights reserved.
</footer>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>
