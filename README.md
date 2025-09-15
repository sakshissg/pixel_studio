# 🎨 Pixel Art Studio

A free, web-based pixel art drawing tool that allows you to create beautiful pixel artwork with ease. No more limitations of Excel - draw freely in any direction with full diagonal support!

## ✨ Features

### 🖌️ Drawing Tools
- **Flexible Drawing**: Click and drag to paint pixels in any direction, including diagonally
- **Paint Mode**: Select colors and draw with smooth drag functionality
- **Eraser Tool**: Remove pixels with precision
- **Clear Canvas**: Reset your entire artwork with one click

### 🎛️ Customizable Grid
- **Adjustable Grid Size**: 10x10 to 50x50 pixel canvas
- **Variable Pixel Size**: 8px to 30px individual pixel dimensions
- **Real-time Preview**: See changes instantly as you adjust settings

### 🎨 Color Management
- **Color Picker**: Easy point-and-click color selection
- **Hex Input**: Enter precise color codes (#FF0000 format)
- **Smart Color Palette**: Automatically saves your used colors
- **Pre-loaded Colors**: 12 common colors ready to use

### 💾 Export Options
- **Transparent Background**: Downloads with transparent background (perfect for logos)
- **High Resolution**: 4x scale factor for crisp, usable images
- **PNG Format**: Industry-standard format with full transparency support
- **Instant Download**: One-click download functionality

### 📊 Live Statistics
- **Pixel Counter**: Track how many pixels you've painted
- **Color Counter**: See how many different colors you've used
- **Visual Feedback**: Real-time updates as you draw

## 🚀 Getting Started

### Quick Start
1. Open the HTML file in any modern web browser
2. Adjust grid size and pixel size to your preference
3. Select a color from the palette or use the color picker
4. Click and drag on the canvas to start drawing
5. Use the eraser tool for corrections
6. Download your masterpiece as a PNG file

### No Installation Required
- **Browser-based**: Works entirely in your web browser
- **No Dependencies**: Single HTML file with everything included
- **Cross-platform**: Works on Windows, Mac, Linux, and mobile devices

## 🎯 Use Cases

- **Logo Design**: Create pixel art logos with transparent backgrounds
- **Game Assets**: Design sprites and icons for games
- **Digital Art**: Express creativity through pixel art
- **Educational**: Learn digital art fundamentals
- **Prototyping**: Quick mockups and designs

## 🛠️ Technical Details

### Built With
- **HTML5**: Modern semantic markup
- **CSS3**: Advanced styling with gradients and animations
- **Vanilla JavaScript**: No external dependencies
- **Canvas API**: For high-quality image export

### Browser Compatibility
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

### File Structure
```
index.html
├── HTML Structure
├── CSS Styling
└── JavaScript Logic
    ├── PixelArtEditor Class
    ├── Grid Management
    ├── Color Management
    ├── Drawing Logic
    └── Export Functionality
```

## 🎮 How to Use

### Basic Drawing
1. **Select Color**: Use color picker or click palette colors
2. **Start Drawing**: Click and drag on grid to paint pixels
3. **Diagonal Support**: Draw in any direction without restrictions
4. **Live Preview**: See your artwork update in real-time

### Advanced Features
- **Custom Colors**: Enter hex codes for precise colors (#FF0000)
- **Eraser Mode**: Toggle eraser to remove pixels
- **Grid Adjustment**: Change canvas size during drawing
- **Pixel Scaling**: Adjust pixel size for comfort

### Exporting
- **One-Click Download**: Press "Download PNG" button
- **Automatic Scaling**: Images export at 4x resolution
- **Transparent Background**: Perfect for overlaying on other images
- **Optimized Output**: Clean, professional results

## ⚙️ Customization

### Modify Scale Factor
To change the export image size, locate the `downloadImage()` function and modify:
```javascript
const scaleFactor = 4; // Change this number (2, 6, 8, etc.)
```

### Add More Default Colors
Modify the `defaultColors` array in `initializeColorPalette()`:
```javascript
const defaultColors = [
    '#ff0000', '#00ff00', '#0000ff', // Add more colors here
];
```

### Adjust Grid Limits
Change the min/max values in the HTML:
```html
<input type="range" id="gridSize" min="10" max="50" value="20">
```

## 🐛 Troubleshooting

### Common Issues
- **Small Download Images**: Scale factor is set to 4x by default
- **Colors Not Saving**: Clear browser cache and reload
- **Mobile Drawing Issues**: Try using a stylus or adjust pixel size

### Browser Issues
- **Safari**: May require user gesture for downloads
- **Mobile**: Some older browsers may have limited touch support

## 🤝 Contributing

This is a single-file project perfect for customization:
1. Modify colors, sizes, or features as needed
2. Add new tools or export formats
3. Improve mobile responsiveness
4. Add keyboard shortcuts

## 📄 License

This project is open source and available for personal and commercial use.

## 🌟 Why Choose Pixel Art Studio?

- **No Registration**: Start creating immediately
- **No Subscriptions**: Completely free forever
- **No Uploads**: Everything stays on your device
- **Professional Results**: High-quality exports with transparency
- **User Friendly**: Intuitive interface for all skill levels

---

**Start creating amazing pixel art today! 🚀**

*Perfect for artists, developers, designers, and anyone who loves creative expression through pixels.*
