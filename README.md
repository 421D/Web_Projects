# Web_Projects

This folder showcases a collection of web projects completed during my early web development practice.  
Each project focuses on different aspects of **front-end design, UI interactivity, and dynamic data management**.  
All projects were independently designed and developed.

| Project | Type | Core Tech | Focus |
|----------|-------|-----------|--------|
| **Mobile_ECommerce_Mockup** | Static | HTML / CSS / JS | Responsive layout, animation, carousel |
| **YiCha_Static** | Static | HTML / CSS / JS / jQuery | Interactivity, DOM manipulation |
| **YiCha_Dynamic_DedeCMS** | Dynamic | PHP / CMS (Dedecms) | Backend logic, template integration |
| **MAC_Cosmetic_Shop** | Static | HTML / CSS / JS | UI design, hover effects, form validation |
| **LegalAid_Platform_Prototype (Figma)** | UI/UX | Figma / Pixso / UCD Principle | User-centred design, accessibility, workflow visualization |
---

## 1. Mobile_ECommerce_Mockup

**Type:** Static Website (HTML / CSS / JS)  
**Description:**  
A front-end mockup of a mobile e-commerce platform demonstrating layout design and user interaction effects.  

**Main Features:**
- **Homepage (index.html):**  
  - Top banner navigation with dropdown menus and hover animations  
  - Auto-sliding image carousel (2s per slide)  
  - Three showcase blocks with a hover zoom-in effect  
  - Informational section with hover colour changes  
- **Shop Page (shop.html):**  
  - Product detail page with colour/version selection  
  - Static combo offers and specifications section  
- **Login Page (login.html):**  
  - Switch between account login and verification code login (UI only)

> Focused on front-end layout design, hover effects, and carousel scripting using vanilla JavaScript.

**Preview:**  
![Preview of Mobile_ECommerce_Mockup](./preview/mobile_preview.png)

---

## 2. YiCha_Static — Chinese Tea Culture Website (静态版一茶)

**Type:** Static Website (HTML / CSS / JavaScript / jQuery)  
**Description:**  
A multi-page static site themed around **Chinese tea culture**, designed to showcase traditional aesthetics combined with modern front-end interactivity.  

**Main Features:**
- **Sticky Navigation Bar** with scroll-highlighting and smooth section jumps  
- **Auto Image Carousel** on homepage  
- **Hover Image Effects:** transparent overlay with product name, price, and add-to-cart button  
- **Shopping Cart Page:**  
  - Auto-calculates total price  
  - Supports item selection, quantity changes, and deletion  
  - (Front-end only; no backend logic)  
- **User Interaction:**  
  - Prompt pop-ups requesting name/email on contact page  
  - Drop-down list of cities in the message form  
- **JavaScript Modules:**
  - `head.js` → prompt & alert interaction  
  - `index.js` → image carousel  
  - `scripts.js` → sticky navbar + scroll animation  
  - `div-hover.js` → hover-to-switch main image  
  - `jQuery Calculation` → shopping cart price calculation  

>  A project focused on mastering DOM manipulation and front-end user experience.

**Preview:**  
![Preview of YiCha_Static](./preview/yichaj_preview.png)

---

## 3. YiCha_Dynamic_DedeCMS — Dynamic Tea Website (动态版一茶)

**Type:** Dynamic Website (PHP + Dedecms CMS)  
**Description:**  
A CMS-based dynamic version of the YiCha static site, rebuilt with **Dedecms** to enable real-time content updates and backend management.  

**Main Features:**
- **CMS-driven Content:** Add/edit products, articles, and categories from the admin dashboard  
- **Dynamic Product Pages:** Auto-generated via Dedecms tags (`{dede:channel}`, `{dede:list}`)  
- **User System:** Basic registration and login integrated into the Dedecms member module  
- **News & Forum Module:** Replaced static forum link with Dedecms article system  
- **Template Conversion:** Static front-end files converted into `.dwt` templates and linked to backend  
- **Breadcrumbs & Navigation:** Auto-rendered via CMS logic  

> Demonstrates transition from static design to data-driven website development using a CMS.

**Preview:**  
![Preview of YiCha_Dynamic_DedeCMS](./preview/yichad_preview.png)

---

## 4. MAC_Cosmetic_Shop — Static Cosmetics Website (化妆品销售网站)

**Type:** Static Website (HTML / CSS / JS)  
**Description:**  
A brand-themed e-commerce website for **MAC Cosmetics**, focusing on clean design and navigation structure.  

**Main Pages:**
- **Home (index.html):** Main banner, navigation links to featured products and categories  
- **Zidantou (子弹头断货王):**  
  - Grid layout of 12 hot-selling products  
  - Hover to view more info or add to cart (static UI)  
- **All Products (quanbucp.html):**  
  - Table layout (3×3) for browsing  
  - Hover image-switch effect (onmouseover / onmouseout)  
- **Register Page (zhuce.html):**  
  - User input form with email, name, password, phone, dropdowns, and checkboxes  
- **Shopping Cart (gwc.html):**  
  - Table layout showing products, quantities, and totals  
  - Editable quantities (static simulation only)

> Built to explore multi-page structure, front-end styling, and form interaction design.

**Preview:**  
![Preview of MAC_Cosmetic_Shop](./preview/MAC_preview.png)


## 5. LegalAid_Platform_Prototype

**Type:** UI/UX Design Prototype
**Design Principle:** UCD (User-Centred Design) + Accessibility
**Description:**  
A complete high-fidelity prototype for a legal aid and consumer rights protection platform.
The project aims to provide an inclusive, accessible, and easy-to-use platform for users to seek legal help, submit cases, and access AI-assisted support.

**Key Pages & Features:**
- **Login Page:**
  - Secure login and OTP password recovery
  - Direct navigation to the main homepage after authentication
- **Homepage:**  
  - Clear navigation bar with modules like Online Services, Legal Wins, Recent News
  - Designed for clarity and accessibility
- **Community Forum:**  
  - Users can browse posts, explore related topics, and post comments
- **FAQ + AI Assistant:**  
  - Combines a static FAQ database with a chatbot for quick inquiry
- **Accessibility Page:**  
  - Supports screen readers, high-contrast mode, and multilingual switching
  - Accessible feedback form for visually impaired users
- **Case Submission:**  
  - Multiple form templates for complaints
  - Optional contact methods (Email or Direct Support)
- **User Account:**  
  - Tracks viewed posts, saved topics, case status, and notifications


**Design Highlights:**
- **Accessibility First:** optimised for all users, including those using assistive technologies
- **UCD Workflow:** follows complete user journey — from learning rights → submitting case → tracking status
- **Visual Consistency:** professional colour scheme, modular layout, high readability



