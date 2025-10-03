# Amir Mohammad Zaker - Portfolio Website

This is a personal portfolio website for **Amir Mohammad Zaker**, a Computer Science student with a passion for **web development**. The website showcases personal projects, experience, skills, and contact information in a responsive and visually appealing layout.

---

## 📂 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Global styles for layout, typography, and sections
├── mediaqueries.css    # Responsive styles for various screen sizes
├── script.js           # JavaScript for interactive elements (hamburger menu, etc.)
├── assets/             # Folder containing images, icons, CV PDF
│   ├── circle.jpg
│   ├── circle1.jpg
│   ├── linkedin.png
│   ├── github.png
│   ├── email.png
│   ├── checkmark.png
│   ├── arrow.png
│   ├── One-pageSite.png
│   ├── Calculator.png
│   └── myCV.pdf
└── README.md           # Project documentation
```

---

## 🏗️ Features

The project is structured into several sections:

### 1. **Navbar**

* Desktop and hamburger navigation
* Smooth scrolling to sections
* Hover effects on links

### 2. **Profile Section**

* Personal introduction
* Profile picture
* Download CV button
* Contact Info and social media links (LinkedIn, GitHub)

### 3. **About Section**

* Short bio and description
* Experience and education blocks with icons
* Fully responsive layout

### 4. **Experience Section**

* Skills with icons and proficiency levels (Java, Python, Django, C, C++)
* Teaching experience
* Clean layout with flex containers

### 5. **Projects Section**

* Display 3 recent projects with images
* Project titles and GitHub links
* Buttons and hover effects
* Styled containers with background colors

### 6. **Contact Section**

* Email and LinkedIn contact info
* Icons with clickable links
* Responsive layout for mobile and tablet

### 7. **Footer**

* Navigation links to each section
* Copyright information

---

## 🎨 Styling

* **Global Styles:** Typography (Poppins), smooth scroll, default margins/paddings
* **CSS Classes:** Flexbox containers for sections, buttons, icons
* **Responsive:**

  * `@media screen and (max-width: 1400px)`
  * `@media screen and (max-width: 1200px)`
  * `@media screen and (max-width: 600px)`
* Hamburger menu for smaller screens
* Styled buttons, icons, and images with hover effects

---

## ⚡ Interactivity (JavaScript)

* Hamburger menu toggle

  ```js
  function toggleMenu() {
      const menu = document.querySelector('.menu-links');
      const icon = document.querySelector('.hamburger-icon');
      menu.classList.toggle('open');
      icon.classList.toggle('open');
  }
  ```
* Smooth navigation between sections

---

## 📦 Commit Highlights

| Type    | Description                                                    |
| ------- | -------------------------------------------------------------- |
| `init`  | Initial project setup                                          |
| `feat`  | Added sections: Profile, Experience, Projects, Contact, Footer |
| `style` | Styled all sections, responsive media queries, buttons, icons  |
| `fix`   | Corrected broken links, markup structure, skill levels         |
| `chore` | Added assets folder and images                                 |
| `docs`  | Updated README and code comments                               |

---

## 📌 Technologies Used

* **HTML5** – Semantic markup and layout
* **CSS3** – Styling, Flexbox, Media Queries, Hover effects
* **JavaScript** – Interactive hamburger menu
* **Fonts & Icons** – Google Fonts (Poppins), custom icons/images

---

## 📱 Responsive Design

* Fully responsive for **desktop, tablet, and mobile**
* Flexbox and media queries adjust layout
* Images and text scale dynamically

---

## 💡 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/amirmohammadzaker/portfolio.git
```

2. Navigate to the project folder:

```bash
cd portfolio
```

3. Open `index.html` in your browser.

---

## 📄 License

This project is **open-source** and free to use for educational purposes.