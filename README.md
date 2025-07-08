# QR Code Generator

A simple and responsive web app to generate QR codes from any text or URL using the [goQR.me API](https://goqr.me/api/).

## 🚀 Features

- Enter any text or URL to instantly generate a QR code.
- Validates input before generating the QR.
- Responsive and clean UI using HTML, CSS, and JavaScript.
- Animated input shake on invalid input.
- QR Code image appears with a smooth transition.



## 📂 Files

- `index.html` – Main HTML structure
- `style.css` – Styling for layout and animations
- `script.js` – JavaScript logic to generate QR codes
- `README.md` – Project documentation

## 🧠 How It Works

1. User types a text or URL in the input field.
2. On clicking the **"Generate QR Code"** button:
   - If input is valid, it fetches the QR from `api.qrserver.com`.
   - If input is empty, it triggers an animated shake as a warning.

## 📦 API Used

- **QR Code API**: [https://api.qrserver.com](https://api.qrserver.com)
  - Example: `https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=YOUR_TEXT`

## 💡 Future Improvements

- Allow download of the QR image.
- Add dark mode toggle.
- Auto-generate QR code on typing (optional debounce).
- Error message on API failure.

## ✅ Requirements

Just a modern browser. No installations or dependencies needed.

## 📸 Screenshot

![UI Preview](https://i.imgur.com/QrZ1D2y.png) *(Replace with actual screenshot if available)*

## 🧑‍💻 Author

- Made with ❤️ by Swayam17o5
