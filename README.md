# Inventory Management Form

A modern, responsive inventory management form built with Bootstrap 5 and custom CSS. This form features a professional SaaS-style design with a clean, card-based layout.

## Features

### ✨ Modern Design
- Professional SaaS-style interface
- Card-based layout with subtle shadows
- Gradient backgrounds and modern typography
- Responsive design for all devices

### 📱 Responsive Layout
- 2-column layout on desktop
- Single-column layout on mobile
- Bootstrap grid system for optimal spacing
- Mobile-first approach

### 🎨 Enhanced Styling
- Custom CSS with CSS variables
- Smooth transitions and hover effects
- Focus states with scale animations
- Staggered fade-in animations
- Custom scrollbars for textareas

### 📋 Form Fields
- **Item Name** - Text input (required)
- **Category** - Dropdown with common categories (required)
- **SKU/Code** - Text input (required)
- **Quantity** - Number input with validation (required)
- **Purchase Price** - Number input with currency symbol (required)
- **Selling Price** - Number input with currency symbol (required)
- **Supplier** - Text input (optional)
- **Date Added** - Date picker (required)
- **Notes** - Textarea for additional information (optional)

### 🔧 Technical Features
- Bootstrap 5 framework
- Bootstrap Icons integration
- Custom CSS with modern design patterns
- No JavaScript dependencies
- Semantic HTML structure
- Accessibility features

## File Structure

```
inventory-managment/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
└── README.md           # Project documentation
```

## Usage

1. **Open the form**: Simply open `index.html` in any modern web browser
2. **Fill out the form**: Enter the required information for your inventory item
3. **Submit**: Click the "Save Item" button to submit the form
4. **Clear**: Use the "Clear Form" button to reset all fields

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Dependencies

- **Bootstrap 5.3.0** - CSS framework (CDN)
- **Bootstrap Icons 1.11.0** - Icon library (CDN)

## Customization

### Colors
The color scheme can be easily customized by modifying the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #0d6efd;
    --primary-hover: #0b5ed7;
    --secondary-color: #6c757d;
    --success-color: #198754;
}
```

### Styling
- Modify border radius: `--border-radius`
- Adjust shadows: `--shadow-light`, `--shadow-medium`, `--shadow-heavy`
- Change transitions: `--transition`

### Categories
To add or modify categories, edit the `<select>` options in `index.html`:

```html
<option value="new-category">New Category</option>
```

## Features in Detail

### Form Validation
- Required field indicators (red asterisks)
- HTML5 validation attributes
- Visual feedback for valid/invalid states

### Responsive Design
- **Desktop**: 2-column layout with optimal spacing
- **Tablet**: Adaptive column layout
- **Mobile**: Single-column layout with full-width buttons

### Accessibility
- Proper label associations
- Semantic HTML structure
- Focus indicators
- Screen reader friendly

### Performance
- Lightweight CSS
- Optimized animations
- Efficient Bootstrap utilities
- Minimal external dependencies

## Browser Compatibility Notes

- **CSS Grid**: Modern browsers only
- **CSS Variables**: IE11+ (with polyfill)
- **Backdrop Filter**: WebKit browsers (Safari, Chrome)
- **CSS Animations**: All modern browsers

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve this form.

---

**Note**: This is a frontend-only implementation. To make it functional, you'll need to add backend processing and database storage for the form submissions.
