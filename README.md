# ElectroParts - Electronic Components Shop

A modern, responsive e-commerce website for electronic components built with HTML, CSS (Tailwind), and JavaScript. This project showcases a complete online store interface for selling electronic components with shopping cart functionality.

## 🚀 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional interface using Tailwind CSS framework
- **Product Catalog**: Display of electronic components with images, prices, and descriptions
- **Shopping Cart**: Full shopping cart functionality with add/remove items
- **Local Storage**: Cart data persists between browser sessions
- **Brand Showcase**: Featured electronics brands section
- **Contact Form**: Contact section with company information
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Animations**: CSS transitions and hover effects

## 🛍️ Product Categories

The website includes various electronic components:
- **Development Boards**: Arduino Uno, Raspberry Pi 4, ESP32
- **Components**: LEDs, Resistors, Capacitors
- **Accessories**: Breadboards, Jumper Wires

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Styling with custom animations
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript (ES6+)**: Interactive functionality and cart management
- **Font Awesome**: Icons for enhanced UI
- **LocalStorage API**: Client-side data persistence

## 📁 Project Structure

```
electroparts/
├── index.html          # Main HTML file
├── README.md          # Project documentation
└── assets/
    └── images/        # Product and brand images (external URLs)
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for CDN resources)

### Installation

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **That's it!** The website is ready to use

### Local Development

For local development, you can:

1. Use a simple HTTP server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

2. Open your browser and navigate to `http://localhost:8000`

## 🎨 Customization

### Adding New Products

To add new products, modify the `products` array in the JavaScript section:

```javascript
const products = [
    {
        id: 9, // Unique ID
        name: "New Component",
        price: 299, // Price in INR
        category: "components",
        image: "https://example.com/image.jpg",
        description: "Component description",
        stock: 50
    }
    // ... existing products
];
```

### Styling Changes

The website uses Tailwind CSS. You can:
- Modify existing classes in the HTML
- Add custom CSS in the `<style>` section
- Update the color scheme by changing Tailwind color classes

### Brand Logos

Brand logos are loaded from `logotyp.us`. To add new brands:

```html
<img src="//logotyp.us/file/brand-name.svg" 
     alt="Brand Name" 
     class="h-24 opacity-70 hover:opacity-100 transition-opacity">
```

## 🛒 Shopping Cart Features

- **Add to Cart**: Click "Add to Cart" on any product
- **View Cart**: Click the cart icon in the navigation
- **Remove Items**: Click the "×" button next to cart items
- **Persistent Storage**: Cart contents saved in browser's local storage
- **Real-time Updates**: Cart count updates immediately

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Business Information

The website includes placeholder business information for:
- **Company**: ElectroParts
- **Location**: Palghar, Maharashtra, India
- **Contact**: Phone, email, and address
- **Pricing**: All prices in Indian Rupees (₹)

## 🔧 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+

## 📈 Performance Considerations

- **CDN Resources**: External CSS/JS loaded from CDNs
- **Image Optimization**: Uses optimized external image URLs
- **Lightweight**: Minimal custom JavaScript for fast loading
- **Caching**: Static assets cached by browser

## 🚧 Future Enhancements

Potential improvements for production use:

1. **Backend Integration**
   - Connect to a real database
   - Implement user authentication
   - Add payment gateway integration

2. **Advanced Features**
   - Product search and filtering
   - User reviews and ratings
   - Wishlist functionality
   - Order tracking system

3. **Performance**
   - Image lazy loading
   - Code splitting
   - Service worker for offline functionality

4. **SEO Optimization**
   - Meta tags for each product
   - Structured data markup
   - XML sitemap

## 📝 License

This project is for educational and demonstration purposes. Feel free to use and modify as needed.

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support:
- Email: info@electroparts.com
- Phone: +91 78754 00163
- Address: 123 Electronics Street, Palghar, MH 401404

---

**Note**: This is a demo website. All business information, contact details, and payment methods are for demonstration purposes only.
