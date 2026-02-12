<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.5">
    <title>Gaawow Academy – Ilayska Aqoonta iyo Xirfadda</title>
    <!-- SEO meta -->
    <meta name="description" content="Gaawow Academy – Ilayska Aqoonta iyo Xirfadda. Professional courses, certificate verification, and modern education in Mogadishu.">
    <meta name="author" content="Dr Osmaan Mohamed Ibrahim">
    <meta name="keywords" content="Gaawow, Academy, Nursing, EMS, Computer, Leadership, Somalia">
    <!-- Fonts & Icons -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- CSS -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- LOADING ANIMATION (PRELOADER) -->
    <div id="preloader">
        <div class="loader"></div>
    </div>

    <!-- DARK/LIGHT TOGGLE BUTTON (floating) -->
    <div class="theme-toggle">
        <button id="theme-switch" aria-label="Switch dark/light mode">
            <i class="fas fa-moon"></i>
        </button>
    </div>

    <!-- STICKY NAVIGATION -->
    <header id="header">
        <nav class="navbar">
            <div class="nav-container">
                <div class="logo">
                    <h1>GAAWOW <span>ACADEMY</span></h1>
                </div>
                <div class="hamburger" id="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <ul class="nav-menu" id="nav-menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#courses">Courses</a></li>
                    <li><a href="#register">Register</a></li>
                    <li><a href="#verify">Verify</a></li>
                    <li><a href="#admin">Admin</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <!-- HERO SECTION -->
        <section id="home" class="hero">
            <div class="hero-content">
                <h1 class="hero-title">Ilayska Aqoonta iyo Xirfadda</h1>
                <p class="hero-subtitle">Accredited international standard academy — bridging knowledge and skills for tomorrow's leaders.</p>
                <div class="hero-buttons">
                    <a href="#register" class="btn btn-primary">Apply Now</a>
                    <a href="#verify" class="btn btn-secondary">Verify Certificate</a>
                </div>
            </div>
            <div class="hero-wave">
                <svg viewBox="0 0 1440 100" preserveAspectRatio="none"><path fill="white" d="M0,64L80,69.3C160,75,320,85,480,80C640,75,800,53,960,48C1120,43,1280,53,1360,58.7L1440,64L1440,100L1360,100C1280,100,1120,100,960,100C800,100,640,100,480,100C320,100,160,100,80,100L0,100Z"/></svg>
            </div>
        </section>

        <!-- ABOUT SECTION with animated counters -->
        <section id="about" class="about">
            <div class="container">
                <div class="section-header">
                    <h2>About Gaawow Academy</h2>
                    <p>Founded by Dr Osmaan Mohamed Ibrahim | Awards Authority: Eng Moscab Osman Mohamed</p>
                </div>
                <div class="about-grid">
                    <div class="about-text">
                        <h3>History</h3>
                        <p>Established in 2020, Gaawow Academy has rapidly become Somalia’s premier institution for healthcare, technology and governance education.</p>
                        <h3>Mission</h3>
                        <p>To empower youth through accessible, high-quality professional training.</p>
                        <h3>Vision</h3>
                        <p>A future where Somali professionals lead globally with integrity and excellence.</p>
                        <h3>Core Values</h3>
                        <p>Excellence, Integrity, Innovation, Inclusivity.</p>
                    </div>
                    <div class="about-stats">
                        <div class="stat-item">
                            <i class="fas fa-graduation-cap"></i>
                            <span class="counter" data-target="2500">0</span>
                            <p>Students</p>
                        </div>
                        <div class="stat-item">
                            <i class="fas fa-book"></i>
                            <span class="counter" data-target="24">0</span>
                            <p>Courses</p>
                        </div>
                        <div class="stat-item">
                            <i class="fas fa-award"></i>
                            <span class="counter" data-target="15">0</span>
                            <p>Awards</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- COURSES SECTION -->
        <section id="courses" class="courses">
            <div class="container">
                <div class="section-header">
                    <h2>Our Professional Programs</h2>
                </div>
                <div class="course-grid">
                    <div class="course-card">
                        <i class="fas fa-user-nurse"></i>
                        <h3>Nursing Assistant</h3>
                        <p>Fundamentals of patient care, clinical skills.</p>
                        <span class="duration">6 months</span>
                        <button class="btn-small enroll-btn">Enroll</button>
                    </div>
                    <div class="course-card">
                        <i class="fas fa-syringe"></i>
                        <h3>Injection Practice</h3>
                        <p>Safe injection techniques, sterilization.</p>
                        <span class="duration">2 months</span>
                        <button class="btn-small enroll-btn">Enroll</button>
                    </div>
                    <div class="course-card">
                        <i class="fas fa-ambulance"></i>
                        <h3>EMS Training</h3>
                        <p>Emergency medical response, trauma care.</p>
                        <span class="duration">4 months</span>
                        <button class="btn-small enroll-btn">Enroll</button>
                    </div>
                    <div class="course-card">
                        <i class="fas fa-laptop"></i>
                        <h3>Computer Basics</h3>
                        <p>Windows, Office, internet, digital literacy.</p>
                        <span class="duration">3 months</span>
                        <button class="btn-small enroll-btn">Enroll</button>
                    </div>
                    <div class="course-card">
                        <i class="fas fa-users-cog"></i>
                        <h3>Leadership & Governance</h3>
                        <p>Public policy, management, ethics.</p>
                        <span class="duration">6 months</span>
                        <button class="btn-small enroll-btn">Enroll</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- STUDENT REGISTRATION SYSTEM -->
        <section id="register" class="register">
            <div class="container">
                <div class="section-header">
                    <h2>Student Registration</h2>
                </div>
                <form id="registrationForm" class="register-form">
                    <div class="form-group">
                        <label for="fullName">Full Name</label>
                        <input type="text" id="fullName" name="fullName" placeholder="Enter full name">
                        <div class="error" id="nameError"></div>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone</label>
                        <input type="tel" id="phone" name="phone" placeholder="+252 ...">
                        <div class="error" id="phoneError"></div>
                    </div>
                    <div class="form-group">
                        <label for="courseSelect">Course</label>
                        <select id="courseSelect">
                            <option value="">-- Select course --</option>
                            <option value="Nursing Assistant">Nursing Assistant</option>
                            <option value="Injection Practice">Injection Practice</option>
                            <option value="EMS Training">EMS Training</option>
                            <option value="Computer Basics">Computer Basics</option>
                            <option value="Leadership & Governance">Leadership & Governance</option>
                        </select>
                    </div>
                    <div class="form-group gender-group">
                        <label>Gender:</label>
                        <label><input type="radio" name="gender" value="Male"> Male</label>
                        <label><input type="radio" name="gender" value="Female"> Female</label>
                    </div>
                    <button type="submit" class="btn btn-primary">Submit Registration</button>
                    <p id="regSuccess" class="success-message"></p>
                </form>
            </div>
        </section>

        <!-- CERTIFICATE VERIFICATION SYSTEM -->
        <section id="verify" class="verify">
            <div class="container">
                <div class="section-header">
                    <h2>Certificate Verification</h2>
                </div>
                <div class="verify-container">
                    <input type="text" id="certIdInput" placeholder="Enter Certificate ID (e.g. GAA-2026-8F4K92-001)">
                    <button id="verifyBtn" class="btn btn-primary">Verify</button>
                </div>
                <div id="certResult" class="cert-result"></div>
            </div>
        </section>

        <!-- ADMIN PANEL (Frontend Demo) -->
        <section id="admin" class="admin">
            <div class="container">
                <div class="section-header">
                    <h2>Admin Dashboard (Demo)</h2>
                    <p>Add student – certificate ID auto‑generated</p>
                </div>
                <div class="admin-grid">
                    <div class="admin-add">
                        <h3>➕ Add Student</h3>
                        <form id="adminAddForm">
                            <input type="text" id="adminName" placeholder="Student full name" required>
                            <select id="adminCourse">
                                <option value="Nursing Assistant">Nursing Assistant</option>
                                <option value="Injection Practice">Injection Practice</option>
                                <option value="EMS Training">EMS Training</option>
                                <option value="Computer Basics">Computer Basics</option>
                                <option value="Leadership & Governance">Leadership & Governance</option>
                            </select>
                            <button type="submit" class="btn-small">Generate ID & Add</button>
                        </form>
                    </div>
                    <div class="admin-list">
                        <h3>📋 Student Certificates</h3>
                        <div id="studentListContainer">
                            <table id="studentTable">
                                <thead>
                                    <tr><th>Name</th><th>Course</th><th>Certificate ID</th><th>Action</th></tr>
                                </thead>
                                <tbody id="studentTableBody"></tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- TESTIMONIALS SLIDER -->
        <section id="testimonials" class="testimonials">
            <div class="container">
                <div class="section-header">
                    <h2>What our students say</h2>
                </div>
                <div class="slider-container">
                    <div class="slider" id="slider">
                        <div class="slide">
                            <i class="fas fa-quote-left"></i>
                            <p>"Gaawow transformed my career. The nursing program is world-class."</p>
                            <h4>– Fartun A.</h4>
                        </div>
                        <div class="slide">
                            <i class="fas fa-quote-left"></i>
                            <p>"EMS training gave me confidence to save lives. Highly recommend."</p>
                            <h4>– Ahmed M.</h4>
                        </div>
                        <div class="slide">
                            <i class="fas fa-quote-left"></i>
                            <p>"Leadership course changed my perspective on governance."</p>
                            <h4>– Hodan I.</h4>
                        </div>
                    </div>
                    <div class="slider-nav">
                        <button id="prevSlide"><i class="fas fa-chevron-left"></i></button>
                        <button id="nextSlide"><i class="fas fa-chevron-right"></i></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- GALLERY GRID -->
        <section id="gallery" class="gallery">
            <div class="container">
                <div class="section-header">
                    <h2>Campus Gallery</h2>
                </div>
                <div class="gallery-grid">
                    <div class="gallery-item"><i class="fas fa-chalkboard-teacher"></i><span>Modern classes</span></div>
                    <div class="gallery-item"><i class="fas fa-stethoscope"></i><span>Lab practice</span></div>
                    <div class="gallery-item"><i class="fas fa-laptop-code"></i><span>Computer lab</span></div>
                    <div class="gallery-item"><i class="fas fa-trophy"></i><span>Award ceremony</span></div>
                    <div class="gallery-item"><i class="fas fa-user-md"></i><span>Clinical training</span></div>
                    <div class="gallery-item"><i class="fas fa-graduation-cap"></i><span>Graduation</span></div>
                </div>
            </div>
        </section>

        <!-- CONTACT SECTION with map placeholder and form -->
        <section id="contact" class="contact">
            <div class="container">
                <div class="section-header">
                    <h2>Contact Us</h2>
                </div>
                <div class="contact-grid">
                    <div class="contact-info">
                        <h3>Get in touch</h3>
                        <p><i class="fas fa-map-marker-alt"></i> Mogadishu, Somalia – KM4 Junction</p>
                        <p><i class="fas fa-phone-alt"></i> +252 61 234 5678</p>
                        <p><i class="fas fa-envelope"></i> info@gaawow.edu.so</p>
                        <div class="map-placeholder">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3983.5574407987393!2d45.3181623147573!3d2.046693998494723!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3d5d3e7a5b3a7b2b%3A0x7b5f3e5b2a7c8d!2sMogadishu%2C%20Somalia!5e0!3m2!1sen!2s!4v1620000000000" allowfullscreen="" loading="lazy"></iframe>
                        </div>
                    </div>
                    <div class="contact-form">
                        <h3>Send a message</h3>
                        <form id="contactForm">
                            <input type="text" id="contactName" placeholder="Your name" required>
                            <input type="email" id="contactEmail" placeholder="Email" required>
                            <textarea id="contactMsg" rows="4" placeholder="Message"></textarea>
                            <button type="submit" class="btn-primary">Send</button>
                            <p id="contactSuccess" class="success-message"></p>
                        </form>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <h3>Gaawow Academy</h3>
                    <p>Ilayska Aqoonta iyo Xirfadda</p>
                    <div class="social-icons">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-linkedin"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#courses">Courses</a></li>
                        <li><a href="#register">Register</a></li>
                        <li><a href="#verify">Verify</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Academy</h4>
                    <p>© 2026 Gaawow Academy. All Rights Reserved.</p>
                </div>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>