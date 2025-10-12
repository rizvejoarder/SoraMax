# Contributing to SoraMax

Thank you for your interest in contributing to SoraMax! This document provides guidelines for contributing to this open-source project.

## 🚀 How to Contribute

### 1. Fork the Repository
- Visit [SoraMax on GitHub](https://github.com/rizvejoarder/soramax)
- Click "Fork" to create your copy
- Clone your fork locally:
```bash
git clone https://github.com/YOUR_USERNAME/soramax.git
cd soramax
```

### 2. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b bugfix/issue-description
```

### 3. Make Your Changes
- Follow the existing code style
- Add comments for complex logic
- Test your changes thoroughly
- Update documentation if needed

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add feature: your descriptive commit message"
```

### 5. Push and Create Pull Request
```bash
git push origin feature/your-feature-name
```
Then create a pull request on GitHub.

## 🎯 Types of Contributions

### 🐛 Bug Fixes
- Fix existing bugs
- Improve error handling
- Enhance stability

### ✨ New Features
- Add new prompt categories
- Improve UI/UX
- Add export formats
- Performance improvements

### 📚 Documentation
- Improve README
- Add code comments
- Create tutorials
- Update examples

### 🧪 Testing
- Add unit tests
- Improve test coverage
- Performance testing

## 📋 Development Guidelines

### Code Style
- Follow PEP 8 Python style guide
- Use meaningful variable names
- Add docstrings to functions
- Keep functions focused and small

### Database Contributions
If adding new database content:
- Ensure clean, professional text
- No inappropriate content
- Follow existing patterns
- Test with various combinations

### UI/UX Improvements
- Maintain consistent styling
- Ensure accessibility
- Test on different screen sizes
- Follow modern design principles

## 🏗️ Development Setup

### Prerequisites
- Python 3.7 or higher
- Git
- Text editor or IDE

### Local Development
```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/soramax.git
cd soramax

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install development dependencies (if any)
pip install -r requirements.txt

# Run SoraMax
python soramax.py
```

### Testing Your Changes
- Test the application thoroughly
- Try edge cases (very large/small inputs)
- Verify CSV output opens correctly
- Test on different operating systems if possible

## 📝 Pull Request Guidelines

### Before Submitting
- ✅ Test your changes thoroughly
- ✅ Update documentation if needed
- ✅ Follow existing code style
- ✅ Add comments for complex code
- ✅ Ensure no breaking changes

### Pull Request Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement

## Testing
- [ ] Tested locally
- [ ] Added unit tests (if applicable)
- [ ] Verified CSV output

## Screenshots (if applicable)
Add screenshots for UI changes
```

## 🎯 Priority Areas for Contribution

### High Priority
1. **Performance Optimization** - Improve database generation speed
2. **Additional Export Formats** - JSON, XML, etc.
3. **UI Improvements** - Better styling, themes
4. **Documentation** - More examples, tutorials

### Medium Priority
1. **Additional Databases** - More locations, fashion styles
2. **Localization** - Support for multiple languages
3. **Templates** - Preset configurations
4. **Batch Processing** - Command-line interface

### Lower Priority
1. **Advanced Features** - API integration, cloud sync
2. **Mobile Version** - Web-based interface
3. **Plugin System** - Extensible architecture

## 🐛 Bug Reports

### Creating Good Bug Reports
Include:
- **Operating System** and version
- **Python version**
- **SoraMax version**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots/error messages**
- **Sample data** (if relevant)

### Bug Report Template
```markdown
**Environment:**
- OS: [e.g., Windows 10, macOS 13, Ubuntu 22.04]
- Python Version: [e.g., 3.9.0]
- SoraMax Version: [e.g., 2.1.0]

**Bug Description:**
Clear description of the bug

**Steps to Reproduce:**
1. Step one
2. Step two
3. Expected result vs actual result

**Additional Context:**
Any other relevant information
```

## 💡 Feature Requests

### Suggesting Features
- Check existing issues first
- Explain the use case
- Provide implementation ideas
- Consider backward compatibility

### Feature Request Template
```markdown
**Feature Description:**
What feature would you like to see?

**Use Case:**
Why is this feature needed?

**Implementation Ideas:**
How do you think this should work?

**Additional Context:**
Any other relevant information
```

## 🏆 Recognition

Contributors are recognized in:
- GitHub contributors list
- Future version release notes
- Special mention for significant contributions

## 📞 Getting Help

Need help with development?
- 💬 [GitHub Discussions](https://github.com/rizvejoarder/soramax/discussions)
- 📧 Email: [Rizve Joarder](mailto:contact@rizvejoarder.com)
- 🐛 [GitHub Issues](https://github.com/rizvejoarder/soramax/issues)

## 📄 License

By contributing to SoraMax, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to SoraMax! Your efforts help make this tool better for the entire creative community. 🎬✨