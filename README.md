# VIII-III-MMV Theme

A sophisticated dark theme for Visual Studio Code with vibrant accent colors and exceptional syntax highlighting designed for modern developers who spend long hours coding.

## ✨ Features

- **🌙 Deep Dark Background**: Ultra-dark editor background (`#0a0a0f`) for reduced eye strain during extended coding sessions
- **🎨 Vibrant Accent Colors**: Striking neon green (`#00ff88`) and cyan (`#00d4ff`) accents for enhanced visual hierarchy
- **⚡ High Contrast Syntax**: Carefully selected colors for maximum readability across all programming languages
- **🔧 Complete UI Coverage**: Fully themed interface including sidebar, activity bar, terminal, and panels
- **🎯 Language Optimized**: Special highlighting for HTML, CSS, JavaScript, JSON, Markdown, and more
- **🔍 Git Integration**: Distinct colors for git decorations (added, modified, deleted, untracked files)

## 🎨 Color Palette

| Element | Color | Hex Code |
|---------|-------|----------|
| Primary Accent | ![#00ff88](https://via.placeholder.com/15/00ff88/000000?text=+) | `#00ff88` |
| Secondary Accent | ![#00d4ff](https://via.placeholder.com/15/00d4ff/000000?text=+) | `#00d4ff` |
| Keywords | ![#ff0066](https://via.placeholder.com/15/ff0066/000000?text=+) | `#ff0066` |
| Strings | ![#66ff99](https://via.placeholder.com/15/66ff99/000000?text=+) | `#66ff99` |
| Classes/Types | ![#ffdd33](https://via.placeholder.com/15/ffdd33/000000?text=+) | `#ffdd33` |
| Numbers | ![#ff9933](https://via.placeholder.com/15/ff9933/000000?text=+) | `#ff9933` |

## 📦 Installation

### From VS Code Marketplace
1. Open Visual Studio Code
2. Go to Extensions (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for "VIII-III-MMV"
4. Click **Install**
5. Select the theme: `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T` → Choose "VIII-III-MMV"

### Manual Installation
1. Download the theme files
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

2. Copy to your VS Code extensions folder:
   - **Windows**: `%USERPROFILE%\.vscode\extensions`
   - **macOS**: `~/.vscode/extensions`
   - **Linux**: `~/.vscode/extensions`
3. Restart VS Code
4. Activate the theme from the Command Palette

## 🚀 Quick Start

After installation, activate the theme:

1. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type "Preferences: Color Theme"
3. Select "VIII-III-MMV"

## 🛠️ Customization

### Override Theme Colors

Add custom colors to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[VIII-III-MMV]": {
      "editor.background": "#0a0a0f",
      "editorCursor.foreground": "#00ff88",
      "editor.selectionBackground": "#264f78"
    }
  }
}
```

### Customize Token Colors

Modify syntax highlighting in your `settings.json`:

```json
{
  "editor.tokenColorCustomizations": {
    "[VIII-III-MMV]": {
      "comments": "#6a6a80",
      "functions": "#00ff88",
      "keywords": "#ff0066",
      "strings": "#66ff99"
    }
  }
}
```

## 🎯 Optimized For

- **Languages**: JavaScript, TypeScript, Python, HTML, CSS, JSON, Markdown, React, Vue
- **Frameworks**: Node.js, React, Angular, Vue.js, Express
- **File Types**: Configuration files, Docker, YAML, XML
- **Development**: Frontend, Backend, Full-stack development

## 🔧 Theme Highlights

### Editor Features
- **Cursor**: Bright neon green for easy tracking
- **Line Numbers**: Subtle with active line highlight
- **Selection**: Semi-transparent blue overlay
- **Indent Guides**: Subtle visual hierarchy

### UI Components
- **Activity Bar**: Clean design with active state indicators
- **Sidebar**: Organized with clear section headers
- **Tabs**: Active tab highlighting with distinct borders
- **Terminal**: Full 16-color ANSI support

### Git Integration
- 🟢 **Added**: `#00ff88` (Bright Green)
- 🟡 **Modified**: `#ffdd33` (Yellow)
- 🔴 **Deleted**: `#ff3366` (Red)
- 🟣 **Untracked**: `#cc66ff` (Purple)
- 🟠 **Conflicted**: `#ff9933` (Orange)

## 📸 Screenshots

*Screenshots will be added in future updates*

## 🐛 Known Issues

- None currently reported

## 📝 Changelog

### [1.0.0] - Initial Release
- Complete dark theme implementation
- Full syntax highlighting for major languages
- UI component theming
- Git decoration support

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs
- Suggest improvements
- Submit pull requests

## 📄 License

This theme is released under the MIT License. See LICENSE file for details.

## 💝 Support

If you enjoy this theme, consider:
- ⭐ Starring the repository
- 📝 Leaving a review on the VS Code Marketplace
- 🐛 Reporting issues or suggestions

## 🔗 Links

- [VS Code Marketplace](#)
- [GitHub Repository](#)
- [Bug Reports](#)
- [Feature Requests](#)

---

**Made with 💚 for developers who code in style**

*VIII-III-MMV - Because your code deserves to look as good as it works.*