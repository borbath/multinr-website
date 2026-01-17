# MultiNr Website

Professional responsive website for MultiNr POSM manufacturer.

## Features

- Bilingual support (Romanian/English)
- Product showcase (HDF, Metal, Cardboard, Counter displays)
- Gallery with lightbox functionality
- Contact form with local storage
- Admin dashboard for form submissions
- Fully responsive design
- Smooth animations

## Deployment Instructions

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub:
   - Go to https://github.com/new
   - Name it `multinr-website` (or any name you prefer)
   - Make it public
   - Don't initialize with README (we already have one)

2. Push your code to GitHub:
   ```bash
   cd C:/Users/Borbi/multinr-website
   git remote add origin https://github.com/YOUR_USERNAME/multinr-website.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Click "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

4. Your site will be live at:
   `https://YOUR_USERNAME.github.io/multinr-website/`

### Option 2: Custom Domain

After deploying to GitHub Pages, you can add a custom domain:

1. In GitHub repository Settings > Pages
2. Under "Custom domain", enter your domain (e.g., www.multinr.com)
3. Add a CNAME record in your domain's DNS settings pointing to:
   `YOUR_USERNAME.github.io`

## Contact Form Setup

The contact form currently uses FormSubmit.co. To activate it:

1. Open `index.html`
2. Find line 1517: `https://formsubmit.co/ajax/YOUR_EMAIL@example.com`
3. Replace `YOUR_EMAIL@example.com` with `borbath@multinr.ro`

## Admin Dashboard

Access the admin dashboard by clicking the "Admin" button in the bottom left corner.
Form submissions are stored locally in the browser's localStorage.

## Local Development

Simply open `index.html` in your browser to view the website locally.

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- No external dependencies

## License

© Copyright multinr.ro, România, 2025. All rights reserved.
