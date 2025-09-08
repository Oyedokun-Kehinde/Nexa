# 🚀 Nexa - Modern Business Solutions Website

A cutting-edge, responsive business website built with modern web technologies. Features stunning animations, interactive UI components, and a professional design that converts visitors into customers.

![Nexa Website Preview](https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

## ✨ Features

### 🎨 **Modern Design**
- **Premium UI/UX** with gradient backgrounds and glassmorphism effects
- **Responsive design** that works perfectly on all devices
- **Dark theme** with vibrant green accent colors
- **Professional typography** using Inter and Raleway fonts
- **Smooth animations** and micro-interactions

### 🔧 **Interactive Components**
- **Custom cursor** with smooth following animation
- **Scroll-triggered animations** using Intersection Observer API
- **Dynamic navbar** that hides/shows on scroll
- **Animated statistics counters**
- **Interactive service cards** with hover effects
- **Smooth scrolling navigation**

### 📱 **Fully Responsive**
- Mobile-first approach
- Tablet and desktop optimization
- Touch-friendly interactions
- Optimized performance across devices

### 🎯 **Business-Ready Sections**
- **Hero section** with compelling call-to-action
- **Statistics showcase** with animated counters
- **About us** with feature highlights
- **Services portfolio** with detailed descriptions
- **Contact form** with validation and feedback
- **Professional footer** with newsletter signup

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **JavaScript ES6+** - Interactive functionality
- **Bootstrap 5** - Responsive grid and components
- **Bootstrap Icons** - Professional iconography
- **Google Fonts** - Premium typography

## 📋 Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/nexa-website.git
cd nexa-website
```

### 2. Project Structure
```
nexa-website/
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css   # Custom styles
│   ├── js/
│   │   └── script.js   # Interactive functionality
│   └── images/         # Project images
├── README.md           # Project documentation
└── LICENSE             # License file
```

### 3. Launch the Website
Simply open `index.html` in your web browser or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization:

```css
:root {
  --primary-green: #00D4AA;
  --primary-green-dark: #00B894;
  --primary-green-light: #00E5B8;
  --dark-bg: #0A0B0D;
  --dark-secondary: #1A1D23;
  --dark-card: #252A32;
}
```

### Content
- **Company Information**: Update the brand name, descriptions, and contact details
- **Services**: Modify the services section to match your offerings
- **Images**: Replace placeholder images with your own professional photos
- **Contact Form**: Connect the form to your preferred form handler or backend

### Fonts
The website uses Google Fonts. To change fonts, update the link in the HTML head:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;500;600;700&display=swap" rel="stylesheet" />
```

## 📱 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Advanced Features

### Custom Cursor
The website includes a custom cursor that follows mouse movement with smooth animation. To disable:

```javascript
// Comment out or remove the cursor JavaScript code
// const cursor = document.getElementById('custom-cursor');
```

### Animation Controls
Animations are triggered when elements enter the viewport. Customize timing and effects in the CSS:

```css
.fade-in-up {
  opacity: 0;
  transform: translateY(50px);
  transition: all 0.6s ease;
}
```

### Contact Form Integration
To connect the contact form to a backend service:

1. **EmailJS**: For client-side email sending
2. **Formspree**: Simple form handling service
3. **Netlify Forms**: If hosting on Netlify
4. **Custom Backend**: Node.js, PHP, or Python server

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (main/master)
4. Your site will be available at `https://yourusername.github.io/nexa-website`

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on every push

### Vercel
```bash
npm i -g vercel
vercel --prod
```

### Traditional Web Hosting
Upload all files to your web hosting provider's public folder (public_html, www, etc.)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/AmazingFeature`
3. **Commit your changes**: `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch**: `git push origin feature/AmazingFeature`
5. **Open a Pull Request**

### Development Guidelines
- Follow consistent code formatting
- Add comments for complex functionality
- Test across different browsers and devices
- Maintain responsive design principles

## 📈 Performance Optimization

- **Images**: Use WebP format for better compression
- **CSS**: Minify CSS for production
- **JavaScript**: Minify and bundle JS files
- **CDN**: Use CDN for external resources
- **Caching**: Implement proper caching headers

## 🐛 Known Issues

- Custom cursor may not work on touch devices (intentional)
- Some animations may be reduced for users with `prefers-reduced-motion`

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Bootstrap** for the responsive framework
- **Google Fonts** for typography
- **Bootstrap Icons** for iconography
- **Unsplash** for placeholder images
- **GitHub** for hosting and version control

## 📞 Support

If you have any questions or need help with customization:

- 📧 Email: support@nexasolutions.com
- 💬 GitHub Issues: [Create an issue](https://github.com/Oyedokun-Kehinde/nexa-website/issues)
- 📖 Documentation: [Wiki](https://github.com/yourusername/nexa-website/wiki)

## 🔄 Changelog

### v1.0.0 (2025-01-XX)
- ✨ Initial release
- 🎨 Modern UI design with dark theme
- 📱 Fully responsive layout
- ⚡ Interactive animations and effects
- 🔧 Professional business sections
- 📝 Contact form with validation

---

⭐ **Star this repository if it helped you build an amazing website!**

Made with ❤️ by [Oyedokun Kehinde ](https://github.com/Oyedokun-Kehinde)
