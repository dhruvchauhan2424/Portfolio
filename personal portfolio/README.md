# Dhruv Chauhan - Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript featuring a dark theme with neon/tech aesthetics, smooth animations, and professional design.

## 🚀 Features

### ✨ Design & Theme
- **Dark Theme**: Modern dark background with neon accents
- **Gradient Elements**: Beautiful gradient text and buttons
- **Glassmorphism**: Translucent card designs with backdrop blur
- **Neon Effects**: Glowing borders and hover animations
- **Responsive Design**: Mobile-first approach with breakpoints

### 🎯 Sections
1. **Hero Section**: Animated background with particles/waves, floating card
2. **About Section**: Modern card design with education and interests
3. **Projects Section**: Interactive project cards with hover effects
4. **Skills Section**: Animated progress bars and tech stack icons
5. **Resume Section**: Download CV functionality
6. **Contact Section**: Stylish contact form with validation
7. **Footer**: Social media links with hover effects

### 🎨 Animations & Interactions
- **Scroll Animations**: Fade-in, slide-in, and scale effects
- **Hover Effects**: Interactive hover states for all elements
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Parallax Effects**: Subtle background movement on scroll
- **Skill Progress**: Animated progress bars
- **Mobile Navigation**: Hamburger menu for mobile devices

### 📱 Responsive Features
- **Mobile-First**: Optimized for all screen sizes
- **Touch-Friendly**: Mobile-optimized interactions
- **Flexible Grids**: CSS Grid layouts that adapt to screen size
- **Typography Scaling**: Responsive font sizes

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern CSS with custom properties, Grid, Flexbox
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Poppins and Roboto typography

## 📁 File Structure

```
personal-portfolio/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local development server (optional but recommended)

### Installation

1. **Clone or Download** the project files to your local machine
2. **Open** `index.html` in your web browser
3. **Or** use a local server for development:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

### Customization

#### 1. Personal Information
Edit `index.html` to update:
- Your name and title
- About section content
- Project details and descriptions
- Contact information
- Social media links

#### 2. Styling
Modify `styles.css` to customize:
- **Colors**: Update CSS custom properties in `:root`
- **Fonts**: Change Google Fonts imports
- **Animations**: Adjust timing and effects
- **Layout**: Modify grid and flexbox properties

#### 3. Functionality
Update `script.js` to:
- Modify animation triggers
- Add new interactive features
- Customize form handling
- Enhance scroll effects

## 🎨 Customization Guide

### Color Scheme
The website uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #00d4ff;      /* Main accent color */
    --secondary-color: #ff6b6b;    /* Secondary accent */
    --accent-color: #4ecdc4;       /* Additional accent */
    --dark-bg: #0a0a0a;           /* Main background */
    --darker-bg: #050505;          /* Secondary background */
    --card-bg: rgba(255, 255, 255, 0.05); /* Card background */
}
```

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style the section in `styles.css`
3. Add animation classes and JavaScript functionality

### Project Cards
To add new projects, duplicate the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-overlay">
            <div class="project-links">
                <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
        <div class="image-placeholder">
            <i class="fas fa-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <a href="#" class="btn btn-project">View Project</a>
    </div>
</div>
```

### Skills & Progress Bars
Add new skills by duplicating the skill item structure:

```html
<div class="skill-item">
    <div class="skill-info">
        <span class="skill-name">Skill Name</span>
        <span class="skill-percentage">85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress" data-percentage="85"></div>
    </div>
</div>
```

## 📱 Browser Support

- **Chrome**: 60+
- **Firefox**: 55+
- **Safari**: 12+
- **Edge**: 79+

## 🔧 Performance Features

- **Lazy Loading**: Images and animations load on scroll
- **Optimized Animations**: CSS transforms and opacity changes
- **Efficient Selectors**: Minimal DOM queries
- **Smooth Scrolling**: Native smooth scroll behavior

## 📧 Contact Form

The contact form includes:
- **Form Validation**: Client-side validation
- **Success/Error Messages**: Toast notifications
- **Loading States**: Visual feedback during submission
- **Responsive Design**: Works on all devices

**Note**: The form currently simulates submission. To make it functional, you'll need to:
1. Set up a backend server
2. Configure form handling
3. Add email service integration

## 🎯 SEO & Accessibility

- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Alt Text**: Descriptive alt attributes for images
- **ARIA Labels**: Accessible navigation and form elements
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: Proper semantic structure

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `master`)

### Netlify
1. Drag and drop project folder to Netlify
2. Configure custom domain (optional)
3. Enable form handling if needed

### Vercel
1. Connect GitHub repository to Vercel
2. Deploy automatically on push
3. Configure environment variables if needed

## 🔮 Future Enhancements

- **Dark/Light Theme Toggle**
- **Blog Section Integration**
- **Portfolio Gallery**
- **Testimonials Section**
- **Analytics Integration**
- **Multi-language Support**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve this portfolio template.

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Built with ❤️ by Dhruv Chauhan**

*Perfect for showcasing your skills to potential employers and clients!*
