# FreeQR - Simple, Free QR Code Generator

[![Live Demo](https://img.shields.io/badge/demo-live-green.svg)](https://freeqr.lkly.net)
[![No Tracking](https://img.shields.io/badge/tracking-none-brightgreen.svg)](#privacy)
[![No Ads](https://img.shields.io/badge/ads-none-brightgreen.svg)](#privacy)

FreeQR is a lightweight, privacy-focused QR code generator that runs entirely in your browser. No ads, no tracking, just a simple tool that gets the job done.

🌐 **[Try it now at freeqr.lkly.net](https://freeqr.lkly.net)**

## Features

- 🚀 **Instant Generation**: Create QR codes in real-time as you type
- 🎨 **Customizable Options**:
  - Multiple size options (200x200, 400x400, 800x800)
  - Adjustable error correction levels (7% to 30%)
  - Optional transparent background
- 📱 **Mobile Friendly**: Responsive design works great on all devices
- 🔒 **Privacy First**: No tracking, no cookies, no analytics
- 💾 **Download as SVG**: Get your QR codes in high-quality vector format
- 🌐 **Works Offline**: All processing happens in your browser

## Technology Stack

- [Alpine.js](https://alpinejs.dev/) for reactive UI
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) for QR code generation

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/freeqr.git
   cd freeqr
   ```

2. Open `index.html` in your browser or serve it using a local server:
   ```bash
   python3 -m http.server 8000
   # or
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Privacy

FreeQR is designed with privacy in mind:
- No server-side processing
- No data collection
- No external analytics
- No cookies
- No user tracking

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Support

If you find FreeQR useful, consider [buying me a coffee](https://buymeacoffee.com/lkly) ☕️

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Deployment

FreeQR is a static site that can be deployed anywhere. The live version is hosted at [freeqr.lkly.net](https://freeqr.lkly.net).

---

Made with ❤️ for the open web