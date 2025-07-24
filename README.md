# React with CDN

This project demonstrates how to use React with CDN imports instead of a build system.

## Getting Started

1. Open `index.html` in your web browser
2. No build process or npm installation required!

## What's Included

The HTML file imports:
- **React 18** - Core React library
- **React DOM 18** - DOM rendering utilities  
- **Babel Standalone** - JSX transformation in the browser

## Features

- Simple counter component demonstrating React hooks
- Modern styling
- Ready to use - just open in browser

## CDN Links Used

```html
<!-- React CDN -->
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

<!-- Babel for JSX -->
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
```

## Notes

- This setup is great for learning, prototyping, and small projects
- For production apps, consider using a build system like Vite or Create React App
- JSX is transformed in the browser using Babel Standalone