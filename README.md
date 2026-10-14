# HEXA Plumbing & Gas - Website

A modern, responsive website for HEXA Plumbing & Gas, a professional plumbing and gas services company based in Manchester, UK.

## Overview

This website provides a comprehensive online presence for HEXA Plumbing & Gas, showcasing their services, portfolio of completed works, customer reviews, and contact information. The site is designed to be fast, accessible, and user-friendly across all devices.

## Features

### 🎨 Modern Design
- Clean, professional interface with navy blue and green color scheme
- Responsive layout that adapts seamlessly to desktop, tablet, and mobile devices
- Smooth animations and transitions for enhanced user experience

### 📱 Mobile-Optimized
- Hamburger menu navigation for mobile devices
- Touch-friendly buttons and interactive elements
- Optimized image viewing with fullscreen lightbox gallery
- Hidden thumbnails on mobile for better image visibility

### 🖼️ Portfolio Gallery
- Project showcase with multiple images per project
- Interactive lightbox for full-screen image viewing
- Navigation arrows for easy browsing
- Organized by project type (bathroom installations, boiler replacements, emergency repairs, etc.)

### 💼 Services Section
- Comprehensive list of plumbing and gas services offered
- Clear service descriptions with icons
- Direct quote request links for each service

### ⭐ Customer Reviews
- Authentic customer testimonials
- Star ratings display
- Clean, card-based layout

### 📞 Contact Options
- Multiple contact methods (phone, WhatsApp, email)
- Integrated contact form with validation
- Social media links
- Business location and service area information

### ♿ Accessibility Features
- Semantic HTML5 structure
- ARIA labels and roles for screen readers
- Keyboard navigation support
- Skip-to-content link
- Proper heading hierarchy
- Alt text for images

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties (CSS variables)
- **JavaScript** - Interactive features (lightbox, form validation, mobile menu)
- **Font Awesome 6.5.2** - Icon library
- **Google Fonts (Manrope)** - Typography
- **Schema.org** - Structured data for local business SEO

## File Structure

```
plum1/
├── index.html          # Main homepage
├── privacy.html        # Privacy policy page
├── terms.html          # Terms and conditions page
├── logo.png            # Company logo (PNG format)
├── logo.jpg            # Alternative logo (JPG format)
├── logo1.jpg           # Additional logo variant
├── cover.jpg           # Hero section background image
├── 1a.jpg, 1b.jpg, 1c.jpg  # Bathroom installation project images
├── 2a.jpg, 2b.jpg          # Emergency repair project images
├── 3a.jpg, 3b.jpg, 3c.jpg  # Hob/cooker installation project images
├── 4a.jpg, 4b.jpg          # Boiler service project images
├── 5a.jpg, 5b.jpg, 5c.jpg, 5d.jpg  # Dual boiler replacement project images
├── 6a.jpg, 6b.jpg          # Drainage system upgrade project images
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Lazy loading for gallery images
- Optimized CSS with minified inline styles
- Efficient JavaScript for interactive features
- Preconnect hints for external resources (Google Fonts, Font Awesome CDN)
- Smooth scrolling with proper scroll padding

## Customization

### Colors
The color scheme is defined using CSS custom properties in the `:root` selector:
- `--navy: #0B2942` - Primary dark blue
- `--blue: #087DB5` - Accent blue
- `--green: #09B66D` - Call-to-action green
- `--mist: #F0F6F9` - Light background
- `--text: #18354D` - Body text color

### Contact Information
Update the following in `index.html`:
- Phone number: `+44 7717 137308`
- Email: `info@hexaplumbingandgas.co.uk`
- WhatsApp: Update the `wa.me` links
- Social media URLs

### Services
Services are listed in the `#services` section. Each service card includes:
- Icon (Font Awesome class)
- Service name
- Description
- Quote request link

### Portfolio Projects
Gallery projects are in the `#work` section. Each project includes:
- Multiple images
- Project title
- Onclick lightbox functionality

## SEO Features

- Semantic HTML structure
- Meta descriptions and Open Graph tags
- Schema.org structured data for local business
- Canonical URLs
- Proper heading hierarchy
- Alt text for all images

## Form Functionality

The contact form includes:
- Client-side validation
- Required field indicators
- Error messaging
- Honeypot field for spam prevention
- Service selection dropdown
- Contact preference options (Phone/Email/WhatsApp)

**Note:** The form currently uses client-side handling. For production, integrate with a backend service or form processing tool (e.g., Formspree, Netlify Forms, or custom backend).

## Deployment

This is a static website and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting (cPanel, FTP)
- AWS S3 + CloudFront
- Azure Static Web Apps

Simply upload all files to your hosting provider, ensuring the directory structure is maintained.

## Future Enhancements

- [ ] Backend integration for contact form submissions
- [ ] Blog section for plumbing tips and company news
- [ ] Online booking system
- [ ] Customer portal for service history
- [ ] Multi-language support
- [ ] Live chat integration
- [ ] Service area map integration

## Contact

**HEXA Plumbing & Gas**  
📞 Phone: +44 7717 137308  
📧 Email: info@hexaplumbingandgas.co.uk  
📍 Location: Manchester and surrounding areas  
🌐 Facebook: [Hexa Plumbing Gas](https://www.facebook.com/p/Hexa-Plumbing-Gas-61560947931557/)
---

*Built with care for professional plumbing services in Manchester.*
