<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>BookedAI – AI Lead Generation & Appointment Booking</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <style>
    :root {
      --bg-gradient: radial-gradient(circle at top left, #1d4ed8 0, #020617 45%, #000 100%);
      --accent: #22c55e;
      --accent-soft: rgba(34, 197, 94, 0.12);
      --text-main: #e5e7eb;
      --text-muted: #9ca3af;
      --card-bg: rgba(15, 23, 42, 0.9);
      --border-subtle: rgba(148, 163, 184, 0.22);
      --shadow-soft: 0 24px 60px rgba(15, 23, 42, 0.8);
      --radius-lg: 18px;
      --radius-md: 12px;
      --transition-fast: 180ms ease-out;
      --transition-med: 260ms ease-out;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #020617;
      color: var(--text-main);
      min-height: 100vh;
      -webkit-font-smoothing: antialiased;
      background-image: var(--bg-gradient);
      background-attachment: fixed;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      inset: -200px;
      background:
        radial-gradient(circle at 10% 0%, rgba(37, 99, 235, 0.25) 0, transparent 55%),
        radial-gradient(circle at 90% 10%, rgba(56, 189, 248, 0.18) 0, transparent 60%),
        radial-gradient(circle at 50% 110%, rgba(34, 197, 94, 0.18) 0, transparent 55%);
      opacity: 0.85;
      pointer-events: none;
      z-index: -1;
      animation: backgroundFloat 18s ease-in-out infinite alternate;
    }

    @keyframes backgroundFloat {
      from {
        transform: translate3d(0, 0, 0) scale(1);
      }
      to {
        transform: translate3d(0, -20px, 0) scale(1.03);
      }
    }

    main {
      max-width: 1200px;
      margin: 0 auto;
      padding: 40px 20px 80px;
    }

    section {
      padding: 60px 0;
      position: relative;
    }

    h1, h2, h3 {
      color: #f9fafb;
      letter-spacing: 0.01em;
    }

    h1 {
      font-size: clamp(2.6rem, 4vw, 3.1rem);
      line-height: 1.1;
    }

    h2 {
      font-size: clamp(2rem, 3vw, 2.4rem);
      margin-bottom: 16px;
    }

    h3 {
      font-size: 1.15rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1rem;
      line-height: 1.75;
      color: var(--text-muted);
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .btn {
      background: linear-gradient(135deg, #22c55e, #4ade80);
      color: #022c22;
      padding: 14px 26px;
      border-radius: 999px;
      font-weight: 600;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      margin-top: 26px;
      border: 1px solid rgba(22, 163, 74, 0.4);
      box-shadow: 0 18px 40px rgba(34, 197, 94, 0.35);
      transition:
        transform var(--transition-med),
        box-shadow var(--transition-med),
        background var(--transition-fast),
        filter var(--transition-fast);
      font-size: 0.98rem;
      position: relative;
      overflow: hidden;
    }

    .btn::after {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at 0% 0%, rgba(255, 255, 255, 0.25) 0, transparent 55%);
      opacity: 0;
      transition: opacity var(--transition-fast);
      pointer-events: none;
    }

    .btn span.arrow {
      display: inline-block;
      transition: transform var(--transition-fast);
    }

    .btn:hover {
      transform: translateY(-1px) scale(1.02);
      box-shadow: 0 24px 55px rgba(34, 197, 94, 0.42);
      filter: brightness(1.02);
    }

    .btn:hover::after {
      opacity: 1;
    }

    .btn:hover .arrow {
      transform: translateX(4px);
    }

    .btn:active {
      transform: translateY(0) scale(0.99);
      box-shadow: 0 12px 24px rgba(34, 197, 94, 0.28);
    }

    .hero {
      display: grid;
      grid-template-columns: minmax(0, 1.3fr) minmax(0, 1fr);
      gap: 40px;
      align-items: center;
    }

    .hero-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(15, 23, 42, 0.8);
      border: 1px solid rgba(148, 163, 184, 0.35);
      color: #e5e7eb;
      font-size: 0.78rem;
      text-transform: uppercase;
      letter-spacing: 0.13em;
      margin-bottom: 16px;
    }

    .hero-eyebrow-dot {
      width: 8px;
      height: 8px;
      border-radius: 999px;
      background: #22c55e;
      box-shadow: 0 0 0 5px rgba(34, 197, 94, 0.25);
      animation: pulseDot 1.8s ease-out infinite;
    }

    @keyframes pulseDot {
      0% {
        transform: scale(1);
        opacity: 1;
      }
      70% {
        transform: scale(1.45);
        opacity: 0;
      }
      100% {
        transform: scale(1.45);
        opacity: 0;
      }
    }

    .hero-subtitle {
      margin: 16px 0 8px;
      font-size: 1.08rem;
    }

    .hero-highlight {
      color: #bbf7d0;
    }

    .hero-bullets {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 22px;
    }

    .hero-chip {
      padding: 6px 12px;
      background: rgba(15, 23, 42, 0.92);
      border-radius: 999px;
      border: 1px solid rgba(148, 163, 184, 0.4);
      font-size: 0.8rem;
      color: #cbd5f5;
    }

    .hero-right {
      position: relative;
    }

    .box {
      background: var(--card-bg);
      padding: 24px 22px;
      border-radius: var(--radius-lg);
      box-shadow: var(--shadow-soft);
      border: 1px solid var(--border-subtle);
      backdrop-filter: blur(18px);
      position: relative;
      overflow: hidden;
      isolation: isolate;
      transition:
        transform var(--transition-med),
        box-shadow var(--transition-med),
        border-color var(--transition-med),
        background var(--transition-med);
    }

    .box::before {
      content: "";
      position: absolute;
      inset: -40%;
      background: conic-gradient(
        from 180deg,
        rgba(34, 197, 94, 0.1),
        transparent,
        rgba(59, 130, 246, 0.1),
        transparent,
        rgba(45, 212, 191, 0.12)
      );
      opacity: 0;
      transform: translate3d(-20px, -10px, 0);
      transition: opacity 260ms ease-out, transform 260ms ease-out;
      z-index: -1;
    }

    .box:hover {
      transform: translateY(-4px);
      box-shadow: 0 26px 60px rgba(15, 23, 42, 0.95);
      border-color: rgba(148, 163, 184, 0.55);
      background: radial-gradient(circle at top left, rgba(34, 197, 94, 0.08), var(--card-bg));
    }

    .box:hover::before {
      opacity: 1;
      transform: translate3d(0, 0, 0);
    }

    .box-title-pill {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 3px 10px;
      border-radius: 999px;
      background: rgba(15, 23, 42, 0.9);
      border: 1px solid rgba(148, 163, 184, 0.5);
      font-size: 0.72rem;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.16em;
      margin-bottom: 10px;
    }

    .badge-dot {
      width: 6px;
      height: 6px;
      border-radius: 999px;
      background: #22c55e;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 24px;
    }

    ul {
      padding-left: 18px;
      margin: 10px 0 0;
    }

    ul li {
      margin-bottom: 8px;
      font-size: 0.96rem;
      color: #cbd5f5;
    }

    .section-header {
      max-width: 640px;
      margin-bottom: 32px;
    }

    .section-tag {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(15, 23, 42, 0.92);
      border: 1px solid rgba(148, 163, 184, 0.4);
      font-size: 0.76rem;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.18em;
    }

    .section-tag span.icon {
      font-size: 0.9rem;
    }

    .funnel-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 18px;
    }

    .funnel-step {
      position: relative;
      padding: 18px 16px;
      text-align: left;
      font-size: 0.96rem;
      border-radius: var(--radius-md);
      background: rgba(15, 23, 42, 0.92);
      border: 1px solid rgba(148, 163, 184, 0.35);
      color: #e5e7eb;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      gap: 6px;
      transition:
        transform var(--transition-med),
        box-shadow var(--transition-med),
        border-color var(--transition-med),
        background var(--transition-med);
    }

    .funnel-step small {
      font-size: 0.75rem;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.11em;
    }

    .funnel-step strong {
      font-size: 0.98rem;
    }

    .funnel-step::after {
      content: "";
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at top right, rgba(34, 197, 94, 0.15), transparent 65%);
      opacity: 0;
      transition: opacity var(--transition-med);
      pointer-events: none;
    }

    .funnel-step:hover {
      transform: translateY(-4px);
      border-color: rgba(74, 222, 128, 0.8);
      background: radial-gradient(circle at top left, rgba(34, 197, 94, 0.14), rgba(15, 23, 42, 0.96));
      box-shadow: 0 18px 45px rgba(34, 197, 94, 0.35);
    }

    .funnel-step:hover::after {
      opacity: 1;
    }

    form {
      margin-top: 10px;
    }

    .form-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 14px 16px;
    }

    .form-grid-full {
      grid-column: 1 / -1;
    }

    label {
      display: block;
      font-size: 0.8rem;
      color: var(--text-muted);
      margin-bottom: 4px;
    }

    input, select, button {
      width: 100%;
      padding: 11px 12px;
      border-radius: 9px;
      border: 1px solid rgba(30, 64, 175, 0.45);
      background: rgba(15, 23, 42, 0.9);
      font-size: 0.95rem;
      color: var(--text-main);
      outline: none;
      transition:
        border-color 160ms ease-out,
        box-shadow 160ms ease-out,
        background 160ms ease-out,
        transform 120ms ease-out;
    }

    input::placeholder,
    select::placeholder {
      color: rgba(148, 163, 184, 0.75);
    }

    input:focus,
    select:focus {
      border-color: rgba(56, 189, 248, 0.9);
      box-shadow: 0 0 0 1px rgba(56, 189, 248, 0.75), 0 0 0 12px rgba(56, 189, 248, 0.16);
      background: #020617;
      transform: translateY(-1px);
    }

    button[type="submit"] {
      margin-top: 4px;
      background: linear-gradient(135deg, #22c55e, #16a34a);
      border-radius: 999px;
      border: none;
      font-weight: 600;
      cursor: pointer;
      box-shadow: 0 12px 32px rgba(34, 197, 94, 0.4);
      letter-spacing: 0.02em;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
    }

    button[type="submit"]:hover {
      filter: brightness(1.05);
      transform: translateY(-1px);
      box-shadow: 0 16px 38px rgba(34, 197, 94, 0.48);
    }

    button[type="submit"]:active {
      transform: translateY(0);
      box-shadow: 0 8px 18px rgba(34, 197, 94, 0.3);
    }

    .hint {
      font-size: 0.78rem;
      color: var(--text-muted);
      margin-top: 8px;
    }

    .calendly-wrapper {
      position: relative;
      border-radius: var(--radius-lg);
      overflow: hidden;
      border: 1px solid rgba(148, 163, 184, 0.35);
      box-shadow: var(--shadow-soft);
      background: radial-gradient(circle at top left, rgba(59, 130, 246, 0.18), rgba(15, 23, 42, 0.96));
    }

    .calendly-wrapper iframe {
      display: block;
      width: 100%;
      height: 600px;
      border: 0;
    }

    footer {
      background: rgba(15, 23, 42, 0.98);
      text-align: center;
      padding: 28px 16px 40px;
      color: #6b7280;
      font-size: 0.86rem;
      border-top: 1px solid rgba(31, 41, 55, 0.9);
      margin-top: 40px;
    }

    footer span.brand {
      color: #e5e7eb;
    }

    .reveal {
      opacity: 0;
      transform: translateY(26px);
      transition:
        opacity 650ms ease-out,
        transform 650ms ease-out;
      will-change: opacity, transform;
    }

    .reveal.reveal-visible {
      opacity: 1;
      transform: translateY(0);
    }

    .reveal-delay-1 {
      transition-delay: 90ms;
    }

    .reveal-delay-2 {
      transition-delay: 180ms;
    }

    .reveal-delay-3 {
      transition-delay: 270ms;
    }

    .reveal-delay-4 {
      transition-delay: 360ms;
    }

    @media (max-width: 960px) {
      main {
        padding-top: 28px;
      }

      .hero {
        grid-template-columns: minmax(0, 1fr);
        gap: 32px;
      }

      section {
        padding: 46px 0;
      }
    }

    @media (max-width: 720px) {
      .form-grid {
        grid-template-columns: 1fr;
      }

      .hero-bullets {
        flex-direction: column;
        align-items: flex-start;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      * {
        scroll-behavior: auto !important;
        animation-duration: 0.001ms !important;
        animation-iteration-count: 1 !important;
        transition: none !important;
      }
    }
  </style>
</head>

<body>
  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="reveal">
        <div class="hero-eyebrow">
          <span class="hero-eyebrow-dot"></span>
          <span>AI-Powered Lead Engine</span>
        </div>

        <h1>We Turn Local Enquiries into Booked Appointments Using AI</h1>

        <p class="hero-subtitle">
          BookedAI helps <span class="hero-highlight">clinics and real estate agents</span> capture, qualify, and convert leads into
          <span class="hero-highlight">predictable bookings</span> without chasing prospects all day.
        </p>

        <a href="#audit" class="btn">
          <span>Get Free AI Lead Audit</span>
          <span class="arrow">→</span>
        </a>

        <div class="hero-bullets">
          <span class="hero-chip">Response in under 60 seconds</span>
          <span class="hero-chip">WhatsApp, SMS & calls</span>
          <span class="hero-chip">Done-for-you setup</span>
        </div>
      </div>

      <div class="hero-right reveal reveal-delay-2">
        <div class="box">
          <div class="box-title-pill">
            <span class="badge-dot"></span>
            <span>Who this is for</span>
          </div>
          <ul>
            <li>Clinics missing calls & enquiries</li>
            <li>Agents struggling with consistent follow-ups</li>
            <li>Local businesses that want predictable leads every month</li>
          </ul>
          <p class="hint" style="margin-top:14px;">
            Plug BookedAI into your existing ads or website and start seeing booked appointments in days, not months.
          </p>
        </div>
      </div>
    </section>

    <!-- PROBLEM -->
    <section>
      <div class="section-header reveal">
        <div class="section-tag">
          <span class="icon">⚠️</span>
          <span>Why leads leak</span>
        </div>
        <h2>Why Most Leads Never Convert</h2>
        <p>
          You are already paying for clicks and calls, but most enquiries slip through the cracks because no one replies fast enough, follows up consistently, or tracks what is working.
        </p>
      </div>

      <div class="grid">
        <div class="box reveal reveal-delay-1">
          <h3>Slow Response</h3>
          <p>
            Leads expect replies in minutes, not hours, and simply move on to the next clinic or agent when they do not hear back quickly.
          </p>
        </div>

        <div class="box reveal reveal-delay-2">
          <h3>No Follow-Ups</h3>
          <p>
            Most interested leads only respond after multiple touchpoints, but manual follow-ups rarely happen beyond the first contact.
          </p>
        </div>

        <div class="box reveal reveal-delay-3">
          <h3>No Tracking</h3>
          <p>
            Owners often cannot see which channels bring revenue, so they keep spending blindly without fixing the leaks in the funnel.
          </p>
        </div>
      </div>
    </section>

    <!-- SOLUTION / FUNNEL -->
    <section>
      <div class="section-header reveal">
        <div class="section-tag">
          <span class="icon">🚀</span>
          <span>Our AI funnel</span>
        </div>
        <h2>How BookedAI Turns Leads into Revenue</h2>
        <p>
          BookedAI captures enquiries across channels, qualifies them using AI, follows up automatically, and books them directly into your calendar.
        </p>
      </div>

      <div class="funnel-grid">
        <div class="funnel-step reveal reveal-delay-1">
          <small>Step 1</small>
          <strong>Lead Capture</strong>
          <p>Forms, WhatsApp, ads, and website chats feed into one unified inbox.</p>
        </div>
        <div class="funnel-step reveal reveal-delay-2">
          <small>Step 2</small>
          <strong>AI Qualification</strong>
          <p>Smart questions qualify intent, budget, and timeline in real time.</p>
        </div>
        <div class="funnel-step reveal reveal-delay-3">
          <small>Step 3</small>
          <strong>Instant Follow-Ups</strong>
          <p>Automated WhatsApp, SMS, and email sequences follow up 24/7.</p>
        </div>
        <div class="funnel-step reveal reveal-delay-4">
          <small>Step 4</small>
          <strong>Appointment Booking</strong>
          <p>Qualified leads are routed and booked directly into your calendar.</p>
        </div>
        <div class="funnel-step reveal reveal-delay-4">
          <small>Step 5</small>
          <strong>Client Revenue</strong>
          <p>You focus on serving clients while BookedAI keeps your pipeline full.</p>
        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section>
      <div class="section-header reveal">
        <div class="section-tag">
          <span class="icon">🎯</span>
          <span>Who we help</span>
        </div>
        <h2>What We Deliver for You</h2>
        <p>
          BookedAI is tailored for high-intent local services where every missed enquiry costs real revenue.
        </p>
      </div>

      <div class="grid">
        <div class="box reveal reveal-delay-1">
          <h3>Clinics & Dental</h3>
          <ul>
            <li>Patient enquiries turned into confirmed appointments</li>
            <li>Automated WhatsApp & SMS recalls and reminders</li>
            <li>No missed calls or lost follow-ups during busy hours</li>
          </ul>
        </div>

        <div class="box reveal reveal-delay-2">
          <h3>Real Estate</h3>
          <ul>
            <li>High-intent buyer and tenant leads from your existing ads</li>
            <li>Automated nurturing until they are ready to visit</li>
            <li>Booked calls and site visits directly on your calendar</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- AUDIT FORM (CONNECTED TO GOOGLE SHEETS) -->
    <section id="audit">
      <div class="section-header reveal">
        <div class="section-tag">
          <span class="icon">📊</span>
          <span>Free lead audit</span>
        </div>
        <h2>Get Your Free AI Lead Audit</h2>
        <p>
          Understand how many leads and appointments you are currently leaking and what is possible with a fully automated AI funnel.
        </p>
      </div>

      <div class="box reveal reveal-delay-1">
        <form id="audit-form">
          <div class="form-grid">
            <div>
              <label for="name">Your Name</label>
              <input id="name" name="name" type="text" placeholder="John Doe" required />
            </div>

            <div>
              <label for="phone">Phone Number</label>
              <input id="phone" name="phone" type="tel" placeholder="+91 98765 43210" required />
            </div>

            <div>
              <label for="email">Email ID</label>
              <input id="email" name="email" type="email" placeholder="you@example.com" required />
            </div>

            <div>
              <label for="website">Website URL</label>
              <input id="website" name="website" type="url" placeholder="https://yourclinic.com" />
            </div>

            <div>
              <label for="city">City</label>
              <input id="city" name="city" type="text" placeholder="Bengaluru" required />
            </div>

            <div>
              <label for="business-type">Business Type</label>
              <select id="business-type" name="businessType" required>
                <option value="">Select Business Type</option>
                <option value="Clinic / Dental">Clinic / Dental</option>
                <option value="Real Estate">Real Estate</option>
              </select>
            </div>

            <div class="form-grid-full">
              <button type="submit">
                Book Free Audit <span>→</span>
              </button>
              <p class="hint">
                No long contracts, no spam. A specialist will review your current setup and walk you through quick wins.
              </p>
            </div>
          </div>
        </form>
      </div>
    </section>
  </main>

  <footer>
    © 2026 <span class="brand">BookedAI</span>. Results-focused AI growth partner.
  </footer>

  <script>
    // Scroll reveal
    const reveals = document.querySelectorAll('.reveal');

    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) {
            entry.target.classList.add('reveal-visible');
            observer.unobserve(entry.target);
          }
        });
      },
      {
        threshold: 0.16
      }
    );

    reveals.forEach((el) => observer.observe(el));

    // === GOOGLE SHEETS INTEGRATION ===
    const scriptURL = "https://script.google.com/macros/s/AKfycbzzhA900NMGFn18HYpoA9DXzv2zOlzEmseVwrh9NjRamRoeEAugr65iCqNRciWj78Eb/exec";
    const form = document.getElementById('audit-form');

    form.addEventListener('submit', (e) => {
      e.preventDefault();

      const submitButton = form.querySelector('button[type="submit"]');
      const originalText = submitButton.textContent;
      submitButton.disabled = true;
      submitButton.textContent = 'Submitting...';

      fetch(scriptURL, {
        method: 'POST',
        body: new FormData(form)
      })
        .then((res) => {
          if (!res.ok) {
            throw new Error('Network response was not ok');
          }
          return res.text();
        })
        .then(() => {
          alert('Thanks! Your audit request has been saved.');
          form.reset();
        })
        .catch((err) => {
          console.error('Error!', err);
          alert('Something went wrong. Please try again.');
        })
        .finally(() => {
          submitButton.disabled = false;
          submitButton.textContent = originalText;
        });
    });
  </script>
  <script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/12.7.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/12.7.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyDZvZDagV0cO9pvlRziDpgxLK4VKliSB1c",
    authDomain: "apex-leads-7bafa.firebaseapp.com",
    projectId: "apex-leads-7bafa",
    storageBucket: "apex-leads-7bafa.firebasestorage.app",
    messagingSenderId: "198817636490",
    appId: "1:198817636490:web:9b48d2b5ab6d80427b8d73",
    measurementId: "G-BJJKQHFV5R"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
</body>
</html>
