# CloudDown

A clean, reliable cross-platform Markdown editor with seamless cloud storage integration.

[![Download on App Store](https://img.shields.io/badge/Download-App%20Store-blue)](https://apps.apple.com/app/clouddown)
[![Get it on Google Play](https://img.shields.io/badge/Download-Google%20Play-green)](https://play.google.com/store/apps/details?id=io.github.digitalninjae.clouddown)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![CloudDown Demo](assets/demo.gif)

## Why CloudDown?

Existing mobile and desktop Markdown editors struggle with cloud storage - files don't save reliably, or require complex sync setups. CloudDown uses native platform file APIs correctly, so your edits actually save to OneDrive, iCloud, Google Drive, and local storage without hassle.

## Features

### Three Powerful Editing Modes

**Writer Mode** ✨
- Edit beautifully formatted text directly
- See headers, bold, italic, lists as you type
- Native implementation (not WebView)
- Perfect for focused writing

**Editor Mode** 💻
- Raw Markdown with syntax highlighting
- Full control over formatting
- Keyboard shortcuts
- Fast and efficient

**Split Mode** 📱
- Live preview alongside editing
- Synchronized scrolling
- Great for learning Markdown

### Cloud Storage Integration

- ☁️ OneDrive
- ☁️ iCloud (iOS/macOS)
- ☁️ Google Drive
- 📁 Local files

### Additional Features

- ⚡ Auto-save with visual status
- 🌙 Dark and light themes
- 📱 Offline editing
- 🔧 Formatting toolbar
- 📋 Recent files
- ⌨️ Keyboard shortcuts
- 🔒 Privacy-focused (no tracking)

## Download

- **iOS/iPadOS:** [App Store](https://apps.apple.com/app/clouddown) (Coming soon)
- **Android:** [Google Play](https://play.google.com/store/apps/details?id=io.github.digitalninjae.clouddown) (Coming soon)
- **Windows:** [Microsoft Store](https://www.microsoft.com/store/apps/clouddown) (Coming soon)
- **macOS:** [App Store](https://apps.apple.com/app/clouddown) (Coming soon)

## Building from Source

### Prerequisites
- .NET 8 SDK
- Visual Studio 2022 or VS Code

### Build
```bash
git clone https://github.com/digitalninjae/clouddown.git
cd clouddown
dotnet restore
dotnet build
```

### Run
```bash
# Android
dotnet build -t:Run -f net8.0-android

# iOS (Mac only)
dotnet build -t:Run -f net8.0-ios

# Windows
dotnet build -t:Run -f net8.0-windows10.0.19041.0

# macOS
dotnet build -t:Run -f net8.0-maccatalyst
```

## Documentation

- [User Guide](docs/user-guide.md)
- [Cloud Storage Setup](docs/cloud-storage-setup.md)
- [Keyboard Shortcuts](docs/keyboard-shortcuts.md)
- [FAQ](docs/faq.md)

## Privacy

CloudDown respects your privacy. See [PRIVACY.md](PRIVACY.md) for details.

- No tracking or analytics
- No accounts required
- Your files stay yours
- Open source and auditable

## Technology

Built with:
- [.NET MAUI](https://github.com/dotnet/maui)
- [CloudDown.Editor](https://github.com/digitalninjae/clouddown-editor) - Reusable markdown editor library
- [Markdig](https://github.com/xoofx/markdig) - Markdown processing

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## License

MIT - See [LICENSE](LICENSE)

## Support

- 🐛 [Report bugs](https://github.com/digitalninjae/clouddown/issues)
- 💡 [Request features](https://github.com/digitalninjae/clouddown/issues)
- 💬 [Discussions](https://github.com/digitalninjae/clouddown/discussions)

## Author

Built by [Brian Cupples](https://github.com/digitalninjae)

---

**Like CloudDown? Star the repo! ⭐**
