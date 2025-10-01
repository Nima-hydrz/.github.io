# Personal Portfolio

A modern and responsive portfolio website to showcase your skills, projects, and contact information.

## Features

- 🎨 Modern and beautiful design
- 📱 Fully responsive (Responsive Design)
- 🌐 English language support (LTR)
- ⚡ Smooth and engaging animations
- 📧 Interactive contact form
- 🎯 Smooth navigation (Smooth Scrolling)
- 📊 Skills and statistics display
- 🔗 Social media links

## Sections Available

### 🏠 Home Section (Hero Section)
- Personal introduction
- Call-to-action buttons
- Profile image

### 👤 About Me Section
- Personal description
- Key statistics and numbers
- Experience and skills

### 🛠️ Skills Section
- Frontend skills
- Backend skills
- Tools and technologies

### 📁 Projects Section
- Showcase completed projects
- Technologies used
- View and code links

### 📞 Contact Section
- Contact information
- Contact form
- Social media links

## Technologies Used

- **HTML5** - Page structure
- **CSS3** - Styling and design
- **JavaScript** - Interactions and animations
- **Font Awesome** - Icons
- **Google Fonts** - Inter font family

## How to Use

1. Download the files
2. Open `index.html` in your browser
3. Replace personal information in the files

## Customization

### Changing Personal Information

#### In `index.html`:

```html
<!-- Change name -->
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>

<!-- Change job title -->
<p class="hero-subtitle">Web Developer & Designer</p>

<!-- Change description -->
<p class="hero-description">
    Write your personal description here...
</p>
```

#### Change contact information:

```html
<!-- Email -->
<p>your.email@example.com</p>

<!-- Phone -->
<p>+1 (555) 123-4567</p>

<!-- Location -->
<p>New York, USA</p>
```

#### Change social media links:

```html
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
<a href="https://linkedin.com/in/yourusername" class="social-link">
    <i class="fab fa-linkedin"></i>
</a>
```

### Changing Colors

In `styles.css` you can change the main colors:

```css
:root {
    --primary-color: #3498db;
    --secondary-color: #f39c12;
    --accent-color: #667eea;
    --text-color: #2c3e50;
}
```

### Adding New Projects

To add a new project, copy this code in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="view-link" class="btn btn-small">View</a>
            <a href="code-link" class="btn btn-small btn-outline">Code</a>
        </div>
    </div>
</div>
```

## Advanced Features

### Animations
- Typing animation for main title
- Counter animation for statistics
- Fade-in animation for elements
- Parallax effect for hero section

### Interactions
- Interactive mobile menu
- Contact form with validation
- Scroll to top button
- Active navigation link highlighting

### Optimization
- Responsive design for all devices
- SEO optimization
- Fast loading
- Cross-browser compatibility

## Browser Support

- Chrome (latest version)
- Firefox (latest version)
- Safari (latest version)
- Edge (latest version)

## License

This project is released under the MIT License.

## Contributing

If you have suggestions for improving this portfolio, I'd love to hear them!

---

**Note**: This portfolio is designed as a base template and you can customize it according to your needs.