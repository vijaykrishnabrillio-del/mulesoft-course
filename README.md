# MuleSoft Learning Guide - HTML Documentation

## 📚 Overview

This folder contains the complete HTML documentation for the 60-Day MuleSoft Learning Program. All content has been converted to interactive HTML pages for easy navigation and learning.

---

## 🌐 How to Use

### Option 1: Open Locally
1. Open `index.html` in your web browser
2. Navigate through the learning materials
3. Bookmark for easy access

### Option 2: Host on Web Server
```bash
# Using Python
cd HTML
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server HTML -p 8000

# Using PHP
cd HTML
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

---

## 📁 Structure

```
HTML/
├── index.html                  # Main landing page
├── getting-started.html        # Setup and prerequisites guide
├── resources.html              # Learning resources and references
├── practice-exam.html          # Practice certification questions
│
├── week-01/                    # Week 1 (Fully detailed)
│   ├── index.html             # Week 1 overview
│   ├── day-01.html            # Introduction to MuleSoft
│   ├── day-02.html            # Anypoint Studio Setup
│   ├── day-03.html            # Application Structure
│   ├── day-04.html            # First Mule Application
│   ├── day-05.html            # Mule Events & Messages
│   ├── day-06.html            # Basic Flow Control
│   └── day-07.html            # Week 1 Review & Quiz
│
├── week-02/ to week-09/        # Weeks 2-9 (Index pages)
│   └── index.html             # Week overview with topic outline
│
└── assets/
    ├── css/
    │   ├── style.css          # Main stylesheet
    │   └── content.css        # Content page styles
    ├── js/                    # JavaScript files (if any)
    └── images/                # Images and diagrams
```

---

## ✨ Features

### 🎨 Professional Design
- Responsive layout (mobile, tablet, desktop)
- Modern gradient headers
- Clean, readable typography
- Syntax-highlighted code blocks

### 🧭 Easy Navigation
- Breadcrumb navigation
- Previous/Next buttons on each page
- Week overview pages
- Quick links to resources

### 📖 Complete Content
- **Week 1:** 7 fully detailed lessons
- **Weeks 2-9:** Outlines and topic breakdowns
- Getting Started guide
- Resource library
- Practice exam questions

### 💻 Code Examples
- Syntax highlighting with Highlight.js
- Copy-friendly code blocks
- XML, Java, DataWeave, and more

---

## 📊 Content Status

### ✅ Fully Complete
- **Main Pages:** index.html, getting-started.html, resources.html, practice-exam.html
- **Week 1 (Days 1-7):** Complete with full content from markdown sources
- **Weeks 2-9:** Index pages with topic outlines

### 📝 Content Sources
- Week 1 content converted from: `../weeks/week-01/*.md`
- Week 2-9 outlines from: `../weeks/week-0X/README.md`
- Resources from: `../resources/`
- Practice exam from: `../quizzes/`

---

## 🎯 Pages Included

### Main Navigation
1. **Home (index.html)**
   - Course overview
   - All 9 weeks listed
   - Quick stats and features
   - Clear learning path

2. **Getting Started (getting-started.html)**
   - Prerequisites
   - Installation steps (Java, Studio, etc.)
   - Setup verification checklist
   - Troubleshooting

3. **Resources (resources.html)**
   - Official documentation links
   - Video tutorials
   - Development tools
   - Quick reference tables
   - Common troubleshooting

4. **Practice Exam (practice-exam.html)**
   - Sample questions with answers
   - Exam format information
   - Study tips
   - Certification resources

### Week 1 Content (7 Pages)
Each day includes:
- Learning objectives
- Detailed explanations
- Code examples
- Hands-on exercises
- Knowledge checks
- Navigation to next/previous

### Weeks 2-9 (8 Index Pages)
Each week includes:
- Week overview
- Topic breakdown
- Daily objectives
- Links to source materials

---

## 🛠️ Technical Details

### Technologies Used
- **HTML5:** Semantic markup
- **CSS3:** Modern styling with gradients, flexbox, grid
- **Font Awesome:** Icons
- **Highlight.js:** Code syntax highlighting
- **No JavaScript frameworks:** Pure HTML/CSS for simplicity

### Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers

### Responsive Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px

---

## 🔄 Regenerating HTML

If you update the markdown source files and want to regenerate the HTML:

```powershell
# Run the generator script
.\generate-html-complete.ps1
```

This will:
1. Convert all Week 1 markdown files to HTML
2. Create/update week index pages
3. Preserve existing main pages
4. Update navigation links

---

## 🎨 Customization

### Changing Colors
Edit `assets/css/style.css`:
```css
:root {
    --primary-color: #00a0df;      /* Main blue */
    --secondary-color: #003865;    /* Dark blue */
    --accent-color: #ff6b35;       /* Orange */
}
```

### Adding Custom Pages
1. Create new HTML file in HTML/
2. Use existing pages as templates
3. Link from index.html or navigation

### Modifying Styles
- `assets/css/style.css` - Main layout and components
- `assets/css/content.css` - Content page specific styles

---

## 📦 Deployment

### GitHub Pages
1. Push HTML folder to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select main branch, /HTML folder
4. Access at `https://username.github.io/repository/`

### Netlify
1. Drag and drop HTML folder to Netlify
2. Or connect to GitHub repository
3. Build command: none (static files)
4. Publish directory: HTML

### AWS S3
```bash
aws s3 sync HTML/ s3://your-bucket-name/ --acl public-read
```

---

## 🐛 Known Issues

### Markdown Conversion Limitations
- Complex markdown tables may need manual formatting
- Some advanced markdown features converted to basic HTML
- Image paths may need adjustment if images are added

### Solutions
- Most content displays correctly
- Code examples properly highlighted
- Navigation works seamlessly
- Week 1 fully functional

---

## 📝 License

This documentation is created for educational purposes.

---

## 🆘 Support

### Issues?
1. Check browser console for errors
2. Verify all files present in HTML folder
3. Re-run `generate-html-complete.ps1` if needed
4. Open index.html directly (not through file explorer on some systems)

### Questions?
- Review the main README.md in project root
- Check source markdown files in ../weeks/
- Refer to resources.html for additional help

---

## ✅ Quick Start Checklist

- [ ] All HTML files generated successfully
- [ ] index.html opens in browser
- [ ] Week 1 pages display content correctly
- [ ] Navigation links work
- [ ] Code syntax highlighting appears
- [ ] Responsive design works on mobile
- [ ] Ready to learn MuleSoft!

---

**Happy Learning! Open `index.html` to get started! 🚀**
