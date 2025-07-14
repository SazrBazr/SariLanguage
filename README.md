# 🌟 Sari Programming Language (SariLang)

SariLang is a clean, expressive programming language designed to help you build **elegant**, **responsive**, and **cross-platform apps** for desktop and mobile — with a native UI syntax and built-in support for layout, theming, data binding, navigation, and more.

This VS Code extension adds syntax highlighting and custom file icons for `.sari` files.

---

## ✨ Features

- Syntax highlighting for `.sari` files
- Custom file icon in the VS Code explorer
- Highlighted UI structure for components, layouts, and bindings
- Comment, keyword, and function highlighting for clarity and speed
- Designed for readability and elegance

> Example:

```sari
app MyApp {
    window(title="Hello") {
        column(spacing=10) {
            label("Welcome to Sari")
                .font(size=20)
                .color(theme.primary)

            button("Click Me") {
                on_press {
                    notify("Thanks!")
                }
            }
        }
    }
}
```
You can also explore the full SariLang Syntax Reference for all supported features.

## 🧰 Requirements
This extension has no external dependencies. Just install it, and start writing .sari files.

## ⚙️ Extension Settings
Currently, this extension does not contribute any VS Code settings. Support for customization and themes may be added in future versions.

## 🐞 Known Issues
- No IntelliSense or auto-complete yet

- No linting or error diagnostics

- No preview or UI rendering support (planned)

Please report issues and suggestions here.

## 📦 Release Notes
### 0.0.1
- Initial release of SariLang extension

- Added syntax highlighting

- Added custom .sari file icon

## 💡 Working with Markdown
If you're editing this file:

- Split the editor (Ctrl+\)

- Toggle preview (Ctrl+Shift+V)

- Press Ctrl+Space to see Markdown snippet suggestions

## 🔗 For More Information
- Visual Studio Code Extension Docs

- VS Code Markdown Support
