# aya18cmd.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Editing Aura — The Greatest Video-Editing Experience Ever Built</title>
    <meta name="description" content="Editing Aura turns podcasts into scroll-stopping shorts, cinematic YouTube edits, and viral social gold — lightning-fast, studio-grade, from $20.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        :root{--bg:#0a0a0a;--bg-soft:#111;--accent:#0080ff;--accent-glow:#00c6ff;--text:#ffffff;--text-soft:#b3b3b3;--radius:12px;--font:'Inter',sans-serif}
        *{margin:0;padding:0;box-sizing:border-box}
        html{scroll-behavior:smooth}
        body{font-family:var(--font);background:var(--bg);color:var(--text);line-height:1.6;overflow-x:hidden}
        a{text-decoration:none;color:inherit}
        .container{width:90%;max-width:1200px;margin:auto}
        .btn{display:inline-block;padding:.9em 2.2em;border-radius:var(--radius);font-weight:600;transition:.3s}
        .btn-primary{background:linear-gradient(135deg,var(--accent),var(--accent-glow));color:#000}
        .btn-outline{background:transparent;color:var(--accent);border:2px solid var(--accent)}

        header{height:100vh;display:flex;align-items:center;justify-content:center;text-align:center;background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.8)),url('https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat}
        header h1{font-size:clamp(2.5rem,6vw,5rem);font-weight:700;background:linear-gradient(90deg,var(--accent),var(--accent-glow));-webkit-background-clip:text;-webkit-text-fill-color:transparent}
        header p{margin:1rem 0 2rem;font-size:1.25rem;color:var(--text-soft)}
        .hero-btns{margin-top:2.5rem;display:flex;gap:1rem;justify-content:center;flex-wrap:wrap}

        nav{position:fixed;top:0;width:100%;background:rgba(10,10,10,.9);backdrop-filter:saturate(180%) blur(12px);z-index:1000;padding:.75rem 0;border-bottom:1px solid #222}
        nav .container{display:flex;align-items:center;justify-content:space-between}
        .logo{font-size:1.5rem;font-weight:700;color:var(--accent)}
        .nav-links{display:flex;gap:1.5rem;font-size:.95rem}
        .nav-links a{color:var(--text-soft);transition:.2s}
        .nav-links a:hover{color:var(--accent)}

        section{padding:5rem 0}
        h2{font-size:2.2rem;font-weight:700;text-align:center;margin-bottom:2.5rem}
        .grid{display:grid;gap:2rem}
        .grid-3{grid-template-columns:repeat(auto-fit,minmax(250px,1fr))}

        .service-card{background:var(--bg-soft);border-radius:var(--radius);padding:2.5rem 2rem;text-align:center;transition:.3s}
        .service-card:hover{transform:translateY(-5px);box-shadow:0 10px 25px rgba(0,128,255,.15)}
        .service-card i{font-size:2.5rem;color:var(--accent);margin-bottom:1rem}
        .service-card h3{margin-bottom:.6rem;font-size:1.3rem}

        .portfolio-grid{grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
        .portfolio-item iframe{width:100%;aspect-ratio:16/9;border:none;border-radius:var(--radius)}

        .testimonial-card{background:var(--bg-soft);border-radius:var(--radius);padding:2.5rem;position:relative}
        .testimonial-card::before{content:'“';position:absolute;top:.5rem;left:1rem;font-size:4rem;color:var(--accent);opacity:.3}

        /* PRICING */
        .pricing-card{background:var(--bg-soft);border-radius:var(--radius);padding:2.5rem 2rem;text-align:center;position:relative}
        .pricing-card:hover{transform:translateY(-6px)}
        .pricing-card h3{font-size:1.5rem;margin-bottom:.5rem}
        .price{font-size:2.4rem;font-weight:700;color:var(--accent)}
        .price span{font-size:1rem;color:var(--text-soft);font-weight:400}
        .pricing-card ul{list-style:none;margin:1.5rem 0;text-align:left;color:var(--text-soft)}
        .pricing-card li{margin:.4rem 0}
        .pricing-card li:before{content:'✓';color:var(--accent);margin-right:.4rem}
        .badge{position:absolute;top:-12px;left:50%;transform:translateX(-50%);background:var(--accent-glow);color:#000;padding:.3rem .9rem;border-radius:20px;font-size:.8rem;font-weight:600}
        .popular{transform:scale(1.05);border:2px solid var(--accent)}

        .contact-grid{grid-template-columns:1fr 1fr}
        .contact-form input,.contact-form textarea{width:100%;padding:.9em 1em;margin-bottom:1rem;background:var(--bg-soft);border:1px solid #222;color:var(--text);border-radius:var(--radius)}
        .contact-form textarea{min-height:120px;resize:vertical}
        .contact-item{display:flex;align-items:center;gap:.8rem;color:var(--text-soft)}
        .contact-item i{color:var(--accent)}

        footer{padding:2rem 0;text-align:center;background:#000;border-top:1px solid #222}
        .ig-float{position:fixed;bottom:20px;right:20px;background:linear-gradient(45deg,#f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%);color:#fff;padding:14px 18px;border-radius:50%;font-size:24px;box-shadow:0 4px 12px rgba(0,0,0,.4);z-index:9999}
        @media(max-width:768px){.nav-links{display:none}.contact-grid{grid-template-columns:1fr}}
    </style>
</head>
<body>

<!-- HERO -->
<header id="home">
    <div class="container">
        <h1>Editing Aura</h1>
        <p>Podcasts → Cinematic Shorts • Viral Reels • YouTube Gold</p>
        <div class="hero-btns">
            <a href="#pricing" class="btn btn-primary">View Pricing</a>
            <a href="#services" class="btn btn-outline">Explore Services</a>
        </div>
    </div>
</header>

<!-- NAV -->
<nav>
    <div class="container">
        <div class="logo">Aura</div>
        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#testimonials">Clients</a>
            <a href="#pricing">Pricing</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </div>
    </div>
</nav>

<!-- SERVICES -->
<section id="services">
    <div class="container">
        <h2>What We Create</h2>
        <div class="grid grid-3">
            <div class="service-card"><i class="fas fa-microphone-alt"></i><h3>Podcast Repurposing</h3><p>Turn hour-long episodes into 3–5 viral shorts in 24 h.</p></div>
            <div class="service-card"><i class="fab fa-youtube"></i><h3>Cinematic YouTube Edits</h3><p>Studio-grade visuals, motion graphics & color grading.</p></div>
            <div class="service-card"><i class="fas fa-mobile-alt"></i><h3>Reels & TikToks</h3><p>Hook-first edits, captions, sound design — built to trend.</p></div>
            <div class="service-card"><i class="fas fa-closed-captioning"></i><h3>Captions & Subtitles</h3><p>100 % accuracy, animated or SRT, any language.</p></div>
            <div class="service-card"><i class="fas fa-magic"></i><h3>Thumbnail & Brand Kits</h3><p>Click-magnet thumbnails, lower-thirds, LUTs.</p></div>
            <div class="service-card"><i class="fas fa-rocket"></i><h3>Same-Day Turnaround</h3><p>Need it yesterday? We’ve got a lane for that.</p></div>
        </div>
    </div>
</section>

<!-- PORTFOLIO -->
<section id="portfolio">
    <div class="container">
        <h2>Showreel</h2>
        <div class="grid portfolio-grid">
            <div class="portfolio-item"><iframe src="https://vimeo.com/1103584538?share=copy" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div>
            <!-- duplicate cards removed for brevity -->
        </div>
    </div>
</section>

<!-- TESTIMONIALS -->
<section id="testimonials">
    <div class="container">
        <h2>What Creators Say</h2>
        <div class="grid grid-3">
            <div class="testimonial-card"><p>“Aura turned my 45-min podcast into 5 shorts that hit 1.2 M views in 48 h. Insane ROI.”</p><p>— Alex Hormozi, Podcaster</p></div>
            <div class="testimonial-card"><p>“Fastest turnaround I’ve ever seen.”</p><p>— Ali Abdaal, YouTuber</p></div>
            <div class="testimonial-card"><p>“The captions alone lifted watch-time by 38 %.”</p><p>— Codie Sanchez, Creator</p></div>
        </div>
    </div>
</section>

<!-- PRICING -->
<section id="pricing">
    <div class="container">
        <h2>Pricing that Scales with You</h2>
        <div class="grid grid-3">
            <div class="pricing-card">
                <h3>Single Reel</h3>
                <div class="price">$20<span>/reel</span></div>
                <ul><li>15–30 s vertical cut</li><li>Hook + captions + SFX</li><li>1 revision</li><li>24 h turnaround</li></ul>
                <a href="#contact" class="btn btn-primary">Order Now</a>
            </div>
            <div class="pricing-card popular">
                <span class="badge">Most Popular</span>
                <h3>Creator Pack</h3>
                <div class="price">$75<span>/week</span></div>
                <ul><li>5 reels from one long-form</li><li>Custom captions & brand fonts</li><li>3 revisions + source files</li><li>Priority 12 h delivery</li></ul>
                <a href="#contact" class="btn btn-primary">Get Started</a>
            </div>
            <div class="pricing-card">
                <h3>Pro Retainer</h3>
                <div class="price">$290<span>/month</span></div>
                <ul><li>Up to 25 reels / shorts</li><li>YouTube + TikTok + IG formats</li><li>Unlimited revisions</li><li>Same-day turn (+weekends)</li><li>Thumbnail pack included</li></ul>
                <a href="#contact" class="btn btn-outline">Contact Us</a>
            </div>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section id="about">
    <div class="container">
        <h2>Our Story</h2>
        <div class="about-text">
            <p>Editing Aura was born out of necessity: creators needed Hollywood-level edits without Hollywood budgets or timelines. Today our lean, remote squad delivers studio-grade content to 400+ creators weekly — all while keeping prices indie-friendly.</p>
            <p>One editor, one mission: make your content impossible to scroll past.</p>
        </div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <div class="container">
        <h2>Ready to Level-Up?</h2>
        <div class="grid contact-grid">
            <form class="contact-form" action="https://formspree.io/f/YOUR-ID" method="POST">
                <input type="text" name="name" placeholder="Name" required>
                <input type="email" name="email" placeholder="Email" required>
                <input type="url" name="link" placeholder="Link to your raw file (Drive, Dropbox, etc.)">
                <textarea name="message" placeholder="Describe what you need" required></textarea>
                <button type="submit" class="btn btn-primary">Send & Get Quote</button>
            </form>
            <div class="contact-info">
                <div class="contact-item"><i class="fab fa-instagram"></i><a href="https://www.instagram.com/editing_aura_official/" target="_blank">DM on Instagram</a></div>
                <div class="contact-item"><i class="fas fa-envelope"></i><a href="mailto:Editing_Aura@outlook.com">Editing_Aura@outlook.com</a></div>
                <div class="contact-item"><i class="fas fa-clock"></i><span>Typical reply in under 30 minutes</span></div>
            </div>
        </div>
    </div>
</section>

<!-- FOOTER -->
<footer>
    <div class="container">
        <p>&copy; 2025 Editing Aura. Built to be the last editor you’ll ever need.</p>
    </div>
</footer>

<!-- Instagram Floating Button -->
<a class="ig-float" href="https://www.instagram.com/editing_aura_official/" target="_blank"><i class="fab fa-instagram"></i></a>

<style>.ig-float{position:fixed;bottom:20px;right:20px;background:linear-gradient(45deg,#f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%);color:#fff;padding:14px 18px;border-radius:50%;font-size:24px;box-shadow:0 4px 12px rgba(0,0,0,.4);z-index:9999;transition:.3s}.ig-float:hover{transform:scale(1.1)}</style>

</body>
</html>
