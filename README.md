# Abdul Saboor — Cinematic 3D Scroll Portfolio

A high-performance, cinematic developer portfolio engineered for **Abdul Saboor** (Computer Science undergraduate at **FAST NUCES**, Full-Stack Developer, and AI Engineer). 

The website merges modern dark luxury design principles with an **Apple / Awwwards-inspired 3D scroll-driven animation sequence**, delivering a fluid, responsive experience across all viewports.

---

## 🌟 Live Demo & Local Links

- **Local Development Server**: [http://localhost:5500](http://localhost:5500)
- **Direct File**: [`index.html`](file:///f:/abdul_Saboor/index.html)
- **Repository / Project Directory**: [`F:\abdul_Saboor`](file:///f:/abdul_Saboor/)

---

## 🚀 Key Highlights & Architectural Features

### 1. Zero-Lag 3D Scroll Scrubbing
- **238 Sequential Frames**: Renders high-resolution image frames (`ezgif-frame-001.png` to `ezgif-frame-238.png`) in sync with scroll progress.
- **Hardware-Accelerated Canvas**: Pinned full-screen `<canvas>` utilizing `transform: translateZ(0)` and `desynchronized: true` for direct GPU compositing.
- **Linear Interpolation (Lerp) Physics**: Smooth damping (`lerpFactor = 0.14`) provides instantaneous response to trackpads, mice, and mobile touch without sluggish delay.
- **Asynchronous Image Preloading & Decoding**: Uses progressive `Image()` loading and `img.decode()` to eliminate micro-stutters during rapid scrubbing.
- **Nearest-Frame Fallback**: Seamlessly renders the closest loaded keyframe during quick scroll gestures so the canvas never flashes blank.

### 2. Transparent, Face-Preserving Header
- **100% Transparent Navbar**: Zero blur (`backdrop-filter: none`) and zero background tint in all scroll states.
- **Open-Center Layout**: Navigation links and the *"Hire Me"* button are grouped to the far right, leaving the center open so Abdul's face in the 3D model is never obscured or cropped.
- **Dual Resume Access (AI/ML & Software Dev)**: Instant navbar dropdown and hero action buttons linking directly to [`resume/Abdul Saboor AI-ML.pdf`](file:///f:/abdul_Saboor/resume/Abdul%20Saboor%20AI-ML.pdf) and [`resume/Abdul_Saboor_Software_Development.pdf`](file:///f:/abdul_Saboor/resume/Abdul_Saboor_Software_Development.pdf).
- **Top Scroll Progress Bar**: A sleek 2.5px glowing gradient line indicating live scroll progress (0% → 100%).
- **Mobile Navigation Drawer**: Responsive slide-out menu with direct section navigation, dual resume downloads, and contact button for phones (< 768px).
- **SEO & Social Share Previews**: Comprehensive OpenGraph and Twitter cards embedded with SVG favicon for rich link previews across LinkedIn, WhatsApp, and Discord.
- **Top-Anchored Cover Fit**: The canvas rendering engine dynamically scales the 16:9 frames while anchoring `y = 0` to preserve full headroom on all screen aspect ratios.

### 3. Streamlined, Scannable Page Flow
The website is structured into a logical, high-impact storytelling sequence:
1. **Hero**: Big display typography, 4 technical pillars, and core stack badge bar.
2. **Experience**: Work history at A-Nets Cyber Solution and teaching at FAST-NUCES.
3. **Projects**: Interactive 14-project showcase with instant category filtering and case study modal.
4. **Skills**: Core language percentage scoreboard, 6 technical domains, and workflow tools ribbon.
5. **Journey**: Concise milestones from FAST Islamabad (2023) to FAST Karachi (2024–2026).
6. **Contact**: Direct communication links (Email, Phone/WhatsApp, LinkedIn, GitHub) and interactive message dispatch.

---

## 📂 Section-by-Section Breakdown

### 1. Hero Section (`#hero`)
- **Headline**: *Abdul Saboor — CS @ FAST NUCES • Full Stack | AI Engineer*
- **Tagline**: *"Building reliable software with a blend of machine learning rigor, systems thinking, and human-centered design."*
- **4 Focus Pillars**:
  - `// 01 Full-Stack Development`
  - `// 02 AI & Multi-Agent Systems`
  - `// 03 Systems & Low-Level C++`
  - `// 04 Data Structures & Algorithms`
- **Core Stack Trust Bar**: `Python & LangChain`, `React.js & Next.js`, `C++ & Multithreading`, `PostgreSQL & Firebase`.

### 2. Professional Experience (`#experience`)
- **Full-Stack Developer Intern | A-Nets Cyber Solution** *(Jun 2026 – Aug 2026)*:
  - Engineered responsive front-ends and back-end logic, integrating RESTful APIs and databases.
  - Debugged and stress-tested features; maintained clean technical documentation.
  - Collaborated across teams to ship features on time.
- **Lab Demonstrator, Programming Fundamentals | FAST-NUCES, Karachi** *(Aug 2025 – Dec 2025)*:
  - Taught weekly hands-on programming labs to 50+ undergraduate CS students.
  - Guided debugging sessions, graded assignments, and provided constructive code feedback.

### 3. Projects Showcase (`#projects`)
Includes dynamic category filtering (`All (14)`, `AI & Multi-Agent`, `Full-Stack & Web`, `Systems & C++`, `Games & Low-Level`) and an interactive case study modal.

| # | Project Name | Category | Tech Stack | Links |
|---|-------------|----------|------------|-------|
| 1 | **StratosAI** | AI / Multi-Agent | Python, LangGraph, LangChain, FastAPI | [Code](https://github.com/abdulsaboor190/StratosAI-Multi-Agent-Startup-Analyst) |
| 2 | **FAST Sports Complex** | Full-Stack Web | React, Node.js, PostgreSQL, REST APIs | [Code](https://github.com/abdulsaboor190/FAST_Sport_Complex_Management_System) · [Live Demo](https://fscm-topaz.vercel.app/) |
| 3 | **Scholr** | Mobile / Full-Stack | React Native, Next.js, Node.js, PostgreSQL | [Code](https://github.com/abdulsaboor190/Scholr) |
| 4 | **MediMind** | AI / LLM | Python, LangChain, Gemini API, RAG | [Code](https://github.com/abdulsaboor190/Health_Assistance_LLM) · [Live Demo](https://health-assistant-abdul-saboor.streamlit.app/) |
| 5 | **Toxicity Detection** | AI / NLP | Python, PyTorch, Scikit-learn, NLP | [Code](https://github.com/abdulsaboor190/Toxicity-Detector) · [Live Demo](https://toxicity-detector-rho.vercel.app/) |
| 6 | **FAST Past Papers** | Web Platform | HTML5, CSS3, JavaScript, JSON | [Code](https://github.com/abdulsaboor190/FAST-Past-Papers) · [Live Demo](https://fast-past-papers.vercel.app/) |
| 7 | **GoTaxi** | Web Application | React.js, JavaScript, Software Design, JSON | [Live Demo](https://go-taxi-alpha.vercel.app/#/) |
| 8 | **ChatNet** | Real-Time Systems | React.js, Firebase, Socket Programming | [Code](https://github.com/abdulsaboor190/ChatNet) |
| 9 | **Fake News Analysis** | Data / Research | Graph Theory, Similarity Index, Bipartite Graphs | [Code](https://github.com/abdulsaboor190/FakeNews) |
| 10 | **Airline Simulation** | Systems / OS | C++, Multithreading, Synchronization, Mutex | [Code](https://github.com/abdulsaboor190/AirlineSimulation) |
| 11 | **GitHub Lite** | Systems & DSA | C++, Data Structures, Algorithms, File Systems | Academic Project |
| 12 | **Zuma Deluxe** | Games / Low-Level | x86 Assembly, Hardware Interrupts, VGA Graphics | [Code](https://github.com/abdulsaboor190/ZumaDeluxe) |
| 13 | **Plants vs. Zombies** | Games / OOP | C++, Object-Oriented Programming, 2D Graphics | [Code](https://github.com/abdulsaboor190/PlantsVsZombies) |
| 14 | **Centipede Game** | Games / Console | C++, Problem Solving, Game Loops, Collision | [Code](https://github.com/abdulsaboor190/Centipede_Game_in_C) |

### 4. Technical Arsenal (`#skills`)
- **Core Languages**: JavaScript (90%), Python (88%), C++ (85%), SQL (82%), C (82%), Assembly x86 (78%).
- **Categorized Competencies**:
  - *Frontend*: React.js, HTML5/CSS3/ES6+, Responsive UI/UX, Tailwind CSS, Framer Motion.
  - *Backend & Databases*: JSON Data Handling, Firebase (Auth/DB), SQL Schemas, RESTful APIs.
  - *Machine Learning & Deep Learning*: Supervised Learning, Neural Networks, Keras, Scikit-learn, Regression & Classification.
  - *NLP & Language Models*: Chatbots, NLP Pipelines, Vector Space Models, Similarity Measures.
  - *Systems & Low-Level*: C++ Multithreading & Synchronization, OS Concepts, Memory Management, x86 Assembly.
  - *DSA & Networks*: Tree Data Structures (AVL, Red-Black), Graph Theory & Algorithms, Socket Programming.
- **Workflow Tools Ribbon**: React.js, Node.js, Firebase, Keras, Scikit-learn, Pandas, NumPy, TensorFlow, Azure Cloud, Git/GitHub, Tailwind CSS, Framer Motion, Express, Socket.io, VS Code, Linux.

### 5. Journey & Story (`#journey`)
- **Core Values**: `💡 Innovation` (creative problem solving), `✨ Clean Code` (modular scalability), `📈 Growth` (relentless build ethic).
- **Milestones**:
  - **2023 · FAST NUCES Islamabad**: Foundational training in programming fundamentals, algorithms, and discrete mathematics.
  - **2024 · Transition to Karachi Campus**: Broadened exposure to large-scale collaborative team architectures.
  - **2025 · ML & Systems Focus**: Deep dive into neural networks, operating systems, and multithreading.
  - **2025 · Shipped Capstone Projects**: Launched GoTaxi, ChatNet, and Graph-Theory Fake News analysis.
  - **2026 · Industry & Credentials**: A-Nets Full-Stack Intern, FAST Lab Demonstrator, and ML/IBM certifications.

### 6. Contact Us (`#contact`)
- **Direct Email**: [shahabdulsaboor208@gmail.com](mailto:shahabdulsaboor208@gmail.com)
- **Phone / WhatsApp**: [+92 319 165 9370](tel:03191659370)
- **LinkedIn**: [abdul-saboor-a572a0289](https://www.linkedin.com/in/abdul-saboor-a572a0289/)
- **GitHub**: [abdulsaboor190](https://github.com/abdulsaboor190)
- **Interactive Form**: Pre-fills direct email dispatch with project/opportunity type selection.

---

## 🛠️ Tech Stack & Implementation Details

- **Frontend Core**: Vanilla HTML5, CSS3, ES6+ JavaScript (zero framework runtime overhead for raw performance).
- **Animation Engine**: HTML5 Canvas 2D Context (`desynchronized: true`, custom lerp velocity tracking, capped DPR scaling for 4K performance).
- **Typography**: Google Fonts (`Syne` for display titles; `Plus Jakarta Sans` for body copy).
- **Assets**: 238 local PNG frames stored in `./file/`.

---

## 💻 How to Run Locally

### Option 1: Python Built-in Server (Recommended)
```powershell
cd F:\abdul_Saboor
python -m http.server 5500
```
Then open [http://localhost:5500](http://localhost:5500) in any modern browser.

### Option 2: Node.js `serve` / `http-server`
```powershell
npx serve .
```

### Option 3: Direct File Opening
Double click [`index.html`](file:///f:/abdul_Saboor/index.html) or open it directly in Chrome, Edge, Firefox, or Brave.

---

## 🚢 Deployment Guide

This portfolio is static and zero-dependency, making it compatible with any hosting provider:

1. **Vercel**: Run `vercel` in `F:\abdul_Saboor` or push to a GitHub repository and import.
2. **Netlify**: Drag-and-drop the `F:\abdul_Saboor` folder directly into the Netlify dashboard.
3. **GitHub Pages**: Push to `https://github.com/abdulsaboor190/abdulsaboor190.github.io` and enable GitHub Pages in repository settings.

---

## 📜 License & Copyright

© 2026 **Abdul Saboor**. All rights reserved.  
Crafted with 🧡 using Canvas physics and modern web design principles.

