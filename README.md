# Portfolio Website

A modern, responsive portfolio website showcasing your skills, projects, and experience.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Dark/Light Theme Toggle**: Automatic system theme detection with manual toggle option
- **Interactive Elements**: Hover effects, smooth scrolling, and animated sections
- **Contact Form**: Functional contact form with validation
- **Social Media Integration**: Links to your social profiles
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## Sections

1. **Hero Section**: Eye-catching introduction with your name and title
2. **About**: Personal information and statistics
3. **Skills**: Showcase your technical skills with animated progress bars
4. **Projects**: Featured projects with descriptions and tech stacks
5. **Contact**: Contact form and contact information
6. **Footer**: Social links and copyright

## Customization

### Personal Information
1. Replace placeholder text in `index.html`:
   - Update "Your Name" with your actual name
   - Change the title/subtitle to match your profession
   - Update the about section with your story
   - Replace contact information

### Images
- Replace placeholder images with your actual photos:
  - Profile picture: Update the `src` attribute in the hero section
  - About section image: Replace the about image URL
  - Project images: Add your project screenshots

### Social Links
Update social media links in the hero section and footer:
```html
<a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
<a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
```

### Projects
Replace the sample projects with your actual work:
1. Update project images
2. Change project titles and descriptions
3. Update technology tags
4. Add links to live demos and GitHub repositories

### Skills
Modify the skills section to reflect your expertise:
1. Update skill categories
2. Change skill descriptions
3. Replace technology tags

### Colors and Styling
The portfolio includes both light and dark themes with a purple gradient accent. To customize:

#### Theme Colors
The website uses CSS custom properties (variables) for theming:
- Light theme: Clean whites and grays with purple accents
- Dark theme: Dark backgrounds with white text and purple accents

#### Customizing Colors
1. Open `styles.css`
2. Find the `:root` and `[data-theme="dark"]` sections at the top
3. Modify the CSS custom properties:
   ```css
   :root {
     --gradient-primary: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
     /* ... other variables */
   }
   ```

#### Theme Toggle
The theme toggle button:
- Automatically detects system preference (light/dark)
- Remembers user's manual selection in localStorage
- Provides smooth transitions between themes
- Located as a floating button in the bottom-right corner

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations, Custom Properties/Variables)
- JavaScript (ES6+, Theme Toggle, Local Storage)
- Font Awesome Icons
- Google Fonts (Poppins)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. **Download/Clone** the portfolio files
2. **Customize** the content with your information
3. **Replace** placeholder images with your photos
4. **Test** the website by opening `index.html` in a browser
5. **Deploy** to your preferred hosting platform

## Deployment Options

### GitHub Pages
1. Create a new repository
2. Upload your files
3. Go to Settings > Pages
4. Select source branch
5. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Sign up at netlify.com
2. Drag and drop your portfolio folder
3. Your site will be deployed instantly

### Vercel
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy with one click

## Performance Tips

- Optimize images (use WebP format when possible)
- Minify CSS and JavaScript for production
- Use a CDN for external libraries
- Enable gzip compression on your server

## SEO Optimization

- Update the `<title>` tag with your name and profession
- Add meta description in the `<head>` section:
  ```html
  <meta name="description" content="Your Name - Full Stack Developer portfolio showcasing web development projects and skills">
  ```
- Add relevant keywords
- Use semantic HTML structure
- Ensure fast loading times

## Accessibility

The website includes:
- Semantic HTML elements
- Alt text for images
- Keyboard navigation support
- High contrast colors
- Responsive text sizing

## Contact Form

The contact form includes:
- Client-side validation
- Success/error notifications
- Responsive design

**Note**: To make the contact form fully functional, you'll need to:
1. Set up a backend service (e.g., Formspree, Netlify Forms)
2. Update the form action attribute
3. Configure email handling

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check the code comments for guidance
2. Refer to this README
3. Search online for HTML/CSS/JavaScript tutorials

---

**Happy coding!** 🚀