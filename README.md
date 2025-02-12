# cutyCSS  
**cutyCSS** is a **lightweight and modular CSS framework** designed by **IMD 25W_MTM6407_310 Web Development IV** students.  
It provides utility classes and pre-styled components to speed up development while maintaining flexibility.  

---

## 📌 Why use cutyCSS?  
✅ **BEM-based SCSS structure** – for consistency & maintainability  
✅ **Modular utilities** – easily extend and customize styles  
✅ **Minimalist & efficient** – no unnecessary bloat  
✅ **Responsive by default** – works on all screen sizes  

---

## 🚀 How to Use cutyCSS  
### 1️⃣ Installation  
To use cutyCSS in your project, include the compiled CSS file:  
```html
<link rel="stylesheet" href="css/style.css">
```

---
---


# 🎨 CSS Class Guide  

cutyCSS follows a **utility-first approach** with **BEM naming conventions** for maintainability. Below are the key components and utilities.

---

## 1️⃣ Utility Classes  

cutyCSS provides utility classes for quick layout and styling adjustments.

### 📏 Spacing  
| Class Name      | Description        |
|---------------|------------------|
| `.padding__1`  | Small padding    |
| `.padding__2`  | Medium padding   |
| `.margin__auto` | Centers element |

### 🛠️ Display & Flexbox  
| Class Name                        | Description                  |
|-----------------------------------|------------------------------|
| `.u-d__flex`                      | Applies `display: flex;`    |
| `.u-d__row`                       | `flex-direction: row;`      |
| `.u-d__column`                    | `flex-direction: column;`   |
| `.u-d__justify-content-center`    | Center content horizontally |
| `.u-d__align-items-center`        | Center content vertically   |

### 📐 Width & Height  
| Class Name             | Description                |
|-----------------------|--------------------------|
| `.u-container__100vw` | Full width (`100vw`)     |
| `.u-container__2-col` | 2-column width setting   |
| `.u-height__10vh`     | Height of `10vh`         |

---

## 2️⃣ Components  

cutyCSS includes pre-styled elements for quick prototyping.

### ✨ Typography  
| Class Name       | Description              |
|----------------|-------------------------|
| `.text-prime`  | Primary text color      |
| `.text-success`| Success text (green)    |
| `.text-alert`  | Alert text (red)        |
| `.text-link`   | Link-style text (blue)  |

#### Example:  
```html
<h2 class="text-prime">Primary Heading</h2>


---

## Group SCSS Editing Guidelines

## Note for Group Members
We will follow the **BEM (Block Element Modifier)** naming convention for our SCSS editing.  
This ensures consistent and maintainable code across the project.

- [BEM System Introduction (Chinese)](https://jarvis.princityle.com.tw/course/course/10)  
- [BEM System Introduction (English)](https://css-tricks.com/bem-101/)

---

## Tasks of Each Member
Please focus on your assigned tasks:

- **Broccoli**:
  - `utility.scss`
  - `reset.scss`
  - `variables.scss`
- **Rui**:
  - `typography.scss`
  - `objects.scss`
- **Ana**:
  - Header
  - List
  - Buttons
- **Zahara**:
  - Hero
  - Media
  - Footer

---

## Reminders
1. Let me know if I missed anything!  
2. **Always push to your personal branch!**

Happy coding! 😊
