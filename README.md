# 🎵 Global Radio Player

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

A modern, responsive web-based radio streaming application featuring **80+ international radio stations** from around the world. Built with vanilla JavaScript for maximum compatibility and zero dependencies.

## ✨ Features

### 🌍 **Global Station Library**
- **80+ Radio Stations** from 40+ countries worldwide
- Organized by country with station counts
- Real-time streaming with HTML5 Audio API

### ❤️ **Personal Experience**
- **Favorites System** - Save preferred stations with heart icons
- **Recently Played** - Track last 10 stations with timestamps
- **Smart Search** - Find stations by name or country
- **Persistent Storage** - All preferences saved locally

### 🎨 **Modern Interface**
- **Light/Dark Theme** - Seamless theme switching
- **Mobile Responsive** - Optimized for all screen sizes
- **Tabbed Navigation** - Countries, Favorites, Recent tabs
- **Loading States** - Visual feedback for all actions

### ⚡ **Enhanced UX**
- **Keyboard Shortcuts** - Power user navigation
- **Connection Retry** - Auto-retry failed streams
- **Error Handling** - Graceful error management
- **Zero Dependencies** - Pure vanilla JavaScript

## 🚀 Quick Start

### Option 1: Single File Deployment
1. Download [`radio-player.html`](radio-player.html)
2. Upload to any web hosting service
3. Open in browser and start listening!

### Option 2: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access via `https://yourusername.github.io/global-radio-player`

## 📱 Demo

[Live Demo](https://keerthivasan-global-radio-player.netlify.app) | [Screenshot Gallery](#screenshots)

## 🛠️ Installation & Deployment

### Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/global-radio-player.git
cd global-radio-player

# Serve locally (Python 3)
python -m http.server 8000

# Or with Node.js
npx serve .

# Open http://localhost:8000
```

### Free Hosting Options

| Platform | Deployment Method | Custom Domain |
|----------|-------------------|---------------|
| **Netlify** | Drag & drop `radio-player.html` | ✅ Free |
| **Vercel** | Upload single file | ✅ Free |
| **GitHub Pages** | Push to repository | ✅ Free |
| **Surge.sh** | `surge radio-player.html` | ✅ Free |
| **Firebase Hosting** | `firebase deploy` | ✅ Free |

### Single File Deployment
The `radio-player.html` file is completely self-contained:
- ✅ Complete HTML structure
- ✅ Embedded CSS styling (15KB+)
- ✅ All JavaScript functionality (25KB+)
- ✅ Radio station data embedded
- ✅ Font Awesome icons (CDN)

## 🎯 Browser Compatibility

| Browser | Minimum Version | Status |
|---------|----------------|--------|
| Chrome | 60+ | ✅ Fully Supported |
| Firefox | 55+ | ✅ Fully Supported |
| Safari | 11+ | ✅ Fully Supported |
| Edge | 79+ | ✅ Fully Supported |
| Mobile Chrome | 60+ | ✅ Responsive Design |
| Mobile Safari | 11+ | ✅ Touch Optimized |

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` | Switch to Countries tab |
| `2` | Switch to Favorites tab |
| `3` | Switch to Recent tab |
| `Spacebar` | Play/Pause current station |
| `/` | Focus search input |
| `Escape` | Close modals/blur search |

## 🏗️ Technical Architecture

### Technology Stack
- **Frontend**: Vanilla JavaScript (ES6+)
- **Styling**: CSS3 with Custom Properties
- **Audio**: HTML5 Audio API
- **Storage**: localStorage for persistence
- **Icons**: Font Awesome 6.0.0 (CDN)
- **Build**: None required - pure static files

### File Structure
```
global-radio-player/
├── radio-player.html      # Complete single-file application
├── index.html            # Multi-file version entry point
├── styles.css            # Separate CSS file
├── script.js             # Separate JavaScript file
├── stations.json         # Radio station data
├── LICENSE               # Apache 2.0 license
└── README.md             # This file
```

### Key Features Implementation
- **State Management**: Pure JavaScript with localStorage
- **Responsive Design**: CSS Grid & Flexbox with media queries
- **Theme System**: CSS custom properties for light/dark modes
- **Audio Streaming**: Direct URL streaming with retry logic
- **Error Handling**: Comprehensive error states and user feedback

## 🌐 Radio Stations

The application includes curated stations from:

**Europe**: Germany, France, Netherlands, Norway, Sweden, Finland, Denmark, Lithuania, Poland, Ireland, Italy, Iceland, Portugal, Romania, Croatia, Hungary, Austria, Belgium, Liechtenstein

**Asia**: Japan, Malaysia, Uzbekistan, Azerbaijan, Georgia

**Americas**: Mexico, Argentina, Brazil, Jamaica, Panama, USA

**Africa**: Egypt, Senegal, Uganda

**Oceania**: Australia, Samoa

**Arctic**: Greenland

## 🤝 Contributing

This project is open source under Apache 2.0. Contributions are welcome!

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across browsers
5. Submit a pull request

### Adding New Stations
Edit the `STATIONS_DATA` array in `radio-player.html` or `stations.json`:

```javascript
{
    "name": "Station Name",
    "country": "Country",
    "url": "https://stream-url-here"
}
```

### Reporting Issues
- Check existing issues first
- Provide browser and OS information
- Include steps to reproduce
- Test with multiple stations if audio-related

## 📄 License

Licensed under the **Apache License, Version 2.0**.

```
Copyright 2025 Keerthivasan

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

See [LICENSE](LICENSE) for the full license text.

## 👨‍💻 Author

**Keerthivasan**
- Created: 2025
- License: Apache 2.0
- Type: Open Source Web Application

## 📊 Project Stats

- **File Size**: ~80KB (single file)
- **Lines of Code**: 1,500+
- **Radio Stations**: 80+
- **Countries**: 40+
- **Dependencies**: 0 (except Font Awesome CDN)
- **Browser Support**: 95%+ global coverage

## 🔧 Customization

### Adding Your Own Stations
1. Find radio stream URLs (usually ending in .mp3, .aac, or .m3u8)
2. Add to the `STATIONS_DATA` array
3. Test the stream in your browser first
4. Ensure HTTPS streams for secure sites

### Theming
Modify CSS custom properties in the `:root` selector:
```css
:root {
    --primary-color: #your-color;
    --background-color: #your-bg;
    /* ... other variables ... */
}
```

### Branding
- Update the `<title>` tag
- Modify the logo text in the header
- Customize the footer copyright
- Add your own favicon

---

⭐ **Star this repository** if you find it useful!

🐛 **Found a bug?** [Open an issue](../../issues)

💡 **Have an idea?** [Start a discussion](../../discussions)