# Sand's Color Wheel

A professional color theory and palette generator with the distinctive Sand.gallery aesthetic - dark theme with gold accents.

![Sand's Color Wheel](https://img.shields.io/badge/version-1.0.0-gold)

## Features

### 🎨 Interactive Color Wheel
- Click anywhere on the wheel to select a color
- Automatic hue, saturation, and lightness extraction
- Real-time preview updates

### 🔄 Color Harmonies
Six harmony modes inspired by Canva's color wheel:
- **Complementary** - Two colors opposite on the wheel
- **Analogous** - Three adjacent colors
- **Triadic** - Three evenly spaced colors
- **Tetradic** - Four colors forming a rectangle
- **Monochromatic** - Variations in saturation/lightness
- **Split-Complementary** - Base color + two adjacent to complement

### 📊 Color Values
- HEX (e.g., #D4A853)
- RGB (e.g., rgb(212,168,83))
- HSL (e.g., hsl(42,60%,58%))
- One-click copy to clipboard

### 🛠️ Professional Tools

#### Sliders
Fine-tune Hue (0-360°), Saturation (0-100%), and Lightness (0-100%)

#### Shades Generator
Generate 10 shades/tints from any selected color - click to select

#### WCAG Contrast Checker
- Check contrast against white and black backgrounds
- WCAG AA (4.5:1) and AAA (7:1) badges
- Accessibility compliance at a glance

#### Color Blindness Simulator
Preview how colors appear to users with:
- Protanopia (red-blind)
- Deuteranopia (green-blind)
- Tritanopia (blue-blind)
- Achromatopsia (total color blindness)
- Protanomaly (red-weak)

### 💾 Palette Management
- Save unlimited palettes with custom names
- Stored in localStorage (persists across sessions)
- Quick-load saved palettes
- Delete unwanted palettes

### 📦 Export Options
- **CSS Variables** - `:root { --color-1: #xxx; }`
- **JSON** - `{ "colors": ["#xxx", ...] }`
- **SCSS** - `$color-1: #xxx;`
- **Tailwind** - Complete theme config object
- **Shareable URL** - URL with color params encoded

## Usage

1. Open `index.html` in any modern browser
2. Click on the color wheel to select a base color
3. Choose a harmony mode to generate a palette
4. Use tools (sliders, shades, contrast, etc.) as needed
5. Save palettes or export in your preferred format

## Keyboard Shortcuts

| Action | Result |
|--------|--------|
| Click wheel | Select color |
| Click palette color | Load that color |
| Click shade | Load that shade |

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript
- No external dependencies (except Google Fonts)
- Canvas API for color wheel rendering
- localStorage for persistence

## Design System

### Colors
| Role | Color | Hex |
|------|-------|-----|
| Background | Near Black | #0a0a0f |
| Card | Dark Gray | #15151f |
| Border | Muted | #2a2a3a |
| Text Primary | Off-White | #e8e8ec |
| Text Secondary | Gray | #9898a8 |
| Accent | Gold | #d4a853 |

### Typography
- **Headings**: Outfit (Google Fonts)
- **Code/Values**: JetBrains Mono (Google Fonts)

## File Structure

```
Sands-Color-Wheel/
├── index.html    # Complete application
└── README.md     # This file
```

## Credits

Built with the Sand.gallery design system - crafted by Sand (Kyle Touchet).

## License

MIT License - Feel free to use, modify, and distribute.
