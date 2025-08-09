# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations and interactive elements.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **SEO Friendly**: Semantic HTML structure
- **Fast Loading**: Optimized for performance

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Change "Full Stack Developer & Designer" to your title
- **Description**: Update the hero description to match your expertise
- **About Section**: Modify the about text to reflect your background
- **Stats**: Update the statistics (years experience, projects, clients)
- **Contact Information**: Replace with your actual contact details

### 2. Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### 3. Skills Section

Update the skills to match your expertise:

- **Frontend**: HTML5, CSS3, JavaScript, React, Vue.js, etc.
- **Backend**: Node.js, Python, MongoDB, Express.js, etc.
- **Tools**: Git, Docker, AWS, Firebase, etc.

### 4. Contact Information

Update the contact section with your details:

- Email address
- Phone number
- Location
- Social media links (GitHub, LinkedIn, Twitter, Instagram)

### 5. Color Scheme

To change the color scheme, modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --light-bg: #f8fafc;
}
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: ES6+ for interactivity
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Features Explained

### Navigation
- Fixed navigation bar with smooth scrolling
- Mobile hamburger menu
- Active section highlighting

### Hero Section
- Gradient background with animated elements
- Call-to-action buttons
- Floating profile card animation

### Projects
- Hover effects on project cards
- Technology tags
- Live demo and code links

### Skills
- Interactive skill cards
- Categorized by frontend, backend, and tools
- Hover animations

### Contact Form
- Form validation
- Success/error notifications
- Responsive design

## 🚀 Getting Started

1. **Download/Clone** the files to your local machine
2. **Customize** the content as per the guide above
3. **Test** the website locally by opening `index.html` in a browser
4. **Deploy** to your preferred hosting service

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your project folder
2. Get instant deployment
3. Custom domain support

### Vercel
1. Connect your GitHub repository
2. Automatic deployments
3. Custom domain support

## 📝 Customization Tips

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Add JavaScript functionality if needed

### Changing Animations
- Modify CSS keyframes in `styles.css`
- Adjust JavaScript animation timing in `script.js`

### Adding More Projects
- Copy the project card structure
- Update content and links
- Add appropriate icons

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📞 Support

If you need help customizing your portfolio:

1. Check the customization guide above
2. Review the code comments
3. Test on different devices and browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Coding! 🎉**

Feel free to modify and customize this portfolio to make it truly yours. Don't forget to add your own projects, skills, and personal touch! 