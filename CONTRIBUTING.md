# Contributing to VIB34D Holographic Engine

Thank you for your interest in contributing to the VIB34D Holographic Engine! This document provides guidelines and instructions for contributing.

## 🤝 Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct:
- Be respectful and inclusive
- Welcome newcomers and help them get started
- Focus on constructive criticism
- Accept feedback gracefully

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/vib34d-holographic-engine.git
   cd vib34d-holographic-engine
   ```
3. **Create a branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 Development Process

### Setting Up Development Environment

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run tests
npm test
```

### Code Style

- Use ES6+ JavaScript features
- Follow existing code formatting
- Add comments for complex algorithms
- Use meaningful variable names

### Commit Messages

Follow conventional commit format:
- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes
- `refactor:` Code refactoring
- `test:` Test additions/changes
- `chore:` Build process/auxiliary tool changes

Example:
```
feat: add audio reactivity system
fix: resolve memory leak in render loop
docs: update API documentation for v2.0
```

## 🎯 Areas for Contribution

### High Priority
- [ ] Audio reactivity implementation
- [ ] Accelerometer support
- [ ] Unity WebGL bridge
- [ ] Performance optimizations
- [ ] Mobile touch enhancements

### Documentation
- [ ] Video tutorials
- [ ] Parameter effect GIFs
- [ ] Integration guides
- [ ] API examples

### New Variations
- [ ] Additional geometry types
- [ ] Hybrid geometry combinations
- [ ] User-created variation system

### Testing
- [ ] Unit tests for core functions
- [ ] Visual regression tests
- [ ] Performance benchmarks
- [ ] Browser compatibility tests

## 🔧 Technical Guidelines

### WebGL Shaders
- Maintain GLSL ES 1.0 compatibility
- Optimize for mobile GPUs
- Comment complex math operations
- Keep uniforms to minimum

### Performance
- Target 60 FPS on mid-range devices
- Use requestAnimationFrame properly
- Implement level-of-detail system
- Profile before optimizing

### Browser Support
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers

## 📤 Submitting Changes

1. **Ensure tests pass** (when available)
2. **Update documentation** if needed
3. **Create pull request** with clear description
4. **Link related issues** using #issue-number
5. **Wait for review** from maintainers

### Pull Request Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Tested on mobile

## Screenshots (if applicable)
Add screenshots or GIFs here

## Related Issues
Fixes #issue-number
```

## 🐛 Reporting Issues

### Bug Reports
Include:
- Browser and version
- Steps to reproduce
- Expected behavior
- Actual behavior
- Console errors
- Screenshots/videos

### Feature Requests
Include:
- Use case description
- Proposed solution
- Alternative solutions
- Additional context

## 📚 Resources

- [WebGL Specification](https://www.khronos.org/webgl/)
- [4D Mathematics Resources](https://en.wikipedia.org/wiki/Four-dimensional_space)
- [GLSL Reference](https://www.khronos.org/opengl/wiki/OpenGL_Shading_Language)

## 💬 Communication

- **GitHub Issues**: Bug reports and feature requests
- **Discussions**: General questions and ideas
- **Pull Requests**: Code contributions

## 🎉 Recognition

Contributors will be:
- Added to CONTRIBUTORS.md
- Mentioned in release notes
- Given credit in documentation

Thank you for helping make VIB34D better! 🌌