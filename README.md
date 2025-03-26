### **QR Code Generator (CLI)**
A simple command-line tool to generate QR codes from text or URLs and save them as images.  

## 🚀 Features
- Generate a QR code from any text or URL  
- Save the QR code as an image (`.png` format)  
- Lightweight and easy to use  

## 🛠 Installation  
Make sure you have Python installed. Then, install the required library:  
```bash
pip install qrcode[pil]
```

## 🎯 Usage  
Run the script with a text or URL as an argument:  
```bash
python qr_generator.py "https://github.com/AmirMohammedi"
```
This will generate a QR code and save it as `qrcode.png` in the current directory.  

### **Custom Filename**  
You can specify a custom filename for the QR code:  
```bash
python qr_generator.py "https://github.com/AmirMohammedi" my_qr.png
```

## 📂 Example Output  
After running the script, you’ll find a QR code image like this:  

![QR Code Example](https://via.placeholder.com/150)  

## 🏗 How It Works  
1. Takes input text or a URL  
2. Generates a QR code using `qrcode` library  
3. Saves the image as `qrcode.png` (or a custom filename)  

## 🔧 License  
This project is **MIT Licensed** – feel free to use and modify it.  
