# BOI Exemption Checker (Unofficial)

A free, open-source "Access to Justice" tool designed to help U.S. small business owners determine if they are exempt from filing the **Beneficial Ownership Information (BOI)** report under the Corporate Transparency Act (CTA).

## 🚀 Live Demo
[Link to your GitHub Pages URL here]

## ⚖️ Disclaimer
**This tool is for informational purposes only and does not constitute legal advice.** The Corporate Transparency Act is complex. This tool simplifies the 23 exemptions into a logical flow, but it cannot account for every nuance of your specific business situation. Always consult with a qualified attorney or CPA for a final determination.

## ✨ Features
* **Privacy First:** Zero data collection. The entire logic runs locally in your browser (Client-Side JavaScript). No data is sent to any server.
* **Complete Logic:** Covers all 23 FinCEN exemptions, including the complex "Large Operating Company" test.
* **Compliance Record:** Generates a timestamped, printer-friendly "Determination Record" (PDF) for your files.
* **Responsive:** Works on mobile and desktop.

## 🛠️ Technology
* **Single-File Architecture:** The entire app is contained in one `index.html` file. 
* **Frameworks:** Built with vanilla HTML/JS and [Tailwind CSS](https://tailwindcss.com/) (via CDN) for styling.

## 📦 How to Use
1.  **For Users:** simply visit the [Live Demo](https://your-username.github.io/boi-checker) link.
2.  **For Developers:**
    * Clone this repo.
    * Open `index.html` in your browser.
    * No build step or `npm install` required.

## 🤝 Contributing
Contributions are welcome! If you find a logic error regarding the CTA regulations or want to improve the UI:
1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License
Distributed under the MIT License. See below for details.

---

### MIT License

Copyright (c) 2024 BOI Exemption Checker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
