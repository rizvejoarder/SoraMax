# SoraMax Installation Guide

## 🚀 Quick Start

### Method 1: Direct Download (Recommended)
1. Download `soramax.py` from GitHub releases
2. Ensure Python 3.7+ is installed
3. Double-click `soramax.py` or run: `python soramax.py`

### Method 2: Git Clone
```bash
git clone https://github.com/rizvejoarder/soramax.git
cd soramax
python soramax.py
```

## 📋 System Requirements

- **Python**: 3.7 or higher
- **OS**: Windows 10+, macOS 10.14+, Ubuntu 18.04+
- **RAM**: 4GB minimum, 8GB recommended
- **Storage**: 50MB free space

## 🔧 Installation Steps

### Windows
1. **Install Python:**
   - Download from [python.org](https://python.org)
   - ✅ Check "Add Python to PATH"
   - Install with default settings

2. **Download SoraMax:**
   - Go to [GitHub releases](https://github.com/rizvejoarder/soramax/releases)
   - Download `soramax.py`

3. **Run SoraMax:**
   ```cmd
   python soramax.py
   ```

### macOS
1. **Install Python (if not already installed):**
   ```bash
   brew install python
   ```

2. **Download and run:**
   ```bash
   curl -O https://github.com/rizvejoarder/soramax/releases/download/v2.1.0/soramax.py
   python soramax.py
   ```

### Linux (Ubuntu/Debian)
1. **Install Python and tkinter:**
   ```bash
   sudo apt update
   sudo apt install python3 python3-tk
   ```

2. **Download and run:**
   ```bash
   wget https://github.com/rizvejoarder/soramax/releases/download/v2.1.0/soramax.py
   python3 soramax.py
   ```

## 🔧 Troubleshooting

### Common Issues

**❓ "python is not recognized"**
- Windows: Add Python to PATH in Environment Variables
- Try: `py soramax.py` instead

**❓ "No module named tkinter"**
```bash
# Windows
pip install tk

# Mac
brew install python-tk

# Linux
sudo apt-get install python3-tk
```

**❓ Application opens and closes immediately**
- Run from command line to see error messages
- Check Python version: `python --version`

**❓ Character encoding issues in CSV**
- Enable "Clean text output" option in SoraMax
- Open CSV with UTF-8 encoding in Excel

## 📱 Usage Guide

1. **Launch**: Run `python soramax.py`
2. **Configure**: Set number of prompts (1-1,000,000)
3. **Options**: Choose desired features
4. **Generate**: Click "Generate SoraMax Prompts"
5. **Export**: CSV file saved automatically

## 🎯 Performance Tips

- **Memory**: Close other applications for large generations
- **Speed**: Start with smaller batches (100-1000 prompts)
- **Storage**: Ensure sufficient disk space for CSV output

## 📞 Getting Help

- 🐛 **Issues**: [GitHub Issues](https://github.com/rizvejoarder/soramax/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/rizvejoarder/soramax/discussions)
- 📧 **Email**: contact@rizvejoarder.com

## 🎬 What's Next?

After installation:
1. Try generating 10 sample prompts
2. Explore different options
3. Check the generated CSV file
4. Use prompts with Sora AI
5. Share your creations!

---

Built with ❤️ by [Rizve Joarder](https://www.rizvejoarder.com)