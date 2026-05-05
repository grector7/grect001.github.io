[index.html](https://github.com/user-attachments/files/27407285/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>George Rector — ePortfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <header class="header">
    <div class="header-inner">
      <a href="index.html" class="brand">
        <span class="brand-first">George Rector</span>
        <span class="brand-sep">·</span>
        <span class="brand-second">ePortfolio</span>
      </a>
      <nav class="nav">
        <a href="index.html" class="nav-link active">About Me</a>
        <a href="cyse.html" class="nav-link">CYSE 201S</a>
      </nav>
      <button class="mobile-toggle" onclick="document.querySelector('.mobile-menu').classList.toggle('open')">☰</button>
    </div>
    <div class="mobile-menu">
      <a href="index.html" class="nav-link">About Me</a>
      <a href="cyse.html" class="nav-link">CYSE 201S — Overview</a>
      <a href="reviews.html" class="sub-link">Article Reviews</a>
      <a href="career.html" class="sub-link">Career Paper</a>
      <a href="presentation.html" class="sub-link">Presentation</a>
      <a href="case-study.html" class="sub-link">Case Study</a>
    </div>
  </header>

  <main>
    <div class="container">
      <div class="section" style="padding-top: 80px;">
        <div class="kicker fade-up">HELLO —</div>

        <h1 class="hero-title fade-up delay-1">
          I'm <em class="title-italic">George Rector</em>,<br />
          welcome to my ePortfolio.
        </h1>

        <div class="hero-grid">
          <div class="image-wrap fade-up delay-2">
            <div class="image-frame">
              <!-- TO ADD YOUR PHOTO: Replace the div below with: <img src="photo.jpg" alt="George Rector" /> -->
              <div class="image-placeholder">
                <div style="font-size: 32px; margin-bottom: 12px; color: #c4983a;">◐</div>
                <div style="font-size: 13px; font-weight: 600; color: #1a1a1a; margin-bottom: 6px;">Your Photo Goes Here</div>
                <div style="font-size: 11px; color: #888; line-height: 1.6;">Replace this placeholder with a recent, professional photo of yourself.</div>
              </div>
            </div>
            <div class="image-meta">
              <span>01 / PORTRAIT</span>
            </div>
          </div>

          <div class="bio-section fade-up delay-3">
            <p class="bio-para">
              Hi, my name is <strong>George Rector</strong> and this is my ePortfolio. I am 24 years old and am currently studying at <strong>Old Dominion University</strong> for a Bachelor's in Cybersecurity with a Major in Artificial Intelligence.
            </p>
            <p class="bio-para">
              I graduated high school in 2020 and enlisted in the Marine Corps afterwards <em>(Semper Fi)</em>. My hobbies are video games, golf, watching sports, and making homebrews.
            </p>
            <p class="bio-para">
              When I graduate I hope to find a job in the ever growing AI field and live the good life. Below are different aspects of my time here at Old Dominion including classes and the work I did in those classes.
            </p>

            <div class="fact-grid">
              <div class="fact">
                <div class="fact-label">University</div>
                <div class="fact-value">Old Dominion University</div>
              </div>
              <div class="fact">
                <div class="fact-label">Major</div>
                <div class="fact-value">Cybersecurity / AI</div>
              </div>
              <div class="fact">
                <div class="fact-label">Background</div>
                <div class="fact-value">U.S. Marine Corps Veteran</div>
              </div>
              <div class="fact">
                <div class="fact-label">Class of</div>
                <div class="fact-value">High School '20</div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="section" style="padding-top: 40px; padding-bottom: 80px;">
        <div class="kicker fade-up">COURSEWORK</div>
        <h2 class="section-title fade-up delay-1">Explore my work</h2>

        <div class="work-grid">
          <a href="cyse.html" class="card-link fade-up delay-1">
            <div class="work-num">→</div>
            <div class="work-title">CYSE 201S</div>
            <div class="work-desc">Cybersecurity and the Social Sciences — article reviews, career paper, presentation, and case study.</div>
            <div class="work-arrow">→ View Course</div>
          </a>
        </div>
      </div>
    </div>
  </main>

  <footer class="footer">
    <div class="footer-inner">
      <div class="footer-brand">George Rector</div>
      <div class="footer-meta">Old Dominion University · Cybersecurity & AI</div>
      <div class="footer-meta">© 2026</div>
    </div>
  </footer>

</body>
</html>
