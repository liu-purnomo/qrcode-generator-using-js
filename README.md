# QR Code Generator - Advanced

A modern, feature-rich QR code generator with extensive customization options built with vanilla JavaScript.

## Features

### Customization Options

- **Custom Size**: Adjustable QR code size from 128px to 512px
- **Custom Colors**:
  - Foreground (QR code) color picker with hex input
  - Background color picker with hex input
- **Logo/Icon Support**: Upload and overlay your logo on the QR code
  - Adjustable logo size (10% - 30% of QR code size)
  - Automatic white background padding for logo visibility
- **Finder Pattern Styles**:
  - Square (Default)
  - Rounded
  - Dots (Circular)
  - Extra Rounded
- **Error Correction Levels**: L (7%), M (15%), Q (25%), H (30%)
  - Higher levels allow for better logo overlay and damage resistance

### Export Options

- **PNG Format**: Perfect for digital use
- **JPG Format**: Smaller file size for web
- **SVG Format**: Vector format for scalability

## How to Use

1. **Enter URL/Text**: Input the URL or text you want to encode
2. **Customize Appearance**:
   - Adjust the size using the slider
   - Pick your preferred colors for QR code and background
   - Select error correction level
   - Choose a finder pattern style
3. **Add Logo (Optional)**:
   - Upload an image file (PNG, JPG, SVG, etc.)
   - Adjust logo size as needed
4. **Generate**: Click "Generate QR Code" button
5. **Download**: Choose your preferred format (PNG, JPG, or SVG)

## Technical Details

### Built With

- **QRious**: Core QR code generation library
- **Vanilla JavaScript**: No framework dependencies
- **HTML5 Canvas**: For advanced customization and rendering
- **CSS3**: Modern styling with gradient backgrounds

### Browser Support

Works on all modern browsers that support:
- HTML5 Canvas API
- File API
- ES6 JavaScript

### Features Implementation

#### Logo Overlay
The logo is centered on the QR code with a white circular background for better visibility. The size is adjustable to ensure the QR code remains scannable.

#### Custom Finder Patterns
The three corner squares (finder patterns) can be styled with:
- Rounded corners for a softer look
- Circular dots for a modern appearance
- Extra rounded for maximum smoothness

#### Color Customization
Full color picker support with synchronized hex input for precise color selection.

## Development

### File Structure

```
qrcode-generator-using-js/
├── index.html    # Main HTML file with JavaScript
├── style.css     # Styling and responsive design
└── README.md     # Documentation
```

### Local Development

Simply open `index.html` in a web browser. No build process or server required.

## Tips for Best Results

1. **Use High Error Correction**: When adding a logo, use level H (30%) for best results
2. **Logo Size**: Keep logo size between 15-25% for optimal scannability
3. **Contrast**: Ensure good contrast between foreground and background colors
4. **Testing**: Always test your QR code with multiple scanners before production use

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Author

Liu Purnomo - [liupurnomo.com](https://liupurnomo.com)

## Contributing

Contributions, issues, and feature requests are welcome!

---

Made with JavaScript and love
