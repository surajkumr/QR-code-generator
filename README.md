# 📲 QR Code Generator

A fast and user-friendly QR code generator built with **JavaScript**, **HTML**, and **CSS**. Just type in any text or URL, hit Enter or click the button, and instantly get a scannable QR code.

## 🔗 Live Demo

Try it now:(https://qrcodeconv.netlify.app/)  
Perfect for sharing links, contact info, or quick messages!

## ✨ Features

- 🧠 Real-time QR code generation using [QRServer API](https://goqr.me/api/)
- 🖱️ Generate via button click or press `Enter`
- ⚠️ Input validation with visual feedback
- 📦 Lightweight and responsive design

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- External API: `https://api.qrserver.com/v1/create-qr-code/`

## 🚀 How It Works

- **Input Field**: Accepts any text or URL.
- **QR Generation**: On valid input, sets the `src` of an `<img>` tag to the QRServer API with the user’s data.
- **Error Handling**: Highlights the input box if it's empty.
- **Keyboard Support**: Pressing `Enter` triggers the QR generation.

## 📁 File Structure
