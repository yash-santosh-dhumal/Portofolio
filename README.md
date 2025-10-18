# Yash Santosh Dhumal - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and professional profile.

## Features

- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop devices
- **Modern UI/UX**: Clean, light, and cool-themed design with green, white, and beige colors
- **Smooth Animations**: Fade-in effects, scroll animations, and smooth transitions
- **Interactive Elements**: Hover effects, animated skill bars, and dynamic navigation
- **Project Showcase**: Detailed project cards with technology tags and links
- **Contact Form**: Functional contact form with validation and success messaging
- **Performance Optimized**: Fast loading and smooth scrolling experience

## Sections

1. **Home**: Professional introduction with profile image
2. **About**: Educational background and career overview
3. **Skills**: Technical skills with visual progress indicators
4. **Projects**: Featured projects with descriptions and tech stack
5. **Contact**: Contact form and social media links

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Poppins)

## Projects Featured

1. **Medibot** - Healthcare automation system
2. **AI Learning Path Generator** - Personalized learning tool
3. **Resume Analyzer** - Resume optimization tool
4. **Indian States Travels Fare Analysis** - Data visualization dashboard

## Technical Skills Highlighted

- MERN Stack (MongoDB, Express.js, React.js, Node.js)
- General Artificial Intelligence
- Database Management and Design

## Customization Guide

### Updating Personal Information

1. **Contact Details**: Edit the email, phone, and location in the Contact section of `index.html`
2. **Social Media Links**: Update the href attributes in the social-links section
3. **Profile Image**: Replace the image in the `images` folder

### Adding New Projects

To add a new project, copy this template in the projects section:

```html
<div class="project-card">
    <div class="project-header">
        <div class="project-icon">
            <i class="fas fa-icon-name"></i>
        </div>
        <h3>Project Name</h3>
    </div>
    <p class="project-description">
        Project description here...
    </p>
    <div class="project-tech">
        <span class="tech-tag">Technology 1</span>
        <span class="tech-tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
        <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
    </div>
</div>
```

### Modifying Colors

Update the CSS variables in `styles.css`:

```css
:root {
    --primary-green: #2ecc71;
    --dark-green: #27ae60;
    --light-green: #a8e6cf;
    --beige: #f5f5dc;
    --light-beige: #faf8f3;
}
```

### Adding New Skills

Add a new skill card in the skills section:

```html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fab fa-skill-icon"></i>
    </div>
    <h3>Skill Name</h3>
    <p>Skill description</p>
    <div class="skill-bar">
        <div class="skill-progress" style="width: XX%"></div>
    </div>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Optimization Tips

1. Compress images before uploading
2. Use lazy loading for images if adding more content
3. Minify CSS and JavaScript for production
4. Enable caching for static assets
5. Use a CDN for external libraries

## Future Enhancements

- [ ] Add blog section
- [ ] Integrate with backend for contact form
- [ ] Add dark mode toggle
- [ ] Include testimonials section
- [ ] Add downloadable resume
- [ ] Implement project filtering
- [ ] Add loading animations
- [ ] Include achievement badges

## Deployment

To deploy this website:

1. **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages
2. **Netlify**: Drag and drop the folder to Netlify
3. **Vercel**: Import the project from GitHub
4. **Traditional Hosting**: Upload all files via FTP

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── README.md           # Documentation
│
└── images/             # Image assets
    └── [profile photo]
```

## Credits

- Icons: Font Awesome
- Fonts: Google Fonts (Poppins)
- Design: Custom

## License

This project is open source and available for personal use.

## Contact

For questions or suggestions, please reach out through the contact form on the website.

---

Built with ❤️ by Yash Santosh Dhumal

