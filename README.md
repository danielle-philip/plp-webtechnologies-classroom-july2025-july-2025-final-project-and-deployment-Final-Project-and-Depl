 Green Ripper – Multipage Product Website

A static, responsive **multipage website** for **Green Ripper** — a brand offering premium **tissues, serviettes, aluminium foil rolls, and eco-friendly carrier bags.**  
This site demonstrates best practices in **planning, building, and organizing** a small front-end project with **HTML5, CSS3, and JavaScript**.

---

Project Purpose
- Present Green Ripper’s brand identity and products in a **clear, mobile-friendly layout**.
- Showcase a **structured, multipage navigation experience**.
- Include basic **interactivity** (mobile menu toggle, gallery animations, form validation).
- Serve as a **deployment-ready project** for GitHub Pages or any static-site host.

---

Project Structure
green_ripper_multipage/
├── index.html # Home – welcome banner & highlights
├── about.html # About – company story & mission
├── products.html # Product showcase with hover animations
├── gallery.html # Gallery – images fade in on scroll
├── contact.html # Contact form with JS validation
│
├── css/
│ ├── main.css # Global styling, responsive layout, product hover effects
│ └── animations.css # Fade-in animation classes for gallery images
│
├── js/
│ ├── main.js # Mobile-menu toggle & IntersectionObserver for fade-ins
│ └── validate.js # Client-side form validation for Contact page
│
└── images/ # Banner & placeholder product/gallery images

yaml
Copy code

---

Site Map & User Journey
| Page         | Purpose / Content Highlights                           | Interactive Element        |
|--------------|-------------------------------------------------------|----------------------------|
| **Home**     | Hero banner + 3 product highlights                     | –                          |
| **About**    | Brand story, eco-friendly commitment                   | –                          |
| **Products** | Grid of 4 product cards with hover-scale + tilt effect | Image hover animation      |
| **Gallery**  | 4-image grid of product use cases                      | Fade-in on scroll          |
| **Contact**  | Form for name, email, message                          | JavaScript form validation |

Navigation is consistent across all pages (header links & footer links).

---

 Features
- **Responsive Design:** mobile-first, adapts to different screen sizes.
- **Consistent Layout:** shared header, footer, and banner style on all pages.
- **Interactive Elements:**
  - Mobile **menu toggle** for small screens.
  - **Hover animations** for product images.
  - **Fade-in animation** for gallery images as they scroll into view.
  - **Form validation** alerts if fields are empty.
- **Lightweight:** built with vanilla HTML/CSS/JS — no frameworks required.

---

## ⚙️ Running Locally

Link: https://danielle-philip.github.io/green-web/
