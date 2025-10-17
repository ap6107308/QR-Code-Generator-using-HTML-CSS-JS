# QR Code Generator

A simple, client-side web application for generating and downloading QR codes. Just enter any text or URL, and get an instant, savable QR code image!

---

## 🚀 Features

* **Instant Generation:** Generates a QR code immediately upon form submission.
* **Image Download:** Provides a "Save QR Code" button to download the image as a **PNG**.
* **Client-Side Only:** No server or backend processing is required; all logic runs in the browser.
* **Clean UI:** Simple and intuitive user interface using basic HTML and CSS.

---

## 🛠️ Technologies Used

* **HTML5:** Structure of the web application.
* **CSS3:** Styling and layout.
* **JavaScript (ES6):** Core logic for generation and download.
* **`qrcode.js`:** A lightweight, pure JavaScript library for generating the QR code graphic.

---

## 🏃 Getting Started

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, Edge, or Safari).

### Installation & Setup

Since this is a client-side application, setup is very easy:

1.  **Clone the repository** (or download the files).
2.  **Open `index.html`** in your preferred web browser.

That's it! The application is ready to use.

---

## 💡 How to Use

1.  Open the application in your browser.
2.  Enter the text or URL you want to encode into the input field.
3.  Click the "**Generate QR Code**" button.
4.  The QR code will appear below the form.
5.  Click the "**Save QR Code**" button to download the image to your device.

---

## 📁 File Structure

| File | Description |
| :--- | :--- |
| `index.html` | The main structure of the application. Links to the CSS and JS files, and includes the `qrcode.js` library via CDN. |
| `style.css` | Defines the visual styling, layout, and responsiveness. |
| `main.js` | Contains the core application logic: handling form submission, calling the QR code generation function, and implementing the image download feature. |
