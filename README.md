# Athletic Edge Recruiting Website

Simple, fast, professional. Built to convert.

## Quick Deploy to Vercel

1. **Push to GitHub**
   ```bash
   cd landing
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up with GitHub
   - Click "Add New..." → "Project"
   - Import your GitHub repo
   - Click "Deploy"

That's it. Your site will be live in about 30 seconds.

## Custom Domain

After deploying:
1. Go to your project settings on Vercel
2. Click "Domains"
3. Add your custom domain
4. Follow the instructions to update DNS records

## Editing the Site

- `index.html` — Main landing page
- `services.html` — Services & pricing
- `about.html` — About us
- `styles.css` — All styles (edited once, applies everywhere)

## Images

The site uses free images from Unsplash. Replace these with your own for production:
- Replace image URLs in the `<img class="hero-img" ...>` tags
- Recommended: Use locally hosted images in an `/images` folder

## Forms

The forms currently show an alert on submit. To make them functional:

1. **Formspree** (easiest):
   - Sign up at [formspree.io](https://formspree.io)
   - Create a form, get your URL
   - Change `<form>` to: `<form action="YOUR_FORMSPREE_URL" method="POST">`

2. **Netlify Forms** (if hosting on Netlify):
   - Add `netlify` attribute to form: `<form name="athlete" netlify>`

3. **Custom backend**:
   - Point `action` to your own endpoint
   - Handle form data however you want

## Support

Questions? Reach out — we're happy to help with tweaks and changes.