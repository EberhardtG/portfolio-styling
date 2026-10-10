
# 🌐 Grant Eberhardt — Developer Portfolio  
A clean, responsive personal portfolio built with **HTML5** and **modern CSS**, showcasing projects, skills, and contact information. Designed with a centered content layout, accent‑styled section headings, and a flexible project grid.

---

## 📌 Overview

This project is a simple, elegant developer portfolio intended to highlight:

- Professional identity  
- Technical skills  
- Featured projects  
- Contact information  

The layout is fully responsive and uses modern CSS techniques such as:

- Flexbox  
- Box‑shadow transitions  
- Accent borders  
- Max‑width centered content  
- Semantic HTML structure  

---

## 🎨 Features

### ✔ Clean, Centered Layout  
Main content is limited to **900px max width**, centered with `margin: auto` for readability.

### ✔ Modern Header & Footer  
A bold green header and footer create a strong visual identity.

### ✔ Section Heading Accents  
Each section heading uses a **3px accent border** for visual hierarchy.

### ✔ Responsive Project Grid  
Projects are displayed in a flexible two‑column layout using Flexbox.

### ✔ Smooth Hover Effects  
Cards lift slightly on hover using `transform` and `box-shadow` transitions.

### ✔ Semantic HTML  
Uses `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>` for accessibility and SEO.

---

## 📂 File Structure

```
portfolio/
│
├── index.html
└── portfolio-styles.css
```

---

## 🧩 HTML Structure

The portfolio includes four main sections:

### **1. Header**
Displays your name, tagline, and navigation links.

### **2. About**
A short introduction and background summary.

### **3. Projects**
A grid of project cards, each with a title and description.

### **4. Skills**
A simple list of technical skills.

### **5. Footer**
Contact email, GitHub link, and copyright.

---

## 🎨 CSS Highlights

### **Global Reset**
Ensures consistent spacing across browsers.

### **Header Styling**
Deep green background, centered text, and hover‑animated nav links.

### **Main Content**
```css
main {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
}
```

### **Section Heading Accent**
```css
.main-content h2, h3 {
    border-bottom: 3px solid #4A90E2;
}
```

### **Project Grid**
```css
.project-grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}
```

### **Hover Lift Effect**
```css
.project-grid article:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 12px rgba(0,0,0,0.2);
}
```

---

## 🚀 How to Use

### **1. Clone the repository**
```bash
git clone <your-repo-url>
cd portfolio
```

### **2. Open the HTML file**
Simply open `index.html` in any browser.

### **3. Customize**
Update:

- Your name  
- Bio  
- Projects  
- Skills  
- Contact info  

You can also adjust colors, fonts, or layout in `portfolio-styles.css`.

---

## 📸 Preview (Optional)

Add a screenshot here if you want:

```
![Portfolio Screenshot](screenshot.png)
```

---

## 🔧 Future Improvements

- Add a dark mode toggle  
- Add animations for section transitions  
- Convert project cards into clickable links  
- Add a contact form  
- Add mobile navigation menu  

---

## 📜 License

MIT License (or your preferred license)
