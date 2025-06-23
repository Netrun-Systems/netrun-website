# Shared Assets Directory

This directory contains shared resources used across all Netrun Systems product websites.

## Structure

```
shared-assets/
├── css/
│   ├── base.css          # Base styles shared across all products
│   └── components.css    # Reusable component styles
├── js/
│   ├── analytics.js      # Shared analytics tracking
│   └── common.js         # Common JavaScript utilities
├── images/
│   ├── logos/           # Product and company logos
│   ├── icons/           # Shared icon set
│   └── illustrations/   # Common illustrations
└── fonts/               # Custom web fonts
```

## Usage

Reference shared assets from product websites using relative paths:

```html
<!-- From product website -->
<link rel="stylesheet" href="../../shared-assets/css/base.css">
<script src="../../shared-assets/js/analytics.js"></script>
```

## Guidelines

1. **Consistency**: All shared assets should maintain consistent branding
2. **Performance**: Optimize all images and minimize CSS/JS files
3. **Documentation**: Document any new shared components
4. **Versioning**: Use semantic versioning for major updates

## Product-Specific Assets

Each product maintains its own assets in their respective directories:
- Intirkast: `product-websites/intirkast-site/`
- Intirfix: `product-websites/intirfix-site/`
- Intirkon: `product-websites/intirkon-site/` 