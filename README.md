# Smitkumar Patel - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing software engineering skills, professional experience, and projects.

## 🌟 Features

- **Responsive Design** - Optimized for all devices and screen sizes
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Sections** - About, Experience, Projects, Skills, and Contact
- **GitHub Integration** - Direct links to repositories and GitHub stats
- **Company Information** - Detailed company descriptions with official website links
- **Contact Form** - Functional contact form for inquiries
- **SEO Optimized** - Meta tags and structured content for better search visibility

## 🚀 Live Demo

**GitHub Pages:** [https://smitkumarpatel4.github.io/smit-patel-portfolio/](https://smitkumarpatel4.github.io/smit-patel-portfolio/)

## 📋 Table of Contents

- [Features](#-features)
- [Live Demo](#-live-demo)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Local Development](#-local-development)
- [Deployment Options](#-deployment-options)
- [Customization](#-customization)
- [Contributing](#-contributing)
- [License](#-license)

## 🛠️ Technologies Used

- **Frontend:**
  - HTML5
  - CSS3 (with Flexbox and Grid)
  - JavaScript (ES6+)
  - Font Awesome Icons
  - Google Fonts (Inter)

- **Development:**
  - Node.js (for local server)
  - Git (version control)

## 📁 Project Structure

```
smit-patel-portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   └── images/             # Image assets (if any)
├── server.js               # Local development server
├── package.json            # Node.js dependencies
└── README.md              # Project documentation
```

## 💻 Local Development

### Prerequisites
- Node.js (v14 or higher)
- Git

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/smitkumarpatel4/smit-patel-portfolio.git
   cd smit-patel-portfolio
   ```

2. **Install dependencies (optional - for local server):**
   ```bash
   npm install
   ```

3. **Run locally:**
   
   **Option 1: Using Node.js server**
   ```bash
   node server.js
   ```
   Then open [http://localhost:3000](http://localhost:3000)

   **Option 2: Direct file access**
   - Simply open `index.html` in your browser
   - Or use any local server like Live Server (VS Code extension)

## 🌐 Deployment Options

### 1. GitHub Pages (Recommended)

**Automatic Deployment:**
1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **master** branch and **/(root)** folder
5. Click **Save**
6. Your site will be available at: `https://smitkumarpatel4.github.io/smit-patel-portfolio/`

**Manual Deployment:**
```bash
# Create and switch to gh-pages branch
git checkout -b gh-pages

# Push to GitHub
git push origin gh-pages

# Go back to master branch
git checkout master
```

### 2. Netlify

1. **Drag & Drop Method:**
   - Go to [netlify.com](https://netlify.com)
   - Drag your project folder to the deploy area
   - Your site will be live instantly

2. **Git Integration:**
   - Connect your GitHub repository
   - Netlify will automatically deploy on every push

### 3. Vercel

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Deploy:**
   ```bash
   vercel
   ```

### 4. Firebase Hosting

1. **Install Firebase CLI:**
   ```bash
   npm install -g firebase-tools
   ```

2. **Initialize and deploy:**
   ```bash
   firebase login
   firebase init hosting
   firebase deploy
   ```

### 5. Traditional Web Hosting

Upload the following files to your web server:
- `index.html`
- `assets/` folder (entire directory)
- `package.json` (optional)

## 🎨 Customization

### Updating Personal Information

1. **Edit `index.html`:**
   - Update name, title, and contact information
   - Modify experience details
   - Add/remove projects
   - Update skills section

2. **Edit `assets/css/styles.css`:**
   - Change colors, fonts, and styling
   - Modify layout and animations
   - Update responsive breakpoints

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation menu if needed

### Adding Projects

1. Copy an existing project card structure
2. Update project details, links, and technologies
3. Add any new technology tags to the skills section

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (320px - 767px)

## 🔧 Performance Optimization

- **Minified CSS and JS** (for production)
- **Optimized images** (WebP format recommended)
- **Lazy loading** for images
- **Preload critical resources**

## 🚀 SEO Features

- Meta tags for social sharing
- Open Graph tags
- Twitter Card support
- Semantic HTML structure
- Alt text for images
- Structured data (schema.org)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- GitHub for hosting
- All contributors and supporters

---

**Last Updated:** January 2025
**Version:** 1.0.0
