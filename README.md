# CSS Loader Animation — runnable recreation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-loader-animation/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

This project recreates the screen-recorded **CSS Loader Animation** page. It contains seven animated CSS loader examples in the same order and a dark two-column card layout with orange outer border, blue-glow title, preview area and code panel.

## Loaders included

1. **Double Ring** — cyan top arc and pink lower arc rotating
2. **Ripple** — two expanding and fading blue rings
3. **Pulse Grid** — nine green squares pulsing in sequence
4. **Arc Spinner** — green partial circular border rotating
5. **Diamond Orbit** — four colored diamond/square particles rotating
6. **Rotating Square** — purple outlined square rotating and scaling
7. **Neon** — cyan glowing ring pulsing

## Visible CSS snippets transcribed from the recording

```css
.double-ring {
  border-top-color: #38bdf8;
  border-bottom-color: #f472b6;
  animation: spin 1s linear infinite;
}
```

```css
.ripple span {
  border: 4px solid #60a5fa;
  animation: ripple 1.8s infinite;
}
```

```css
.pulse-grid span {
  animation: gridPulse .9s infinite ease-in-out;
}
```

```css
.arc {
  border-top-color: #22c55e;
  border-right-color: #22c55e;
  animation: spin .9s linear infinite;
}
```

```css
.diamond-orbit {
  animation: spin 2s linear infinite;
}
```

```css
.rot-square {
  border: 5px solid #c084fc;
  animation: rotSquare 1.2s infinite ease-in-out;
}
```

```css
.neon {
  border: 4px solid #00f7ff;
  box-shadow: 0 0 24px #00f7ff;
  animation: pulse 1s infinite;
}
```

The labels and readable declarations above are transcribed from the visible screen. The complete HTML structure, loader elements, and supporting keyframe definitions are reconstructed to make the examples work. The source recording does not expose every original declaration, so this is not represented as the creator's exact hidden source.

## Run

1. Extract the ZIP.
2. Open `index.html` in Chrome, Firefox, Safari, or Edge.
3. All seven loaders animate automatically.

No JavaScript, dependencies, external assets, build command, or server required.

## Files

- `index.html` — gallery markup and visible code examples
- `style.css` — layout, loader shapes, and keyframe animations
- `README.md` — transcription notes and instructions

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
