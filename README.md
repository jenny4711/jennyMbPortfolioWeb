# Jenny Lee - iOS Developer Portfolio

A modern, responsive portfolio website showcasing iOS development skills and published App Store applications.

## Features

- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Responsive**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Interactive**: Smooth scrolling, hover effects, and animated elements
- **Project Showcase**: Detailed project cards with images, descriptions, and App Store links
- **Skills Visualization**: Animated skill bars showing technical proficiency
- **Contact Form**: Functional contact form that opens email client
- **Performance Optimized**: Debounced scroll events and efficient animations
- **Multilingual**: Korean/English language toggle functionality

## Projects Featured

1. **Habbits** - iOS Habit Tracker (SwiftUI + SwiftData)
2. **FaithLog** - Christian Journaling App (SwiftUI + SwiftData + Node.js)
3. **Daymoji** - Emoji Journal (React Native + TypeScript)
4. **CookTok** - Grocery Management with AI (React Native + Google Gemini)

## Technologies Used

- HTML5
- CSS3 (with CSS Grid, Flexbox, and animations)
- Vanilla JavaScript (ES6+)
- Font Awesome icons
- Google Fonts (Inter)

## File Structure

```
jennyMbPortfolioWeb/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── image/              # Project images and logos
    ├── habbitsLogo.png
    ├── faithLogLogo.png
    ├── daymojiLogo.png
    ├── cooktokLogo.png
    ├── myImg.png       # Profile image
    └── ... (other project images)
```

## How to Use

1. **Local Development**: Simply open `index.html` in a web browser
2. **Web Hosting**: Upload all files to your web hosting service
3. **GitHub Pages**: Push to a GitHub repository and enable GitHub Pages

## Customization

### Updating Contact Information
Edit the contact section in `index.html`:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</div>
```

### Adding New Projects
Add a new project card in the projects section:
```html
<div class="project-card">
    <div class="project-header">
        <img src="image/your-logo.png" alt="Your App Logo" class="project-logo">
        <div class="project-info">
            <h3 class="project-title">Your App</h3>
            <p class="project-category">App Category</p>
        </div>
    </div>
    <!-- Add more content -->
</div>
```

### Modifying Skills
Update the skills section in `index.html` and adjust the `data-width` attributes for skill bars.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Lazy loading animations
- Debounced scroll events
- Optimized images
- Minimal JavaScript footprint
- CSS-only animations where possible

## SEO Optimized

- Semantic HTML structure
- Meta tags for social sharing
- Alt text for all images
- Proper heading hierarchy
- Fast loading times

## License

This portfolio template is free to use and modify for personal and commercial projects.
