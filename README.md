# Circular Testimonials

A lightweight, responsive testimonial carousel with 3D circular animation effects. Built with pure HTML, CSS, and JavaScript - no dependencies required.

## ✨ Features

- 🎨 3D perspective animation with circular layout
- 📱 Fully responsive design
- ⚡ Lightweight - No frameworks or libraries
- 🎯 Auto-play with manual controls
- ⌨️ Keyboard navigation (Arrow keys)
- 🎭 Light & Dark theme support
- 🔄 Smooth word-by-word text animation

## 🚀 Demo

[View Live Demo](https://alirezaaliniya.github.io/Circular-Testimonials/)

## 📦 Installation

Simply download `index.html` and open it in your browser. That's it!

## 🛠️ Usage

### Adding a New Testimonial

1. Add the image in the `image-container`:

```html
<img src="your-image.jpg" 
     alt="Person Name" 
     class="testimonial-image" 
     data-index="3">
```

2. Add the content in the `content-wrapper`:

```html
<div class="testimonial-item" data-index="3">
  <h3 class="name">Person Name</h3>
  <p class="designation">Job Title</p>
  <p class="quote">Your testimonial text here...</p>
</div>
```

**Important:** Make sure `data-index` matches between image and content!

### Customization

Configure colors and sizes via `data-` attributes on `.testimonial-container`:

```html
<div class="testimonial-container" 
     data-autoplay="true"
     data-name-color="#0a0a0a"
     data-designation-color="#454545"
     data-testimony-color="#171717"
     data-arrow-bg="#141414"
     data-arrow-fg="#f1f1f7"
     data-arrow-hover="#00A6FB"
     data-name-size="28px"
     data-designation-size="20px"
     data-quote-size="20px">
```

## ⚙️ Configuration Options

| Attribute | Description | Default |
|-----------|-------------|---------|
| `data-autoplay` | Enable auto-play | `true` |
| `data-name-color` | Name text color | `#000` |
| `data-designation-color` | Job title color | `#6b7280` |
| `data-testimony-color` | Quote text color | `#4b5563` |
| `data-arrow-bg` | Button background | `#141414` |
| `data-arrow-fg` | Button icon color | `#f1f1f7` |
| `data-arrow-hover` | Button hover color | `#00a6fb` |
| `data-name-size` | Name font size | `28px` |
| `data-designation-size` | Job title font size | `20px` |
| `data-quote-size` | Quote font size | `20px` |

## 🎮 Controls

- **← →** Arrow keys for navigation
- **Click** navigation buttons
- **Auto-play** switches testimonials every 5 seconds

## 📱 Browser Support

Works on all modern browsers:
- Chrome, Firefox, Safari, Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

MIT License - Feel free to use in personal and commercial projects!

## 👨‍💻 Author

Created by [Alireza Aliniya](https://github.com/alirezaaliniya)

---

⭐ If you found this useful, please star the repo!
