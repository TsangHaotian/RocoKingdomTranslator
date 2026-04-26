# RocoKingdomTranslator

A web-based translator for converting between English and RocoKingdom language.

## Features

- **Letter Mapping Table**: Shows the mapping between 26 English letters and RocoKingdom characters
- **English → RocoKingdom**: Input English text, get instant RocoKingdom translation
- **RocoKingdom → English**:
  - Use the virtual keyboard to input RocoKingdom characters
  - Click "Bind Physical Keyboard" to use your actual keyboard
  - Real-time translation support
- **Copy Function**: One-click copy to paste results elsewhere

## Usage

### English to RocoKingdom

1. Enter English text in the "English → RocoKingdom" section
2. Translation displays instantly on the right
3. Click "Copy Roco Language" to copy the result

### RocoKingdom to English

**Method 1: Virtual Keyboard**
1. Click RocoKingdom characters on the virtual keyboard
2. Translation displays instantly on the right

**Method 2: Bind Physical Keyboard**
1. Click "Bind Physical Keyboard" button
2. Type directly on your keyboard to input RocoKingdom characters
3. Click the button again to unbind

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Custom Font (RUNEREGULAR.ttf)

## Run Locally

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

Then visit `http://localhost:8000`

## Project Structure

```
RocoKingdomTranslator/
├── index.html          # Main page
├── font/
│   └── RUNEREGULAR.ttf # RocoKingdom font file
├── README.md           # English documentation
├── README_cn.md        # Chinese documentation
└── .gitignore
```

## License

MIT License