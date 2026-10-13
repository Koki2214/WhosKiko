# John Francis A. Flores — Interactive Tech Portfolio & Owner Admin Dashboard

A futuristic, high-performance, and interactive portfolio website designed for **John Francis A. Flores** (Company Tech Support & Computer Engineering '26 Graduate).

Built with **Tailwind CSS**, **HTML5 Canvas**, **Web Audio API**, and **JetBrains Mono / Inter** typography. Ready for immediate deployment to **GitHub Pages** with zero backend or build setup required.

---

## ⚡ Live Interactive Features

1. **Dynamic HTML5 Constellation Canvas**:
   - Floating interactive cyber particle field that responds to mouse velocity, proximity, and movement.
2. **Interactive 3D Spotlight Cards**:
   - Glassmorphism panels featuring real-time radial light glow following the user's cursor.
3. **Interactive CLI Terminal (`flores@box:~$`)**:
   - Run commands (`help`, `about`, `skills`, `projects`, `experience`, `contact`, `time`, `matrix`, `sudo`, `clear`, `exit`).
   - Quick command pills for one-click execution.
4. **Interactive Project Showcase with Spec Sheets**:
   - Filter projects by category (*All*, *Robotics & IoT*, *Networking*, *Hardware & PC*).
   - Click **"Deep Dive Spec Sheet"** to open a detailed modal with hardware components, network topology, and project outcomes.
5. **Real-time Telemetry & Live Clock**:
   - Displays real-time Philippine Standard Time (PST / UTC+8), system status, and deployment health.
6. **Dynamic Typewriter Subheading**:
   - Automatically types and cycles through John's key competencies.
7. **Synthesized Sci-Fi Audio FX (Web Audio API)**:
   - Self-contained audio feedback on interactions, togglable with sound control on the side dock.
8. **Accent Theme Switcher**:
   - Instant theme switching between *Cyber Cyan*, *Neon Violet*, *Matrix Emerald*, and *Electric Amber*.
9. **One-Click Clipboard & Contact Actions**:
   - Instant copy for email and contact number with animated toast notifications.
10. **Owner Admin Control Center**:
    - Protected by PIN authentication (**Default PIN:** `1234` or click *Demo Bypass*).
    - **Visitor Inquiries Inbox**: Read, reply via mailto, delete, or clear visitor messages.
    - **Content Editor**: Update profile bio, skills, experience, and projects in real time.
    - **JSON Backup & Restore**: Export and import your entire portfolio configuration as a `.json` backup file.

---

## 🚀 How to Deploy to GitHub Pages (2-Minute Guide)

Because this website is 100% static and self-contained in `index.html`, you can deploy it for free on GitHub Pages in just a few clicks!

### Option A: Using the GitHub Website (No Git required)

1. Open [github.com](https://github.com) and sign in.
2. Click the **`+`** icon in the top right corner and choose **New repository**.
3. Name your repository (e.g., `MyPortfolio` or `<your-username>.github.io`).
   - Set it to **Public**.
   - Check **"Add a README file"** (or leave unchecked).
   - Click **Create repository**.
4. In your new repository, click **Add file** -> **Upload files**.
5. Drag and drop `index.html` from this folder (`c:\Users\LQ Home\Desktop\MyPortfolio\index.html`) into GitHub.
6. Click **Commit changes**.
7. Enable GitHub Pages:
   - Go to your repository **Settings** (tab at the top).
   - On the left sidebar, click **Pages**.
   - Under **Build and deployment** -> **Branch**, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
8. In 1 to 2 minutes, GitHub will give you a live URL:
   `https://<your-username>.github.io/MyPortfolio/`!

---

### Option B: Using Git / GitHub Desktop

If you install [GitHub Desktop](https://desktop.github.com/) or Git:

```bash
cd "c:\Users\LQ Home\Desktop\MyPortfolio"
git init
git add index.html README.md
git commit -m "Initial release of modern interactive portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/MyPortfolio.git
git push -u origin main
```
Then turn on GitHub Pages in repository **Settings -> Pages**.

---

## 🌐 Site Routes & Architecture
- **Public Portfolio Route**: `https://koki2214.github.io/WhosKiko/` (`index.html`)
  - 100% public, fast, no login required.
- **Admin Control Center Route**: `https://koki2214.github.io/WhosKiko/admin.html` (`admin.html`)
  - Protected by a lightweight client-side login gate.
  - Restricted strictly to: `johnfrancis.flores22@gmail.com`.
  - Default PIN: `1234` (or `admin2026`).
  - Session state is securely saved in `sessionStorage` (stays authenticated until you close the browser tab).

---

© 2026 John Francis A. Flores. All rights reserved.
