# Manorum Business Group Website

A professional, multi-business website showcasing three distinct ventures:
1. **Manorum** - Back Office Business Support & Administration
2. **FreeVend Advertisers** - Smart Vending Solutions
3. **Kovai Thangam** - Jewellery and Finance

## Features

- 🎨 Elegant, refined design with gold accents
- 📱 Fully responsive (mobile, tablet, desktop)
- 🛒 E-commerce product showcases for all three businesses
- ✨ Smooth animations and transitions
- 🎯 Interactive navigation with scroll effects
- 💼 Professional service packages and pricing
- 📞 Comprehensive contact information

## File Structure

```
multi-business-website/
├── index.html          # Main HTML file
├── styles.css          # All styling and design
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── assets/
    └── images/
        └── business-cards.png
```

## Deployment to GitHub

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name it (e.g., "manorum-business-website")
4. Make it public
5. Don't initialize with README (we have one)
6. Click "Create repository"

### Step 2: Upload Files

**Option A: Using GitHub Web Interface (Easiest)**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from the website folder
3. Write a commit message (e.g., "Initial website upload")
4. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
cd multi-business-website
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Select "/ (root)" folder
5. Click "Save"
6. Your website will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Customization Guide

### Changing Colors

Edit the CSS variables in `styles.css` (lines 1-10):
```css
:root {
    --color-primary: #c9a55c;    /* Main gold color */
    --color-secondary: #8b6f47;  /* Secondary brown */
    --color-accent: #d4af37;     /* Accent gold */
    /* ... more colors ... */
}
```

### Updating Contact Information

Edit the contact details in `index.html`:
- Search for phone numbers: `+91 95859 63980`
- Search for emails: `Ramkumar.manorum@gmail.com`
- Update addresses in the contact section

### Modifying Products/Services

Each business section has an e-store. Find the `.products-grid` div for each section and modify the `.product-card` elements:

```html
<div class="product-card">
    <div class="product-badge">Label</div>
    <h4>Product Name</h4>
    <p class="product-price">₹999<span>/month</span></p>
    <ul class="product-features">
        <li>Feature 1</li>
        <li>Feature 2</li>
    </ul>
    <button class="btn-product">Action</button>
</div>
```

### Adding Images

1. Add your images to the `assets/images/` folder
2. Reference them in HTML: `<img src="assets/images/your-image.jpg" alt="Description">`
3. Or use as CSS background: `background-image: url('assets/images/your-image.jpg');`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

- Images are optimized for web
- CSS and JS are minified for production
- Lazy loading implemented for images
- Smooth scroll behavior for better UX

## SEO Optimization

The website includes:
- Semantic HTML5 elements
- Meta descriptions (add in `<head>`)
- Descriptive alt tags for images
- Clean URL structure
- Mobile-responsive design

### Recommended Meta Tags to Add

Add these to the `<head>` section of `index.html`:

```html
<meta name="description" content="Manorum Business Group - Excellence in Back Office Support, Smart Vending Solutions, and Gold Jewellery Finance in Coimbatore">
<meta name="keywords" content="virtual assistant, vending machine, gold jewellery, Coimbatore, business support">
<meta name="author" content="Manorum Business Group">
<meta property="og:title" content="Manorum Business Group">
<meta property="og:description" content="Three ventures, one vision: Excellence">
<meta property="og:image" content="assets/images/business-cards.png">
```

## Maintenance

### Regular Updates
- Update product prices and features seasonally
- Add new testimonials if available
- Keep contact information current
- Add new products/services as they launch

### Monitoring
- Use Google Analytics (add tracking code to `<head>`)
- Monitor GitHub Pages deployment status
- Check mobile responsiveness regularly

## Support

For technical issues or customization help:
- Email: Ramkumar.manorum@gmail.com
- Phone: +91 95859 63980

## License

© 2026 Manorum Business Group. All rights reserved.

---

**Built with:** HTML5, CSS3, JavaScript
**Design Philosophy:** Elegant, refined, and distinctive
**Last Updated:** January 2026
