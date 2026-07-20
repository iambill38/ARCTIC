# Arctic Luxury E-Commerce

A simple, elegant luxury fashion website with premium design inspired by arctic aesthetics.

## What's Included

✓ Beautiful homepage with hero section  
✓ Product grid (6 featured products)  
✓ Editorial banner section  
✓ Luxury footer  
✓ Full product detail page (PDP)  
✓ Color & size selectors  
✓ Quantity controls  
✓ Responsive design (mobile & desktop)  
✓ Smooth scroll effects  
✓ Glass morphism effects  

## Design Features

- **Arctic Color Palette**: Deep grays, silver accents, ice blue highlights
- **Premium Typography**: Bebas Neue for headings, Inter for body text
- **Smooth Interactions**: Click products to view details
- **Responsive**: Works beautifully on mobile, tablet, desktop
- **No Build Process**: Just open index.html in your browser

## How to Use

1. **Open in Browser**:
   - Simply open `index.html` in any web browser
   - No installation or dependencies needed

2. **Click Products**:
   - Click any product card to view full details
   - Adjust colors, sizes, and quantity
   - Click "BACK TO SHOP" to return to homepage

3. **Customize**:
   - Edit product names and prices in the HTML
   - Change colors in the CSS (look for color codes like #D7DDE5)
   - Modify text content directly

## File Structure

```
arctic-luxury/
├── index.html          ← Complete website (open this!)
└── README.md          ← This file
```

## Customization Guide

### Change Product Names/Prices
Find this section and edit:
```html
<div class="product-item" onclick="viewProduct('ARCTIC SHELL', 599)">
```

### Change Colors
Look for these color codes in the CSS and modify:
- `#111317` - Background
- `#D7DDE5` - Silver accent
- `#CFEFFF` - Light blue hover
- `#B7C0CC` - Text secondary

### Add Product Images
Replace placeholder letters (A, B, C, etc.) with actual images:
```html
<div class="product-image-inner">A</div>
<!-- Replace A with <img src="your-image.jpg"> -->
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## That's It!

No build tools, no dependencies, no complications. Just pure HTML, CSS, and JavaScript.

Enjoy! ❄️
