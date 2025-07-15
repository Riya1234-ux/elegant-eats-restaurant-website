# Elegant Eats - Fine Dining Restaurant Website

A modern, responsive website for a fine dining restaurant built with HTML5 and CSS3. The site features elegant design, smooth animations, and a sophisticated user experience that reflects the luxury dining atmosphere.

## 🍽️ Features

- **Modern Design**: Clean, elegant interface with sophisticated typography using Google Fonts (Playfair Display & Inter)
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Navigation**: Fixed header with smooth scrolling to sections
- **Interactive Elements**: Hover effects, transitions, and form interactions
- **Accessibility**: Semantic HTML, proper contrast ratios, and keyboard navigation support
- **Professional Sections**:
  - Hero section with compelling call-to-action
  - About section highlighting restaurant story
  - Menu showcase with high-quality food imagery
  - Reservation form with validation
  - Contact information and location details
  - Professional footer with quick links

## 📁 Project Structure

```
elegant-eats/
├── index.html          # Main HTML structure
├── style.css           # Complete CSS styling and responsive design
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation & Usage

1. **Clone or download** the project files
2. **Open `index.html`** in your preferred web browser
3. **Navigate** through the site using the header menu or scroll naturally

### Local Development
For local development with live reload:
```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Then open http://localhost:8000 in your browser
```

## 🎨 Design Features

### Color Palette
- **Primary**: #8B4513 (Saddle Brown) - Elegant, warm brown
- **Secondary**: #2c2c2c (Dark Gray) - Professional text
- **Accent**: #f8f8f8 (Light Gray) - Section backgrounds
- **Text**: #333 (Dark Gray), #555 (Medium Gray), #666 (Light Gray)

### Typography
- **Headings**: Playfair Display (Serif) - Elegant, classic feel
- **Body Text**: Inter (Sans-serif) - Clean, readable
- **Responsive font sizes** that scale appropriately across devices

### Layout
- **CSS Grid & Flexbox** for modern, flexible layouts
- **Mobile-first responsive design** with breakpoints at 768px and 480px
- **Smooth animations** and hover effects throughout
- **Fixed navigation** with backdrop blur effect

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (Full layout)
- **Tablet**: 768px - 1199px (Adjusted grid layouts)
- **Mobile**: 480px - 767px (Single column, stacked elements)
- **Small Mobile**: <480px (Optimized spacing and typography)

## 🔧 Customization

### Changing Colors
Update the color variables in `style.css`:
```css
/* Primary brand color */
color: #8B4513; /* Change to your preferred color */
background: #8B4513;
```

### Adding Content
- **Menu Items**: Add new `.menu-item` divs in the menu section
- **Images**: Replace image URLs with your own high-quality photos
- **Text Content**: Update restaurant name, description, and contact details

### Form Integration
The reservation form is ready for backend integration:
```html
<form class="reservation-form" action="your-backend-url" method="post">
```

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📸 Image Sources

All images are sourced from [Pexels](https://pexels.com) - a free stock photo service:
- Hero background: Fine dining restaurant interior
- Menu items: Professional food photography
- High-resolution images optimized for web display

## ♿ Accessibility Features

- **Semantic HTML5** elements for screen readers
- **Proper heading hierarchy** (h1, h2, h3)
- **Alt text** for all images
- **Keyboard navigation** support
- **Focus indicators** for interactive elements
- **Color contrast** meets WCAG guidelines
- **Responsive text** that scales appropriately

## 🚀 Performance Optimizations

- **Optimized images** from external CDN (Pexels)
- **Minimal CSS** with efficient selectors
- **Google Fonts** loaded efficiently
- **Smooth scrolling** with reduced motion preference support
- **CSS Grid and Flexbox** for efficient layouts

## 🔮 Future Enhancements

### Potential Improvements
- **JavaScript interactivity** for form validation and submission
- **Image gallery** with lightbox functionality
- **Online ordering system** integration
- **Social media** integration
- **Multi-language support**
- **SEO optimization** with meta tags and structured data
- **Progressive Web App** features
- **Content Management System** integration

### Technical Enhancements
- **CSS animations** library integration
- **Lazy loading** for images
- **Service worker** for offline functionality
- **Analytics** integration (Google Analytics)
- **Performance monitoring**

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## 📞 Support

For questions or support regarding this template:
- Create an issue in the repository
- Review the code comments for implementation details
- Check browser developer tools for any console errors

---

**Elegant Eats** - Where culinary artistry meets exceptional web design ✨
