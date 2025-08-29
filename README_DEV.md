# 🎨 Streetwear Pro - Shopify Theme

> A modern, mobile-first Shopify theme designed specifically for streetwear and urban fashion brands.

[![GitHub release](https://img.shields.io/github/release/AhmedAbdelhady22/streetwear-theme.svg)](https://github.com/AhmedAbdelhady22/streetwear-theme/releases)
[![Theme Check](https://img.shields.io/badge/Theme%20Check-Passing-brightgreen)](https://github.com/AhmedAbdelhady22/streetwear-theme/actions)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE.md)

## 🚀 Features

### 🎯 **Streetwear Focused**
- Urban aesthetic designed for streetwear brands
- Bold typography and modern layouts
- Product photography optimization
- Collection showcase capabilities
- Brand storytelling sections

### 📱 **Mobile-First Design**
- Responsive across all devices
- Touch-optimized interactions
- Fast mobile performance
- Progressive image loading
- Mobile checkout optimization

### ⚡ **Performance Optimized**
- Lighthouse Score: 90+
- Critical CSS loading
- Optimized asset delivery
- Minimal JavaScript footprint
- SEO-ready structure

### 🛍️ **E-commerce Features**
- Advanced product filtering
- Quick add to cart
- Variant selection with previews
- Shopping cart optimization
- Free shipping progress bar
- Enhanced search functionality

## 🛠️ Development Setup

### Prerequisites
- [Shopify CLI](https://shopify.dev/themes/tools/cli) 3.0+
- [Node.js](https://nodejs.org/) 18+
- Git
- A Shopify development store

### Installation
```bash
# Clone the repository
git clone https://github.com/AhmedAbdelhady22/streetwear-theme.git
cd streetwear-theme

# Connect to your development store
shopify theme dev

# Start development server
shopify theme serve
```

### Development Workflow
```bash
# Pull latest theme from store
shopify theme pull

# Make your changes locally
# Files are automatically synced when using 'shopify theme dev'

# Push changes to development theme
shopify theme push --development

# Create a new theme version
shopify theme push --unpublished
```

## 📁 File Structure

```
streetwear-pro-theme/
├── assets/           # CSS, JS, images
├── blocks/           # Reusable content blocks
├── config/           # Theme settings
├── layout/           # Base templates
├── locales/          # Translation files
├── sections/         # Page sections
├── snippets/         # Reusable code snippets
├── templates/        # Page templates
└── .github/          # GitHub workflows
```

## 🎨 Customization

### Theme Settings
The theme includes comprehensive customization options:
- **Brand Identity**: Logo, colors, typography
- **Layout Options**: Header styles, spacing, grid layouts
- **E-commerce Settings**: Cart behavior, product display
- **Social Integration**: Social media links and sharing

### Custom CSS
Add custom styles through the theme editor:
```css
/* Example: Custom button styles */
.btn--custom {
  background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
  border: none;
  color: white;
}
```

### Section Development
Create new sections using Shopify's section system:
```liquid
{% comment %} sections/custom-section.liquid {% endcomment %}
<section class="custom-section">
  <div class="container">
    <h2>{{ section.settings.heading }}</h2>
    <!-- Your section content -->
  </div>
</section>

{% schema %}
{
  "name": "Custom Section",
  "settings": [
    {
      "type": "text",
      "id": "heading",
      "label": "Section Heading"
    }
  ]
}
{% endschema %}
```

## 🚀 Deployment

### Using GitHub Actions (Recommended)
1. Fork this repository
2. Set up repository secrets:
   - `SHOPIFY_STORE`: Your store domain
   - `SHOPIFY_ACCESS_TOKEN`: Your private app token
3. Push changes to trigger automatic deployment

### Manual Deployment
```bash
# Deploy to your store
shopify theme push

# Deploy as new unpublished theme
shopify theme push --unpublished

# Deploy and publish
shopify theme push --live
```

## 📦 Creating Releases

### Automatic Releases
Create a git tag to trigger automatic release creation:
```bash
git tag v1.0.0
git push origin v1.0.0
```

### Manual Package Creation
```bash
# Create theme package for Shopify Theme Store
zip -r streetwear-pro-v1.0.0.zip \
  assets/ blocks/ config/ layout/ locales/ sections/ snippets/ templates/ \
  *.md *.json .shopifyignore \
  -x "*.git*" "*node_modules*"
```

## 🔍 Testing

### Theme Check (Linting)
```bash
# Install theme-check
gem install theme-check

# Run linting
theme-check .
```

### Performance Testing
```bash
# Test with Shopify CLI
shopify theme check

# Run Lighthouse audit
lighthouse https://your-store.myshopify.com
```

### Browser Testing
Test across major browsers:
- Chrome (latest)
- Firefox (latest)  
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📊 Analytics & Monitoring

### Performance Metrics
- Page load speed
- Core Web Vitals
- Conversion rates
- Mobile usability

### Error Monitoring
- JavaScript errors
- Liquid template errors
- 404 pages
- Performance bottlenecks

## 🤝 Contributing

### Development Process
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Standards
- Follow Shopify's Liquid best practices
- Use semantic HTML
- Write mobile-first CSS
- Add comments for complex logic
- Test across devices

### Pull Request Guidelines
- Include description of changes
- Add screenshots for UI changes
- Ensure all tests pass
- Update documentation if needed

## 📞 Support

- **Documentation**: [Theme Documentation](DOCUMENTATION.md)
- **Issues**: [GitHub Issues](https://github.com/AhmedAbdelhady22/streetwear-theme/issues)
- **Discussions**: [GitHub Discussions](https://github.com/AhmedAbdelhady22/streetwear-theme/discussions)
- **Email**: support@yourthemes.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments

- Shopify for the excellent theme development tools
- The streetwear community for design inspiration
- Contributors and testers

---

**Ready to elevate your streetwear brand?** Star ⭐ this repo and [get started today](DOCUMENTATION.md)!
