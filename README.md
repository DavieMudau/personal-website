# Personal Website Portfolio

A modern, responsive, and professional personal website built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**
- Clean and professional UI/UX
- Smooth animations and transitions
- Gradient backgrounds and modern styling

📱 **Fully Responsive**
- Desktop, tablet, and mobile optimized
- Mobile-first approach
- Hamburger menu for mobile navigation

🎯 **Complete Sections**
- Hero/Home section with call-to-action buttons
- Professional introduction
- Technical and soft skills showcase
- Featured projects with descriptions
- Education and certifications timeline
- Work experience timeline
- Contact form with social media links
- Professional footer

⚙️ **Interactive Features**
- Smooth scroll navigation
- Mobile menu toggle
- Active navigation highlighting
- Scroll-to-top button
- Contact form integration
- Intersection observer for animations

## Sections Included

1. **Navigation Bar** - Sticky navigation with mobile toggle
2. **Hero Section** - Eye-catching introduction with CTAs
3. **About Me** - Professional introduction with statistics
4. **Skills** - Technical and soft skills display
5. **Projects** - Featured projects showcase with details
6. **Education** - Timeline of education with details
7. **Certifications** - Professional certifications timeline
8. **Work Experience** - Career timeline with accomplishments
9. **Contact** - Contact information and message form
10. **Footer** - Copyright and credits

## Getting Started

### Prerequisites
- A modern web browser
- Text editor (VS Code recommended)
- Git (for version control)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/DavieMudau/personal-website.git
cd personal-website
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

3. Visit `http://localhost:8000` in your browser

## Customization

### Personal Information
1. Update name and title in the hero section
2. Modify professional introduction in the about section
3. Update skills lists (technical and soft)
4. Add your projects with descriptions
5. Fill in education details
6. Add certifications
7. Update work experience
8. Change contact email and social media links

### Styling
- Colors can be customized in `styles.css` CSS variables (`:root`)
- Font families can be changed in the body selector
- Spacing and layout can be adjusted as needed

### Adding Projects
To add more projects, duplicate the project card structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">Project Name</div>
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <a href="#" class="project-link">View Project <i class="fas fa-external-link-alt"></i></a>
    </div>
</div>
```

## Deployment

### GitHub Pages
1. Push code to GitHub
2. Go to repository settings
3. Scroll to GitHub Pages section
4. Select main branch as source
5. Site will be live at `https://yourusername.github.io/personal-website`

### Other Hosting Options
- **Vercel**: Connect GitHub repo and deploy
- **Netlify**: Drag and drop folder or connect GitHub
- **GitHub Pages**: Built-in GitHub feature

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **JavaScript (Vanilla)** - No frameworks needed
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (if added)

## File Structure
```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## Features Explained

### Mobile Navigation
- Hamburger menu appears on screens below 768px
- Smooth toggle animation
- Closes automatically when a link is clicked

### Active Navigation Highlighting
- Current section is highlighted in navigation
- Updates as you scroll
- Works with smooth scrolling

### Contact Form
- Opens default email client
- Pre-fills subject and message
- Can be integrated with backend services

### Scroll Animations
- Elements fade in when they come into view
- Uses Intersection Observer API
- Smooth and performant

## Tips for Optimization

1. **Add Real Project Images**: Replace placeholder text with actual project images
2. **Optimize Images**: Compress images for faster loading
3. **Add CV Download**: Include a downloadable PDF resume
4. **SEO Optimization**: Add meta tags for better search visibility
5. **Form Integration**: Connect contact form to email service (Formspree, Emailjs, etc.)
6. **Analytics**: Add Google Analytics or similar

## License

This project is open source and available under the MIT License.

## Author

**Davie Mudau**
- GitHub: [@DavieMudau](https://github.com/DavieMudau)
- Website: [Your Website](https://daviemudau.github.io/personal-website)

## Support

If you have questions or need help, feel free to:
1. Check existing GitHub issues
2. Create a new GitHub issue
3. Reach out via email

## Changelog

### Version 1.0.0
- Initial release
- All core sections implemented
- Fully responsive design
- Mobile navigation
- Contact form
- Smooth animations

---

**Built with ❤️ using HTML, CSS, and JavaScript**