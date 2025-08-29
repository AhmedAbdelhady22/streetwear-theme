# Urban Edge Theme Documentation

## Table of Contents
1. [Installation](#installation)
2. [Theme Setup](#theme-setup)
3. [Customization Guide](#customization-guide)
4. [Section Documentation](#section-documentation)
5. [Performance Optimization](#performance-optimization)
6. [Troubleshooting](#troubleshooting)

## Installation

### Requirements
- Shopify Online Store 2.0
- Modern web browser
- High-quality product images (recommended 1200x1200px minimum)

### Steps
1. Download the theme ZIP file
2. In your Shopify admin, go to Online Store > Themes
3. Click "Upload theme" and select the ZIP file
4. Once uploaded, click "Customize" to start setting up your store

## Theme Setup

### Initial Configuration
1. **Brand Identity**
   - Upload your logo in Theme Settings > Header
   - Set brand colors in Theme Settings > Colors
   - Configure typography in Theme Settings > Typography

2. **Navigation**
   - Set up your main menu in Navigation settings
   - Add social media links in Theme Settings > Social Media

3. **Homepage Setup**
   - Customize hero banner content
   - Select featured products
   - Configure collection showcases
   - Add about section content

## Customization Guide

### Colors
Navigate to **Theme Settings > Colors** to customize:
- **Primary Colors**: Main brand colors for buttons and accents
- **Background Colors**: Page and section backgrounds
- **Text Colors**: Heading and body text colors
- **Border Colors**: Subtle dividers and borders

### Typography
In **Theme Settings > Typography**:
- **Heading Font**: Choose from Google Fonts or system fonts
- **Body Font**: Select readable fonts for content
- **Font Sizes**: Adjust base font sizes for different screen sizes

### Layout Options
**Theme Settings > Layout**:
- **Container Width**: Adjust maximum content width
- **Spacing**: Control section and element spacing
- **Border Radius**: Set rounded corner styles

## Section Documentation

### Header Section
- **Logo**: Upload PNG/SVG logo (recommended: 200x60px)
- **Navigation**: Configure main menu
- **Cart Icon**: Shows item count
- **Search**: Toggle search functionality
- **Social Links**: Add social media icons

### Hero Banner Section
- **Background Image**: High-res image (1920x800px recommended)
- **Overlay**: Control background opacity
- **Content**: Heading, subheading, and CTA buttons
- **Text Alignment**: Left, center, or right alignment

### Featured Products Section
- **Collection Source**: Select which collection to feature
- **Product Count**: Control how many products to show
- **Grid Layout**: Choose columns (2-4 on desktop)
- **Show Vendor**: Toggle brand names

### Collections Showcase
- **Featured Collections**: Select up to 6 collections
- **Layout Style**: Grid or carousel display
- **Image Overlay**: Text overlay options

### Footer Section
- **Newsletter**: MailChimp or Klaviyo integration
- **Social Media**: Link to social profiles
- **Payment Icons**: Display accepted payment methods
- **Legal Links**: Privacy policy, terms, etc.

## Performance Optimization

### Image Optimization
- Use WebP format when possible
- Compress images before upload
- Use appropriate dimensions:
  - Product images: 1200x1200px
  - Collection images: 800x600px
  - Hero banners: 1920x800px

### Loading Speed
- Enable Shopify's native lazy loading
- Minimize custom JavaScript
- Use theme's built-in CSS optimization

### Mobile Performance
- Images automatically optimize for mobile
- Touch-friendly button sizes (44px minimum)
- Simplified mobile navigation

## Troubleshooting

### Common Issues

**1. Logo not displaying**
- Check image format (PNG, JPG, SVG supported)
- Ensure image file size is under 1MB
- Verify image is uploaded correctly

**2. Colors not updating**
- Clear browser cache
- Check if CSS variables are properly configured
- Ensure theme settings are saved

**3. Mobile layout issues**
- Test on actual devices, not just browser resize
- Check viewport meta tag is present
- Verify responsive breakpoints

**4. Slow loading**
- Optimize image sizes
- Reduce number of product variants
- Check for conflicting apps

### Getting Help
- **Email Support**: support@yourcompany.com
- **Documentation**: [Link to full docs]
- **Video Tutorials**: [Link to tutorial series]
- **Community Forum**: [Link to forum]

## Advanced Customization

### Custom CSS
Add custom styles in **Theme Settings > Custom CSS**:

```css
/* Example: Custom button styles */
.btn--custom {
  background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
  border: none;
  color: white;
}

/* Example: Custom typography */
.custom-heading {
  font-family: 'Your Custom Font', sans-serif;
  text-transform: uppercase;
  letter-spacing: 2px;
}
```

### Liquid Customization
For advanced users, customize Liquid templates:
- Product page enhancements
- Custom collection layouts
- Additional section types

### App Integration
Recommended apps that work well with this theme:
- **Reviews**: Judge.me, Yotpo
- **Email Marketing**: Klaviyo, MailChimp
- **SEO**: TinyIMG, SearchPie
- **Analytics**: Google Analytics, Hotjar

## Support

For technical support:
1. Check this documentation first
2. Search our knowledge base
3. Contact support with theme version and issue details
4. Include screenshots when possible

**Theme Version**: 1.0.0
**Last Updated**: August 29, 2025
