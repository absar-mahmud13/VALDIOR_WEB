# Valdior Website

A modern, responsive e-commerce website for the Valdior fashion brand. Built with HTML, CSS, and JavaScript following the design requirements for "Luxury and Premium in Your Affordability."

## 🌟 Features

### Core Pages
- **Homepage**: Hero section, featured collections, brand story, testimonials, Instagram feed
- **Shop Page**: Product gallery with filters, categories, sorting, and quick view modal
- **About Page**: Brand story, team information, mission/vision, manufacturing process
- **Contact Page**: Contact form, business information, FAQ section, newsletter signup

### Key Functionality
- **Responsive Design**: Mobile-first approach, works on all devices
- **Shopping Cart**: Add to cart functionality with counter
- **Wishlist**: Save favorite products for later
- **Search**: Global search functionality across products
- **Filters**: Category, price, size, and color filtering on shop page
- **Interactive Elements**: Smooth animations, hover effects, modal dialogs

### Design Elements
- **Color Scheme**: Black, white, gray with gold (#d4af37) accents
- **Typography**: Playfair Display for headings, Open Sans for body text
- **Icons**: Font Awesome 6.0 icons throughout
- **Layout**: CSS Grid and Flexbox for modern layouts

## 📁 Project Structure

```
Valdior-website/
├── index.html          # Homepage
├── shop.html           # Shop/Products page
├── about.html          # About Us page
├── contact.html        # Contact page
├── styles.css          # Global styles
├── shop.css           # Shop page specific styles
├── about.css          # About page specific styles
├── contact.css        # Contact page specific styles
├── script.js          # Global JavaScript functionality
├── shop.js            # Shop page JavaScript
├── about.js           # About page JavaScript
├── contact.js         # Contact page JavaScript
└── README.md          # This file
```

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open index.html** in a web browser
3. **Navigate** between pages using the navigation menu

### Development Setup
- No build process required - pure HTML/CSS/JS
- Use a local server for best experience:
  ```bash
  # Using Python
  python -m http.server 8000
  
  # Using Node.js
  npx serve
  ```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🎨 Color Palette

```css
Primary Colors:
- Black: #000000
- White: #FFFFFF
- Dark Gray: #2c3e50
- Light Gray: #f8f9fa

Accent Colors:
- Gold: #d4af37
- Gold Hover: #b8941f
- Error: #e74c3c
- Success: #27ae60
```

## 🛠 Customization

### Adding New Products
1. Copy an existing product card in `shop.html`
2. Update the data attributes:
   - `data-category`: Product category
   - `data-price`: Price in Taka
   - `data-size`: Available sizes (comma-separated)
   - `data-color`: Product color
3. Update product information (title, description, price)

### Modifying Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
  --primary-color: #d4af37;
  --secondary-color: #2c3e50;
  --accent-color: #f1c40f;
}
```

### Adding New Pages
1. Create new HTML file
2. Copy navigation and footer from existing pages
3. Add corresponding CSS file
4. Update navigation links in all pages

## 📧 Contact Information

**Business Details:**
- **Location**: Chittagong, Bangladesh
- **Phone**: 01795-997309
- **Email**: valdior242@gmail.com

**Social Media:**
- Facebook: [To be added]
- Instagram: [To be added]
- WhatsApp: [To be added]

## 🔧 Technical Features

### JavaScript Functionality
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Search Overlay**: Full-screen search interface
- **Product Filtering**: Real-time filtering by category, price, size, color
- **Form Validation**: Client-side form validation with Bengali messages
- **Local Storage**: Saves cart and wishlist counts
- **Smooth Scrolling**: Enhanced user experience
- **Intersection Observer**: Scroll-based animations

### Performance Optimizations
- **Lazy Loading**: Images load as needed
- **CSS Grid/Flexbox**: Efficient layouts
- **Minimal Dependencies**: Only Font Awesome CDN
- **Optimized Images**: Placeholder system for future image integration

## 🌐 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 TODO / Future Enhancements

- [ ] Integrate real payment gateway (bKash, Nagad, etc.)
- [ ] Add product image gallery
- [ ] Implement user accounts/login
- [ ] Add product reviews and ratings
- [ ] Integrate with inventory management
- [ ] Add multi-language support (English/Bengali toggle)
- [ ] Implement real-time chat support
- [ ] Add order tracking functionality
- [ ] SEO optimization
- [ ] Google Analytics integration

## 🐛 Known Issues

- Map integration is placeholder (needs Google Maps API)
- Social media links are placeholder
- Form submissions are simulated (need backend integration)
- Product images use placeholders (need real product photos)

## 📝 License

This project is created for Valdior brand. All rights reserved.

## 👨‍💻 Development Notes

### Code Organization
- **Modular CSS**: Separate files for each page
- **Progressive Enhancement**: Works without JavaScript
- **Semantic HTML**: Proper HTML5 structure
- **Accessible**: ARIA labels and keyboard navigation support

### Best Practices Followed
- Mobile-first responsive design
- Clean, readable code structure
- Consistent naming conventions
- Cross-browser compatibility
- Performance optimization
- SEO-friendly markup

---

**Built with ❤️ for Valdior - Luxury and Premium in Your Affordability**
