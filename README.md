# Evolved Tech Stack - Company Website

A modern, responsive company website for Evolved Tech Stack showcasing software development services and published mobile applications.

## 🚀 Live Site

Visit: [evolvedtechstack.co.za](https://evolvedtechstack.co.za)

## 📱 Featured Apps

- **ToDo** - Productivity & Task Management App
  - [Google Play Store](https://play.google.com/store/apps/details?id=com.ets.todo)

- **Particles (Live)** - Neon Arcade Dodger Game
  - [Google Play Store](https://play.google.com/store/apps/details?id=com.ets.live)
  - [Game Website](https://livegameapp.co.za/)

## 🛠️ Tech Stack

- Pure HTML5, CSS3, JavaScript
- No build tools required
- Optimized for GitHub Pages hosting

## 📦 Deployment to GitHub Pages

### Option 1: Direct GitHub Pages (Recommended)

1. Push this repository to GitHub
2. Go to repository **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/evolved-tech-stack-site/`

### Option 2: Custom Domain Setup

To use your custom domain `evolvedtechstack.co.za`:

1. In your domain DNS settings (GoDaddy), update the A record:
   - Delete the existing WebsiteBuilder A record
   - Add these A records pointing `@` to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

2. Update the CNAME record for `www`:
   - Point `www` to `yourusername.github.io`

3. In GitHub repository **Settings** → **Pages**:
   - Enter `evolvedtechstack.co.za` in the "Custom domain" field
   - Enable "Enforce HTTPS"

4. Create a `CNAME` file in the repository root containing:
   ```
   evolvedtechstack.co.za
   ```

## 📁 Project Structure

```
evolved-tech-stack-site/
├── index.html          # Main HTML file
├── styles.css          # All styles
├── script.js           # JavaScript functionality
├── Logo.jpeg           # Company logo
├── Cover_Image.jpeg    # Header/cover image
├── CNAME              # Custom domain (create after setup)
└── README.md          # This file
```

## 🎨 Brand Colors

- **Primary Purple**: `#7c5cbf`
- **Accent Orange/Gold**: `#f5a623`
- **Background Dark**: `#1a1625`

## 📞 Contact

- **Email**: szarath@gmail.com
- **Phone**: 082 693 1251
- **LinkedIn**: [linkedin.com/in/szarath-kumar](https://linkedin.com/in/szarath-kumar)
- **GitHub**: [github.com/szarath](https://github.com/szarath)

## 📄 License

© 2026 Evolved Tech Stack. All rights reserved.
