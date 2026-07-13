# Aman Vishwakarma - Premium Personal Brand Sales Website

A modern, minimal, mobile-first sales website built with HTML5, CSS3, and vanilla JavaScript. Designed to showcase digital products, generate leads, and convert visitors into customers.

## 🎯 Features

- **Premium Design**: Minimal, clean UI with black & white theme and blue accents
- **Glassmorphism Effects**: Modern UI trend with frosted glass backgrounds
- **Mobile-First Responsive**: Optimized for all devices
- **Smooth Animations**: Scroll animations and transitions
- **Dark Mode**: Toggle between light and dark themes
- **SEO Optimized**: Meta tags, Open Graph, structured data
- **Payment Ready**: Razorpay integration (modular setup)
- **Social Integration**: WhatsApp, Instagram, Email
- **Fast Loading**: Optimized performance, no heavy dependencies

## 📁 Project Structure

```
Aman-/
├── index.html
├── about.html
├── products.html
├── testimonials.html
├── faq.html
├── contact.html
├── css/
│   ├── style.css
│   ├── responsive.css
│   ├── animations.css
│   └── dark-mode.css
├── js/
│   ├── main.js
│   ├── navigation.js
│   ├── animations.js
│   ├── form-handler.js
│   ├── payment.js
│   └── theme.js
├── images/
│   ├── hero/
│   ├── products/
│   ├── testimonials/
│   └── icons/
├── assets/
│   ├── favicon.ico
│   └── favicon.svg
└── README.md
```

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/growwithaman/Aman-.git
   cd Aman-
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. Customize the content:
   - Update personal information in `index.html`
   - Add your photos to the `images/` folder
   - Update products and testimonials
   - Configure Razorpay keys in `js/payment.js`

## 🎨 Customization

### Colors
Update color variables in `css/style.css`:
```css
:root {
  --primary-color: #1a1a1a;      /* Black */
  --secondary-color: #ffffff;     /* White */
  --accent-color: #3b82f6;        /* Blue */
  --text-dark: #1a1a1a;
  --text-light: #ffffff;
}
```

### Content
Each HTML page contains clearly marked sections for easy editing. Search for `<!-- CUSTOMIZE -->` comments.

### Razorpay Integration
Update your Razorpay key ID in `js/payment.js`:
```javascript
const RAZORPAY_KEY_ID = 'your_key_id_here';
```

## 📱 Pages

- **Home** (`index.html`) - Hero, mission, products, testimonials, FAQ, contact
- **About** (`about.html`) - Your story, expertise, achievements
- **Products** (`products.html`) - Digital products showcase with pricing
- **Testimonials** (`testimonials.html`) - Success stories and customer feedback
- **FAQ** (`faq.html`) - Common questions and answers
- **Contact** (`contact.html`) - Contact form and information

## 🔗 Deployment

### GitHub Pages
1. Push to your repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://growwithaman.github.io/Aman-/`

### Cloudflare Pages
1. Connect your GitHub repository
2. Build settings: Leave blank (static site)
3. Deploy!

## 🛠️ Payment Integration

### Razorpay Setup
1. Create a Razorpay account at [razorpay.com](https://razorpay.com)
2. Get your Key ID from dashboard
3. Update `js/payment.js` with your Key ID
4. Configure payment buttons with product IDs

## 📊 SEO

- Semantic HTML5 structure
- Meta descriptions and Open Graph tags
- Mobile-friendly viewport
- Fast loading optimization
- Proper heading hierarchy
- Schema.org structured data

## 🌙 Dark Mode

Users can toggle dark mode with the theme button in the header. Preference is saved in localStorage.

## ⚡ Performance

- No heavy dependencies
- Optimized CSS and JavaScript
- Image optimization recommended
- Lazy loading ready
- ~50KB total (without images)

## 📞 Social Links

- WhatsApp floating button
- Instagram integration
- Email subscription
- Contact form

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Support

For questions or customization help, reach out via the contact form or social links.

---

**Built with ❤️ for your success**
