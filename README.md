# Himanshu Chauhan – Premium Dynamic Developer Portfolio

A modern, responsive, and interactive personal portfolio website for **Himanshu Chauhan – Full Stack Developer**, built with **React.js**, **React Router**, and pure **CSS3** (with glassmorphism, gradient lighting, and fluid animations).

---

## 🚀 Key Highlights & Features

- **Frontend Technology Stack**: React 19, React Router 7, Pure CSS3, Lucide Icons, and custom high-fidelity SVG logos.
- **Design & UI**:
  - Light theme (white, soft blue, subtle purple) with dynamic Light/Dark mode toggle (persisted to `localStorage`).
  - Glassmorphic cards with `backdrop-filter: blur()`, glowing borders, and smooth hover micro-interactions.
  - Dynamic animated background with glowing blurred orbs and subtle grid pattern.
  - Interactive typing animation for *"Full Stack Developer"*.
  - Smooth page transitions and floating Back-to-Top button.
- **Multi-Page React Router Navigation**:
  - `/` — **Home**: Hero section with interactive avatar, floating tech badges, quick stats, core competencies preview, featured projects, and CTA.
  - `/about` — **About Me**: Professional introduction, passion for Full Stack Development, continuous learning mindset, problem-solving and teamwork abilities, snapshot card, and 4-step engineering workflow.
  - `/skills` — **Technical Skills**: Categorized animated cards with official vector logos (C, C++, Java, JavaScript, PHP, HTML5, CSS3, React.js, Node.js), proficiency meters, live search, and category filters.
  - `/projects` — **Projects Showcase**: Interactive cards with UI mockups for *PDFora*, *Mobile Billing Software*, and *Developer Portfolio*, with live demo modal preview and GitHub integration.
  - `/contact` — **Contact**: Professional contact cards, direct email launcher, instant copy email button, and validated mailto-based contact form.

---

## 🛠️ Project Structure

```
himanshu-portfolio/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx                  # Application entry point with BrowserRouter
    ├── App.jsx                   # Main layout, routing, and scroll restoration
    ├── App.css
    ├── index.css
    ├── assets/                   # Static assets
    ├── context/
    │   └── ThemeContext.jsx      # Light / Dark theme state management
    ├── data/
    │   ├── skillsData.js         # Full technical skills dataset with proficiency
    │   └── projectsData.js       # Projects showcase dataset
    ├── styles/
    │   ├── variables.css         # CSS custom properties (light & dark theme)
    │   └── global.css            # Base typography, utilities, and animations
    ├── components/
    │   ├── BackgroundOrbs.jsx    # Floating animated gradient background
    │   ├── BackgroundOrbs.css
    │   ├── Navbar.jsx            # Sticky blurred navbar with hamburger drawer
    │   ├── Navbar.css
    │   ├── Footer.jsx            # Professional multi-column footer
    │   ├── Footer.css
    │   ├── ThemeToggle.jsx       # Light / Dark mode toggle switch
    │   ├── BackToTop.jsx         # Smooth scroll-to-top floating button
    │   ├── BackToTop.css
    │   ├── TypingAnimation.jsx   # Dynamic typewriter effect
    │   ├── TechIcon.jsx          # Official SVG logos (C, C++, Java, JS, PHP, etc.)
    │   ├── SocialIcons.jsx       # GitHub vector icon
    │   ├── SkillCard.jsx         # Interactive skill card with proficiency bar
    │   ├── SkillCard.css
    │   ├── ProjectCard.jsx       # Project card with visual mockup illustration
    │   ├── ProjectCard.css
    │   ├── ProjectModal.jsx      # Interactive project details & preview modal
    │   ├── ContactForm.jsx       # Validated form with mailto draft generator
    │   └── ContactForm.css
    └── pages/
        ├── Home.jsx              # Landing & hero page
        ├── Home.css
        ├── About.jsx             # About Me & Core Pillars
        ├── About.css
        ├── Skills.jsx            # Skills directory with filters & search
        ├── Skills.css
        ├── Projects.jsx          # Projects showcase with filters
        ├── Projects.css
        ├── Contact.jsx           # Contact page & info cards
        └── Contact.css
```

---

## 💻 How to Run Locally

### 1. Install Dependencies
```bash
npm install
```

### 2. Run the Development Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 3. Build for Production
```bash
npm run build
```

### 4. Preview the Production Build
```bash
npm run preview
```

---

## 👤 Personal Information Configured

- **Name**: Himanshu Chauhan
- **Title**: Full Stack Developer
- **Email**: [himanshuchauahn0361@gmail.com](mailto:himanshuchauahn0361@gmail.com)
- **GitHub**: [https://github.com/himanshuchauhan3117-commits](https://github.com/himanshuchauhan3117-commits)
- **Copyright**: © 2026 Himanshu Chauhan. All Rights Reserved.
