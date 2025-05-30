# Explore Tourist Spots in Palawan 🏝️

A modern, responsive tourism website showcasing the beautiful destinations, attractions, and experiences available in Palawan, Philippines.

## 🌟 Features

### ✨ Modern Design
- **Glassmorphism UI** with backdrop blur effects
- **Gradient backgrounds** and smooth animations
- **Responsive design** that works on all devices
- **Interactive hover effects** and transitions

### 🎠 Dynamic Content
- **Hero carousel** with auto-rotating beautiful Palawan images
- **Interactive modals** for destinations, packages, guides, and food
- **Smooth animations** and loading effects
- **Modern typography** with gradient text effects

### 📱 Responsive Layout
- Mobile-first design approach
- Optimized for tablets and desktop
- Collapsible navigation for mobile devices
- Grid layouts that adapt to screen size

## 🗂️ Project Structure



## 🎨 Design Elements

### Color Palette
- **Primary Gradient**: `#667eea` to `#764ba2`
- **Background**: `#f5f7fa` to `#c3cfe2`
- **Text**: `#2c3e50` (dark) and `#7f8c8d` (muted)
- **Accent**: `#ecf0f1` and `#bdc3c7`

### Typography
- **Primary Font**: Inter, Segoe UI, Tahoma
- **Headings**: Bold weights (700)
- **Body Text**: Regular weight (400-500)

## 🏖️ Sections Overview

### 1. Header Navigation
- **Logo placement** with drop shadow
- **Glassmorphism navigation** with hover effects
- **User actions** (search, favorites, profile)
- **Sticky positioning** for easy access

### 2. Hero Carousel
- **Auto-rotating slides** (5-second intervals)
- **Full-screen images** with overlay text
- **Call-to-action buttons** with gradient styling
- **Custom navigation controls**

### 3. Highlights Section
- **Featured destinations**: Puerto Princesa, El Nido, Coron
- **Card-based layout** with hover animations
- **Image scaling effects** on hover
- **Gradient text headings**

### 4. Featured Destinations
- **Grid layout** for additional locations
- **Port Barton, Sabang, Tubbataha Reef**
- **Consistent card styling** with shadows
- **Responsive grid system**

### 5. Interactive Modals
- **Destinations Modal**: Popular tourist spots with descriptions
- **Travel Packages Modal**: Various tour packages and pricing
- **Guides Modal**: Travel tips and practical information
- **Food Modal**: Local cuisine with images and prices

### 6. Footer
- **Company information** and social links
- **Customer service** links
- **Social media** integration
- **Multi-column responsive** layout

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox/Grid
- **Bootstrap 4.5.2**: Responsive framework
- **Font Awesome 6.0**: Icon library
- **jQuery 3.5.1**: JavaScript functionality
- **Popper.js**: Tooltip and popover positioning

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS (for customization)

### Installation
1. **Clone or download** the project files


2. **Open `index.html`** in your web browser

### Local Development
```bash
# If you have Python installed, you can run a local server:
python -m http.server 8000
# Then open http://localhost:8000 in your browser

# Or if you have Node.js:
npx http-server
```

## 🖼️ Image Requirements

### Image Specifications
- **Format**: JPG, PNG
- **Hero carousel images**: Minimum 1920x1080px
- **Destination cards**: 400x250px recommended
- **Food images**: 300x200px
- **Logo**: PNG with transparent background

### Image Sources Used
- Hero carousel images from external URLs (Miro, ImageKit, iStock)
- Food images from Unsplash API
- Local images should be added to `/images/` folder

## 🎯 Customization Guide

### Changing Colors
Update the CSS custom properties in the `<style>` section:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --background-gradient: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
}
```

### Adding New Destinations
1. Add new product card in the `.product-grid` section
2. Include corresponding image in the `images/` folder
3. Update modal content if needed

### Modifying Animations
Adjust animation properties in CSS:
```css
.highlight:hover {
  transform: translateY(-10px);
  transition: all 0.3s ease;
}
```

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Optimization

### Implemented Optimizations
- **CSS animations** using `transform` for better performance
- **Lazy loading** effects for images
- **Optimized CSS** with efficient selectors
- **Minified external libraries** from CDN

### Recommendations
- Compress images before uploading
- Use WebP format for better compression
- Consider lazy loading for below-the-fold images
- Optimize CSS delivery for faster loading

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

For questions or suggestions about this Palawan tourism website:
- Create an issue in this repository
- Contact through the website's contact form

## 🏆 Acknowledgments

- **Palawan Tourism Board** for destination inspiration
- **Bootstrap team** for the responsive framework
- **Font Awesome** for beautiful icons
- **Unsplash photographers** for stunning food imagery
- **Local Palawan photographers** for destination images

---

**Made with ❤️ for Palawan Tourism**

*Explore the last frontier of the Philippines - Palawan!* 🌺
