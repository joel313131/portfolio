# 🚀 Joel Wilfred — Personal Portfolio Website

A modern, premium, fully responsive personal portfolio website for **Joel Wilfred**, Full Stack Developer & Designer based in Porayar, Mayiladuthurai, Tamil Nadu, India.

Built strictly using **HTML5**, **CSS3**, and **Vanilla JavaScript** (No external frameworks like React, Vue, Angular, Bootstrap, or jQuery).

---

## 🌟 Key Features

1. **Sticky Glassmorphic Navigation Bar**:
   - Modern blur background, smooth scroll tracking (ScrollSpy).
   - Fully responsive hamburger drawer menu for mobile devices.
   - Built-in Dark / Light mode toggle with instant persistence via `localStorage`.

2. **Full-Screen Hero Section**:
   - Dynamic typing animation cycling through developer & designer titles.
   - Ambient floating tech badges (`React`, `Spring Boot`, `UI/UX`).
   - Profile avatar visual container with action CTA buttons.

3. **About Me & Animated Statistics**:
   - Highlighting Full Stack Development, Frontend, Backend, UI/UX, and Responsive Design.
   - Interactive counter stats (Projects, Technologies, Certifications, Designs Created) powered by `IntersectionObserver`.

4. **Skills Dashboard**:
   - Categorized skills: Frontend, Backend, Database Systems, Developer Tools, and Creative Design.
   - Animated progress bars triggered upon scroll visibility.

5. **Services Section**:
   - Service cards with glassmorphism backgrounds, custom icons, gradient accents, and hover tilt effects.

6. **Filterable Projects Portfolio**:
   - Dynamic JavaScript filter buttons: *All*, *Web Development*, *Full Stack*, *Java*, *Python*, *Design*.
   - Displays 5 full-stack and web projects with tech stack tags, Live Demo links, and GitHub repository links.

7. **Education & Certifications**:
   - Vertical timeline showcasing **MCA**, **BCA** (TBML College, Porayar 2021-2024), and **Higher Secondary**.
   - Certification cards for Power BI (Edunet), Cloud (IBM SkillsBuild), Microsoft Office, and AI Full Stack (Livewire).

8. **Graphic Design Portfolio & Lightbox**:
   - Masonry gallery with filtering across 8 design categories (*Wedding Designs*, *Flex & Banners*, *Invitations*, *Posters*, *Visiting Cards*, *Social Media*, *Logos*, *Photo Editing*).
   - Built-in Vanilla JS **Lightbox Modal** for full-screen image previews.

9. **Resume Download Area**:
   - Direct call-to-action block for downloading `assets/Joel-Wilfred-Resume.pdf`.

10. **Interactive Contact Form & Social Links**:
    - Contact card featuring Name, Phone, Email, Location, and LinkedIn.
    - Quick social action buttons for Email, WhatsApp, LinkedIn, and GitHub.
    - Client-side form validation with animated toast notification alerts.

---

## 📁 Directory & Folder Structure

```
portfolio/
├── index.html                   # Main HTML5 Document (All 12 Sections)
├── css/
│   └── style.css                # CSS Variables, Animations, Glassmorphism & Responsive Media Queries
├── js/
│   └── script.js                # Vanilla JS (Theme Toggle, Typing, ScrollSpy, Filters, Lightbox, Form Validation)
├── assets/
│   ├── images/
│   │   ├── profile.svg          # Professional Profile Avatar Graphic
│   │   ├── project1.svg         # KEYSTONE Field Service Platform Mockup
│   │   ├── project2.svg         # Online Sports Store E-Commerce Mockup
│   │   ├── project3.svg         # Restaurant Ordering & QR System Mockup
│   │   ├── project4.svg         # Student Study Materials Hub Mockup
│   │   ├── project5.svg         # Java Full Stack Job Portal Mockup
│   │   └── designs/             # Graphic Design Portfolio Visuals
│   │       ├── wedding1.svg
│   │       ├── flex1.svg
│   │       ├── invitation1.svg
│   │       ├── poster1.svg
│   │       ├── card1.svg
│   │       ├── social1.svg
│   │       ├── logo1.svg
│   │       └── photo1.svg
│   └── Joel-Wilfred-Resume.pdf  # Downloadable PDF Resume
└── README.md                    # Documentation & Deployment Instructions
```

---

## 💻 How to Run the Website Locally in VS Code

### Option 1: Using Live Server Extension in VS Code (Recommended)
1. Open **VS Code**.
2. Go to **File -> Open Folder...** and select the `portfolio` directory.
3. Install the **Live Server** extension:
   - Click the Extensions icon on the left sidebar (or press `Ctrl+Shift+X`).
   - Search for **"Live Server"** (by Ritwick Dey).
   - Click **Install**.
4. Open `index.html` in VS Code.
5. Click **"Go Live"** at the bottom right status bar of VS Code, or right-click inside `index.html` and select **"Open with Live Server"**.
6. The portfolio will open automatically in your browser at `http://127.0.0.1:5500`.

### Option 2: Direct Browser File Opening
1. Navigate to the `portfolio` folder on your computer.
2. Double-click `index.html` to open it directly in Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari.

### Option 3: Using Python Local Server (Terminal / PowerShell)
1. Open PowerShell or Command Prompt inside the `portfolio` directory.
2. Run the command:
   ```bash
   python -m http.server 8000
   ```
3. Open your browser and navigate to `http://localhost:8000`.

---

## 🌐 How to Deploy the Portfolio Website for FREE

### Method A: Deploy Free on GitHub Pages

1. **Create a GitHub Repository**:
   - Go to [github.com](https://github.com) and log in.
   - Click **New Repository**.
   - Name your repository (e.g. `joel-wilfred-portfolio` or `joelwilfred.github.io`).
   - Leave it **Public** and click **Create Repository**.

2. **Push Code to GitHub**:
   Open terminal inside your local `portfolio` folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of Joel Wilfred portfolio website"
   git branch -M main
   git remote add origin https://github.com/joelwilfred/joel-wilfred-portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click **Settings** -> **Pages** (under Code and automation).
   - Under **Build and deployment -> Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)`, then click **Save**.
   - After 1-2 minutes, your website will be live at:
     `https://<your-username>.github.io/joel-wilfred-portfolio/`

---

### Method B: Deploy Free on Netlify

1. **Sign Up / Log In**:
   - Visit [netlify.com](https://www.netlify.com/) and create a free account.

2. **Drag & Drop Deployment**:
   - Go to your Netlify Dashboard.
   - Click **Sites** -> Drag & Drop your `portfolio` folder directly into the designated drop zone.
   - Netlify will instantly upload and deploy your website in less than 10 seconds.
   - You will receive a free public URL (e.g., `https://joel-wilfred-portfolio.netlify.app`).
   - You can customize your subdomain for free in **Site Settings -> Change Site Name**.

---

## 🛠️ How to Customize

- **Updating Profile Photo**: Replace `assets/images/profile.svg` with your high-resolution portrait photograph (e.g., `assets/images/profile.jpg`) and update the `src` attribute in `index.html`.
- **Updating Resume**: Replace `assets/Joel-Wilfred-Resume.pdf` with your actual updated PDF resume file.
- **Adding Projects & Designs**: Duplicate a `.project-card` or `.gallery-item` block inside `index.html` and update the title, tags, description, and images.

---

© 2026 **Joel Wilfred**. All Rights Reserved.
