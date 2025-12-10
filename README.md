# Glory Books - Digital Publishing & CMS Platform

[![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://cy-demo.github.io/glorybooks/)
![Status](https://img.shields.io/badge/status-active-blue.svg)

## 📖 Project Overview (專案簡介)

**Glory Books** is a full-stack Single Page Application (SPA) designed for digital publishing houses. It functions as both a public-facing e-commerce showcase and a comprehensive internal **Content Management System (CMS)**.

This project was developed to demonstrate **AI-driven rapid prototyping** and **full-stack development capabilities**, integrating a custom frontend with a serverless backend for real-time data management.

👉 **Live Demo:** [Click Here to View](https://cy-demo.github.io/glorybooks/)

---

## 🚀 Key Features (核心功能)

### 🛍️ Public Storefront (前台展示)
* **Dynamic Catalog:** Real-time fetching of books, merchandise, and events from the database.
* **Advanced Filtering:** Filter books by category, color themes (CSS Variables), tags, and authors.
* **Author Portfolios:** Dedicated pages for authors with biographies, works lists, and "Universe" link integration.
* **Responsive Design:** Fully optimized for mobile and desktop devices.

### 🛠️ Admin Dashboard (後台管理)
* **Secure Authentication:** Powered by **Supabase Auth** for secure admin login.
* **CRUD Operations:** Full capability to Create, Read, Update, and Delete records for books, merch, and activities.
* **Rich Text Editor:** Custom-built WYSIWYG editor for formatting descriptions and announcements.
* **Asset Management:** Integrated **Cloudinary API** for seamless image uploading and hosting.
* **Site Settings:** Dynamic control over site title, logos, and home page announcements without touching code.

---

## 🛠️ Tech Stack (技術架構)

This project utilizes a modern, serverless architecture to minimize maintenance costs while maximizing performance.

* **Frontend:**
    * HTML5 / CSS3 (Grid & Flexbox)
    * JavaScript (ES6+, Vanilla JS for performance)
* **Backend & Database:**
    * **Supabase:** PostgreSQL database & Authentication service.
* **Integrations:**
    * **Cloudinary:** Image CDN and storage.
    * **MailerLite:** Newsletter subscription integration.
* **Development Methodology:**
    * **Vibe Coding / AI-Assisted Development:** Leveraged AI tools to accelerate logic implementation, CSS styling, and database schema design.

---

## 🤖 AI-Driven Development Workflow

This project serves as a case study in **"Vibe Coding"**—using AI as a co-pilot to bridge the gap between business logic and technical implementation.

1.  **Architecture Design:** AI assisted in defining the JSON schema and Supabase table relationships (Books <-> Authors).
2.  **Rapid Prototyping:** Accelerated the creation of the Admin Dashboard UI and complex form handling logic.
3.  **Problem Solving:** Used AI to debug asynchronous data fetching (Async/Await) and cross-origin (CORS) image upload issues.

---

## 📸 Screenshots



| Home Page | Admin Dashboard |
|:---:|:---:|
| <img width="2692" height="1308" alt="image" src="https://github.com/user-attachments/assets/e6c0d602-82ef-456c-a8da-427938c3e5fe" />
 | <img width="2804" height="1374" alt="image" src="https://github.com/user-attachments/assets/5340a3f2-2537-4efb-9a2a-289a2837474c" />
 |

---

## 🔧 Installation & Setup

Since this is a client-side SPA connected to a BaaS (Backend-as-a-Service), setup is straightforward:

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/cy-demo/glorybooks.git](https://github.com/cy-demo/glorybooks.git)
    ```
2.  **Open `index.html`:**
    Simply open the file in any modern browser. No build step (npm/webpack) required for this vanilla JS version.

*Note: Backend features require valid API Keys (Supabase/Cloudinary) which are secured in the production environment.*

---

## 👤 Author

**ChiungYun Chang**
* **Role:** Full-Stack Developer & Capacity Planner
* **Focus:** Supply Chain Technology, AI Applications, and System Optimization.
* **LinkedIn:** https://www.linkedin.com/in/chiung-yun-chang-54454884/
