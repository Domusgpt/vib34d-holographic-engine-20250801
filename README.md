# VIB34D Holographic Engine 🌌

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![WebGL](https://img.shields.io/badge/WebGL-Powered-orange.svg)](https://www.khronos.org/webgl/)
[![Variations](https://img.shields.io/badge/Variations-30-green.svg)](https://github.com/domusgpt/vib34d-holographic-engine)
[![4D Math](https://img.shields.io/badge/Mathematics-4D-purple.svg)](https://github.com/domusgpt/vib34d-holographic-engine)

A production-ready holographic visualization engine combining advanced 4D polytopal mathematics with a 5-layer holographic rendering system. Features 30 built-in variations based on 8 fundamental VIB3 geometries.

![VIB34D Demo](./assets/vib34d-demo.gif)

## 🚀 Features

### Core Capabilities
- **5-Layer Holographic System** - Multi-layered WebGL rendering with blend modes
- **30 VIB3 Variations** - From 8 base geometries (Tetrahedron, Hypercube, Sphere, Torus, Klein Bottle, Fractal, Wave, Crystal)
- **4D Mathematics** - Real 4D rotation matrices (XW, YW, ZW) with 3D projection
- **Agent-Ready API** - Complete JSON import/export workflow for AI agents
- **Multi-Format Export** - JSON, CSS, HTML, PNG export capabilities
- **Real-Time Interaction** - Mouse, touch, and keyboard controls

### Advanced Features (Coming Soon)
- **Audio Reactivity** - Beat detection and frequency analysis
- **Accelerometer Support** - Device motion integration
- **Scroll Parallax** - Depth-based scrolling effects
- **Marketplace Integration** - Unity, Unreal Engine, and design tool plugins

## 🎯 Quick Start

### Browser Usage
Simply open `index.html` in a modern web browser:
```bash
# Clone the repository
git clone https://github.com/domusgpt/vib34d-holographic-engine.git
cd vib34d-holographic-engine

# Open in browser
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

### NPM Package (Coming Soon)
```bash
npm install vib34d-engine
```

## 🎨 30 Variations Gallery

The engine includes 30 pre-configured variations organized by geometry type:

<table>
<tr>
<td align="center">
<img src="./assets/variations/tetrahedron-lattice.png" width="150" /><br>
<b>1. Tetrahedron Lattice</b>
</td>
<td align="center">
<img src="./assets/variations/hypercube-field.png" width="150" /><br>
<b>5. Hypercube Field</b>
</td>
<td align="center">
<img src="./assets/variations/sphere-matrix.png" width="150" /><br>
<b>10. Sphere Matrix</b>
</td>
<td align="center">
<img src="./assets/variations/torus-quantum.png" width="150" /><br>
<b>15. Torus Quantum</b>
</td>
</tr>
</table>

[View All 30 Variations →](./docs/variations.md)

## 🔧 Parameters Guide

### Polytopal Controls
| Parameter | Range | Description | Visual Effect |
|-----------|-------|-------------|---------------|
| **4D Rotation XW** | -2.0 to 2.0 | Rotation in XW plane | ![XW Rotation](./assets/params/xw-rotation.gif) |
| **4D Rotation YW** | -2.0 to 2.0 | Rotation in YW plane | ![YW Rotation](./assets/params/yw-rotation.gif) |
| **4D Rotation ZW** | -2.0 to 2.0 | Rotation in ZW plane | ![ZW Rotation](./assets/params/zw-rotation.gif) |
| **Dimension Level** | 3.0 to 4.5 | 4D projection depth | ![Dimension](./assets/params/dimension.gif) |

### Holographic Controls
| Parameter | Range | Description | Visual Effect |
|-----------|-------|-------------|---------------|
| **Grid Density** | 4 to 30 | Lattice grid resolution | ![Density](./assets/params/density.gif) |
| **Morph Factor** | 0 to 2 | Geometry morphing amount | ![Morph](./assets/params/morph.gif) |
| **Chaos Intensity** | 0 to 1 | Glitch and distortion | ![Chaos](./assets/params/chaos.gif) |
| **Speed Multiplier** | 0.1 to 3.0 | Animation speed | ![Speed](./assets/params/speed.gif) |

## 💻 API Documentation

### JavaScript API
```javascript
// Initialize the engine
const engine = new VIB34DIntegratedEngine();

// Set a specific variation (0-29)
engine.setVariation(15); // Torus Quantum

// Update parameters
engine.updateParams({
    gridDensity: 20.0,
    morphFactor: 1.5,
    chaos: 0.8,
    speed: 2.0,
    hue: 240
});

// Export configuration
const config = engine.exportJSON();

// Import configuration
engine.importJSON(configFile);
```

### Agent Integration
```javascript
// For AI agents and automated workflows
const agentConfig = {
    variation: 7,  // Hypercube Quantum
    parameters: {
        rot4dXW: 1.0,
        rot4dYW: 0.5,
        rot4dZW: 0.3,
        dimension: 4.0,
        gridDensity: 15.0,
        morphFactor: 0.7,
        chaos: 0.4,
        speed: 1.5,
        hue: 180
    }
};

engine.loadJSONConfig(JSON.stringify(agentConfig));
```

## 🔌 Integration Guides

### Unity Integration
```csharp
// Coming Soon: Unity WebGL Bridge
using VIB34D.Unity;

public class HolographicRenderer : MonoBehaviour {
    private VIB34DEngine engine;
    
    void Start() {
        engine = new VIB34DEngine();
        engine.SetVariation(12); // Torus Lattice
    }
}
```

### Unreal Engine Integration
```cpp
// Coming Soon: Unreal Engine Plugin
#include "VIB34DEngine.h"

AVIB34DActor::BeginPlay() {
    Engine = NewObject<UVIB34DEngine>();
    Engine->SetVariation(20); // Fractal Lattice
}
```

### React Component
```jsx
// Coming Soon: React Component
import { VIB34DEngine } from 'vib34d-react';

function HolographicVisualizer() {
    return (
        <VIB34DEngine
            variation={8}
            parameters={{
                gridDensity: 18,
                morphFactor: 0.5,
                chaos: 0.3
            }}
            onExport={(config) => console.log(config)}
        />
    );
}
```

## 🎮 Controls

### Mouse/Touch
- **Move**: Interactive glow follows cursor
- **Click/Tap**: Pulse effect at click location
- **Drag**: (Coming soon) Rotate 4D projection

### Keyboard Shortcuts
- **Arrow Keys**: Navigate variations
- **Space**: Random variation
- **R**: Randomize all parameters
- **E**: Export current configuration
- **M**: Minimize/expand control panel

## 🛠️ Development

### Building from Source
```bash
# Clone repository
git clone https://github.com/domusgpt/vib34d-holographic-engine.git
cd vib34d-holographic-engine

# Install dependencies (when package.json is added)
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

### Testing
```bash
# Run unit tests
npm test

# Run visual regression tests
npm run test:visual

# Run agent compatibility tests
npm run test:agents
```

## 📁 Project Structure
```
vib34d-holographic-engine/
├── index.html              # Main engine file
├── README.md              # This file
├── LICENSE                # MIT License
├── package.json           # NPM package config
├── docs/                  # Documentation
│   ├── variations.md      # All 30 variations detailed
│   ├── api.md            # Complete API reference
│   ├── integration.md    # Integration guides
│   └── parameters.md     # Parameter deep dive
├── examples/             # Example implementations
│   ├── basic.html        # Basic usage
│   ├── agent.html        # Agent integration
│   ├── react/           # React example
│   └── unity/           # Unity example
├── assets/              # Images and media
│   ├── vib34d-demo.gif  # Main demo animation
│   ├── variations/      # Variation screenshots
│   └── params/          # Parameter effect GIFs
└── tests/               # Test suite
    ├── unit/           # Unit tests
    ├── visual/         # Visual tests
    └── integration/    # Integration tests
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Roadmap
- [ ] Audio reactivity system
- [ ] Accelerometer integration
- [ ] Scroll parallax enhancements
- [ ] Unity WebGL bridge
- [ ] Unreal Engine plugin
- [ ] React/Vue/Angular components
- [ ] Node.js server-side rendering
- [ ] WebAssembly optimization
- [ ] Mobile app (React Native)

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built on WebGL and modern web standards
- Inspired by 4D mathematical visualization research
- Uses VIB3 geometry system fundamentals
- Special thanks to the holographic visualization community

## 📧 Contact

- **GitHub Issues**: [Report bugs or request features](https://github.com/domusgpt/vib34d-holographic-engine/issues)
- **Email**: phillips.paul.email@gmail.com
- **Twitter**: [@domusgpt](https://twitter.com/domusgpt)

---

<p align="center">
Made with 🌌 by [Your Name]<br>
<a href="https://github.com/domusgpt/vib34d-holographic-engine">View on GitHub</a> • 
<a href="https://domusgpt.github.io/vib34d-holographic-engine">Live Demo</a> • 
<a href="./docs/api.md">API Docs</a>
</p>