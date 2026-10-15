Jisna Raj P P — Portfolio

Personal portfolio website of Jisna Raj P P, QA + Data Analyst based in Kerala, India.

Live site: https://jisnaraj.github.io (update this link if you use a different repo name or domain)

About this site

A single-page, responsive portfolio that presents my background in software QA and data analysis, along with selected projects.

Sections

About: short introduction and quick facts
Skills: QA & Testing, Data & Analytics, Engineering & Tools, Languages
Experience: timeline of roles (Yente AI, Edure, Guest Lecturer at IPT & Govt. Polytechnic College)
Projects: 15 projects, filterable by QA Testing, Data & Analytics and Engineering, with dashboard and output screenshots (click an image to enlarge)
Education: B.Tech, Diploma and certifications
Contact: email, phone, LinkedIn, GitHub and a contact form
Built with
HTML5, CSS3 and vanilla JavaScript (no frameworks, no build step)
Google Fonts: Source Serif 4 and IBM Plex Sans
Photo and project screenshots are embedded in index.html as base64, so the site is one self-contained file

Features: responsive layout for desktop and mobile, sticky navigation with mobile menu, scroll-reveal animations (disabled for visitors who prefer reduced motion), project category filter, screenshot lightbox, and a contact form that opens the visitor's email app (mailto:).

Project structure
.
├── index.html    # the complete website (HTML, CSS, JS and images)
├── jisna.png     # original profile photo (not required by the site)
└── README.md
Run locally

No installation needed. Download or clone the repository and double-click index.html to open it in your browser.

Optionally, serve it locally:

bash
python -m http.server 8000
# then open http://localhost:8000
Deploy with GitHub Pages
Create a public repository named Jisnaraj.github.io (or any name).
Upload index.html (and this README) to the repository root.
Go to Settings → Pages, set Source to Deploy from a branch, choose the main branch and / (root), then save.
The site goes live within a few minutes at https://jisnaraj.github.io.

To update the site, replace index.html in the repository. Changes appear after a short rebuild.

Customising

All content lives in index.html:

Colours: edit the CSS variables at the top of the <style> block (:root).
Text, roles and projects: edit the matching HTML sections (#about, #experience, #projects, and so on).
Add a project: copy an existing <div class="project-row" data-cat="..."> block. Use qa, data or eng as the category.
Contact details: search for the email, phone and profile links and replace them.
Contact
Email: jisnaraj13@gmail.com
Phone: +91 62381 63677
LinkedIn: https://www.linkedin.com/in/jisna-raj-p-p-42716a252/
GitHub: https://github.com/Jisnaraj
