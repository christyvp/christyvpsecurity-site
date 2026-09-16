# christyvp.security

Personal site for Christy VanderPloeg, Independent Security Consultant.
Live at: christyvpsecurity.com

## Files

christyvpsecurity-site/
├── index.html        ← main page (edit content here)
├── css/style.css     ← all styles (always dark)
├── js/main.js        ← mobile menu + smooth scroll
└── images/
    └── christy.jpg   ← ADD YOUR PHOTO HERE

## How to edit content

1. Go to the GitHub repo
2. Click index.html
3. Click the ✏️ pencil icon (top right)
4. Find the section to update — look for comments like TESTIMONIALS, PROJECTS
5. Edit the text
6. Click Commit changes

GitHub Pages auto-deploys in ~30 seconds.

## Add a photo

Upload a headshot to the images/ folder named christy.jpg.
Portrait ratio (taller than wide) looks best in the circle frame.
The site shows "CV" initials as a fallback until a photo is added.

## Update the LinkedIn URL

In index.html, find https://linkedin.com and replace with the actual LinkedIn profile URL.

## Hosting — GitHub Pages

1. Go to the repo on GitHub
2. Settings → Pages
3. Source → Deploy from branch → select main → / (root) → Save
4. GitHub gives a temporary URL: christyvp.github.io/christyvpsecurity-site

## Connect the custom domain (Squarespace)

1. In GitHub Pages settings, add custom domain: christyvpsecurity.com → Save
2. Log into Squarespace → Domains → christyvpsecurity.com → DNS Settings
3. Add these 4 A records:
   - Name: @ / Value: 185.199.108.153
   - Name: @ / Value: 185.199.109.153
   - Name: @ / Value: 185.199.110.153
   - Name: @ / Value: 185.199.111.153
4. Add 1 CNAME record:
   - Name: www / Value: christyvp.github.io
5. Back in GitHub Pages → check Enforce HTTPS

Takes 10-30 minutes to go live.

## Contact info

- Email: christy@christyvpsecurity.com
- Booking: https://calendar.app.google/y3G7U5zF6wvPr6P68