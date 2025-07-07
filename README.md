# Horizon Value Fund Website

A beautiful, modern website for a long-only value fund with an analyst program application feature. Built with HTML, CSS, and JavaScript.

## Features

### 🎨 Design
- **Modern & Aesthetic**: Clean, professional design with beautiful gradients and animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling, hover effects, and animated elements
- **Professional**: Trust-building design elements suitable for institutional investors

### 📊 Content Sections
- **Hero Section**: Eye-catching introduction with key statistics
- **About**: Investment philosophy and core principles
- **Strategy**: Detailed investment approach and process
- **Performance**: Fund performance metrics and risk statistics
- **Team**: Professional team profiles
- **Careers**: Analyst program application form
- **Contact**: Contact information and inquiry form

### 💼 Analyst Program Application
- **Comprehensive Form**: Collects all necessary information for analyst candidates
- **File Upload**: Resume/CV upload functionality
- **Validation**: Form validation with user-friendly error messages
- **Professional**: Structured to attract top talent

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Setup Instructions

1. **Download Files**: Save all files in the same directory
2. **Open Website**: Double-click `index.html` or open it in a web browser
3. **Local Server** (Optional): For best experience, serve files through a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Customization

### Branding
- **Company Name**: Update "Horizon Value Fund" in `index.html`
- **Colors**: Modify the gradient colors in `styles.css` (search for `#667eea` and `#764ba2`)
- **Logo**: Replace the text logo with your company logo (EonFund.png)

### Content
- **Statistics**: Update the hero section statistics with your fund's actual numbers
- **Performance**: Replace performance metrics with real fund data
- **Team**: Update team member information and photos
- **Contact**: Update contact information and address

### Forms
- **Application Form**: Customize fields in the careers section
- **Contact Form**: Modify the contact form fields as needed
- **Backend Integration**: Connect forms to your backend system

## Key Features Explained

### Responsive Design
The website automatically adapts to different screen sizes:
- **Desktop**: Full layout with side-by-side sections
- **Tablet**: Adjusted grid layouts
- **Mobile**: Single-column layout with hamburger menu

### Interactive Elements
- **Smooth Scrolling**: Click navigation links for smooth page scrolling
- **Hover Effects**: Cards and buttons have subtle hover animations
- **Form Validation**: Real-time validation with helpful error messages
- **Loading States**: Buttons show loading states during form submission

### Performance Optimizations
- **CSS Animations**: Hardware-accelerated animations for smooth performance
- **Lazy Loading**: Elements animate in as they come into view
- **Minimal JavaScript**: Lightweight, efficient code

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Future Enhancements

### Potential Additions
- **Real-time Performance Charts**: Integrate with Chart.js or D3.js
- **Blog Section**: Add investment insights and market commentary
- **Investor Portal**: Secure login for existing investors
- **Newsletter Signup**: Email marketing integration
- **Social Media**: Links to LinkedIn, Twitter, etc.

### Technical Improvements
- **Backend Integration**: Connect forms to a real backend system
- **CMS Integration**: Make content editable through a CMS
- **SEO Optimization**: Add meta tags and structured data
- **Analytics**: Google Analytics or similar tracking

## Contact & Support

For questions about customization or implementation:
- Review the code comments for guidance
- Test thoroughly across different browsers
- Consider hiring a developer for complex customizations

## License

This website template is provided as-is for educational and commercial use. Customize as needed for your specific requirements.

---

**Note**: This is a frontend-only implementation. For production use, you'll need to:
1. Connect forms to a backend system
2. Add proper security measures
3. Implement data validation and sanitization
4. Set up proper hosting and SSL certificates 