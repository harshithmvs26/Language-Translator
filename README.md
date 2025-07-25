# 🌐 Language Translator GUI using Tkinter

This is a simple yet elegant **Language Translator Desktop App** built using `Tkinter`, `googletrans`, and `textblob`. It allows users to translate text from one language to another with a sleek gradient-themed GUI.

## 🚀 Features

- 🌍 Translate between any two languages supported by Google Translate  
- 🎨 Gradient background from Red to Blue for a modern UI  
- 📋 Copy & Paste support for text fields  
- 📱 Easy-to-use interface with dropdowns for language selection  
- 💡 Live translation with just a button click  

## 🛠️ Requirements

Make sure to have Python installed (preferably 3.7 or above) and install the following packages:

```bash
pip install tkinter
pip install googletrans==4.0.0-rc1
pip install textblob

```
## Folder Structure

├── translator.py           # Main application code
├── logo_simpli.ico         # App icon
├── screenshot.png          # App screenshot (optional)
└── README.md               # This file

## 💻 How to Run

#### Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/language-translator-gui.git
cd language-translator-gui

#### Run the translator GUI:

bash
Copy
Edit
python translator.py
Make sure logo_simpli.ico is in the same directory as translator.py.

## 📚 Libraries Used

tkinter – for GUI components

googletrans – for translation functionality

textblob – for language detection and correction

PIL (Pillow) – for advanced GUI effects (optional for gradient)

random – for dynamic visual elements (if used)

## 📌 Future Improvements

Add voice input and output

Add dark mode toggle

Add auto language detection

Allow saving translations to a file
