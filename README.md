# Writeboard [WIP]
Handwriting keyboard for Linux, similar to Windows 10's. Powered with Tesseract OCR.

![Writeboard](https://user-images.githubusercontent.com/40331046/172014100-b4d90218-3385-4397-9ed1-838ceb9f9ab4.gif)

## Installation
1. Follow [this tutorial](https://tesseract-ocr.github.io/tessdoc/Installation.html) to install Tesseract, then run:
```bash
git clone https://github.com/brian-the-dev/Writeboard && cd Writeboard && pip install -r requirements.txt
```
2. Copy `traineddata/writeboard.traineddata` into `/usr/share/tessdata` (requires root privilege):
```bash
sudo cp traineddata/writeboard.traineddata /usr/share/tessdata
```

## Usage
```bash
python3 main.py
```

## TODO
- Add button to close and move the window.
- Add button to manually input space, backspace, enter, etc.
- Train more data. Current accuracy: 95% (train data)
- Publish train data
- Publish to AUR
