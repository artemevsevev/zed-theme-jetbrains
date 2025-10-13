# JetBrains Themes for Zed Editor

A color theme extension for the [Zed editor](https://zed.dev/) based on JetBrains IDE color schemes. This theme brings the familiar and comfortable look of JetBrains IDEs (IntelliJ IDEA, PyCharm, WebStorm, RustRover, etc.) to your Zed editor experience.

## Features

- Includes both **light** and **dark** theme variants
- Carefully crafted color palette based on JetBrains IDE themes
- Optimized for code readability and extended coding sessions
- Syntax highlighting that follows JetBrains color conventions

## Installation

To install the theme in Zed editor, open the [extension page](https://zed.dev/extensions/jetbrains-themes) and click **Install in Zed**.

Alternatively, you can install it from within the Zed editor:
1. Open Zed editor
2. Press `Cmd+Shift+P` (macOS) or `Ctrl+Shift+P` (Linux/Windows) to open the command palette
3. Type "extensions" and select **Extensions: Install Extensions**
4. Search for "JetBrains"
5. Click **Install** on the JetBrains Themes extension

## Theme Previews

### JetBrains Dark

![jetbrains-dark](./screenshots/dark.png)

### JetBrains Light

![jetbrains-light](./screenshots/light.png)

## Activating the Theme

After installation, you can activate the theme:
1. Press `Cmd+K` then `Cmd+T` (macOS) or `Ctrl+K` then `Ctrl+T` (Linux/Windows)
2. Select **JetBrains Dark** or **JetBrains Light** from the theme selector

### Automatic Theme Switching

You can configure Zed to automatically switch between light and dark themes based on your system theme. Add the following to your Zed settings (`Cmd+,` or `Ctrl+,` to open settings):

```json
"theme": {
  "mode": "system",
  "light": "JetBrains Light",
  "dark": "JetBrains Dark"
}
```

With this configuration, the theme will automatically match your operating system's appearance settings.
