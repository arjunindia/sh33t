# 📊 Sheet - A Powerful Virtual Scrolling Spreadsheet

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=flat&logo=github)](https://github.com/arjunindia/sh33t)
[![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?style=flat&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-blue?style=flat&logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)

> A feature-rich, browser-based spreadsheet application with virtual scrolling, formula support, AI integration, and seamless data management. Built entirely with vanilla HTML, CSS, and JavaScript - all in just 37KB!

[![spreadsheet demo](https://i.ibb.co/7G5Q0YB/vivaldi-7o-GXSc7-TU2-ezgif-com-gif-maker.gif)](https://ibb.co/xSycn2TR)
*Experience the power of a full-fledged spreadsheet right in your browser!*

## 🌟 Key Features

### 📈 Virtual Scrolling Grid

- **Massive Capacity**: Handle up to **1,000 rows** and **50 columns** efficiently
- **Smooth Performance**: Only renders visible cells, ensuring lightning-fast scrolling
- **Dynamic Sizing**: Automatically adjusts to window resize for optimal viewing

### ✏️ Advanced Cell Editing

- **Intuitive Editing**: Double-click any cell to edit its content
- **Formula Support**: Powerful formula engine with cell references and functions
- **Real-time Evaluation**: Formulas update instantly as dependencies change

### 🧮 Formula Engine

- **Basic Arithmetic**: Full support for `+`, `-`, `*`, `/` operations
- **Built-in Functions**:
  - `SUM(range)`: Calculate sum of a cell range
  - `AVERAGE(range)`: Compute average of a cell range
- **Cell References**: Use `A1`, `B2:C10` style references in formulas

### 🤖 AI-Powered Features

- **AI Integration**: Connect to OpenAI API for intelligent data processing
- **Smart Settings**: Secure modal for configuring API credentials
- **Ask AI**: Natural language prompts to update sheet data
- **AI Formulas**: Use `=AI(prompt)` for dynamic AI-generated content
- **Offline Handling**: Graceful degradation when internet is unavailable

### ⌨️ Powerful Keyboard Shortcuts

- **Navigation**: Arrow keys for seamless cell movement
- **Editing**: Enter to edit, Escape to cancel
- **Operations**:
  - `Ctrl+Z` / `Ctrl+Y`: Undo/Redo
  - `Ctrl+C` / `Ctrl+V` / `Ctrl+X`: Copy/Paste/Cut
  - `Ctrl+Shift+C`: Copy cell value only
  - `Del`: Delete cell content
- **File Operations**:
  - `Ctrl+N`: New sheet
  - `Ctrl+S`: Save as CSV
  - `Ctrl+O`: Open CSV
- **AI Shortcuts**:
  - `Ctrl+Alt+S`: AI Settings
  - `Ctrl+Alt+A`: Ask AI

### 📋 Clipboard Management

- **Full Cell Copy**: Preserves both value and formula
- **Value-Only Copy**: Copy just the displayed value
- **Smart Paste**: Handles cut/copy operations seamlessly
- **Cross-Cell Operations**: Copy formulas that adapt to new locations

### 💾 Data Persistence

- **CSV Export**: Save your work as industry-standard CSV files
- **CSV Import**: Load existing spreadsheets with full formula support
- **Local Storage**: AI settings persist across browser sessions
- **Undo/Redo History**: 100-level history for safe editing

### 🎨 User Interface

- **Responsive Design**: Adapts beautifully to any screen size
- **Professional Styling**: Clean, modern interface with subtle animations
- **Hover Effects**: Visual feedback for better user experience
- **Focus Indicators**: Clear highlighting of active cells
- **Tooltips**: Show full content for truncated cells

### 🗂️ Menu System

- **File Menu**:
  - New Sheet: Start fresh
  - Save as CSV: Export your data
  - Open CSV: Import existing files
- **Edit Menu**:
  - Undo/Redo: Time travel through your edits
  - Cut/Copy/Paste: Standard clipboard operations
  - Delete: Clear cell contents
- **AI Menu**:
  - Settings: Configure AI integration
  - Ask AI: Interactive AI assistance

### 🔧 Advanced Features

- **Formula Dependencies**: Automatic recalculation when referenced cells change
- **Error Handling**: Clear error messages for invalid formulas
- **Focus Trapping**: Proper modal accessibility
- **Cell Validation**: Intelligent handling of different data types
- **Performance Optimized**: Efficient rendering for large datasets

## 🚀 Quick Start

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for AI features (optional)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/arjunindia/sh33t.git
   cd sh33t
   ```

2. **Open the application**:
   - Simply open `index.html` in your web browser
   - No server required - works directly from file system!

### Basic Usage

1. **Navigate**: Use arrow keys or click cells to move around
2. **Edit**: Double-click a cell or press Enter to start editing
3. **Formulas**: Start with `=` for formulas (e.g., `=A1+B1`)
4. **Save**: Press `Ctrl+S` to export as CSV
5. **AI**: Configure in AI Settings and use `=AI(prompt)` or Ask AI modal

## 🛠️ Technical Architecture

### Core Technologies

- **Frontend**: Pure HTML5, CSS3, ES6+ JavaScript
- **No Dependencies**: Zero external libraries for maximum portability
- **Browser APIs**: Leverages modern browser features for optimal performance

### Key Components

- **Virtual Scrolling Engine**: Custom implementation for handling large grids
- **Formula Parser**: Safe evaluation using JavaScript's Function constructor
- **AI Integration Layer**: RESTful API communication with OpenAI
- **State Management**: In-memory Maps for cell values and formulas
- **Event System**: Comprehensive event handling for user interactions

### Performance Optimizations

- **Lazy Rendering**: Only visible cells are created and rendered
- **Efficient Updates**: Targeted re-rendering of affected cells
- **Memory Management**: Automatic cleanup of unused DOM elements
- **Debounced Operations**: Smooth scrolling and resizing

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

### Development Guidelines

- Follow existing code style and naming conventions
- Add comments for complex logic
- Test thoroughly across different browsers
- Update documentation for new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic spreadsheet applications
- Built with modern web standards in mind
- Special thanks to the open-source community

---

**Made with ❤️ and vanilla JavaScript**

*Experience the future of web-based spreadsheets - no installation, no plugins, just pure productivity!*

![GitHub stars](https://img.shields.io/github/stars/arjunindia/sh33t?style=social)
![GitHub forks](https://img.shields.io/github/forks/arjunindia/sh33t?style=social)
