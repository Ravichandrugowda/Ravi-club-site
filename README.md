# Ravi-club-site
🚀 First Website
Created a simple responsive web layout with sticky header, interactive image cards, and footer using HTML and CSS.
Hover animations included for a modern UI feel.

Here's the current draft of your **README** for the Ravi Chandru Club website project:

---

# Ravi Chandru Club – First Website

Welcome to **Ravi Chandru Club**, a playful single-page website built with nothing but vanilla **HTML** and **CSS**. The project is perfect for beginners who want to understand modern CSS positioning, hover effects, and responsive-friendly layouts without any JavaScript.

---

### 📸 Preview

![Screenshot of Ravi Chandru Club](./assets/screenshot.png)

> *Hover over each “Bag” card to see rotation, scaling, and color-change animations in action!*

---

## ✨ Key Features

| Feature                      | Description                                                                                                               |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Sticky Header & Footer**   | Remain fixed at the top and bottom of the viewport for constant visibility.                                               |
| **Flexible Grid ( `.Car` )** | Uses `flexbox` to lay out four “Bag” cards horizontally across the full width.                                            |
| **Animated Hover Effects**   | Scale-down on parent hover (`.Car:hover .Bag`) and individual card spin/scale with a background swap (`.Car .Bag:hover`). |
| **Viewport-Based Sizing**    | Each “Bag” card sizes itself with `vw`/`vh` units for quick responsiveness.                                               |
| **Pure CSS Styling**         | No external libraries or JavaScript dependencies—just clean, readable CSS.                                                |

---

## 🗂️ Project Structure

```
.
├── index.html          # The page you see above
├── Ourwebsite.css      # (Optional) External stylesheet if you prefer splitting CSS
├── assets/
│   ├── Students.jpg    # Sample image used for all four cards
│   └── screenshot.png  # Add your own screenshot for the README
└── README.md           # You are here 🙂
```

> **Tip:** Inline styles are shown in `index.html`, but feel free to move them into `Ourwebsite.css` for better maintainability.

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. **Add assets**

   * Place `Students.jpg` (or any image you like) inside the `assets/` folder.

3. **Open in your browser**

   ```bash
   # Simply double-click
   open index.html
   # or use a local server:
   python -m http.server 8000
   # Navigate to http://localhost:8000
   ```

---

## 🛠️ Customization

* **Change the Cards**: Duplicate or remove any `.Bag` div to adjust the number of cards.
* **Colors & Sizes**: Update the `background-color`, `width`, or `height` values to suit your design.
* **Responsive Tweaks**: Add media queries for better mobile behavior if needed.

---

## 🤝 Contributing

Found something interesting to add? Feel free to open a pull request!

1. Fork the repo
2. Create your feature branch:
   `git checkout -b feature/YourAmazingFeature`
3. Commit your changes:
   `git commit -m "Add amazing feature"`
4. Push to the branch:
   `git push origin feature/YourAmazingFeature`
5. Open a pull request

---

