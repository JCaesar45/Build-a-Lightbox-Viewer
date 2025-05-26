```markdown
# 📸 Lightbox Viewer

A lightweight Lightbox Gallery app that displays full-size images when you click a thumbnail. Built using HTML, CSS, and vanilla JavaScript.

## 🧩 Features

- Responsive image gallery with clickable thumbnails
- Fullscreen lightbox overlay with image preview
- Click-to-close functionality (on close button or background)
- Minimal and clean UI design
- Easily customizable for additional images or styles

## 📁 File Structure

``

lightbox-viewer/
│
├── index.html         # Main HTML file
├── styles.css         # Stylesheet for layout and visuals
├── script.js          # Lightbox functionality logic
└── README.md          # Project documentation

``

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/lightbox-viewer.git
   cd lightbox-viewer
``

2. **Open in browser**

   ```bash
   open index.html
   ``

No build tools or dependencies required.

## 🖼️ Image Sources

Thumbnails and full-size images are loaded from [freeCodeCamp CDN](https://cdn.freecodecamp.org):

* Stonehenge
* Storm
* Trees

## 🔧 How It Works

* Each thumbnail has a `.gallery-item` class and links to a `-thumbnail.jpg` image.
* When clicked, JavaScript swaps `-thumbnail` with `.jpg` to load the full-size version.
* The lightbox (`.lightbox`) uses `flex` display and `fixed` positioning to overlay content.

## 🛠️ Customization

To add more images:

1. Upload a `yourimage-thumbnail.jpg` and `yourimage.jpg` to your host.
2. Add another `<img class="gallery-item" src="yourimage-thumbnail.jpg">` to the `.gallery` div.

## 📄 License

This project is open-source and free to use for educational or personal projects.

---

💡 Inspired by web UI best practices. Designed with simplicity in mind.

```
