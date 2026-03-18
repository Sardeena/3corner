# The Three Corners Equinox Reviews Landing Page

A production-ready, mobile-first landing page for The Three Corners Equinox hotel in Marsa Alam, Egypt. This page allows guests to leave reviews on multiple travel platforms.

## 🚀 Features

- **Mobile-First Design**: Fully responsive from 320px to desktop
- **Touch-Friendly**: Minimum 60px tap targets for mobile users
- **Modern UI**: Clean design with subtle gradients and smooth animations
- **Accessible**: Semantic HTML5 with proper focus states
- **Performance Optimized**: Minimal CSS, fast loading
- **SEO Ready**: Proper meta tags and semantic markup
- **Vercel Ready**: Drag-and-drop deployment ready

## 📱 Responsive Breakpoints

- **Mobile**: 320px - 479px (1 column grid)
- **Tablet**: 480px - 767px (2 column grid)
- **Desktop**: 768px - 1023px (3 column grid)
- **Large Desktop**: 1024px+ (enhanced spacing)

## 🛠️ Customization

### Replace Review Links

Update the placeholder URLs in `index.html` with your actual review links:

```html
<!-- Google Reviews -->
<a href="https://g.page/YOUR_GOOGLE_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>

<!-- TripAdvisor -->
<a href="https://www.tripadvisor.com/YOUR_TRIPADVISOR_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>

<!-- HolidayCheck -->
<a href="https://www.holidaycheck.com/YOUR_HOLIDAYCHECK_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>

<!-- Zoover -->
<a href="https://www.zoover.com/YOUR_ZOOVER_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>

<!-- TopHotels -->
<a href="https://www.tophotels.com/YOUR_TOPHOTELS_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>

<!-- Booking.com -->
<a href="https://www.booking.com/YOUR_BOOKING_REVIEW_LINK" target="_blank" rel="noopener noreferrer" class="cta-button">
    Write Review
</a>
```

### Update Hotel Information

Edit the hotel details in the header section:

```html
<h1 class="hotel-name">The Three Corners Equinox</h1>
<p class="hotel-location">Marsa Alam, Egypt</p>
<p class="hotel-description">Share your experience or read reviews from fellow travelers</p>
```

### Customize Colors

Modify the color scheme in `style.css`:

```css
/* Primary gradient colors */
.cta-button {
    background: linear-gradient(135deg, #667eea, #764ba2);
}

/* Update these hex codes to match your brand */
--primary-color: #667eea;
--secondary-color: #764ba2;
```

## 📁 Project Structure

```
/
├── index.html          # Main HTML file
├── style.css           # Mobile-first CSS with animations
├── assets/
│   └── logos/
│       ├── google-reviews.svg
│       ├── tripadvisor.svg
│       ├── holidaycheck.svg
│       ├── zoover.svg
│       ├── tophotels.svg
│       └── bookingcom.svg
└── README.md           # This file
```

## 🚀 Deployment Options

### Option 1: Vercel Drag & Drop (Easiest)

1. Go to [vercel.com](https://vercel.com)
2. Sign up or log in
3. Drag the entire project folder onto the Vercel dashboard
4. Your site will be live in seconds!

### Option 2: Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to project directory
cd your-project-folder

# Deploy
vercel --prod
```

### Option 3: GitHub Integration

1. Create a new repository on GitHub
2. Push your files to the repository
3. Connect your GitHub account to Vercel
4. Import the repository and deploy

### Option 4: Static Hosting

The site works on any static hosting service:
- Netlify
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

## 📱 Mobile Testing

### Chrome DevTools

1. Open `index.html` in Chrome
2. Press F12 to open DevTools
3. Click the device toggle (📱)
4. Test different screen sizes

### Real Device Testing

1. Transfer files to your mobile device
2. Open `index.html` in mobile browser
3. Test touch interactions and responsiveness

## 🎨 Design Features

### Animations

- **Gradient Background**: Subtle animated gradient
- **Card Animations**: Fade-in with staggered delays
- **Hover Effects**: Scale and shadow transitions
- **Button Shimmer**: Subtle shine effect on hover

### Accessibility

- Semantic HTML5 structure
- Proper focus indicators
- Keyboard navigation support
- Screen reader friendly
- Reduced motion support

### Performance

- Minimal CSS (single file)
- Optimized SVG logos
- Lazy loading for images
- Efficient animations using CSS transforms

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- iOS Safari 12+
- Android Chrome 60+

## 📊 Performance Metrics

- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🛡️ Security

- All external links use `rel="noopener noreferrer"`
- No inline JavaScript
- HTTPS ready
- CSP compatible

## 📞 Support

For issues or questions:

1. Check the browser console for errors
2. Verify all file paths are correct
3. Ensure all links are properly formatted
4. Test on multiple devices and browsers

## 🔄 Updates

To update the site:

1. Modify HTML/CSS files as needed
2. Test locally in browser
3. Deploy using your preferred method
4. Test the live deployment

---

**Built with ❤️ for The Three Corners Equinox**
