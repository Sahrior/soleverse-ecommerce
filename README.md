# 🛒 E-Commerce Frontend Website

A modern, responsive **E-Commerce Frontend Website** built using **HTML, CSS, and JavaScript**. This project demonstrates a complete client-side shopping experience including product display, color variants, dynamic product switching, and a clean UI inspired by real-world sneaker stores.

This project is ideal for:

* Frontend practice
* UI/UX learning
* JavaScript DOM manipulation
* Beginner-friendly e-commerce logic understanding

---

## 📌 Project Overview

This is a **static e-commerce website** that showcases multiple sneaker products. Users can:

* Browse products
* Switch between different products using a slider
* View product details (title, price, colors)
* Change product images based on selected color
* Experience a professional landing page layout similar to Nike / sneaker stores

⚠️ **Note:** This is a frontend-only project. No backend, authentication, or payment gateway is included.

---

## 🧱 Technologies Used

| Technology               | Purpose                                     |
| ------------------------ | ------------------------------------------- |
| **HTML5**                | Page structure and semantic layout          |
| **CSS3**                 | Styling, layout, animations, responsiveness |
| **JavaScript (Vanilla)** | Dynamic behavior, DOM manipulation          |

---

## 📁 Folder Structure

```
📦 e commerce
 ┣ 📜 index.html        # Main HTML file
 ┣ 📜 style.css         # All styles and layout design
 ┣ 📜 app.js            # JavaScript logic and interactivity
 ┣ 📂 img               # Images, icons, product assets
 ┃ ┣ 🖼️ air.png
 ┃ ┣ 🖼️ blazer.png
 ┃ ┣ 🖼️ jordan.png
 ┃ ┣ 🖼️ visa.png
 ┃ ┣ 🖼️ facebook.png
 ┃ ┗ 🖼️ ...
```

---

## 🎨 UI Sections Explained

### 1️⃣ Navigation Bar

* Logo
* Menu items (Home, Products, Contact)
* Search icon
* Cart icon

### 2️⃣ Hero / Slider Section

* Horizontally sliding product showcase
* Each slide represents one sneaker model
* Smooth transitions using CSS & JavaScript

### 3️⃣ Product Details Section

* Product Title
* Price
* Color options
* Product Image updates dynamically on color click

### 4️⃣ Features Section

* Free Shipping
* Easy Returns
* Gift Cards
* Online Support

### 5️⃣ Gallery Section

* High-quality lifestyle images
* Modern grid-based layout

### 6️⃣ Footer Section

* Social media icons
* Payment method icons
* Contact information

---

## ⚙️ JavaScript Functionality (app.js)

The JavaScript file handles:

* Product data stored as an **array of objects**
* Slider movement using `transform: translateX()`
* Dynamic updates for:

  * Product name
  * Price
  * Image
  * Color variants

### Example Product Object Structure

```
{
  id: 1,
  title: "Air Force",
  price: 119,
  colors: [
    { code: "black", img: "./img/air.png" },
    { code: "darkblue", img: "./img/air2.png" }
  ]
}
```

This structure is similar to a **struct in C / class in OOP concepts**, making it beginner-friendly for understanding data modeling.

---

## 🚀 How to Run the Project

### Method 1: Open Directly

1. Extract the project folder
2. Open `index.html` in any modern browser

### Method 2: Using VS Code (Recommended)

1. Open folder in **VS Code**
2. Install **Live Server Extension**
3. Right-click `index.html` → **Open with Live Server**

---

## 📱 Responsiveness

* Desktop-first design
* Works best on desktop screens
* Can be extended to mobile with media queries

---



## 🔮 Possible Improvements

* Add mobile responsiveness
* Add shopping cart functionality
* Add backend (Node.js / Spring Boot)
* Add login & authentication
* Connect real payment gateway
* Convert to React / Vue

---

## 📸 Screenshots

*(Add screenshots here if needed)*

---

## 📄 License

This project is for **educational purposes only**. Free to use, modify, and learn from.

---

## 🙌 Author

**Sahrior**
Frontend Developer & Learner

---

