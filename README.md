# 📄 Mobile Document Scanner with OpenCV

**Transform smartphone photos into scanned documents in seconds!** This Python-based document scanner automatically detects edges, corrects perspective, and enhances document images to produce clean, scanner-like results.

## ✨ Features

- **Automatic edge detection** - Finds document boundaries even at angles
- **Perspective correction** - Converts skewed photos to perfect top-down views
- **Image enhancement** - Applies adaptive thresholding for crisp black-and-white output
- **Easy integration** - Simple CLI interface and modular code structure
- **Interactive mode** - Visualize each processing step

## 🛠️ Built With

- OpenCV (Computer Vision)
- scikit-image (Image Processing)
- NumPy (Numerical Operations)
- imutils (Image Utilities)

## 📦 Installation

```bash
git clone https://github.com/yourusername/document-scanner.git
cd document-scanner
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## 🚀 Usage

```bash
# Basic scanning
python main.py -i input.jpg -o output.jpg

# Interactive mode (shows processing steps)
python main.py -i receipt.jpg --interactive
```

## 📸 Example

**Before** (angled photo) | **After** (scanned result)
---|---
![Input]("Pmyfile.jpg") | ![Output]("myfile_scanned.jpg")

## 🤝 Contributing

PRs welcome! Please open an issue first to discuss proposed changes.

---

### Key Elements Included:
1. Clear value proposition in the header
2. Emoji-enhanced section headers
3. Technical stack transparency
4. Concise installation/usage instructions
5. Visual example (replace with actual image URLs)
6. Contribution guidelines
