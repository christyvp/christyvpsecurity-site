# christyvp.security

Personal site for Christy VanderPloeg, Independent Security Consultant.

## Files

```
christyvp-site/
├── index.html        ← main page (edit content here)
├── css/style.css     ← all styles (always dark)
├── js/main.js        ← mobile menu + smooth scroll
└── images/
    └── christy.jpg   ← ADD YOUR PHOTO HERE
```

## How to edit content

1. Go to your GitHub repo
2. Click `index.html`
3. Click the ✏️ pencil icon (top right)
4. Find the section you want — look for comments like `<!-- TESTIMONIALS -->`, `<!-- PROJECTS -->`
5. Edit the text
6. Click **Commit changes**

Cloudflare auto-deploys in ~30 seconds.

## Add your photo

Upload your headshot to the `images/` folder named `christy.jpg`.
Portrait ratio (taller than wide) looks best in the circle frame.
The site shows "CV" initials as a fallback until you add it.

## Update your LinkedIn URL

In `index.html`, find `https://linkedin.com` and replace with your actual LinkedIn profile URL.

## Deploy to Cloudflare Pages

1. Push this folder to a **private** GitHub repo (e.g. `christyvp-site`)
2. Go to dash.cloudflare.com → Workers & Pages → Create → Pages
3. Connect GitHub → select your repo
4. Leave all build settings blank (plain HTML, no build step needed)
5. Click Deploy

## Connect your domain

- If bought through Cloudflare: Pages → Custom Domains → Add → `christyvpsecurity.com` (auto-connects)
- If at Squarespace/Google Domains: update nameservers there to point to Cloudflare

## Contact info already set

- Email: christy@christyvpsecurity.com
- Booking: https://calendar.app.google/y3G7U5zF6wvPr6P68
