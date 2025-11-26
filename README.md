# 🌐 Frontend Mentor - Product preview card component solution

This is my solution for the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

## 📋 Table of contents

- [Overview](#-overview)
  - [Features](#-features)
  - [Preview](#-preview)
  - [Links](#-links)
- [My process](#-my-process)
  - [Built with](#-built-with)
  - [What I learned](#-what-i-learned)
- [Development Workflow](#-development-workflow)
- [Useful Resources](#-useful-resources)
- [Author](#-author)
- [Acknowledgments](#-acknowledgments)

---

## 🌍 Overview

### ✨ Features

A stylish product preview card that shows a product image, details, pricing, and a clear call-to-action button, all wrapped in a modern, responsive layout.

### 🖼️ Preview

![Preview](./preview.png)

### 🔗 Links

- 💡 Solution URL: [Frontend Mentor Submission](https://www.frontendmentor.io/solutions/product-preview-card-with-css-and-tailwindcss-iIkrFjIfvP)
- 🌐 Live Site URL: [Live Demo](https://thewizard04-product-card.vercel.app)

---

## 🛠️ My process

### 🧰 Built with

| Category  | Tools                           |
| --------- | ------------------------------- |
| Structure | **Semantic HTML5 markup**       |
| Styles    | **CSS** and **Tailwind CSS v4** |

### 🧠 What I learned

- Improved my understanding of semantic HTML5 markup
- Strengthened my styling skills using CSS and Tailwind CSS
- Explored creating animations to enhance the user experience
- Enhanced accessibility by ensuring the page can be easily navigated using only the keyboard

Here are the snippet which shows the grid in the main section:

On mobile devices the grid only has 1 column.

```css
main {
  display: grid;
  grid-template-columns: 1fr;
  background-color: var(--color-white);

  border-radius: 0.75rem;
  overflow: hidden;
  animation: slide-in 0.6s ease;
}
```

And on bigger devices it has 2 equal sized columns:

```css
main {
  max-width: var(--card-container);
  grid-template-columns: 1fr 1fr;
}
```

---

## 🧩 Development Workflow

### 🧱 Local Setup

1. **Start using Tailwind in your HTML**
   ```html
   <link rel="stylesheet" href="styles/tailwindcss/output.css" />
   ```
2. **Start using CSS in your HTML**
   ```html
   <link rel="stylesheet" href="styles/css/index.css" />
   ```

Then open your index.html file in the browser.

---

## 📖 Useful Resources

- [HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp) - A helpful article explaining semantic HTML5 elements and their purpose.
- [CSS Animations](https://www.w3schools.com/css/css3_animations.asp) - A clear introduction to CSS animations and keyframes.

---

## 👨‍💻 Author

- GitHub - [CrazyWizard04](https://github.com/CrazyWizard04)
- Frontend Mentor - [@CrazyWizard04](https://www.frontendmentor.io/profile/crazywizard04)

---

## 💖 Acknowledgments

A big thanks to **Frontend Mentor** for providing this project.
Their challenges are a great way for developers of all levels to practice, learn, and improve their skills through real-world examples.

Thank you <3
