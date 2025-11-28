# Supporting Documents

> "Include supporting documents such as certificates, code snippets, charts, work samples, or any relevant supplementary material."

## Work Samples / Code Snippets

Below are the code snippets for the "Premium Ocean Design" version of the IEEE OES Kerala Chapter website, demonstrating advanced CSS animations, responsive grid layouts, and modern UI principles.

### 1. Premium HTML Structure (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IEEE OES Kerala Chapter</title>
    <meta name="description" content="Official website of the IEEE Oceanic Engineering Society Kerala Chapter.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans:wght@400;600&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="container nav-container">
            <a href="#" class="logo">
                <img src="images/oes-logo.png" alt="IEEE OES Kerala Chapter" class="logo-img">
            </a>
            <button class="nav-toggle" aria-label="Toggle navigation">
                <span class="hamburger"></span>
            </button>
            <ul class="nav-links">
                <li><a href="#about" class="nav-link">About</a></li>
                <li><a href="#initiatives" class="nav-link">Initiatives</a></li>
                <li><a href="#activities" class="nav-link">Activities</a></li>
                <li><a href="#gallery" class="nav-link">Gallery</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <div class="hero-bg"></div>
        <div class="spiral-bg"></div>
        <div class="spiral-bg"></div>
        <div class="spiral-bg"></div>
        <div class="container hero-content">
            <p class="hero-subtitle spiral-reveal">Welcome to</p>
            <h1 class="hero-title spiral-reveal">IEEE OES<br>Kerala Chapter</h1>
            <p class="hero-desc spiral-reveal">Advancing technology for the ocean. Connecting professionals, students,
                and researchers in the field of oceanic engineering.</p>
            <a href="#about" class="btn spiral-reveal">Discover More</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="section">
        <div class="container">
            <div class="about-grid">
                <div class="about-text">
                    <h2 class="section-title spiral-reveal">About Us</h2>
                    <p class="spiral-reveal">The IEEE Oceanic Engineering Society (OES) Kerala Chapter is dedicated to
                        promoting the objectives of the society within the region. We focus on the advancement of the
                        theory and practice of electrotechnology applied to the ocean environment.</p>
                    <p class="spiral-reveal">Our chapter organizes technical talks, workshops, and conferences to foster
                        knowledge sharing and collaboration among members.</p>
                </div>
                <div class="about-image spiral-reveal">
                    <img src="images/about.jpg" alt="Ocean Engineering">
                </div>
            </div>
        </div>
    </section>

    <!-- Initiatives Section -->
    <section id="initiatives" class="section">
        <div class="container">
            <h2 class="section-title spiral-reveal">Our Initiatives</h2>
            <div class="grid-minimal">
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-university card-icon"></i>
                    <h3>Student Chapters</h3>
                    <p>Empowering student branches across Kerala to lead in ocean engineering.</p>
                </div>
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-handshake card-icon"></i>
                    <h3>Industry Collaboration</h3>
                    <p>Bridging the gap between academia and the marine industry.</p>
                </div>
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-seedling card-icon"></i>
                    <h3>Sustainability</h3>
                    <p>Promoting eco-friendly technologies for ocean conservation.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Activities Section -->
    <section id="activities" class="section">
        <div class="container">
            <h2 class="section-title spiral-reveal">Activities</h2>
            <div class="grid-minimal">
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-microphone-alt card-icon"></i>
                    <h3>Technical Talks</h3>
                    <p>Expert sessions on the latest trends in marine technology and ocean engineering.</p>
                </div>
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-users card-icon"></i>
                    <h3>Workshops</h3>
                    <p>Hands-on workshops providing practical experience in underwater robotics.</p>
                </div>
                <div class="minimal-card spiral-reveal">
                    <i class="fas fa-globe-asia card-icon"></i>
                    <h3>Conferences</h3>
                    <p>International and national conferences connecting professionals and students.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="section">
        <div class="container">
            <h2 class="section-title spiral-reveal">Gallery</h2>
            <div class="gallery-grid">
                <div class="gallery-item spiral-reveal">
                    <img src="images/gallery-1.jpg" alt="Event 1">
                    <div class="overlay">
                        <h3>Community</h3>
                    </div>
                </div>
                <div class="gallery-item spiral-reveal">
                    <img src="images/gallery-2.jpg" alt="Event 2">
                    <div class="overlay">
                        <h3>Expertise</h3>
                    </div>
                </div>
                <div class="gallery-item spiral-reveal">
                    <img src="images/gallery-3.jpg" alt="Event 3">
                    <div class="overlay">
                        <h3>Leadership</h3>
                    </div>
                </div>
                <div class="gallery-item spiral-reveal">
                    <img src="images/gallery-4.jpg" alt="Event 4">
                    <div class="overlay">
                        <h3>Knowledge</h3>
                    </div>
                </div>
                <div class="gallery-item spiral-reveal">
                    <img src="images/gallery-5.jpg" alt="Event 5">
                    <div class="overlay">
                        <h3>Networking</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="footer">
        <div class="container">
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
            <p>&copy; 2025 IEEE OES Kerala Chapter. All rights reserved.</p>
            <p>contact@ieeeoeskerala.org</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
```

### 2. Premium CSS Styling (`styles.css`)

```css
:root {
    --bg-color: #020c1b;
    /* Deepest Navy */
    --text-color: #e6f1ff;
    /* Off-white */
    --primary-color: #64ffda;
    /* Teal Accent */
    --secondary-color: #8892b0;
    /* Muted Blue-Grey */
    --font-heading: 'Montserrat', sans-serif;
    --font-body: 'Open Sans', sans-serif;
    --transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: var(--bg-color);
    color: var(--text-color);
    font-family: var(--font-body);
    line-height: 1.8;
    overflow-x: hidden;
    font-size: 18px;
}

a {
    text-decoration: none;
    color: inherit;
    transition: var(--transition);
}

a:hover {
    color: var(--primary-color);
}

.container {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 40px;
}

/* Typography */
h1,
h2,
h3 {
    font-family: var(--font-heading);
    font-weight: 700;
    line-height: 1.1;
    color: var(--text-color);
}

.section-title {
    font-size: 4rem;
    margin-bottom: 4rem;
    text-align: left;
    position: relative;
    display: inline-block;
}

.section-title::after {
    content: '';
    display: block;
    width: 100px;
    height: 2px;
    background: var(--primary-color);
    margin-top: 20px;
}

/* Navbar */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 0;
    background: rgba(2, 12, 27, 0.85);
    backdrop-filter: blur(10px);
    z-index: 1000;
    transition: var(--transition);
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
}

.logo-img {
    height: 50px;
    width: auto;
    object-fit: contain;
}

.nav-links {
    display: flex;
    gap: 3rem;
    list-style: none;
}

.nav-link {
    font-size: 0.9rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--text-color);
}

.nav-toggle {
    display: none;
    background: none;
    border: none;
    cursor: pointer;
}

.hamburger {
    display: block;
    width: 30px;
    height: 2px;
    background: var(--primary-color);
    position: relative;
}

.hamburger::before,
.hamburger::after {
    content: '';
    position: absolute;
    width: 100%;
    height: 2px;
    background: var(--primary-color);
    left: 0;
}

.hamburger::before {
    top: -10px;
}

.hamburger::after {
    bottom: -10px;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    position: relative;
    overflow: hidden;
}

.hero-bg {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    background: radial-gradient(circle at 50% 50%, #112240 0%, #020c1b 100%);
}

/* Spiral / Wave Effect Background */
.spiral-bg {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 200vw;
    height: 200vw;
    border: 1px solid rgba(100, 255, 218, 0.05);
    border-radius: 40%;
    transform: translate(-50%, -50%);
    animation: rotate 20s linear infinite;
    pointer-events: none;
}

.spiral-bg:nth-child(2) {
    width: 180vw;
    height: 180vw;
    animation-duration: 25s;
    border-color: rgba(100, 255, 218, 0.03);
}

.spiral-bg:nth-child(3) {
    width: 160vw;
    height: 160vw;
    animation-duration: 30s;
    border-color: rgba(100, 255, 218, 0.02);
}

@keyframes rotate {
    from {
        transform: translate(-50%, -50%) rotate(0deg);
    }

    to {
        transform: translate(-50%, -50%) rotate(360deg);
    }
}

.hero-content {
    max-width: 900px;
    padding-top: 100px;
}

.hero-subtitle {
    color: var(--primary-color);
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
    font-family: var(--font-body);
    letter-spacing: 2px;
    text-transform: uppercase;
}

.hero-title {
    font-size: 5rem;
    line-height: 1.1;
    margin-bottom: 2rem;
}

.hero-desc {
    font-size: 1.2rem;
    color: var(--secondary-color);
    max-width: 600px;
    margin-bottom: 3rem;
}

.btn {
    display: inline-block;
    padding: 1.2rem 3rem;
    border: 1px solid var(--primary-color);
    border-radius: 4px;
    color: var(--primary-color);
    font-family: var(--font-body);
    font-size: 1rem;
    letter-spacing: 1px;
    transition: var(--transition);
    background: transparent;
}

.btn:hover {
    background: rgba(100, 255, 218, 0.1);
    transform: translateY(-3px);
}

/* Sections */
.section {
    padding: 150px 0;
}

/* Spiral Text Transition */
.spiral-reveal {
    opacity: 0;
    transform: translateY(50px) rotate(5deg) scale(0.9);
    transition: opacity 1s ease, transform 1s cubic-bezier(0.215, 0.61, 0.355, 1);
    transform-origin: center left;
}

.spiral-reveal.active {
    opacity: 1;
    transform: translateY(0) rotate(0deg) scale(1);
}

/* About Section */
.about-grid {
    display: grid;
    grid-template-columns: 3fr 2fr;
    gap: 5rem;
    align-items: center;
}

.about-text p {
    font-size: 1.3rem;
    color: var(--secondary-color);
    margin-bottom: 2rem;
}

.about-image {
    position: relative;
    z-index: 1;
}

.about-image img {
    width: 100%;
    border-radius: 4px;
    filter: grayscale(100%) contrast(1.2);
    transition: var(--transition);
}

.about-image:hover img {
    filter: none;
}

.about-image::after {
    content: '';
    position: absolute;
    top: 20px;
    left: 20px;
    width: 100%;
    height: 100%;
    border: 2px solid var(--primary-color);
    z-index: -1;
    border-radius: 4px;
    transition: var(--transition);
}

.about-image:hover::after {
    top: 10px;
    left: 10px;
}

/* Initiatives & Activities - Minimalist Grid */
.grid-minimal {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    gap: 4rem;
}

.minimal-card {
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding-top: 2rem;
    transition: var(--transition);
}

.minimal-card:hover {
    transform: translateY(-5px);
}

.minimal-card .card-icon {
    font-size: 2rem;
    color: var(--primary-color);
    margin-bottom: 1.5rem;
}

.minimal-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.minimal-card p {
    color: var(--secondary-color);
    font-size: 1rem;
}

/* Gallery */
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: 1.5rem;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 4px;
    height: 300px;
    grid-column: span 4;
}

.gallery-item:nth-child(1) {
    grid-column: span 8;
}

.gallery-item:nth-child(4) {
    grid-column: span 8;
}

.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
    filter: grayscale(100%);
}

.gallery-item:hover img {
    transform: scale(1.1);
    filter: none;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(2, 12, 27, 0.7);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: var(--transition);
}

.gallery-item:hover .overlay {
    opacity: 1;
}

/* Footer */
.footer {
    padding: 5rem 0;
    text-align: center;
    color: var(--secondary-color);
    font-size: 0.9rem;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-bottom: 2rem;
}

.social-links a {
    font-size: 1.5rem;
}

/* Responsive */
@media (max-width: 768px) {
    .section-title {
        font-size: 2.5rem;
    }

    .hero-title {
        font-size: 3rem;
    }

    .about-grid {
        grid-template-columns: 1fr;
    }

    .gallery-item {
        grid-column: span 12 !important;
    }

    .nav-links {
        display: none;
    }

    .nav-toggle {
        display: block;
    }
}
```
