# Everforest Xcode Themes 🌲

Beautiful, eye-friendly color themes for Xcode based on the popular [Everforest](https://github.com/sainnhe/everforest) color scheme. **Now with 100% accurate colors matching the official VSCode theme!**

## Why I Created This Project

As a developer who spends countless hours in Xcode, I was looking for a color scheme that would be gentle on my eyes during long coding sessions. After discovering the amazing Everforest theme in other editors, I noticed there wasn't an official Xcode port. This project brings the natural, warm aesthetics of Everforest to Xcode developers, maintaining the same carefully crafted color relationships that make the original theme so popular.

Everforest is designed to protect developers' eyes with its soft contrast and warm tones, making it perfect for those late-night coding sessions or anyone sensitive to harsh color schemes.

## Theme Variants

This package includes all 6 official Everforest theme variations:

### 🌙 Dark Themes
- **Everforest Dark Hard** - Highest contrast dark theme for maximum clarity
- **Everforest Dark Medium** - Balanced contrast dark theme (recommended)
- **Everforest Dark Soft** - Lowest contrast dark theme for minimal eye strain

### ☀️ Light Themes
- **Everforest Light Hard** - Highest contrast light theme for bright environments
- **Everforest Light Medium** - Balanced contrast light theme (recommended)
- **Everforest Light Soft** - Lowest contrast light theme for gentle viewing

## Installation

### Method 1: Manual Installation
1. **Download the themes**: Clone this repository or download the `.xccolortheme` files
2. **Install to Xcode**: Copy the `.xccolortheme` files to your Xcode themes directory:
   ```bash
   cp *.xccolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
   ```
3. **Apply the theme**: 
   - Open Xcode
   - Go to `Xcode > Preferences > Themes` (or `Xcode > Settings > Themes` on newer versions)
   - Select your preferred Everforest theme from the list

### Method 2: Command Line Installation
```bash
# Clone the repository
git clone https://github.com/agisilaos/everforest-xcode-themes.git
cd everforest-xcode-themes

# Install all themes
cp *.xccolortheme ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
```

## Syntax Color Mapping

### Dark Themes (Hard/Medium/Soft)

| Element | Color | Hex | Usage |
|---------|-------|-----|-------|
| **Keywords** | Red | `#E67E80` | `struct`, `class`, `func`, `var`, `let`, control flow |
| **Strings** | Yellow | `#DBBC7F` | String literals, string interpolation |
| **Comments** | Gray | `#859289` | Comments, documentation |
| **Numbers** | Purple | `#D699B6` | Numbers, booleans, literals |
| **Functions** | Green | `#A7C080` | Function names, method calls |
| **Types** | Blue | `#7FBBB3` | Type names, class names, protocols |
| **Variables** | Beige | `#D3C6AA` | Variable names, identifiers |
| **Constants** | Purple | `#D699B6` | Constants, static values, macros |
| **Operators** | Orange | `#E69875` | Operators, arithmetic symbols |
| **Preprocessor** | Aqua | `#83C092` | `#import`, `#define`, preprocessor directives |

### Light Themes (Hard/Medium/Soft)

| Element | Color | Hex | Usage |
|---------|-------|-----|-------|
| **Keywords** | Red | `#F85552` | `struct`, `class`, `func`, `var`, `let`, control flow |
| **Strings** | Yellow | `#DFA000` | String literals, string interpolation |
| **Comments** | Gray | `#939F91` | Comments, documentation |
| **Numbers** | Purple | `#DF69BA` | Numbers, booleans, literals |
| **Functions** | Green | `#8DA101` | Function names, method calls |
| **Types** | Blue | `#3A94C5` | Type names, class names, protocols |
| **Variables** | Dark Gray | `#5C6A72` | Variable names, identifiers |
| **Constants** | Purple | `#DF69BA` | Constants, static values, macros |
| **Operators** | Orange | `#F57D26` | Operators, arithmetic symbols |
| **Preprocessor** | Aqua | `#35A77C` | `#import`, `#define`, preprocessor directives |

## Background Color Palettes

### Dark Palette

#### Background Colors
| Variant | bg_dim | bg0 | bg1 | bg2 | bg3 | bg4 | bg5 |
|---------|--------|-----|-----|-----|-----|-----|-----|
| **Hard** | `#1E2326` | `#272E33` | `#2E383C` | `#374145` | `#414B50` | `#495156` | `#4F5B58` |
| **Medium** | `#232A2E` | `#2D353B` | `#343F44` | `#3D484D` | `#475258` | `#4F585E` | `#56635f` |
| **Soft** | `#293136` | `#333C43` | `#3A464C` | `#434F55` | `#4D5960` | `#555F66` | `#5D6B66` |

#### Special Background Colors
| Variant | Visual | Red | Yellow | Green | Blue | Purple |
|---------|--------|-----|--------|-------|------|--------|
| **Hard** | `#4C3743` | `#493B40` | `#45443c` | `#3C4841` | `#384B55` | `#463F48` |
| **Medium** | `#543A48` | `#514045` | `#4D4C43` | `#425047` | `#3A515D` | `#4A444E` |
| **Soft** | `#5C3F4F` | `#59464C` | `#55544A` | `#48584E` | `#3F5865` | `#4E4953` |

### Light Palette

#### Background Colors
| Variant | bg_dim | bg0 | bg1 | bg2 | bg3 | bg4 | bg5 |
|---------|--------|-----|-----|-----|-----|-----|-----|
| **Hard** | `#F2EFDF` | `#FFFBEF` | `#F8F5E4` | `#F2EFDF` | `#EDEADA` | `#E8E5D5` | `#BEC5B2` |
| **Medium** | `#EFEBD4` | `#FDF6E3` | `#F4F0D9` | `#EFEBD4` | `#E6E2CC` | `#E0DCC7` | `#BDC3AF` |
| **Soft** | `#E5DFC5` | `#F3EAD3` | `#EAE4CA` | `#E5DFC5` | `#DDD8BE` | `#D8D3BA` | `#B9C0AB` |

#### Special Background Colors
| Variant | Visual | Red | Yellow | Green | Blue | Purple |
|---------|--------|-----|--------|-------|------|--------|
| **Hard** | `#F0F2D4` | `#FFE7DE` | `#FEF2D5` | `#F3F5D9` | `#ECF5ED` | `#FCECED` |
| **Medium** | `#EAEDC8` | `#FDE3DA` | `#FAEDCD` | `#F0F1D2` | `#E9F0E9` | `#FAE8E2` |
| **Soft** | `#E1E4BD` | `#FADBD0` | `#F1E4C5` | `#E5E6C5` | `#E1E7DD` | `#F1DDD4` |

## Design Philosophy

The Everforest theme is designed with these principles:
- 🌲 **Natural & Warm**: Green-based color scheme inspired by forest aesthetics
- 👁️ **Eye-friendly**: Carefully designed to reduce eye strain during long coding sessions
- 🎨 **Consistent**: Maintains color harmony across different syntax elements
- 💡 **Versatile**: Works well with blue light filters like f.lux and redshift
- 🔍 **Accessible**: Provides good contrast while remaining gentle on the eyes
- ✅ **Accurate**: Colors match the official VSCode Everforest theme exactly

## Accuracy Guarantee

This Xcode port has been carefully verified against the official VSCode Everforest themes to ensure **100% color accuracy**. Every syntax highlighting color matches the original theme specification exactly, providing a consistent experience across editors.

## Screenshots

*Screenshots coming soon - please feel free to contribute by submitting screenshots of the themes in action!*

## About Everforest

Everforest is originally created by [sainnhe](https://github.com/sainnhe) and is available for many editors including:
- Vim/Neovim
- Visual Studio Code
- Sublime Text
- IntelliJ IDEA
- Terminal emulators
- And many more!

Visit the [official Everforest repository](https://github.com/sainnhe/everforest) to see all available ports and learn more about the color scheme's design philosophy.

## Contributing

Contributions are welcome! If you'd like to help improve these themes:

1. Fork this repository
2. Make your changes
3. Test the themes in Xcode
4. Submit a pull request

### Ideas for Contributions
- Screenshots of the themes in action
- Bug fixes for color mappings
- Documentation improvements
- Testing on different Xcode versions

## License

This project is inspired by and maintains compatibility with the original [Everforest](https://github.com/sainnhe/everforest) color scheme. Please refer to the original repository for licensing information.

## Changelog

### v1.1.0 - Color Accuracy Update
- ✅ Fixed all color mismatches with official VSCode themes
- ✅ Corrected string colors (now proper yellow instead of green)
- ✅ Fixed type/class colors (now proper blue instead of yellow)
- ✅ Corrected constant colors (now proper purple instead of aqua)
- ✅ Fixed preprocessor colors (now proper aqua instead of purple)
- ✅ Applied fixes to all 6 theme variants (Dark + Light × Hard/Medium/Soft)

### v1.0.0 - Initial Release
- 🎉 All 6 Everforest theme variants for Xcode
- 🌲 Complete color palette implementation
- 📖 Comprehensive documentation

## Acknowledgments

- **[sainnhe](https://github.com/sainnhe)** - Creator of the original Everforest color scheme
- The Everforest community for maintaining such a beautiful and thoughtful color palette
- Xcode developers who value eye-friendly coding environments

---

*Enjoy coding with the natural beauty of Everforest! 🌲*