# FluxUI Sublime Text Package

Complete FluxUI component library for Sublime Text with intelligent autocomplete and snippets for Laravel Livewire development.

[![Package Control](https://img.shields.io/packagecontrol/dt/FluxUI?style=flat-square)](https://packagecontrol.io/packages/FluxUI)
[![GitHub release](https://img.shields.io/github/release/claudiodaud/fluxui-sublime-package.svg?style=flat-square)](https://github.com/claudiodaud/fluxui-sublime-package/releases)
[![GitHub stars](https://img.shields.io/github/stars/claudiodaud/fluxui-sublime-package.svg?style=flat-square)](https://github.com/claudiodaud/fluxui-sublime-package/stargazers)

## ✨ Features

- **94+ FluxUI Components** - Complete coverage of Free and Pro components
- **Intelligent Autocomplete** - Type `flux:` and see all available options
- **Blade Template Support** - Optimized for Laravel Blade templates
- **Livewire Integration** - Perfect for Livewire development
- **Clean Snippets** - Professional, ready-to-use component structures
- **No Bloat** - Just the essentials, no unnecessary properties

## 🚀 Installation

### Via Package Control (Recommended)

1. Open Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Type "Package Control: Install Package"
3. Search for "FluxUI"
4. Press Enter to install

### Manual Installation

1. Download the latest release
2. Extract to `Packages/User/FluxUI/`
3. Restart Sublime Text

## 📝 Usage

### Quick Start

1. Open any `.blade.php` file
2. Type `flux:` to see all available components
3. Use arrow keys to navigate, press Tab to expand

### Examples

```blade
flux:button     → <flux:button>Button</flux:button>
flux:table      → Complete table structure with columns and rows
flux:card       → <flux:card>Card content</flux:card>
flux:chart      → Chart component with SVG structure (Pro)
```

### Component Categories

**Layout Components:**
- `flux:header`, `flux:sidebar`, `flux:main`, `flux:footer`
- `flux:container`, `flux:spacer`, `flux:profile`

**Form Components:**
- `flux:input`, `flux:textarea`, `flux:select`, `flux:checkbox`
- `flux:radio`, `flux:switch`, `flux:field`, `flux:label`

**UI Components:**
- `flux:button`, `flux:badge`, `flux:avatar`, `flux:icon`
- `flux:modal`, `flux:tooltip`, `flux:dropdown`, `flux:menu`

**Navigation:**
- `flux:navbar`, `flux:navlist`, `flux:breadcrumbs`

**Pro Components:**
- `flux:card`, `flux:chart`, `flux:calendar`, `flux:tabs`
- `flux:table`, `flux:editor`, `flux:date-picker`

## ⚙️ Configuration

Access settings via `Preferences > Package Settings > FluxUI > Settings`

```json
{
    "auto_complete_triggers": [
        {
            "selector": "text.html.blade",
            "characters": "flux:"
        }
    ],
    "auto_complete_commit_on_tab": true,
    "enable_fluxui_completions": true
}
```

## 🎯 Requirements

- Sublime Text 3 or 4
- Laravel Blade Highlighter (recommended)

## 📚 Documentation

- [FluxUI Official Documentation](https://fluxui.dev)
- [Laravel Livewire](https://livewire.laravel.com)
- [Package Issues](https://github.com/claudiodaud/fluxui-sublime-package/issues)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [FluxUI Team](https://fluxui.dev) for creating this amazing component library
- [Laravel](https://laravel.com) and [Livewire](https://livewire.laravel.com) communities
- Sublime Text developers and community

---

**Made with ❤️ for the FluxUI, Livewire, Laravel and Sublime Text communities**
