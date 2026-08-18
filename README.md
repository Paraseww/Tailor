# 🧵 Tailor - Full-Stack Bespoke E-Commerce & Custom Tailoring Platform

![Java](https://img.shields.io/badge/Java-21-orange.svg?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2-brightgreen.svg?style=for-the-badge&logo=springboot)
![Database](https://img.shields.io/badge/Database-H2%20%2F%20MySQL-blue.svg?style=for-the-badge&logo=hibernate)
![Cloudinary](https://img.shields.io/badge/Cloud-Cloudinary%20CDN-blueviolet.svg?style=for-the-badge&logo=cloudinary)
![Cloud-AWS](https://img.shields.io/badge/Cloud-AWS%20S3-FF9900.svg?style=for-the-badge&logo=amazonaws&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3%20%2F%20JS-informational.svg?style=for-the-badge&logo=javascript)

> **A full-stack Java Spring Boot web platform bridging traditional bespoke tailoring with modern digital retail.**

---

## 📌 Project Overview
**Tailor** is a modern full-stack web application designed for custom tailoring studios and fashion retailers. Developed as part of our 2nd Year 1st Semester Object-Oriented Programming (OOP) with Java module, it offers a dual shopping experience:
* **Readymade Retail & Raw Materials Store:** Customers can browse off-the-rack fashion collections, purchase raw fabrics per meter, select garment sizes, and manage persistent shopping carts.
* **Bespoke Custom Tailoring Engine:** Customers can order custom-made suits, blazers, shirts, and trousers by inputting precise measurements (chest, waist, inseam, sleeve, and length).

---

## 📸 Platform Visual Showcase

### 🌐 Digital Storefront & Service Portal
*Home Landing Page, About Us Story, Custom Tailoring Services, and Contact Us Hub*

![Digital Storefront Showcase](frontend/images/first4.png)

---

### 🛒 Retail Shopping, Checkout & Tracking Hub
*Interactive Shop Catalog, Shopping Cart, Real-Time Order Tracking, and User Authentication*

![Retail Shopping Showcase](frontend/images/last4.png)

---

## ✨ Key Features

| Category | Feature | Description |
| :--- | :--- | :--- |
| 📏 **Bespoke Tailoring** | **Custom Measurement Engine** | Enter custom chest, waist, sleeve, length, and inseam measurements for tailored apparel. |
| 🛍️ **E-Commerce Shop** | **Dynamic Product Catalog** | Browse readymade garments and raw fabrics per meter with responsive category filters. |
| 🛒 **Cart & Checkout** | **Persistent Shopping Cart** | Real-time tax (2%) & delivery fee calculations with promotional free-shipping logic over Rs 20,000. |
| 🚚 **Order Tracking** | **Visual Progress Pipeline** | Real-time multi-stage order tracking (*Confirmed → Tailoring → Quality Check → Delivered*). |
| ⚙️ **Admin Dashboard** | **Inventory Control & Reports** | Full CRUD product operations, live drag-and-drop image upload preview, and automated CSV sales export. |
| ☁️ **Cloud Infrastructure** | **Hybrid Media Engine** | Embedded H2 & MySQL database support, paired with Cloudinary CDN and AWS S3 media management. |

---

## 💻 Technologies Used

| Layer | Technologies & Tools |
| :--- | :--- |
| **Backend Core** | Java 21, Spring Boot 3.2 (Spring MVC, Spring Data JPA, Hibernate) |
| **Database Systems** | Embedded H2 File Database (`jdbc:h2:file:./data/tailorshopdb`) & MySQL Support |
| **Cloud & Media Storage** | Cloudinary Java SDK, Cloudinary Global CDN, AWS S3 & Local Storage Fallback |
| **Frontend UI** | HTML5, CSS3, JavaScript (ES6+), Bootstrap 4.4.1, FontAwesome 6.5 |
| **APIs & Protocols** | RESTful Web APIs, JSON Serialization, Multipart File Uploads |
| **Build & Tools** | Apache Maven, Git / GitHub, Visual Studio Code |

---

## 🎨 UI/UX Design Case Study
Check out the complete visual UI design showcase and case study on **Behance**:  
👉 [**View Behance UI/UX Showcase**](https://www.behance.net/gallery/242378331/Tailor-Website-UIUX-Design)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Paraseww/Tailor.git
cd Tailor
