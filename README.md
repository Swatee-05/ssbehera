<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushree Swateeprajnya Behera | Quantum Hardware Researcher</title>
    <style>
        :root {
            --primary: #1e3a8a;
            --primary-light: #2563eb;
            --text-dark: #1f2937;
            --text-muted: #4b5563;
            --bg-body: #f8fafc;
            --bg-card: #ffffff;
            --border-color: #e2e8f0;
        }

        * {
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--bg-body);
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        header {
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 25px;
            margin-bottom: 35px;
        }

        h1 {
            margin: 0;
            color: var(--primary);
            font-size: 2.2rem;
            letter-spacing: -0.5px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--primary-light);
            margin-top: 5px;
            font-weight: 600;
        }

        .contact-bar {
            margin-top: 15px;
            font-size: 0.95rem;
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }

        .contact-bar a {
            color: var(--primary-light);
            text-decoration: none;
            font-weight: 500;
        }

        .contact-bar a:hover {
            text-decoration: underline;
        }

        .btn-cv {
            display: inline-block;
            background: var(--primary);
            color: #ffffff;
            padding: 10px 18px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 20px;
            transition: background 0.2s ease;
        }

        .btn-cv:hover {
            background: var(--primary-light);
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            color: var(--primary);
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
            font-size: 1.4rem;
            margin-bottom: 20px;
        }

        .exp-item {
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 20px;
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
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--text-dark);
        }

        .date-badge {
            font-size: 0.85rem;
            background: #e0e7ff;
            color: #3730a3;
            padding: 3px 8px;
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

        .pub-list, .talk-list {
            list-style-type: square;
        }

        .pub-list li, .talk-list li {
            margin-bottom: 12px;
        }

        footer {
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid var(--border-color);
            text-align: center;
            font-size: 0.85rem;
            color: var(--text-muted);
        }
    </style>
</head>
<body>

    <header>
        <h1>Sushree Swateeprajnya Behera</h1>
        <div class="subtitle">Experimental Quantum Hardware Researcher</div>
        <p style="margin-top: 10px; color: var(--text-muted);">
            Specializing in solid-state quantum photonics, color centers in silicon carbide (4H-SiC), atomic systems (174-Yb, 85-enriched Rb), and precision optical measurement platforms.
        </p>
        <div class="contact-bar">
            <a href="mailto:sushreeswateeprajnyabehera@gmail.com">sushreeswateeprajnyabehera@gmail.com</a>
            <span>•</span>
            <a href="tel:+352661158039">+352 661158039</a>
            <span>•</span>
            <a href="tel:+917008544939">+91 7008544939</a>
            <span>•</span>
            <a href="https://linkedin.com" target="_blank">LinkedIn Profile</a>
        </div>
        <a href="CV.pdf" class="btn-cv" target="_blank">📄 Download Full Curriculum Vitae (PDF)</a>
    </header>

    <section>
        <h2>Professional Summary & Research Interests</h2>
        <p>
            I am an experimental quantum hardware researcher with hands-on experience in designing, integrating, and characterizing complex photonic and atomic systems. I am proficient in laboratory automation, subsystem interfacing, and building precision measurement platforms from scratch for high-stability environments. Alongside, I am experienced in navigating cleanroom fabrication workflows, managing multi-instrument data acquisition pipelines, and translating high-level physics requirements into scalable quantum hardware solutions.
        </p>
        <p><strong>Research Interests:</strong> Solid-state quantum photonics, quantum light sources, nanophotonic device integration, quantum networks, and precision optical measurement platforms.</p>
    </section>

    <section>
        <h2>Research Experience</h2>

        <div class="exp-item">
            <div class="exp-header">
                <span class="role-title">Quantum Sensing Researcher</span>
                <span class="date-badge">March 2026 – July 2026</span>
            </div>
            <div class="org-name">QuBeats (M/s Nostradamus Technologies) & TIFR Hyderabad, India</div>
            <ul>
                <li>Designed and built a GUI for compact optically pumped magnetometer (OPM) to sense and measure earth's magnetic field using Rubidium (Rb) atoms.</li>
                <li>Performed DAQ and signal analysis of frequency-modulated signals in a Rb-based nonlinear magneto-optical rotation (NMOR) experiment using Moku:Go platform (lock-in detection, waveform generation, oscilloscope).</li>
                <li>Built a Python-based digital lock-in amplifier for signal extraction and phase-sensitive detection using Butterworth low-pass filtering.</li>
                <li>Designed, wound, and characterized Helmholtz coils for precision magnetic-field generation and control in quantum optics experiments.</li>
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
                <li>Designed and built an optical fiber gluing station for waveguide–fiber interfacing from scratch, enabling stable chip–fiber coupling.</li>
                <li>Integrated visible to near-infrared (780–1220 nm) laser systems with 4H-SiC nanophotonic devices.</li>
                <li>Led cleanroom fabrication of specialty fibers (1060XP and ZBLAN in association with Flawless Photonics Inc.) and process logistics coordination.</li>
                <li>Qualified optical adhesives for chip-level fiber attachment, defining bonding protocols for mechanical and optical stability.</li>
                <li>Conducted theoretical study of neutral divacancy (VV) in 4H-SiC, analyzing electronic structure and optical transitions in single-photon generation.</li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="role-title">Guest Scientist – Quantum Photonics Group</span>
                <span class="date-badge">May 2024 – July 2024</span>
            </div>
            <div class="org-name">Universität des Saarlandes, Saarbrücken, Germany</div>
            <ul>
                <li>Investigated coherent population trapping and dark-state formation in a Λ-system of <sup>174</sup>Yb using 680 nm and 770 nm repump lasers.</li>
                <li>Built a double-pass Acousto-Optic Modulator (AOM) setup for 397 nm laser, DAQ, analysis, and stability characterization using MATLAB object-oriented programming.</li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="role-title">Project Associate I – Quantum Optics & QIP Group</span>
                <span class="date-badge">October 2022 – April 2024</span>
            </div>
            <div class="org-name">Indian Institute of Science (IISc), Bengaluru, India</div>
            <ul>
                <li>Generated quantum hyperentanglement via spontaneous parametric down-conversion (SPDC) using Type I/II BBO and PPKTP crystals.</li>
                <li>Established violation of Bell’s inequalities using heralded single-photon sources and EMCCD camera detection.</li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="role-title">Visiting Researcher</span>
                <span class="date-badge">July 2022 – October 2022</span>
            </div>
            <div class="org-name">Institute of Mathematical Sciences (IMSc), Chennai, India</div>
            <ul>
                <li>Researched topological networks for quantum communication between distant qubits and robust communication protocols.</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Laboratory Hardware & Technical Skills</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <h3>Lasers & Optics</h3>
                <p>CW lasers (Vis to NIR), free-space and fiber optics, optical components, AOMs, RF drivers, spectroscopy, fiber splicing, high-speed spectrometers.</p>
            </div>
            <div class="skill-card">
                <h3>Detectors & Timing</h3>
                <p>SPCM-AQ4C, APDs, PMT, EMCCD, Time Tagger S15, HYDRA II, PicoHarp, PD10B high-gain balanced photodetectors, TCSPC.</p>
            </div>
            <div class="skill-card">
                <h3>Automation & Electronic Instrumentation</h3>
                <p>Hardware synchronization, 6-axis stages, PicoScope, Moku:Go, Digilent AD3, lock-in amplifiers, waveform generators, Twinleaf precision magnetic controllers.</p>
            </div>
            <div class="skill-card">
                <h3>Cleanroom (ISO 4) & Characterization</h3>
                <p>Specialty fiber fabrication (1060XP, ZBLAN), fiber-chip integration, nanostructure characterization using SEM and AFM, protocol compliance.</p>
            </div>
            <div class="skill-card">
                <h3>Software & Programming</h3>
                <p>Python, MATLAB, Mathematica, Qiskit, Amazon Braket, IBM Quantum Experience, OriginPro, LaTeX, Overleaf.</p>
            </div>
        </div>
    </section>

    <section>
        <h2>Education</h2>
        <div class="exp-item">
            <div class="exp-header">
                <span class="role-title">BS-MS Dual Degree (Physics)</span>
                <span class="date-badge">August 2016 – August 2021</span>
            </div>
            <div class="org-name">Indian Institute of Science Education and Research (IISER) Tirupati, India</div>
            <p><strong>MS CGPA:</strong> 8.3 / 10.0</p>
            <p><strong>Thesis Title:</strong> <em>Quantum Volume: Capability of a quantum computer and effective implementation of quantum circuits</em></p>
            <ul>
                <li>Computed noise in state preparation, gate operations, and measurements limiting quantum processor performance.</li>
                <li>Analyzed protocols for accurate estimation of quantum volume in noisy NISQ devices.</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>Publications & Preprints</h2>
        <ul class="pub-list">
            <li>
                <strong>Observation of geometric phase in a molecular Aharonov-Bohm system using IBM Quantum Computer</strong><br>
                Gaurav Rudra Malik, Sushree Swateeprajnya Behera, Shubham Kumar, Bikash K. Behera, Prasanta K. Panigrahi<br>
                <em>Preprint: arXiv:1909.00298 [quant-ph], 2019</em>
            </li>
            <li>
                <strong>Controlling asymptotic self-similar optical beams in a semiconductor waveguide doped with quantum dots</strong><br>
                Sushree Swateeprajnya Behera, Nikhitha Nunavath, Vineetha Ashok, Thokala Soloman Raju<br>
                <em>Published as conference paper at Optical Society of America (OSA), PHOTONICS 2018</em>
            </li>
        </ul>
    </section>

    <section>
        <h2>Invited Talks & Presentations</h2>
        <ul class="talk-list">
            <li><strong>Invited Talk (Oral):</strong> <em>Two-photon interference with divacancies in silicon carbide</em>, Quantum SiC Workshop, Stralsund, Germany (October 2025).</li>
            <li><strong>Oral & Poster:</strong> <em>Towards two-photon interference with color centers in silicon carbide</em>, Greenhorn Meeting, Saarbrücken, Germany (September 2025).</li>
            <li><strong>Poster:</strong> <em>Multiplexing divacancies in silicon carbide for quantum networks</em>, DPPM PhD Day, University of Luxembourg (April 2025).</li>
            <li><strong>Poster:</strong> <em>Multiplexing color centers in silicon carbide for quantum networks</em>, DPG Conference, Bonn, Germany (March 2025).</li>
            <li><strong>Oral Presentation:</strong> <em>Journal club presentation in quantum metrology</em>, IISc Bengaluru, India (June 2023).</li>
        </ul>
    </section>

    <footer>
        <p>© Sushree Swateeprajnya Behera | Hosted on GitHub Pages</p>
    </footer>

</body>
</html>
