# Code Editor

A sleek, modern web-based code editor that allows you to write and preview HTML, CSS, and JavaScript code in real-time. Perfect for quick prototyping, learning web development, or testing code snippets.



## ✨ Features

- **Real-time Preview**: See your code changes instantly in the output panel
- **Multi-language Support**: Write HTML, CSS, and JavaScript in separate panels
- **Modern UI**: Clean, professional interface with syntax highlighting icons
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark Theme**: Easy on the eyes with a modern dark color scheme
- **Live Updates**: Code executes automatically as you type (on keyup)

## 🚀 Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling with modern features like Flexbox and custom properties
- **JavaScript**: Dynamic functionality and code execution
- **Boxicons**: Beautiful icons for language identification
- **Google Fonts**: Poppins font family for clean typography

## 📋 Project Structure

```
code-editor/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/code-editor.git
   cd code-editor
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using Live Server (VS Code extension)
   Right-click on index.html → "Open with Live Server"
   ```

3. **Start coding!**
   - Write HTML in the first textarea
   - Add CSS styling in the second textarea
   - Include JavaScript functionality in the third textarea
   - Watch your code come to life in the output panel

## 💻 How to Use

1. **HTML Panel**: Write your HTML structure
2. **CSS Panel**: Add styles to beautify your HTML
3. **JavaScript Panel**: Add interactivity and dynamic behavior
4. **Output Panel**: View the live result of your code

The editor automatically updates the preview as you type, making it perfect for rapid prototyping and experimentation.

## 🎨 Features in Detail

### Real-time Execution
- Code runs automatically on every keystroke (`onkeyup` event)
- Instant feedback for quick debugging and testing

### Responsive Layout
- Vertical stacking on mobile devices
- Optimized textarea heights for different screen sizes
- Flexible layout using CSS Flexbox

### Visual Indicators
- Color-coded icons for each language (HTML5, CSS3, JavaScript)
- Hover effects on labels for better user experience
- Professional color scheme with accent colors

## 🔧 Customization

### Changing the Theme
Modify the CSS variables in `style.css`:
```css
:root {
    --bg-primary: #1e1e2f;
    --bg-secondary: #252744;
    --accent-color: #2898c1;
    --text-color: #fff;
}
```

### Adding New Features
- **Syntax Highlighting**: Integrate CodeMirror or Monaco Editor
- **File Management**: Add save/load functionality
- **Multiple Tabs**: Support for multiple code files
- **Console Output**: Display JavaScript console messages

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📱 Mobile Experience

The editor is fully responsive and works great on mobile devices:
- Touch-friendly interface
- Optimized layout for small screens
- Smooth scrolling and zooming

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Boxicons](https://boxicons.com/) for the beautiful icons
- [Google Fonts](https://fonts.google.com/) for the Poppins font family
- Inspired by popular online code editors like CodePen and JSFiddle

## 📧 Contact

Your Name - Sai Revu

Project Link: [https://github.com/yourusername/code-editor](https://github.com/SaiAkhil145/Code-Editor)

---

⭐ Star this repository if you found it helpful!
