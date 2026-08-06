# Basketball Portfolio Website

A modern, visually engaging basketball portfolio website built with HTML, CSS, and JavaScript. This website showcases an athlete's skills, achievements, and gallery with smooth animations and responsive design.

## 📋 Features

### Sections Included
- **Navigation Bar** - Fixed header with smooth scrolling, active link highlighting, and responsive hamburger menu
- **Hero Section** - Full-screen layout with player name, tagline, call-to-action button, and animated background
- **About Me** - Personal background, career goals, and stat cards
- **Skills/Stats** - Animated progress bars for 6 key basketball skills
- **Highlights** - Achievement cards with badges (Championship, All-Star, Record, MVP, International, Community)
- **Gallery** - 8-item grid with professional basketball images, hover effects, and lightbox modal
- **Contact** - Contact form with validation, contact details, and social media links
- **Footer** - Professional footer with copyright information

### Design Features
- **Color Palette**: Dark theme (#1a1a1a) with bold orange accents (#FF6B35, #F7931E)
- **Animations**: Smooth fade-in, slide-in, and scale animations throughout
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Elements**:
  - Hover effects on cards and buttons
  - Progress bar animations on scroll
  - Lightbox gallery with arrow and keyboard navigation
  - Form validation with real-time feedback
  - Scroll progress indicator
  - Parallax effects

## 🚀 Getting Started

### Quick Start
1. Extract the zip file to your desired location
2. Open `index-updated.html` in your web browser (this version includes the basketball images)
3. Or open `index.html` for the version with placeholder gradients

### File Structure
```
basketball-portfolio/
├── index.html                 # Main HTML file (with gradient placeholders)
├── index-updated.html         # HTML file with real basketball images
├── css/
│   └── styles.css            # Complete stylesheet
├── js/
│   ├── script.js             # JavaScript for index.html
│   └── script-updated.js     # JavaScript for index-updated.html
├── images/
│   ├── gallery-1.jpg         # Professional basketball action shot
│   ├── gallery-2.jpg         # Player dribbling
│   ├── gallery-3.jpg         # Three-point shot
│   ├── gallery-4.jpg         # Championship celebration
│   ├── gallery-5.jpg         # Defensive stance
│   ├── gallery-6.jpg         # Slam dunk
│   ├── gallery-7.jpg         # Player portrait
│   └── gallery-8.jpg         # Team huddle
└── README.md                 # This file
```

## 🎨 Customization

### Change Player Information
Edit the following in `index-updated.html`:
- Player name in the hero section
- About me text
- Contact information
- Social media links

### Modify Colors
Update the CSS variables in `css/styles.css`:
```css
:root {
    --primary-dark: #1a1a1a;
    --primary-orange: #FF6B35;
    --secondary-orange: #F7931E;
    --accent-white: #ffffff;
}
```

### Update Skills
Modify the skill cards in the Skills section with different percentages and skill names.

### Add More Gallery Images
1. Add new images to the `images/` folder
2. Add new gallery items in the HTML:
```html
<div class="gallery-item">
    <img class="gallery-image" src="images/your-image.jpg" alt="Description">
    <div class="gallery-overlay">
        <i class="fas fa-search-plus"></i>
    </div>
</div>
```

## 📱 Responsive Breakpoints

- **Desktop**: 1440px and above
- **Tablet**: 768px to 1439px
- **Mobile**: 480px to 767px
- **Small Mobile**: Below 480px

## ✨ Interactive Features

### Navigation
- Smooth scrolling between sections
- Active link highlighting based on scroll position
- Mobile hamburger menu with smooth transitions
- Keyboard navigation support

### Gallery
- Click any image to open the lightbox
- Navigate with arrow buttons or keyboard arrows
- Press Escape to close
- Smooth zoom and fade animations

### Contact Form
- Real-time validation
- Email format checking
- Success/error notifications
- Form reset after submission

### Animations
- Scroll-triggered animations for cards
- Parallax background effect
- Progress bars animate on view
- Smooth hover transitions

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📦 Dependencies

- Font Awesome 6.4.0 (for icons)
- No other external dependencies required

## 🎯 Performance Optimizations

- Lazy loading for images
- Intersection Observer for scroll animations
- Debounced scroll events
- Optimized CSS animations
- Minimal JavaScript footprint

## 📄 License

This template is free to use and modify for personal and commercial projects.

## 🤝 Support

For issues or questions about the template, please refer to the code comments throughout the files.
