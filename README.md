# Marp Presentation: Advanced Analytics Platform

A professional product documentation presentation created with Marp (Markdown Presentation Ecosystem).

## 📋 Overview

This presentation demonstrates:
- Custom theme styling with CSS
- Page numbering and footers
- Background images on specific slides
- Mathematical equations using KaTeX
- Code syntax highlighting
- Responsive tables and layouts
- Professional slide transitions

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Or use npx without installing
npx @marp-team/marp-cli@latest slides.md
```

## 📦 Build Commands

```bash
# Start development server with live preview
npm start

# Build HTML version
npm run build

# Export to PDF
npm run pdf

# Export to PowerPoint
npm run pptx

# Watch mode (auto-rebuild on changes)
npm run watch

# Export to all formats
npm run export:all
```

## 📁 Project Structure

```
Marp/
├── slides.md           # Main presentation file
├── images/             # Image assets
│   ├── background.jpg  # Background image for slides
│   └── README.md       # Image guidelines
├── themes/             # Custom theme files (optional)
├── package.json        # Build configuration
├── .gitignore         # Git ignore rules
└── README.md          # This file
```

## ✨ Features Included

### 1. Custom Theme
- Gaia theme as base
- Custom CSS styling for sections
- Gradient backgrounds
- Professional color scheme

### 2. Page Numbering
- Automatic page numbers on all slides
- Custom footer with email

### 3. Background Images
- Slide 4 features a custom background
- Image directives for proper positioning

### 4. Mathematical Equations
- KaTeX support for inline and block math
- Algorithmic complexity examples: $O(\log n)$
- Statistical formulas

### 5. Custom Styling
- Multiple slide classes (title, custom-bg)
- Color-coded headers
- Styled code blocks and tables
- Professional blockquotes

## 👤 Author

**Anand S**
- Email: 23f2005347@ds.study.iitm.ac.in
- Role: Technical Documentation Specialist

## 📝 Presentation Contents

1. **Title Slide** - Introduction with custom gradient background
2. **Table of Contents** - Navigation overview
3. **Platform Overview** - Key features and benefits
4. **Architecture Components** - Technical stack details
5. **Performance Metrics** - Mathematical formulas and complexity
6. **Getting Started** - Installation and setup guide
7. **API Reference** - Code examples and endpoints
8. **Best Practices** - Optimization strategies
9. **Troubleshooting** - Common issues and solutions
10. **Additional Topics** - Deployment, scaling, support

## 🎨 Customization

### Modify Theme Colors

Edit the `<style>` section in `slides.md`:

```css
section {
  background-color: #your-color;
}

h1 {
  color: #your-heading-color;
}
```

### Add More Slides

Use `---` to separate slides:

```markdown
---

## New Slide Title

Content goes here
```

### Change Background Images

Replace `images/background.jpg` with your own image, or specify different images:

```markdown
<!-- _class: custom-bg -->
![bg](images/your-image.jpg)
```

## 🔧 VS Code Integration

### Install Marp Extension

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "Marp for VS Code"
4. Install by Marp team

### Preview Presentation

- Press `F1` and type "Marp: Toggle Preview"
- Or use `Ctrl+K V` for side-by-side preview

## 📤 Exporting

### HTML (Default)
Best for web hosting and GitHub Pages:
```bash
npm run build
```

### PDF
Best for sharing and printing:
```bash
npm run pdf
```

### PowerPoint
Best for editing in Microsoft PowerPoint:
```bash
npm run pptx
```

## 🌐 Hosting Options

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Set source to `main` branch, `/dist` folder
4. Access at: `https://[username].github.io/[repo]/slides.html`

### Netlify
1. Connect your repository
2. Set build command: `npm run build`
3. Set publish directory: `dist`

### Self-hosted
Simply copy `dist/slides.html` to your web server.

## 📚 Resources

- [Marp Official Documentation](https://marpit.marp.app/)
- [Marp CLI Documentation](https://github.com/marp-team/marp-cli)
- [Marp VS Code Extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [KaTeX Documentation](https://katex.org/)

## 🐛 Troubleshooting

### Images Not Loading
- Ensure images are in the `images/` folder
- Use relative paths from `slides.md`
- Add `--allow-local-files` flag for PDF export

### Build Errors
- Check Node.js version: `node --version`
- Clear cache: `rm -rf node_modules && npm install`
- Use verbose flag: `marp --verbose slides.md`

## 📄 License

MIT License - Feel free to use and modify for your own presentations.

## 🤝 Contributing

To contribute or suggest improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**Last Updated:** December 7, 2025
**Version:** 1.0.0
