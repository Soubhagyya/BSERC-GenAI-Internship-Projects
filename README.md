# BSERC GenAI Internship — Week 1 Projects

**Author & Developer:** Soubhagyya Bhattacharya  
**Program:** Def-Space GenAI Internship  
**Institution:** Bharat Space Education Research Centre (BSERC)  
**Instructor:** Karan Bagul  

---

## 📌 Executive Overview

This repository contains the complete deliverables for **Week 1** of the BSERC GenAI Internship, demonstrating the transition from passive AI consumption to active AI tool-building:

1. **Project 1: Source-Grounded AI Research Notebook** — A strictly grounded, hallucination-free research partner in Google NotebookLM focused on Space Dynamics and Satellite Astrodynamics.
2. **Project 2: Thinking in HTML** — Three standalone, interactive, single-file web applications engineered with zero external libraries or CDNs, functioning 100% offline.

---

## 🪐 Project 1: Source-Grounded Space Astrodynamics Notebook

* **Platform:** Google NotebookLM (`notebook.google.com`)
* **Topic:** Spacecraft Systems & Keplerian Orbital Mechanics
* **Core Rule:** Strictly grounded answering exclusively from uploaded trusted sources with exact inline bracketed citations `[1]`, `[2]`.

### Curated Multi-Modal Source Base (3 Formats)
- **Web Reference:** NASA Science — Basics of Space Flight (Central force gravity & reference systems).
- **Video Transcript:** Khan Academy — Planetary Motion & Kepler's Laws.
- **Technical Manuscript:** ESA & ISRO Flight Dynamics — Vis-Viva velocity equation, Hohmann transfer orbits, and atmospheric drag perturbations.

### Tested Capabilities
- **Citation Precision:** Automated synthesis with direct line citations.
- **Negative Boundary Testing:** Out-of-bounds rejection (verified with ungrounded queries).
- **Native Language Synthesis:** Comprehensive executive summaries and key takeaways in Bengali.
- **Studio Panel Generation:** Audio Overview podcast, Mind Map, Flashcards, Scored Diagnostic Quiz, and Executive Briefing Reports.

---

## 💻 Project 2: Thinking in HTML (Interactive Web Applications)

Each web application is contained within a **single standalone `.html` file** with zero third-party dependencies (no React, no Tailwind, no Bootstrap). Built using semantic HTML5, modern CSS glassmorphism, and native JavaScript.

### 1. Revision Command Center (`page1_dashboard.html`)
* **Purpose:** Exam readiness and technical retention platform for competitive engineering entrance.
* **Key Interactive Mechanisms:**
  - **Live Exam Countdown Clock:** Customizable countdown timer showing days, hours, minutes, seconds with dynamic date picker.
  - **Filterable Syllabus Checklist:** 9 complex technical topics with status dropdowns, search bar, and dynamic percentage progress bar.
  - **3D Active-Recall Flashcards:** 180° flip animation on tap, featuring technical concepts, formulas, and shuffle controls.
  - **Diagnostic Scored Quiz:** 4-question technical test with immediate visual color feedback, emoji score badges, and clean reset.
  - **Daily Study Goal Slider:** Pacing slider (1–12h) calculating Pomodoros, rest intervals, and hydration alerts.
  - **Local Scratchpad:** Persistent note-taking utilizing browser `localStorage`.
  - **Dark / Light Theme Switcher:** Smooth CSS variables transition.

### 2. Orbital Mechanics & Satellite Simulation Studio (`page2_model.html`)
* **Purpose:** Standalone astrodynamics laboratory exploring Keplerian orbits and satellite coverage footprints.
* **Key Interactive Mechanisms:**
  - **60-FPS HTML5 Canvas Engine:** Central Earth with atmospheric radial glow and rotating latitude coordinates.
  - **Keplerian Trajectory Solver:** Simulates LEO (Alpha), MEO (Beta), and GEO (GeoComm) orbits ($r = \frac{a(1-e^2)}{1+e\cos\theta}$).
  - **Live Telemetry Inspection Card:** Real-time Vis-Viva velocity ($v = \sqrt{\mu(2/r - 1/a)}$), altitude, and true anomaly ($\theta$).
  - **Simulation Time Warp Slider:** 0x (Pause) to 5x orbital speed with Play/Pause button.
  - **Physical Parameter Sliders:** Interactive semi-major axis radius scale and eccentricity ($e$) adjustments.
  - **Visualizer Overlays:** Toggleable fading orbital trails, communication cone footprints, and velocity vectors.
  - **Theme Modes:** Deep Space Neon, Tactical Radar Thermal, and Minimal Blueprint Wireframe.

### 3. Architecture Trade-Off Decision Matrix (`page3_decision.html`)
* **Purpose:** Multi-criteria weighted evaluation engine for cloud systems and software architecture selection.
* **Key Interactive Mechanisms:**
  - **5 Criteria Weight Sliders:** Individual sliders (0–100%) for Development Cost, Scalability, Latency, Speed to Market, and Security.
  - **Live Dynamic Leaderboard:** Automatically recalculates and re-ranks 4 baseline options (Serverless, Monolith, Edge, Kubernetes) with rank badges.
  - **Dynamic Reactive Bar Chart:** Pure SVG/CSS comparative bars that animate and adjust color states in real time.
  - **Strategy Preset Buttons:** Instant configuration for "Balanced", "Startup Speed", "Enterprise Security", and "Cost Minimizer".
  - **Candidate Adder Modal:** Form allowing users to input custom architectures and criteria ratings.
  - **Normalized Scoring Formula:** $\text{Total} = \frac{\sum (W_i \times S_i)}{\sum W_i} \times 100$.

---

## 🛠️ Prompt Engineering Methodology (`prompts.txt`)

Every HTML application was engineered through a disciplined **4-Part Framework**:
1. **WHO:** Target user persona and operational objective.
2. **WHAT:** System scope and functional requirements.
3. **DO:** Exact interactive mechanisms (at least 6 per application).
4. **RULES:** Technical boundaries (single file, 100% offline, zero external CDNs, mobile responsiveness).

Each application underwent **4 rounds of iterative prompt refinement** covering mobile layout clamps, canvas DPI sharpening, mathematical score normalization, and state persistence.

---

## 🚀 How to Run the Applications

No installation, web server, or Node.js required!

1. Clone or download this repository.
2. Double-click any `.html` file (`page1_dashboard.html`, `page2_model.html`, or `page3_decision.html`).
3. The application will open instantly in Google Chrome, Microsoft Edge, Firefox, or Safari.
4. Or open `Launch_Portfolio_Hub.html` to access the master navigation launchpad.

---

## 👤 Author

* **Developer:** Soubhagyya Bhattacharya
* **Program:** Def-Space GenAI Internship Week 1
* **Centre:** Bharat Space Education Research Centre (BSERC)
