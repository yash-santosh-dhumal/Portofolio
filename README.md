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

1. **Home**: Professional introduction with achievements
2. **About**: Educational background and focus areas
3. **Skills**: Technical skills grouped by focus
4. **Projects**: Featured projects with descriptions and tech stack
5. **Education**: Academic timeline with scores
6. **Certifications**: Highlighted certificates and dates
7. **Hackathons**: Participation highlights
8. **Contact**: Contact form and social media links

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Poppins)

## Projects Featured

1. **Medi-Bot** - End-to-end medical chatbot
2. **Automated Resume Relevance Check System** - AI scoring system
3. **AI Learning Path Generator** - Personalized learning tool

## Technical Skills Highlighted

- MERN Stack (MongoDB, Express.js, React.js, Node.js)
- Next.js and modern web frameworks
- LangChain, Gemini, Pinecone, and vector databases
- Data visualization with Power BI

## Customization Guide

### Updating Personal Information

1. **Contact Details**: Edit the email, phone, and location in the Contact section of `index.html`
2. **Social Media Links**: Update the href attributes in the social-links section
3. **Profile Image**: Replace `images/yash-profile.svg` with your real photo (recommended file: `images/yash-profile.jpg`) and update `index.html` accordingly.

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
    <div class="chip-group">
        <span class="chip">Technology 1</span>
        <span class="chip">Technology 2</span>
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

1. **GitHub Pages**: Push to a GitHub repository, enable GitHub Pages, and use the included workflow in `.github/workflows/pages.yml`.
2. **Netlify**: Drag and drop the folder to Netlify.
3. **Vercel**: Import the project from GitHub.
4. **Traditional Hosting**: Upload all files via FTP.

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

