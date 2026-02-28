# JTr Marketing Agency Website

A modern, high-converting website for a Kenya-based marketing agency specializing in youth marketing, brand activations, and experiential campaigns.

## Features

- **Modern Dark Theme** with electric orange accent colors
- **Fully Responsive** mobile-first design
- **Smooth Animations** and scroll effects
- **Glassmorphism UI** elements
- **Interactive Statistics** counter animations
- **Contact Form** with validation
- **3 Complete Pages**: Home, About, Services

## Pages

### Homepage (index.html)
- Hero section with bold headline and CTAs
- Animated statistics showcase
- Services overview grid
- Why Choose Us section
- Case study highlights
- Contact form

### About Page (about.html)
- Company story and background
- Mission & Vision statements
- Core values showcase
- Founder profile
- Team member grid
- Office location

### Services Page (services.html)
Detailed information for 6 core services:
1. Experiential Marketing & Roadshows
2. Influencer & Creator Marketing
3. Billboard & Outdoor Advertising
4. Campus Activations
5. Digital Campaign Strategy
6. Corporate Brand Launches

Each service includes:
- What it is
- How it works
- Who it's for
- Real-world examples
- Expected ROI

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, animations
- **Vanilla JavaScript** - No dependencies, lightweight and fast
- **Mobile-First** - Responsive design approach

## Setup Instructions

1. Extract all files to your web server directory
2. Ensure the folder structure is maintained:
   ```
   agency/
   ├── index.html
   ├── about.html
   ├── services.html
   ├── assets/
   │   ├── css/
   │   │   └── style.css
   │   ├── js/
   │   │   └── main.js
   │   └── images/
   ```
3. Open index.html in a web browser or deploy to a web server

## Customization

### Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
    --primary: #FF6B35;      /* Main accent color */
    --secondary: #F7931E;    /* Secondary accent */
    --dark: #0a0a0a;         /* Background */
}
```

### Content
- Update contact information in all HTML files
- Replace placeholder images with actual brand photos
- Modify case studies with real campaign data
- Update team member information

### Contact Form
The form currently shows an alert on submission. To connect to a backend:
1. Edit the form submission handler in `assets/js/main.js`
2. Add your API endpoint or email service
3. Implement server-side validation

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight: ~50KB total (HTML + CSS + JS)
- No external dependencies
- Optimized animations
- Fast load times

## Future Enhancements

- Add actual campaign photos/videos
- Integrate with CRM for form submissions
- Add blog section for case studies
- Implement portfolio gallery
- Add testimonials section
- Connect to Google Maps API for location

## License

© 2024 JTr Marketing Agency. All rights reserved.

## Support

For questions or support, contact: hello@jtr.co.ke
