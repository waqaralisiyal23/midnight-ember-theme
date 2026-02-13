# 🔥 Midnight Ember

> A premium dark theme with warm ember accents, teal highlights, and a rich midnight base. Built for developers who live in the dark.

![Midnight Ember](https://img.shields.io/badge/theme-dark-0D1117?style=for-the-badge&labelColor=0D1117&color=E8964F)
![VS Code](https://img.shields.io/badge/VS%20Code-1.70+-0D1117?style=for-the-badge&labelColor=0D1117&color=7DCFFF)
![License](https://img.shields.io/badge/license-MIT-0D1117?style=for-the-badge&labelColor=0D1117&color=3FB950)

---

## 🎨 Variants

### Midnight Ember
The flagship variant. Deep midnight blacks with bold ember orange keywords, teal functions, and rose strings. Maximum contrast for focused coding.

### Midnight Ember Soft
A gentler variant with slightly warmer backgrounds and softer pastel accents. Perfect for extended late-night sessions.

---

## 🌈 Color Palette

| Element | Midnight Ember | Midnight Ember Soft |
|---------|---------------|-------------------|
| **Background** | `#0F1419` | `#1A1A20` |
| **Foreground** | `#C9D1D9` | `#D4D4D8` |
| **Keywords** | `#E8964F` 🟠 | `#F5A97F` 🟠 |
| **Functions** | `#82CFBE` 🟢 | `#94E2D5` 🟢 |
| **Strings** | `#F7768E` 🔴 | `#F38BA8` 🔴 |
| **Types** | `#7DCFFF` 🔵 | `#89DCEB` 🔵 |
| **Numbers** | `#FF9E64` 🟡 | `#FFB86C` 🟡 |
| **Constants** | `#79C0FF` 🔵 | `#89B4FA` 🔵 |
| **Generics** | `#BB9AF7` 🟣 | `#CBA6F7` 🟣 |
| **Comments** | `#484F58` ⚫ | `#52525B` ⚫ |

---

## 📦 Installation

### From the Marketplace
1. Open VS Code
2. Go to **Extensions** (`Cmd+Shift+X` / `Ctrl+Shift+X`)
3. Search for **"Midnight Ember"**
4. Click **Install**
5. Go to **Settings** → **Color Theme** → Select **Midnight Ember** or **Midnight Ember Soft**

### Manual Installation
1. Clone or download this repository
2. Copy the folder to your VS Code extensions directory:
   - **macOS**: `~/.vscode/extensions/`
   - **Linux**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
3. Restart VS Code
4. Select the theme from **Settings** → **Color Theme**

### From VSIX
```bash
# Package the extension
npx -y @vscode/vsce package

# Install the VSIX file
code --install-extension midnight-ember-theme-1.0.0.vsix
```

---

## 🛠 Development

### Testing the Theme
1. Open this project in VS Code
2. Press `F5` to launch the Extension Development Host
3. In the new VS Code window, go to **Color Theme** and select **Midnight Ember**

### Customizing
The theme files are located in `./themes/`:
- `midnight-ember-color-theme.json` — Main variant
- `midnight-ember-soft-color-theme.json` — Soft variant

Use the **Developer: Inspect Editor Tokens and Scopes** command (`Cmd+Shift+P`) to find the scope names for any code element you want to customize.

---

## 🗣 Language Support

Optimized syntax highlighting for:
- **JavaScript / TypeScript** (including JSX/TSX)
- **Python**
- **Dart / Flutter**
- **Rust**
- **Go**
- **HTML / CSS / SCSS**
- **JSON / YAML / TOML**
- **Markdown**
- **SQL**
- **Shell / Bash**
- And more via TextMate grammars!

---

## 💜 Inspiration

Born out of years of loving **Shades of Purple** but wanting something fresh. Midnight Ember takes the "warm in the dark" philosophy and pushes it further with:
- Warmer, more natural accent colors
- Better contrast ratios for accessibility
- Comprehensive UI coverage (every corner of VS Code is themed)
- Semantic highlighting support for modern language servers

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 Waqar Ali Siyal

---

**Enjoy coding in the ember glow! 🔥**
