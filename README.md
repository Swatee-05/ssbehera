<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushree Swateeprajnya Behera | Quantum Hardware Researcher</title>
    <style>
        :root {
            --primary: #0f172a;       /* Deep slate/navy for serious, scientific tone */
            --accent: #2563eb;        /* Professional blue accent */
            --accent-hover: #1d4ed8;
            --text-dark: #1e293b;
            --text-muted: #475569;
            --bg-body: #f8fafc;
            --bg-card: #ffffff;
            --border-color: #cbd5e1;
        }

        * {
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--bg-body);
            margin: 0;
            padding: 0;
        }

        /* Fixed Navigation Header */
        nav {
            position: sticky;
            top: 0;
            background-color: #ffffff;
            border-bottom: 2px solid var(--border-color);
            z-index: 1000;
            padding: 12px 20px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.05);
        }

        .nav-container {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
        }

        .nav-logo {
            font-weight: 700;
            font-size: 1.1rem;
            color: var(--primary);
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            gap: 18px;
            align-items: center;
        }

        .nav-links a {
            color: var(--text-dark);
            text-decoration: none;
            font-weight: 500;
            font-size: 0.95rem;
            transition: color 0.2s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        .btn-hire {
            background-color: var(--accent);
            color: #ffffff !important;
            padding: 6px 14px;
            border-radius: 6px;
            font-weight: 600 !important;
            transition: background 0.2s;
        }

        .btn-hire:hover {
            background-color: var(--accent-hover) !important;
        }

        /* Layout Container */
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        header.hero {
            padding-bottom: 30px;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 40px;
        }

        h1 {
            margin: 0;
            color: var(--primary);
            font-size: 2.3rem;
            letter-spacing: -0.5px;
        }

        .subtitle {
            font-size: 1.25rem;
            color: var(--accent);
            margin-top: 5px;
            font-weight: 600;
        }

        .btn-cv {
            display: inline-block;
            background: var(--primary);
            color: #ffffff;
            padding: 10px 18px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 15px;
            transition: background 0.2s ease;
        }

        .btn-cv:hover {
            background: #334155;
        }

        section {
            margin-bottom: 60px;
            scroll-margin-top: 80px; /* Offset for fixed nav */
        }

        h2 {
            color: var(--primary);
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 8px;
            font-size: 1.5rem;
            margin-bottom: 25px;
        }

        .exp-item {
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 22px;
            margin-bottom: 20px;
        }

        .exp-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            gap: 10px;
        }

        .role-title {
            font-size: 1.15rem;
            font-weight: 700;
            color: var(--primary);
        }

        .date-badge {
            font-size: 0.85rem;
            background: #e2e8f0;
            color: #334155;
            padding: 3px 10px;
            border-radius: 12px;
            font-weight: 600;
        }

        .org-name {
            font-style: italic;
            color: var(--text-muted);
            margin-bottom: 12px;
            font-size: 0.95rem;
        }

        ul {
            margin: 0;
            padding-left: 20px;
        }

        li {
            margin-bottom: 6px;
        }

        /* Image & Report Styling */
        .photo-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .photo-card {
            background: #ffffff;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            overflow: hidden;
            padding: 10px;
        }

        .photo-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 4px;
        }

        .photo-card p {
            margin: 8px 0 0 0;
            font-size: 0.85rem;
            color: var(--text-muted);
        }

        .file-link {
            display: inline-block;
            margin-top: 8px;
            font-size: 0.9rem;
            color: var(--accent);
            text-decoration: none;
            font-weight: 600;
        }

        .file-link:hover {
            text-decoration: underline;
        }

        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 15px;
        }

        .skill-card {
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            padding: 18px;
            border-radius: 8px;
        }

        .skill-card h3 {
            margin-top: 0;
            font-size: 1.05rem;
            color: var(--primary);
            margin-bottom: 8px;
        }

        /* Hire Me Card */
        .hire-card {
            background: #eff6ff;
            border: 1px solid #bfdbfe;
            padding: 25px;
            border-radius: 8px;
        }

        footer {
            margin-top: 60px;
            padding: 25px 0;
            border-top: 1px solid var(--border-color);
            text-align: center;
            font-size: 0.85rem;
            color: var(--text-muted);
        }
    </style>
</head>
<body>

    <!-- Sticky Navigation Bar -->
    <nav>
        <div class="nav-container">
            <a href="#about" class="nav-logo">Sushree Swateeprajnya Behera</a>
            <div class="nav-links">
                <a href="#about">About Me</a>
                <a href="#resume">Resume</a>
                <a href="#research">Research & Setup</a>
                <a href="#publications">Publications</a>
                <a href="#contact">Contact</a>
                <a href="#hire-me" class="btn-hire">Hire Me</a>
            </div>
        </div>
    </nav>

    <div class="container">

        <!-- Header / First Page (About Me) -->
        <header class="hero" id="about">
            <h1>Sushree Swateeprajnya Behera</h1>
            <div class="subtitle">Experimental Quantum Hardware Researcher</div>
            <p style="margin-top: 15px; font-size: 1.05rem; color: var(--text-dark);">
                Hello and welcome! 👋 I am an experimental quantum physicist specializing in solid-state quantum photonics, color centers in 4H-SiC, atomic systems, and precision optical measurement platforms. I bridge high-level theoretical physics requirements with robust, cleanroom-fabricated quantum hardware.
            </p>
            <a href="CV.pdf" class="btn-cv" target="_blank">📥 Download Full Curriculum Vitae (PDF)</a>
        </header>

        <!-- Resume Section -->
        <section id="resume">
            <h2>Resume & Academic Background</h2>

            <h3>Research Positions</h3>

            <div class="exp-item">
                <div class="exp-header">
                    <span class="role-title">Quantum Sensing Researcher</span>
                    <span class="date-badge">March 2026 – July 2026</span>
                </div>
                <div class="org-name">QuBeats (M/s Nostradamus Technologies) & TIFR Hyderabad, India</div>
                <ul>
                    <li>Designed and built a GUI for compact optically pumped magnetometers (OPM) using Rubidium (Rb) atoms.</li>
                    <li>Performed DAQ and signal analysis for NMOR experiments using Moku:Go platform (lock-in detection, waveform generation).</li>
                    <li>Built a Python-based digital lock-in amplifier and wound custom Helmholtz coils for precision magnetic-field control.</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span class="role-title">Researcher – Quantum Materials Team</span>
                    <span class="date-badge">November 2024 – December 2025</span>
                </div>
                <div class="org-name">Luxembourg Institute of Science and Technology (LIST) & Université du Luxembourg</div>
                <ul>
                    <li>Investigated two-photon interference using color centers in silicon carbide (4H-SiC) under the AQuaTSiC project.</li>
                    <li>Designed and built an optical fiber gluing station for waveguide–fiber interfacing from scratch.</li>
                    <li>Integrated 780–1220 nm laser systems with 4H-SiC nanophotonic devices; led cleanroom specialty fiber fabrication.</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span class="role-title">Guest Scientist – Quantum Photonics Group</span>
                    <span class="date-badge">May 2024 – July 2024</span>
                </div>
                <div class="org-name">Universität des Saarlandes, Saarbrücken, Germany</div>
                <ul>
                    <li>Investigated coherent population trapping in a Λ-system of <sup>174</sup>Yb using 680 nm and 770 nm repump lasers.</li>
                    <li>Built a double-pass AOM setup for 397 nm laser stability characterization using MATLAB object-oriented programming.</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span class="role-title">Project Associate I – Quantum Optics Group</span>
                    <span class="date-badge">October 2022 – April 2024</span>
                </div>
                <div class="org-name">Indian Institute of Science (IISc), Bengaluru, India</div>
                <ul>
                    <li>Generated quantum hyperentanglement via SPDC using BBO and PPKTP crystals. Verfied Bell inequality violations.</li>
                </ul>
            </div>

            <h3 style="margin-top: 30px;">Education</h3>
            <div class="exp-item">
                <div class="exp-header">
                    <span class="role-title">BS-MS Dual Degree (Physics)</span>
                    <span class="date-badge">2016 – 2021</span>
                </div>
                <div class="org-name">Indian Institute of Science Education and Research (IISER) Tirupati, India</div>
                <p><strong>MS CGPA:</strong> 8.3 / 10.0 | <strong>Thesis:</strong> <em>Quantum Volume: Capability of a quantum computer and effective implementation of quantum circuits</em></p>
            </div>

            <h3 style="margin-top: 30px;">Laboratory Capabilities</h3>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Lasers & Optics</h3>
                    <p>CW lasers (Vis to NIR), free-space/fiber optics, AOMs, spectroscopy, fiber splicing, high-speed spectrometers.</p>
                </div>
                <div class="skill-card">
                    <h3>Detectors & Timing</h3>
                    <p>SPCM-AQ4C, APDs, PMT, EMCCD, Time Tagger S15, HYDRA II, PicoHarp, balanced photodetectors, TCSPC.</p>
                </div>
                <div class="skill-card">
                    <h3>Cleanroom (ISO 4)</h3>
                    <p>Specialty fiber fabrication (1060XP, ZBLAN), fiber–chip bonding, SEM, AFM characterization.</p>
                </div>
            </div>
        </section>

        <!-- Research & Setups (Placeholders for Photos and Reports) -->
        <section id="research">
            <h2>Research Setups & Experimental Reports</h2>
            <p>Below are highlights of optical setups, cleanroom workflows, and experimental platforms I have built, alongside technical reports available for download:</p>

            <div class="photo-gallery">
                <!-- Example Photo Card 1 -->
                <div class="photo-card">
                    <img src="setup-fiber-gluing.jpg" alt="Fiber Gluing Station" onerror="this.src='https://via.placeholder.com/300x180?text=Optical+Setup+Photo';">
                    <p><strong>Custom Fiber Gluing Station:</strong> Built for high-precision chip-to-waveguide interfacing at LIST, Luxembourg.</p>
                    <a href="reports/Fiber_Gluing_Report.pdf" class="file-link" target="_blank">📄 Download Tech Report (PDF)</a>
                </div>

                <!-- Example Photo Card 2 -->
                <div class="photo-card">
                    <img src="setup-aom.jpg" alt="Double-pass AOM Setup" onerror="this.src='https://via.placeholder.com/300x180?text=Laser+Setup+Photo';">
                    <p><strong>Double-Pass AOM Alignment:</strong> 397 nm laser pulse modulation setup built at Universität des Saarlandes.</p>
                    <a href="reports/AOM_Setup_Summary.pdf" class="file-link" target="_blank">📄 Download Tech Report (PDF)</a>
                </div>

                <!-- Example Photo Card 3 -->
                <div class="photo-card">
                    <img src="cleanroom-characterization.jpg" alt="Cleanroom Characterization" onerror="this.src='https://via.placeholder.com/300x180?text=Cleanroom+Work';">
                    <p><strong>Cleanroom Specialty Fiber Processing:</strong> ISO 4 environment characterization of 1060XP and ZBLAN fibers.</p>
                    <a href="reports/Cleanroom_Workflow.pdf" class="file-link" target="_blank">📄 Download Tech Report (PDF)</a>
                </div>
            </div>
        </section>

        <!-- Publications & Presentations -->
        <section id="publications">
            <h2>Publications & Presentations</h2>
            <ul>
                <li style="margin-bottom: 12px;">
                    <strong>Observation of geometric phase in a molecular Aharonov-Bohm system using IBM Quantum Computer</strong><br>
                    Gaurav Rudra Malik, Sushree Swateeprajnya Behera, Shubham Kumar, Bikash K. Behera, Prasanta K. Panigrahi<br>
                    <em>Preprint: arXiv:1909.00298 [quant-ph], 2019</em>
                </li>
                <li style="margin-bottom: 12px;">
                    <strong>Controlling asymptotic self-similar optical beams in a semiconductor waveguide doped with quantum dots</strong><br>
                    Sushree Swateeprajnya Behera, Nikhitha Nunavath, Vineetha Ashok, Thokala Soloman Raju<br>
                    <em>Published as conference paper at Optical Society of America (OSA), PHOTONICS 2018</em>
                </li>
            </ul>

            <h3 style="margin-top: 25px;">Invited Talks & Conferences</h3>
            <ul>
                <li><strong>Invited Talk:</strong> <em>Two-photon interference with divacancies in silicon carbide</em>, Quantum SiC Workshop, Stralsund, Germany (Oct 2025).</li>
                <li><strong>Presentation:</strong> <em>Towards two-photon interference with color centers in silicon carbide</em>, Greenhorn Meeting, Saarbrücken, Germany (Sep 2025).</li>
                <li><strong>Poster:</strong> <em>Multiplexing divacancies in silicon carbide for quantum networks</em>, DPPM PhD Day, Univ. of Luxembourg (Apr 2025).</li>
            </ul>
        </section>

        <!-- Hire Me Section -->
        <section id="hire-me">
            <h2>Ph.D. & Industry Opportunities</h2>
            <div class="hire-card">
                <h3 style="margin-top: 0; color: var(--primary);">Open to Ph.D. Positions & Quantum Hardware Roles</h3>
                <p>
                    I am actively seeking <strong>Ph.D. positions</strong> and <strong>R&D Quantum Hardware roles</strong> focusing on experimental quantum photonics, color center integration, atomic magnetometry, and scalable optical architectures. 
                </p>
                <p>
                    If you are a Principal Investigator or Group Leader seeking a motivated researcher with extensive experience in building optical platforms from scratch and cleanroom device characterization, I would love to connect!
                </p>
                <a href="mailto:sushreeswateeprajnyabehera@gmail.com" class="btn-cv" style="background: var(--accent);">📧 Get in Touch directly</a>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Information</h2>
            <p><strong>Email:</strong> <a href="mailto:sushreeswateeprajnyabehera@gmail.com">sushreeswateeprajnyabehera@gmail.com</a></p>
            <p><strong>Phone:</strong> +352 661158039 (Luxembourg) / +91 7008544939 (India)</p>
            <p><strong>LinkedIn:</strong> <a href="https://linkedin.com" target="_blank">Connect on LinkedIn</a></p>
        </section>

    </div>

    <footer>
        <p>© Sushree Swateeprajnya Behera | Quantum Hardware Researcher | Hosted on GitHub Pages</p>
    </footer>

</body>
</html>
