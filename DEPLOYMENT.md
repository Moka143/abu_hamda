# Development and Deployment Guide

This repository contains the Rimal Strategic Advisory website - a static HTML website that can be easily deployed using GitHub Pages.

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Moka143/abu_hamda.git
   cd abu_hamda
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```
   
   This will start a local server at `http://localhost:8000` and automatically open it in your browser.

### Development Server Options

- `npm start` - Start server and open in browser
- `npm run dev` - Start server with cache disabled for development
- `npm run build` - No build step required (static files)

## 🌐 Deployment

### GitHub Pages (Automatic)

The website is automatically deployed to GitHub Pages when changes are pushed to the main branch.

**Live URL**: https://moka143.github.io/abu_hamda

### Manual Deployment

If you need to deploy manually:

```bash
npm run deploy
```

This will deploy the current state to the `gh-pages` branch.

### Other Deployment Options

This static website can be deployed to any static hosting service:

- **Netlify**: Connect your GitHub repository for automatic deployments
- **Vercel**: Import project from GitHub
- **Firebase Hosting**: Use Firebase CLI
- **AWS S3**: Upload files to S3 bucket with static website hosting

## 🛠️ GitHub Copilot Integration

This repository is optimized for development with GitHub Copilot:

1. **Automated Deployment**: GitHub Actions automatically deploy changes
2. **Development Server**: Simple npm scripts for local development  
3. **Clear Structure**: Well-organized code structure for Copilot understanding
4. **Documentation**: Clear documentation for Copilot context

### Working with Copilot

When making changes:
1. Use GitHub Codespaces or local development environment
2. Make changes to HTML, CSS, or JavaScript files
3. Test locally with `npm start`
4. Commit and push - deployment happens automatically
5. GitHub Copilot can help with code suggestions and improvements

## 📁 Project Structure

```
├── index.html          # Main website page
├── styles.css          # Website styling
├── script.js           # JavaScript functionality
├── ahmed.jpeg          # Team member photo
├── rimallogo.jpg       # Company logo
├── package.json        # Node.js dependencies and scripts
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment
└── README.md           # This file
```

## 🔧 Configuration

### GitHub Pages Setup

1. Go to repository Settings > Pages
2. Set Source to "GitHub Actions"  
3. The deployment workflow will handle the rest

### Environment Variables

No environment variables are required for this static website.

## 📞 Support

For technical questions about deployment or development, please contact:
- Email: ahmad@rimalstrategic.com
- LinkedIn: [Rimal Strategic Advisory](https://www.linkedin.com/company/rimal-strategic-advisory/)

---

**Rimal Strategic Advisory** - Strategic guidance, delivery & implementation oversight and scalable solutions for startups.