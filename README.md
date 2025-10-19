
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Help Hope Flow — Nonprofit Landing Page</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    /* ========= Brand Identity ========= */
    :root{
      --yellow:#FFC907; /* Primary accent */
      --blue:#2E9DF7;   /* Primary brand blue */
      --ink:#111827;    /* Dark text */
      --bg:#FFFFFF;     /* Background */
      --muted:#6B7280;  /* Secondary text */
    }

    /* ========= Base Reset ========= */
    *,*::before,*::after{ box-sizing:border-box; }
    html,body{ margin:0; height:100%; }
    body{
      font-family:"Inter",system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
      line-height:1.6;
      color:var(--ink);
      background:var(--bg);
    }
    img{ max-width:100%; display:block; height:auto; }
    a{ color:inherit; text-decoration:none; }

    /* ========= Utility Buttons ========= */
    .btn{ display:inline-block; padding:12px 18px; border-radius:999px; font-weight:700; font-size:.95rem; transition:transform .08s ease, box-shadow .2s ease, background .2s ease, color .2s ease; }
    .btn:active{ transform:translateY(1px); }
    .btn-primary{ background:var(--yellow); color:#0B0B0B; box-shadow:0 8px 18px rgba(255,211,0,.35); }
    .btn-primary:hover{ box-shadow:0 10px 24px rgba(255,211,0,.5); }
    .btn-ghost{ border:2px solid var(--blue); color:var(--blue); background:transparent; }
    .btn-ghost:hover{ background:var(--blue); color:#fff; }

    /* ========= Header ========= */
    header{
      position:sticky; top:0; z-index:40;
      background:rgba(255,255,255,.9);
      backdrop-filter:saturate(180%) blur(8px);
      border-bottom:1px solid #EDF2F7;
    }
    .nav{
      max-width:1120px; margin:0 auto;
      display:flex; align-items:center; justify-content:space-between;
      padding:14px 20px;
    }
    .brand{ font-weight:800; letter-spacing:.2px; display:flex; gap:10px; align-items:center; }
    .brand-badge{ width:20px; height:20px; border-radius:6px; background:var(--yellow); box-shadow:inset 0 0 0 2px #0B0B0B; }
    .nav-links{ display:flex; gap:10px; align-items:center; }

    /* ========= Hero (centered, full-width image) ========= */
   <html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Help Hope Flow — Preview</title>
<style>
body{margin:0;background:#fff;font-family:Inter,Arial,sans-serif;display:flex;align-items:center;justify-content:center;height:100vh;}
.hero{position:relative;width:90%;max-width:1120px;}
.hero img{width:100%;border-radius:16px;box-shadow:0 8px 24px rgba(0,0,0,.15);}
.hero-content{position:absolute;top:calc(20% - 30px);left:6%;max-width:500px;z-index:2;color:#8BD1CB;}
.hero h1{font-size:clamp(3rem,6vw,4.5rem);margin-bottom:1rem;letter-spacing:-0.03em;color:#8BD1CB;}
.hero .sub{font-size:1rem;margin-bottom:2rem;color:#fff;max-width:38ch;}
.btn{display:inline-block;padding:12px 18px;border-radius:999px;font-weight:700;font-size:.95rem;text-decoration:none;background:#FFC907;color:#0B0B0B;}
</style>
</head>
<body>
<section class="hero">
  <img src="https://cdn2.dropmarkusercontent.com/52043/809d2040ab4ec6268c738d2599473572e3e6648910f1e5ab507ddb08e5e9c758/Zimbabwe_2022_CG-7529.jpg?Expires=1760846789&Signature=UjPXMSzDxLWKu4WcVoHxPHsUQXJQaIpnBPEJlDWSlBD9aKrH66vYNjKACLX7FmHCU9B6lRs9xGfo9apaZQN9adWF1DXsRnAYCRz4aTZEFG~Gm-R1e8XUJ~60FvbLNBeLgz4fB7IqRH1tXfva7MCXEu6qKa1NIk3b-ukgdtPfE61e8PopF8KN8~744VTa28kSccUmwOrjPaLYhzryU3eGQC7IZ9vgeB46UU1GKOB34-CkgwBLRCPStDP79BBxVqXIyMlpTd82hIWR3J0buTcyC-n-pOh1IvwQp80WZFirFA2B6l4LqYO3J3gnA15E48dbY8UjY1rCVy9GQ0KTZgwmlA__&Key-Pair-Id=APKAITQYWVEN757ZA4KQ" alt="Hero Image">
  <div class="hero-content">
    <h1>Help Hope Flow</h1>
    <p class="sub">Your action today fuels clean water, stronger communities, and climate resilience for generations to come.</p>
    <a class="btn" href="#">Be the Hope</a>
  </div>
</section>
</body>
</html>

    /* ========= Donation CTA ========= */
    .cta{
      text-align:center;
      background:linear-gradient(180deg, #F9FAFB, #FFFFFF);
      border-top:1px solid #EEF2F7; border-bottom:1px solid #EEF2F7;
      padding:64px 20px;
    }
    .cta h2{ margin:0 0 12px; font-size:clamp(1.6rem,3.6vw,2.4rem); }
    .cta p{ margin:0 0 22px; color:var(--muted); }

    footer{
      text-align:center; padding:20px; color:var(--muted); font-size:.9rem;
    }

    /* ========= Responsive: make layout adapt to smaller screens ========= */
    @media (max-width: 900px){
      /* On tablets/smaller laptops, stack the story columns for readability */
      .story{ grid-template-columns:1fr; }
    }

    @media (max-width: 600px){
      /* On phones, reduce paddings and font sizes for comfortable viewing */
      .hero-inner{ padding:42px 16px; }
      .section{ padding:40px 16px; }
      .cta{ padding:48px 16px; }

      /* This media query ensures touch-friendly spacing and avoids text overflow on narrow screens */
      .btn{ padding:11px 16px; font-size:.95rem; }
    }
  </style>
</head>
<body>
  <!-- Header with brand + utility links -->
  <header>
    <div class="nav">
      <div class="brand"><span class="brand-badge" aria-hidden="true"></span>Help Hope Flow</div>
      <nav class="nav-links" aria-label="Primary">
        <a class="btn-ghost btn" href="#story">Our Work</a>
        <a class="btn-ghost btn" href="#donate">See Your Impact</a>
      </nav>
    </div>
  </header>

  <!-- HERO: centered headline, subheadline, full-width background image -->
  <section class="hero" id="hero" aria-label="Hero">
    <div class="hero-inner">
      <h1>Clean Water Transforms Lives</h1>
      <p>Together we bring safe water to families, unlocking health, education, and opportunity.</p>
      <a class="btn btn-primary" href="#donate">Donate Now</a>
    </div>
  </section>

  <!-- STORY: real-world impact with text and image -->
  <section class="section" id="story" aria-label="Impact Story">
    <div class="container story">
      <img src="https://cdn2.dropmarkusercontent.com/52043/2c338c5d3767fc774fbcfefe18e4ad8072a0f5f6f26936fecda4d771e8740dab/Madagascar_2019_CG-2474.jpg?Expires=1760868168&Signature=BdT7jP8yD4o8RszOs2fVgnMxgV9ZVw9e3QOn0dWfsws8M7OseIk0kTR9OaGrju4P-i0Dk~aZlc9ZZKJmpjrwVCIIhTxnvTvFlEcO3n~GZvp3XAMkrR1-IZi735dE81UrcB7YcrURWe1csMHrL6pKKsYNl-irkRXRIb9Al~jl-f~LIMuL5w6yMWWz~nyeWJ9301LKugdhuwXKAkV3SCLhlMlTXRQPAaBeD2vLjhef-bctCXskVVjNVGKRx6w98zv-FAniMJZRTpGJJ5sAKwCxbeAu1N5h11~yPkEECGDvQiphVZesCs4E2qM~25RXKD5~Fy2fvmNsuJMVRveTPXbZRQ__&Key-Pair-Id=APKAITQYWVEN757ZA4KQ">
      <div>
        <h2>Amina's New Hope</h2>
        <p>Amina used to walk miles every day to collect water for her family. Thanks to your support, her village now has a clean water well. Amina can go to school and her family is healthier and happier.</p>
        <a class="btn btn-ghost" href="#donate">Read more impact →</a>
      </div>
    </div>
  </section>

  <!-- CTA: bold donation section -->
  <section class="cta" id="donate" aria-label="Donate">
    <div class="container">
      <h2>Your Gift Starts the Flow</h2>
      <p>$25 helps provide safe water access for a month. Every amount pushes us closer to universal access.</p>
      <a class="btn btn-primary" href="#">Donate Now</a>
    </div>
  </section>

  <footer>
    © Help Hope Flow — Clean water, for everyone.
  </footer>
</body>
</html>
