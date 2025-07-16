# Shahroze Abbas - Data Science Portfolio

[![Live Site](https://img.shields.io/badge/Live%20Site-Visit%20Portfolio-00ff9d)](https://shahrozeabbas.github.io)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20with-GitHub%20Pages-blue)](https://pages.github.com/)

A modern, responsive portfolio website showcasing data science, bioinformatics, and AI/ML projects. Built with clean HTML5, CSS3, and vanilla JavaScript for optimal performance and GitHub Pages compatibility.

## 🌟 Features

### 🎨 Modern Design
- **Dark Theme**: Professional GitHub-inspired dark color scheme
- **Terminal Aesthetic**: Monospace fonts and terminal-style elements
- **Responsive Design**: Mobile-first approach with seamless adaptation across devices
- **Smooth Animations**: Fade-in effects and hover transitions for enhanced UX

### 🧭 Navigation
- **Fixed Navigation Bar**: Always accessible navigation with active section highlighting
- **Mobile Menu**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections

### 📱 Sections

#### 🏠 Hero Section
- Animated typing effect with terminal-style introduction
- Professional subtitle highlighting expertise areas
- Social media links (GitHub, LinkedIn, Email, Resume)

#### 👨‍💻 About Section
- Personal introduction and mission statement
- Research focus and current interests cards
- Technology stack display

#### 🛠️ Skills Section
- **4 Skill Categories**:
  - Programming Languages (Python, R, SQL, JavaScript)
  - AI/ML Frameworks (PyTorch, Scikit-learn, TensorFlow, Transformers)
  - Data Science Tools (Pandas, NumPy, Jupyter, Plotly)
  - Bioinformatics (Scanpy, Seurat, Snakemake, Nextflow)
- Visual progress bars for proficiency levels

#### 🚀 Projects Section
- **Featured Projects**:
  - **Single-Cell Data Preprocessing**: Comprehensive RNA-seq preprocessing pipeline
  - **Pseudotime Analysis**: Advanced cellular differentiation trajectory analysis
  - **Fraud Detection Analysis**: ML-based fraud detection with ensemble methods
- Technology tags for each project
- Direct links to Jupyter notebook analyses

#### 💼 Experience Section
- Timeline-style work history display
- Detailed role descriptions and achievements
- Visual timeline with connecting elements

#### 🎓 Education Section
- Interactive degree cards with terminal-style reveals
- Detailed academic information including GPA and thesis topics
- Expandable content for comprehensive details

#### 📧 Contact Section
- Professional contact form with topic categorization
- Responsive form validation
- Terminal-themed styling consistent with overall design

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Icons**: Font Awesome 6.0
- **Fonts**: Google Fonts (Space Mono, Inter)
- **Hosting**: GitHub Pages
- **Performance**: Optimized for fast loading and SEO

## 📂 Project Structure

```
shahrozeabbas.github.io/
├── index.html              # Main portfolio page
├── README.md               # Project documentation
└── notebooks/              # Data science project notebooks
    ├── 01_preprocessing.html    # Single-cell preprocessing
    ├── 02_pseudotime.html      # Pseudotime analysis
    └── FraudAnalysis.html      # Fraud detection analysis
```

## 🚀 Getting Started

### Prerequisites
- Git installed on your machine
- A GitHub account
- Basic knowledge of HTML/CSS (for customization)

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shahrozeabbas/shahrozeabbas.github.io.git
   cd shahrozeabbas.github.io
   ```

2. **Open in browser**:
   ```bash
   # On macOS
   open index.html
   
   # On Windows
   start index.html
   
   # On Linux
   xdg-open index.html
   ```

3. **Local server (optional)**:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### GitHub Pages Deployment

1. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to Pages section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

2. **Access your site**:
   - Visit `https://yourusername.github.io`
   - Changes are automatically deployed on push to main branch

## 🎨 Customization Guide

### Personal Information

1. **Update Hero Section** (`index.html` lines 430-450):
   ```html
   <h1>Hi, I'm <span class="accent">Your Name</span></h1>
   <p class="subtitle">Your Expertise Areas</p>
   ```

2. **Social Links** (`index.html` lines 452-465):
   ```html
   <a href="https://github.com/yourusername" class="social-link">
   <a href="https://linkedin.com/in/yourusername" class="social-link">
   <a href="mailto:your.email@example.com" class="social-link">
   ```

3. **Skills Section** (`index.html` lines 500-650):
   - Update skill names and proficiency percentages
   - Add or remove skill categories as needed

4. **Projects Section** (`index.html` lines 652-750):
   - Replace project descriptions and links
   - Update technology tags
   - Link to your own project files

5. **Experience Section** (`index.html` lines 752-820):
   - Update job titles, companies, and descriptions
   - Modify timeline periods

### Styling Customization

1. **Color Scheme** (`index.html` lines 10-20):
   ```css
   :root {
       --bg-primary: #0d1117;    /* Main background */
       --accent: #00ff9d;        /* Accent color */
       --text-primary: #e6edf3;  /* Main text */
       /* Modify these values for different themes */
   }
   ```

2. **Typography**:
   - Change fonts in Google Fonts link
   - Update font-family declarations in CSS

3. **Layout**:
   - Modify grid layouts and responsive breakpoints
   - Adjust spacing and sizing variables

### Adding New Sections

1. **HTML Structure**:
   ```html
   <section id="new-section" class="section">
       <div class="container">
           <div class="section-content">
               <h2 class="section-title">> section_title:</h2>
               <!-- Your content here -->
           </div>
       </div>
   </section>
   ```

2. **Navigation Update**:
   ```html
   <li><a href="#new-section" class="nav-link">New Section</a></li>
   ```

## 📊 Performance Features

- **Optimized Loading**: Minimal external dependencies
- **Mobile Performance**: Responsive images and efficient CSS
- **SEO Friendly**: Semantic HTML and meta tags
- **Accessibility**: ARIA labels and keyboard navigation support

## 🔧 Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/shahrozeabbas/shahrozeabbas.github.io/issues).

## 📬 Contact

**Shahroze Abbas**
- Portfolio: [shahrozeabbas.github.io](https://shahrozeabbas.github.io)
- LinkedIn: [linkedin.com/in/shahrozeabbas](https://linkedin.com/in/shahrozeabbas)
- Email: [your.email@example.com](mailto:your.email@example.com)
- GitHub: [@shahrozeabbas](https://github.com/shahrozeabbas)

---

⭐ **If you found this portfolio template helpful, please give it a star!**

## 🔄 Recent Updates

- ✅ Added comprehensive navigation system
- ✅ Integrated project showcases with notebook links
- ✅ Enhanced responsive design for mobile devices
- ✅ Added skills visualization with progress bars
- ✅ Implemented smooth animations and transitions
- ✅ Created professional experience timeline
- ✅ Added interactive education section

---

*Built with ❤️ using modern web technologies*