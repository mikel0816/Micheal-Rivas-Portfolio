# Michael Rivas — AI Automation Specialist | Portfolio

A single-page portfolio site showcasing AI automation projects, built with plain HTML/CSS/JS — no frameworks, no build step.

## 🚀 Quick Start

Just open `index.html` in any browser. No installation, no dependencies, no server required.

```bash
open index.html        # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

To serve it locally (optional):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 📁 Project Structure

```
.
├── index.html      # Entire site — markup, styles, and scripts in one file
└── README.md        # This file
```

## 🧩 Sections

| Section | Description |
|---|---|
| **Hero** | Name, title, intro, and key stats (projects shipped, tools used, automation speed) |
| **About** | Bio and skills list |
| **Projects** | 6 detailed project case studies with tags and flow summaries |
| **In Action** | 7 embedded YouTube demo videos of the automations running |
| **Contact** | Email, LinkedIn, GitHub links + a contact form (front-end only, no backend wired up) |

### Featured Projects
1. BrightSmile Dental — AI-Powered Clinic Management System
2. AI Weekly Sales Report Bot
3. Glow Skin Derma Booking Bot
4. Real Estate Leads Automation
5. GlowLab — Automated Ecommerce Marketing System
6. GlowSkin Derma — AI Chatbot & Voice Agent System (Facebook Messenger + Retell AI voice)

## 🛠️ Tech Stack

- **HTML5 / CSS3** — single-file, no build tools
- **Vanilla JavaScript** — scroll-reveal animations, video upload handlers, contact form interaction
- **Google Fonts** — Space Mono (mono/code accents) + Syne (display headings)
- **YouTube embeds** — for the "In Action" demo videos

## ✏️ Editing

Everything lives in `index.html`:

- **Styles** — in the `<style>` block at the top
- **Content** — in the HTML body, organized by `<section>` (`#hero`, `#about`, `#projects`, `#work`, `#contact`)
- **Behavior** — in the `<script>` block at the bottom (scroll reveal, video upload preview, form submit handler)

To add a new project: copy a `.project-card` block in the `#projects` section and update the number, title, description, and tags.

To add a new demo video: copy a `.video-card` block in the `#work` section and swap in the new YouTube embed URL (`https://www.youtube.com/embed/<VIDEO_ID>`).

## 📬 Contact

- Email: michealrivas0897@gmail.com
- LinkedIn: linkedin.com/in/michaelrivas
- GitHub: github.com/michaelrivas

## 📄 License

© 2025 Michael Rivas. All rights reserved.
