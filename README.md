<details>
<summary><b>📋 Workflow Builder - Complete Documentation</b></summary>
Link to my website:- https://avi-47.github.io/workflow_builder_web/
  
# Workflow Builder

A modern, interactive web-based flowchart and workflow diagram builder with drag-and-drop functionality, real-time editing, and PDF export capabilities.

![Workflow Builder](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## ✨ Features

### Core Functionality
- **Drag & Drop Interface**: Intuitive element placement from sidebar to canvas
- **8 Element Types**: Start/End, Process, Decision, Connector, Document, Database, Predefined, and Delay shapes
- **Smart Connections**: Visual connection points with curved arrow connectors
- **Real-time Editing**: Click-to-edit text with live preview
- **Multi-selection**: Select multiple elements with Ctrl/Cmd+Click

### Visual Customization
- **Color Customization**: Change text and border colors for elements
- **Grid Background**: Clean grid layout for precise alignment
- **Zoom Controls**: Zoom in/out with mouse wheel or controls (30%-300%)
- **Responsive Design**: Works on desktop and mobile devices

### Advanced Features
- **Undo/Redo**: Full history tracking with Ctrl+Z support
- **Copy/Paste**: Duplicate elements and workflows
- **PDF Export**: High-quality PDF generation of your diagrams
- **Keyboard Shortcuts**: Speed up workflow creation with hotkeys
- **Auto-save State**: Maintains your work during the session

## 🚀 Quick Start

1. **Clone or Download**: Get the `workflow_builder.html` file
2. **Open in Browser**: Simply open the HTML file in any modern web browser
3. **Start Creating**: Drag elements from the sidebar to the canvas
4. **Connect Elements**: Click connection points to link elements
5. **Export**: Use the "Export PDF" button to save your diagram

## 🎯 How to Use

### Creating Elements
- **Drag & Drop**: Drag elements from the left sidebar to the canvas
- **Keyboard Shortcuts**: Use hotkeys to quickly add elements:
  - `S` - Start/End element
  - `P` - Process element
  - `D` - Decision element
  - `C` - Connector element
  - `O` - Document element
  - `B` - Database element
  - `R` - Predefined element
  - `L` - Delay element

### Editing Elements
- **Text Editing**: Click any element to edit its text
- **Color Customization**: Use the color picker to change text and border colors
- **Moving Elements**: Click and drag elements to reposition them
- **Deleting Elements**: Click the × button or press Delete/Backspace

### Creating Connections
1. Click a connection point on any element (blue dots appear on hover)
2. Click another connection point on a different element
3. A curved arrow will connect the elements
4. Click connections to select and delete them

### Navigation & Controls
- **Zoom**: Use Ctrl+Mouse Wheel, zoom controls, or keyboard shortcuts:
  - `Ctrl +` - Zoom in
  - `Ctrl -` - Zoom out
  - `Ctrl 0` - Reset zoom
- **Selection**: 
  - Click elements to select
  - `Ctrl+A` - Select all
  - `Ctrl+Click` - Multi-select
- **Copy/Paste**: `Ctrl+C` to copy, `Ctrl+V` to paste selected elements

## ⌨️ Keyboard Shortcuts

| Action | Shortcut | Description |
|--------|----------|-------------|
| Add Start | `S` | Create Start/End element |
| Add Process | `P` | Create Process element |
| Add Decision | `D` | Create Decision element |
| Add Connector | `C` | Create Connector element |
| Add Document | `O` | Create Document element |
| Add Database | `B` | Create Database element |
| Add Predefined | `R` | Create Predefined element |
| Add Delay | `L` | Create Delay element |
| Delete | `Del/Backspace` | Delete selected elements |
| Undo | `Ctrl+Z` | Undo last action |
| Select All | `Ctrl+A` | Select all elements |
| Copy | `Ctrl+C` | Copy selected elements |
| Paste | `Ctrl+V` | Paste copied elements |
| Zoom In | `Ctrl +` | Increase zoom level |
| Zoom Out | `Ctrl -` | Decrease zoom level |
| Reset Zoom | `Ctrl 0` | Reset to 100% zoom |
| Show Shortcuts | `H` | Toggle keyboard shortcuts help |
| Cancel/Escape | `Esc` | Cancel current operation |

## 🎨 Element Types

| Element | Description | Use Case |
|---------|-------------|----------|
| **Start/End** | Oval shapes | Process start and end points |
| **Process** | Rectangles | Process steps and actions |
| **Decision** | Diamonds | Decision points and branching |
| **Connector** | Circles | Connection and flow points |
| **Document** | Document shape | Input/output documents |
| **Database** | Cylinder shape | Data storage operations |
| **Predefined** | Double-bordered rectangles | Predefined processes |
| **Delay** | Circle with arrow | Wait or delay operations |

## 🔧 Technical Details

### Browser Compatibility
- **Modern Browsers**: Chrome 70+, Firefox 65+, Safari 12+, Edge 79+
- **Mobile Support**: iOS Safari 12+, Chrome Mobile 70+
- **Dependencies**: None - pure HTML, CSS, and JavaScript

### File Structure
```
workflow_builder.html
├── HTML Structure
├── CSS Styling (embedded)
├── JavaScript Logic (embedded)
└── External Dependencies
    └── jsPDF (CDN) - for PDF export
```

### Performance
- **Lightweight**: Single HTML file under 50KB
- **Responsive**: Smooth interactions up to 100+ elements
- **Memory Efficient**: Clean up and garbage collection
- **Export Quality**: High-resolution PDF output

## 📱 Mobile Support

- Touch-friendly interface
- Responsive design for tablets and phones
- Gesture support for zoom and pan
- Optimized button sizes for touch interaction

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

1. **Bug Reports**: Report issues via GitHub Issues
2. **Feature Requests**: Suggest new features or improvements
3. **Code Contributions**: Submit pull requests with enhancements
4. **Documentation**: Help improve documentation and examples

### Development Setup
1. Fork the repository
2. Make your changes to `workflow_builder.html`
3. Test in multiple browsers
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web standards (HTML5, CSS3, ES6+)
- PDF export powered by [jsPDF](https://github.com/parallax/jsPDF)
- Inspired by traditional flowchart tools with modern web capabilities

## 📊 Examples

### Basic Process Flow
```
[Start] → [Process 1] → [Decision] → [Process 2] → [End]
                           ↓
                      [Alternative Process] → [End]
```

### Data Flow Example
```
[Database] → [Process Data] → [Document Output]
```

## 🐛 Known Issues

- Complex curves in connections may not export perfectly to PDF
- Very large diagrams (500+ elements) may experience performance degradation
- Mobile text editing requires careful touch handling

## 🔮 Future Enhancements

- [ ] Template library with common workflow patterns
- [ ] Collaborative editing support
- [ ] Export to other formats (SVG, PNG, JSON)
- [ ] Grid snap and alignment guides
- [ ] Custom element shapes and styling
- [ ] Integration with popular diagramming services

---

**Made with ❤️ for the developer community**

For questions, suggestions, or support, please open an issue on GitHub.
