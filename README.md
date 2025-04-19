
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afan Siddique | Business Strategist</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="cursor"></div>
    <nav class="navbar">
        <div class="nav-content">
            <div class="logo">AS</div>
            <div class="menu-toggle">
                <span></span>
                <span></span>
            </div>
            <ul class="nav-links">
                <li><a href="#home" data-text="Home">Home</a></li>
                <li><a href="#about" data-text="About">About</a></li>
                <li><a href="#experience" data-text="Experience">Experience</a></li>
                <li><a href="#skills" data-text="Skills">Skills</a></li>
                <li><a href="#contact" data-text="Contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <div class="hero-text-container">
                    <span class="hero-eyebrow">Business Strategy & Marketing</span>
                    <h1 class="glitch" data-text="Afan Siddique">Afan Siddique</h1>
                    <p class="hero-text">Crafting digital experiences and business strategies at IIM Bangalore</p>
                </div>
                <div class="hero-cta">
                    <a href="#contact" class="cta-button">Let's Connect</a>
                    <a href="https://www.linkedin.com/in/afan-siddique-b62a74328/" target="_blank" class="social-link">
                        <i class="fab fa-linkedin"></i>
                        <span>LinkedIn</span>
                    </a>
                </div>
            </div>
            <div class="hero-visual">
                <div class="shape shape-1"></div>
                <div class="shape shape-2"></div>
                <div class="shape shape-3"></div>
            </div>
        </section>

        <section id="about" class="about">
            <div class="section-header">
                <span class="section-tag">About</span>
                <h2>The Story So Far</h2>
            </div>
            <div class="about-content">
                <div class="about-text">
                    <p>Currently pursuing BBA at IIM Bangalore, blending passion for business with diverse approaches to entrepreneurship. Focused on Marketing, Product Management, and Product Designing, creating impactful, user-centric solutions.</p>
                </div>
                <div class="interests-grid">
                    <div class="interest-card">
                        <i class="fas fa-cricket-bat-ball"></i>
                        <span>Cricket</span>
                    </div>
                    <div class="interest-card">
                        <i class="fas fa-table-tennis"></i>
                        <span>Table Tennis</span>
                    </div>
                    <div class="interest-card">
                        <i class="fas fa-tshirt"></i>
                        <span>Vintage Fashion</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="experience" class="experience">
            <div class="section-header">
                <span class="section-tag">Experience</span>
                <h2>Professional Journey</h2>
            </div>
            <div class="experience-timeline">
                <div class="timeline-item">
                    <div class="timeline-content">
                        <h3>Marketing Consultant & Project Manager</h3>
                        <span class="company">180 Degrees Consulting</span>
                        <span class="duration">Oct 2024 - Present</span>
                        <ul class="achievements">
                            <li>Created social presence for 5+ businesses and NGOs</li>
                            <li>Led market research initiatives</li>
                            <li>Developed business strategies</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills" class="skills">
            <div class="section-header">
                <span class="section-tag">Expertise</span>
                <h2>Skills & Tools</h2>
            </div>
            <div class="skills-container">
                <div class="skill-category marketing">
                    <h3>Marketing & Branding</h3>
                    <ul>
                        <li>Consumer Behavior</li>
                        <li>Brand Positioning</li>
                        <li>Market Analysis</li>
                    </ul>
                </div>
                <div class="skill-category technical">
                    <h3>Technical Skills</h3>
                    <div class="tech-stack">
                        <span>PowerPoint</span>
                        <span>Word</span>
                        <span>Canva</span>
                        <span>Notion</span>
                        <span>ChatGPT</span>
                        <span>HTML & CSS</span>
                    </div>
                </div>
                <div class="skill-category leadership">
                    <h3>Leadership</h3>
                    <ul>
                        <li>Team Management</li>
                        <li>Event Coordination</li>
                        <li>Strategic Planning</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <div class="section-header">
                <span class="section-tag">Contact</span>
                <h2>Get In Touch</h2>
            </div>
            <div class="contact-grid">
                <div class="contact-info">
                    <div class="info-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Okhla, Delhi</span>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-envelope"></i>
                        <span>afansiddique9077@gmail.com</span>
                    </div>
                    <div class="info-item">
                        <i class="fas fa-phone"></i>
                        <span>+91 7783821236</span>
                    </div>
                </div>
                <form class="contact-form">
                    <div class="form-group">
                        <input type="text" placeholder="Your Name" required>
                    </div>
                    <div class="form-group">
                        <input type="email" placeholder="Your Email" required>
                    </div>
                    <div class="form-group">
                        <textarea placeholder="Your Message" required></textarea>
                    </div>
                    <button type="submit" class="submit-btn">Send Message</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <a href="https://www.linkedin.com/in/afan-siddique-b62a74328/" target="_blank" class="social-link">
                <i class="fab fa-linkedin"></i>
            </a>
            <p>&copy; 2024 Afan Siddique</p>
        </div>
    </footer>

    <script>
        // Custom cursor
        document.addEventListener('mousemove', (e) => {
            const cursor = document.querySelector('.cursor');
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';
        });
    </script>
</body>
</html>
