# Ex01 Portfolio
## Date: 27-04-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<body>
    <a class="skip-link" href="#main-content">Skip to content</a>

    <nav class="site-nav" aria-label="Primary">
        <div class="container nav-inner">
            <div class="brand">Sugeshan S</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <button class="theme-toggle" id="theme-toggle" aria-label="Toggle dark mode" title="Toggle theme">
                <i class="fa-solid fa-moon icon-moon" aria-hidden="true"></i>
                <i class="fa-solid fa-sun  icon-sun"  aria-hidden="true"></i>
            </button>
        </div>
    </nav>

    <header class="hero">
        <div class="container">
            <section class="hero-card reveal" aria-labelledby="hero-name">
                <div class="hero-top">
                    <div>
                        <h1 id="hero-name">Sugeshan S</h1>
                        <p class="hero-title">Fullstack Developer</p>
                    </div>
                </div>

                <p class="hero-summary">Dynamic fullstack developer with internship experience in crafting responsive web applications using React and the MERN stack.
                    Possesses a solid foundation in developing reusable UI components, integrating REST APIs, and thriving in Agile team environments through Git-based workflows.
                    Committed to delivering clean code and user-centric designs that enhance product reliability and performance. 
                    Eager to contribute innovative solutions that drive project success and elevate user experiences.</p>

                <div class="hero-actions">
                    <a class="btn btn-primary" href="resume.pdf" download aria-label="Download resume as PDF">
                        <i class="fa-solid fa-download" aria-hidden="true"></i>
                        Download Resume
                    </a>
                    <a class="btn btn-ghost" href="#contact" aria-label="Go to contact section">
                        <i class="fa-regular fa-address-card" aria-hidden="true"></i>
                        Contact Me
                    </a>
                </div>

                <div class="contact-row" aria-label="Primary contact links">
                    <span class="contact-chip"><i class="fa-solid fa-phone"></i> +91 6382111702</span>
                    <a class="contact-chip" href="mailto:sugeshansenthilv@gmail.com"><i class="fa-solid fa-envelope"></i> sugeshansenthilv@gmail.com</a>
                    <a class="contact-chip" href="https://github.com/Sugeshan19" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github"></i> github.com/Sugeshan19</a>
                    <a class="contact-chip" href="https://www.linkedin.com/in/sugeshan-s" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-linkedin"></i> linkedin.com/in/sugeshan-s</a>
                    <a class="contact-chip" href="https://sugeshan-s.vercel.app" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-globe"></i> sugeshan-s.vercel.app</a>
                </div>
            </section>
        </div>
    </header>

    <main id="main-content" class="container">
        <section id="about" class="section reveal" aria-labelledby="about-title">
            <div class="section-header">
                <h2 id="about-title" class="section-title">About / Summary</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>
            <article class="card about-card">
                <p>I’m a passionate Computer Science and Engineering undergraduate with a strong curiosity for solving real-world problems through technology. Currently exploring web development (React, Node.js, MongoDB) and building projects ranging from e-commerce platforms to social impact solutions like emergency volunteer alert systems.
                    <br>⚡ I enjoy working on:
                    <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;development with React.js & Tailwind
                    <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Backend development with Node.js & Express
                    <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Databases like MongoDB
                    <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Problem-solving through hackathons & team projects
                    <br>🌱 As a engineering student, I’m constantly learning and experimenting with new technologies, while sharing my journey through projects and collaborations.
                    <br>🚀 My future goal is to grow as a full-stack developer and contribute to impactful innovations in tech that make life simpler and safer.
                    <br>🤝 Always open to connecting with fellow learners, developers, and mentors to exchange ideas and collaborate!</p>
            </article>
        </section>

        <section id="skills" class="section reveal" aria-labelledby="skills-title">
            <div class="section-header">
                <h2 id="skills-title" class="section-title">Skills</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>
            <div class="card-grid">
                <article class="card skills-card">
                    <h3><i class="fa-solid fa-code" aria-hidden="true"></i> Languages</h3>
                    <div class="tag-list">
                        <span class="tag">JavaScript (ES6+)</span>
                        <span class="tag">HTML5</span>
                        <span class="tag">CSS3</span>
                        <span class="tag">Python</span>
                    </div>
                </article>
                <article class="card skills-card">
                    <h3><i class="fa-solid fa-layer-group" aria-hidden="true"></i> Frameworks</h3>
                    <div class="tag-list">
                        <span class="tag">React</span>
                        <span class="tag">Angular</span>
                        <span class="tag">Node.js</span>
                        <span class="tag">Express.js</span>
                    </div>
                </article>
                <article class="card skills-card">
                    <h3><i class="fa-solid fa-screwdriver-wrench" aria-hidden="true"></i> Tools</h3>
                    <div class="tag-list">
                        <span class="tag">MongoDB</span>
                        <span class="tag">REST APIs</span>
                        <span class="tag">Git/GitHub</span>
                        <span class="tag">Vercel</span>
                        <span class="tag">Figma</span>
                    </div>
                </article>
                <article class="card skills-card">
                    <h3><i class="fa-solid fa-brain" aria-hidden="true"></i> Core Strengths</h3>
                    <div class="tag-list">
                        <span class="tag">Problem Solving</span>
                        <span class="tag">Agile Workflow</span>
                        <span class="tag">UI/UX Collaboration</span>
                    </div>
                </article>
            </div>
        </section>

        <section id="experience" class="section reveal" aria-labelledby="experience-title">
            <div class="section-header">
                <h2 id="experience-title" class="section-title">Experience</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>

            <div class="timeline">
                <article class="card experience-card">
                    <div class="job-header">
                        <h3 class="role">Senior Developer | Intecalic</h3>
                        <span class="date">01/2026 – present </span>
                    </div>
                    <ul>
                        <li>Led end-to-end architecture and development of scalable MERN applications, supporting 5K+ monthly users and reducing deployment time by 30% through streamlined CI/CD workflows.</li>
                        <li>Optimized database queries and frontend performance, decreasing API response times by 40% and improving page load speed by 35%.</li>
                        <li>Mentored a team of 3–5 junior developers, conducting code reviews and enforcing best practices, reducing production bugs by 25%.</li>
                    </ul>
                </article>

                <article class="card experience-card">
                    <div class="job-header">
                        <h3 class="role">Full Stack Developer Intern | Wipro</h3>
                        <span class="date">07/2025 – 08/2025</span>
                    </div>
                    <ul>
                        <li>Developed full-stack features using the MERN stack, improving end-to-end data flow between UI and backend services.</li>
                        <li>Optimized front-end components and database queries to improve responsiveness and overall application performance through Git-based version control.</li>
                    </ul>
                </article>

                <article class="card experience-card">
                    <div class="job-header">
                        <h3 class="role">React Developer Intern | SPARK Solutions</h3>
                        <span class="date">03/2025 – 04/2025</span>
                    </div>
                    <ul>
                        <li>Built responsive and accessible interfaces in React with reusable, maintainable component structure.</li>
                        <li>Integrated REST APIs for dynamic content rendering and improved front-end efficiency through targeted optimizations.</li>
                    </ul>
                </article>

                <article class="card experience-card">
                    <div class="job-header">
                        <h3 class="role">Web Developer Intern | Rinex.AI</h3>
                        <span class="date">01/2025 – 03/2025</span>
                    </div>
                    <ul>
                        <li>Designed and implemented responsive web pages using modern CSS and layout best practices.</li>
                        <li>Supported front-end workflow improvements and UI refinements to enhance consistency and usability.</li>
                    </ul>
                </article>
            </div>
        </section>

        <section id="projects" class="section reveal" aria-labelledby="projects-title">
            <div class="section-header">
                <h2 id="projects-title" class="section-title">Projects</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>

            <article class="card project-card">
                <h3 class="project-title">Yuva Club Website | MERN Stack</h3>
                <ul>
                    <li>Developed a responsive platform supporting member registration and event management workflows for a student club.</li>
                </ul>
                <div class="project-actions">
                    <a class="btn btn-primary" href="https://yuva-web.vercel.app/" target="_blank" rel="noopener noreferrer" aria-label="Open Yuva Club Website live demo">
                        <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i>
                        Live Demo
                    </a>
                    <a class="btn btn-ghost" href="https://github.com/Sugeshan19/yuva-web" target="_blank" rel="noopener noreferrer" aria-label="Open Yuva Club Website GitHub repository">
                        <i class="fa-brands fa-github" aria-hidden="true"></i>
                        GitHub
                    </a>
                </div>
            </article>
        </section>

        <section id="education" class="section reveal" aria-labelledby="education-title">
            <div class="section-header">
                <h2 id="education-title" class="section-title">Education</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>
            <article class="card education-card">
                <div class="job-header">
                    <h3 class="role">B.E. Computer Science Engineering | Saveetha Engineering College</h3>
                    <span class="date">Expected 01/2028</span>
                </div>
                <p>GPA: 7.98 
                    <br> member, Coder’s Club and Tech Society.
                    <br>Branding Ambassador , Yuva Club
                </p>
            </article>
        </section>

        <section id="contact" class="section reveal" aria-labelledby="contact-title">
            <div class="section-header">
                <h2 id="contact-title" class="section-title">Contact</h2>
                <span class="section-line" aria-hidden="true"></span>
            </div>

            <div class="contact-panel">
                <a class="contact-card" href="tel:+916382111702">
                    <span class="contact-icon"><i class="fa-solid fa-phone" aria-hidden="true"></i></span>
                    <span class="contact-meta">
                        <strong>Phone</strong>
                        <span>+91 6382111702</span>
                    </span>
                </a>
                <a class="contact-card" href="mailto:sugeshansenthilv@gmail.com">
                    <span class="contact-icon"><i class="fa-solid fa-envelope" aria-hidden="true"></i></span>
                    <span class="contact-meta">
                        <strong>Email</strong>
                        <span>sugeshansenthilv@gmail.com</span>
                    </span>
                </a>
                <a class="contact-card" href="https://github.com/Sugeshan19" target="_blank" rel="noopener noreferrer">
                    <span class="contact-icon"><i class="fa-brands fa-github" aria-hidden="true"></i></span>
                    <span class="contact-meta">
                        <strong>GitHub</strong>
                        <span>github.com/Sugeshan19</span>
                    </span>
                </a>
                <a class="contact-card" href="https://www.linkedin.com/in/sugeshan-s" target="_blank" rel="noopener noreferrer">
                    <span class="contact-icon"><i class="fa-brands fa-linkedin" aria-hidden="true"></i></span>
                    <span class="contact-meta">
                        <strong>LinkedIn</strong>
                        <span>linkedin.com/in/sugeshan-s</span>
                    </span>
                </a>
                <a class="contact-card" href="https://sugeshan-s.vercel.app" target="_blank" rel="noopener noreferrer">
                    <span class="contact-icon"><i class="fa-solid fa-globe" aria-hidden="true"></i></span>
                    <span class="contact-meta">
                        <strong>Portfolio</strong>
                        <span>sugeshan-s.vercel.app</span>
                    </span>
                </a>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">© 2026 Sugeshan S • Built with semantic HTML, modern CSS, and performance-first design.</div>
    </footer>

    <script>
        // ── Theme Toggle ──
        (function () {
            const saved = localStorage.getItem('theme') || 'dark';
            document.documentElement.setAttribute('data-theme', saved);
        })();

        document.getElementById('theme-toggle').addEventListener('click', function () {
            const current = document.documentElement.getAttribute('data-theme');
            const next = current === 'dark' ? 'light' : 'dark';
            document.documentElement.setAttribute('data-theme', next);
            localStorage.setItem('theme', next);
            this.setAttribute('aria-label', next === 'dark' ? 'Switch to light mode' : 'Switch to dark mode');
        });

        const revealElements = document.querySelectorAll('.reveal');
        const revealObserver = new IntersectionObserver(
            (entries) => {
                entries.forEach((entry) => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('in-view');
                        revealObserver.unobserve(entry.target);
                    }
                });
            },
            { threshold: 0.14 }
        );
        revealElements.forEach((element) => revealObserver.observe(element));
    </script>
</body>
</html>
```

## OUTPUT

<img width="1917" height="1039" alt="image" src="https://github.com/user-attachments/assets/1e91d032-7b3d-41d1-92ea-3450c9e47085" />

<img width="1919" height="1063" alt="image" src="https://github.com/user-attachments/assets/5f26879c-ca49-4428-aeff-ee2868e23644" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
