# Memory Lab AI Website

A professional website for Memory Lab AI - an AI research laboratory focused on improving long-term memory of AI models and building creative content for users.

## 🌐 Live Website

This website is designed to be hosted on GitHub Pages.

## 📋 Features

- **Modern, Responsive Design**: Beautiful UI that works on all devices
- **Smooth Animations**: Scroll-based animations and smooth navigation
- **Complete Pages**:
  - Home page with hero section
  - About section
  - Research focus areas
  - Contact information
  - Privacy Policy (required for Apple Developer Program)
  - Terms of Service

## 🚀 Deploying to GitHub Pages

### Method 1: Using GitHub Settings (Recommended)

1. **Push this code to your GitHub repository**:
   ```bash
   git add .
   git commit -m "Add Memory Lab AI website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be available at: `https://[your-username].github.io/mla_website/`

### Method 2: Custom Domain (Optional)

If you want to use a custom domain like `memorylabai.com`:

1. Add a `CNAME` file to your repository with your domain name:
   ```bash
   echo "memorylabai.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. Configure your domain's DNS settings:
   - Add a CNAME record pointing to `[your-username].github.io`
   - Or add A records pointing to GitHub's IP addresses

3. In GitHub Settings > Pages, add your custom domain

## 📁 File Structure

```
mla_website/
├── index.html          # Main homepage
├── privacy.html        # Privacy policy page
├── terms.html          # Terms of service page
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md          # This file
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --secondary-color: #8b5cf6;
    /* ... other colors */
}
```

### Updating Content

- **Company Information**: Edit text in `index.html`
- **Contact Details**: Update email addresses in `index.html`
- **Privacy Policy**: Customize `privacy.html` as needed
- **Terms of Service**: Customize `terms.html` as needed

## 📱 Apple Developer Program Requirements

This website meets Apple Developer Program requirements by including:

- Company name and description
- Contact information
- Privacy Policy page
- Terms of Service page
- Professional presentation

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript
- Google Fonts (Inter font family)

## 📝 License

Copyright © 2025 Memory Lab AI. All rights reserved.

## 📧 Contact

For questions or support, contact:
- General: contact@memorylabai.com
- Support: support@memorylabai.com

## 🔄 Local Development

To view the website locally:

1. Simply open `index.html` in your web browser, or
2. Use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```
3. Open `http://localhost:8000` in your browser
