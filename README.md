# Krypton investment 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Krypton - Crypto Investment Platform</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #0d1117;
      color: #f1f1f1;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(135deg, #1f2937, #111827);
      text-align: center;
      padding: 60px 20px;
      box-shadow: 0 0 20px rgba(0,255,150,0.2);
    }

    header h1 {
      font-size: 40px;
      margin: 0;
      color: #00ffae;
      text-shadow: 0 0 10px #00ffae88;
    }

    header p {
      margin-top: 10px;
      font-size: 18px;
      color: #ccc;
    }

    .button {
      margin-top: 25px;
      background-color: #00ffae;
      color: #0d1117;
      padding: 14px 28px;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px #00ffaeaa;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    .intro, .steps, .plans {
      margin-bottom: 60px;
      transform: translateY(30px);
      opacity: 0;
      transition: all 0.6s ease-in-out;
    }

    .visible {
      transform: translateY(0);
      opacity: 1;
    }

    .plans {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .plan {
      background: #161b22;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,255,150,0.1);
    }

    .plan h3 {
      color: #00ffae;
    }

    footer {
      background: #111827;
      color: #888;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>KRYPTON</h1>
  <p>Smart Crypto Investments, Made Easy and Secure</p>
  <a class="button" href="https://t.me/Kryptonplans" target="_blank">Get Started on Telegram</a>
</header>

<section class="intro">
  <h2>How to Start Investing with Krypton</h2>
  <p>
    Welcome to Krypton — your gateway to earning steady returns in the booming world of cryptocurrency. Whether you're a beginner or a seasoned investor, our system is built to maximize your gains with minimal stress. Here's how it works:
  </p>
  <p>
    1. <strong>Connect with our team on Telegram</strong>: We'll walk you through the setup process personally.<br>
    2. <strong>Choose your investment tier</strong> based on how much you want to start with.<br>
    3. <strong>Fund your wallet</strong> using any of our supported payment options (crypto, card, etc.)<br>
    4. <strong>Sit back and watch your portfolio grow</strong>, with live updates and withdrawal options anytime.
  </p>
  <p>
    Our automated trading systems, combined with human expertise, help you earn between 5% – 20% weekly. All you have to do is pick a plan and stay connected via Telegram for updates.
  </p>
</section>

<section class="steps">
  <h2>Why Choose Krypton?</h2>
  <ul>
    <li>✔️ Transparent and Real-Time Reporting</li>
    <li>✔️ Weekly Payouts or Compounding Options</li>
    <li>✔️ Low Starting Capital – as low as $10</li>
    <li>✔️ 24/7 Support on Telegram</li>
    <li>✔️ 100% Mobile-Friendly</li>
  </ul>
</section>

<section class="plans">
  <h2>Investment Plans</h2>
  <div class="plan">
    <h3>Starter Plan</h3>
    <p>$10 – $49</p>
    <p>💰 5% return weekly</p>
  </div>
  <div class="plan">
    <h3>Pro Plan</h3>
    <p>$50 – $149</p>
    <p>💰 10% return weekly</p>
  </div>
  <div class="plan">
    <h3>Elite Plan</h3>
    <p>$150 and above</p>
    <p>💰 20% return weekly</p>
  </div>
</section>

<footer>
  <p>© 2025 Krypton. All rights reserved. Powered by smart crypto investing.</p>
</footer>

<script>
  // Reveal animation when scrolling
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  });

  document.querySelectorAll('.intro, .steps, .plans').forEach(section => {
    observer.observe(section);
  });
</script>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Krypton - Crypto Investment Platform</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #0d1117;
      color: #f1f1f1;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(135deg, #1f2937, #111827);
      text-align: center;
      padding: 60px 20px;
      box-shadow: 0 0 20px rgba(0,255,150,0.2);
    }

    header h1 {
      font-size: 40px;
      margin: 0;
      color: #00ffae;
      text-shadow: 0 0 10px #00ffae88;
    }

    header p {
      margin-top: 10px;
      font-size: 18px;
      color: #ccc;
    }

    .button {
      margin-top: 25px;
      background-color: #00ffae;
      color: #0d1117;
      padding: 14px 28px;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      transition: transform 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px #00ffaeaa;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
    }

    .intro, .steps, .plans {
      margin-bottom: 60px;
      transform: translateY(30px);
      opacity: 0;
      transition: all 0.6s ease-in-out;
    }

    .visible {
      transform: translateY(0);
      opacity: 1;
    }

    .plans {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .plan {
      background: #161b22;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,255,150,0.1);
    }

    .plan h3 {
      color: #00ffae;
    }

    footer {
      background: #111827;
      color: #888;
      text-align: center;
      padding: 30px 20px;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>KRYPTON</h1>
  <p>Smart Crypto Investments, Made Easy and Secure</p>
  <a class="button" href="https://t.me/Kryptonplans" target="_blank">Get Started on Telegram</a>
</header>

<section class="intro">
  <h2>How to Start Investing with Krypton</h2>
  <p>
    Welcome to Krypton — your gateway to earning steady returns in the booming world of cryptocurrency. Whether you're a beginner or a seasoned investor, our system is built to maximize your gains with minimal stress. Here's how it works:
  </p>
  <p>
    1. <strong>Connect with our team on Telegram</strong>: We'll walk you through the setup process personally.<br>
    2. <strong>Choose your investment tier</strong> based on how much you want to start with.<br>
    3. <strong>Fund your wallet</strong> using any of our supported payment options (crypto, card, etc.)<br>
    4. <strong>Sit back and watch your portfolio grow</strong>, with live updates and withdrawal options anytime.
  </p>
  <p>
    Our automated trading systems, combined with human expertise, help you earn between 5% – 20% weekly. All you have to do is pick a plan and stay connected via Telegram for updates.
  </p>
</section>

<section class="steps">
  <h2>Why Choose Krypton?</h2>
  <ul>
    <li>✔️ Transparent and Real-Time Reporting</li>
    <li>✔️ Weekly Payouts or Compounding Options</li>
    <li>✔️ Low Starting Capital – as low as $10</li>
    <li>✔️ 24/7 Support on Telegram</li>
    <li>✔️ 100% Mobile-Friendly</li>
  </ul>
</section>

<section class="plans">
  <h2>Investment Plans</h2>
  <div class="plan">
    <h3>Starter Plan</h3>
    <p>$10 – $49</p>
    <p>💰 5% return weekly</p>
  </div>
  <div class="plan">
    <h3>Pro Plan</h3>
    <p>$50 – $149</p>
    <p>💰 10% return weekly</p>
  </div>
  <div class="plan">
    <h3>Elite Plan</h3>
    <p>$150 and above</p>
    <p>💰 20% return weekly</p>
  </div>
</section>

<footer>
  <p>© 2025 Krypton. All rights reserved. Powered by smart crypto investing.</p>
</footer>

<script>
  // Reveal animation when scrolling
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }https://t.me/Kryptonplans
    });
  });

  document.querySelectorAll('.intro, .steps, .plans').forEach(section => {
    observer.observe(section);
  });
</script>

</body>
</html>
