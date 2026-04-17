##  Working Progress
-   I am currently working on this project. Once I complete it, I will inform you, and then you can proceed with the payment. 
##  How to get access of the source code
-   Pay ($200) at PhonePe  6372590364@ybl (Global)
-   Pay (Rs. 17,440) via UPI <b>6372590364@ybl</b> (India)
-   Once payment successfull, please send your git username on my email 97chittaranjanbehera@gmail.com
<p><b>Note: </b>Please create different branch before pushing the code</p>


# Working Project

This is multi-vendor eCommerce website built with Django, Django rest framework, Reacts and Bootstrap 5. 
All the eCommerce features available in this project including vendor panel.  
## Multivendor Ecommerce Websites 
This is multivendor ecommerce websites. Customer can purchase web scripts in various technologies. 
# Features 
----------------------------- 
Website Information 
- Home page 
- Header 
- Latest Projects 
- Popular Categories (According to product downloads count) 
- Popular Projects (According to product downloads count) 
- Popular sellers (According to product) 
- Customer Rating & Reviews 
- Footer 
- All Category List 
- All product list according to price, latest, alphabet, views 
- Sort according to price, latest, alphabet, views 
- Product Detail 
- Checkout Page 
- 1.PayPal 
- 2.Razorpay 
- 3.Stripe 
- Order Success Page 
- Order Failure Page 
- Multilingual 
---------------------------------------------------------------------------- 
---------------------------------------------------------------------------- 
Customer Panel 
- Register 
- Login 
- Forgot Password 
- Dashboard 
- Orders 
- Profile 
- Change Password 
----------------------------------------------------------------------------- 
Seller Panel 
- Register 
- Login 
- Forgot Password 
- Dashboard 
- Manage Categories 
- Manage Products 
- Orders 
- 1.Downloads Scripts 
- Customers 
- Profile 
- Change Password 
-------------------------------------------------------------------------------- 
Admin Panel 
- Manage Sellers 
- Manage Categories 
- Manage Products 
- Manage Customers 
- Manage Orders 
---------------------------------------------------------------------------------- 
Technologies (2022) 
- Python 3.12 
- Django 4.1 
- ReactJs – 18.2 
- Bootstrap 5.2 
- PostgreSQL 14 
- pgAdmi 4 
- Ubuntu 22 (Linux) 
 
## Multivendor Ecommerce Websites 
Setup project and Creating database models 
-------------------- 
1. Python  
2. Install Virtual Environment – pip install virtualenv 
3. Create Virtual Environment – python3 -m venv env 
4. Activate Virtual Environment - source env/bin/activate 
5. Install Django - pip install Django 
6. Create Django Project - django-admin startproject backend _api  
7. Run Django Project – python3 manage.py runserver 
8. Install PostgreSQL – https://www.postgresql.org/docs/ 
 
9. Install PgAdmin4 – https://www.pgadmin.org/ 
10.  Install psycopg2-binary – pip install psycopg2-binary 
11.  Django Rest Framework – pip install djangorestframework.


## Multivendor Ecommerce Websites 
Setup project and Creating chittafrontend
-------------------- 
* First, you need to install Node.js. After that, follow the steps described below.
1. npx create-react-app chittafrontend
2. npm start
3. npm install bootstrap
# Multivendor eCommerce Platform

> A full-featured multivendor eCommerce website built with **Django**, **Django REST Framework**, **React**, and **Bootstrap 5**. Customers can purchase web scripts in various technologies. All eCommerce features are available including a complete vendor panel.

---

## 🚧 Working Progress

I am currently working on this project. Once I complete it, I will inform you, and then you can proceed with the payment.

## 💳 How to Get Access to the Source Code

- Pay **$200** via PhonePe: `6372590364@ybl` (Global)
- Pay **Rs. 17,440** via UPI: `6372590364@ybl` (India)
- Once payment is successful, please send your Git username to: **97chittaranjanbehera@gmail.com**

> **Note:** Please create a different branch before pushing the code.

---

## 📐 System Design Architecture

### Executive Overview

This platform enables multiple sellers to list and sell web scripts across various technologies. Customers browse, purchase, and download digital products in a unified marketplace managed by a central administrator.

The platform is built on a modern, decoupled architecture:

- **Backend API** — Python / Django 4.1 with Django REST Framework
- **Frontend SPA** — React 18.2 with Bootstrap 5.2
- **Database** — PostgreSQL 14 administered via pgAdmin 4
- **Hosting** — Ubuntu 22 LTS Linux server
- **Payments** — PayPal, Razorpay, Stripe (multi-gateway checkout)

### Architecture Layers

| Layer | Components | Technologies / Notes |
|---|---|---|
| **Client tier** | Customer SPA, Seller SPA, Admin panel | React 18.2 + Bootstrap 5.2 (three distinct frontends) |
| **API gateway** | Request routing, authentication, CORS | Django REST Framework — JWT auth, rate limiting |
| **Service layer** | Auth, Product, Order, Vendor, Search, i18n | Django apps (modular, one app per domain) |
| **Data tier** | Relational store, file storage | PostgreSQL 14 + pgAdmin 4 + Django media storage |
| **External APIs** | Payment processing, email delivery | PayPal, Razorpay, Stripe; SMTP for notifications |

---

## ✨ Features

### Website / Public Pages

- Home page with Header
- Latest Projects
- Popular Categories *(by product download count)*
- Popular Projects *(by product download count)*
- Popular Sellers *(by product count)*
- Customer Ratings & Reviews
- Footer
- All Category List
- All Product List — sort by price, latest, alphabetical, views
- Product Detail page
- Checkout Page
  - PayPal
  - Razorpay
  - Stripe
- Order Success Page
- Order Failure Page
- Multilingual support

### Customer Panel

| Feature | Description |
|---|---|
| Register | New customer self-registration |
| Login | JWT-secured authentication |
| Forgot Password | Email-based password reset |
| Dashboard | Order summary and account overview |
| Orders | Full order history and download access |
| Profile | Edit personal details |
| Change Password | Secure password update |

### Seller Panel

| Feature | Description |
|---|---|
| Register | Seller self-registration |
| Login | JWT-secured authentication |
| Forgot Password | Email-based password reset |
| Dashboard | Sales summary and download counts |
| Manage Categories | Create and organise product categories |
| Manage Products | Add, edit, and remove product listings |
| Orders | View customer purchases |
| Download Scripts | Trigger and manage script delivery |
| Customers | List of buyers from this seller |
| Profile | Edit store and personal details |
| Change Password | Secure password update |

### Admin Panel

- Manage Sellers
- Manage Categories
- Manage Products
- Manage Customers
- Manage Orders

---

## 🏗️ Client-Side Architecture

### Customer Portal

- Home page with hero, latest projects, popular categories, popular projects, popular sellers
- Product catalog with sorting by price, latest, alphabetical, and view count
- Product detail page with customer ratings and reviews
- Checkout flow — payment gateway selection, success and failure pages
- Authenticated area — dashboard, order history, profile, password management
- Multilingual support via i18n locale switching

### Seller Panel

- Self-registration and JWT-secured login
- Dashboard with sales summary and download counts
- Product management — create, edit, and categorise listings
- Category management scoped to the seller's store
- Order management — view customer purchases and trigger script downloads
- Customer list — buyers who purchased from this seller
- Profile and password management

### Admin Panel

- Managed via Django's built-in admin interface
- Full control over sellers, categories, products, customers, and orders
- Platform-wide reporting and content moderation

---

## 🔐 API Gateway & Authentication

### Django REST Framework Gateway

All client requests pass through a single DRF API layer serving JSON over HTTPS. The gateway handles:

- JWT token issuance and validation (`djangorestframework-simplejwt`)
- Role-based permission enforcement (Customer, Seller, Admin)
- CORS configuration for the React frontend origin
- Request rate limiting to prevent abuse
- URL routing to the correct Django app / viewset

### Authentication Flow

1. Client sends credentials (email + password) to `/api/auth/login/`
2. DRF validates credentials and returns access + refresh JWT tokens
3. Client stores tokens in memory / HTTP-only cookie
4. Subsequent requests include `Authorization: Bearer <access_token>` header
5. On token expiry, client calls `/api/auth/token/refresh/` with the refresh token
6. Forgot-password flow sends a reset link via SMTP email

---

## 🧩 Backend Service Layer

| Django App | Responsibilities |
|---|---|
| `accounts` | User registration, login, JWT, password reset — Customer and Seller models |
| `products` | Product CRUD, category management, image/file upload, view tracking |
| `orders` | Checkout, payment webhook handling, order status, download token generation |
| `vendors` | Seller profile, seller-scoped analytics, approval workflow |
| `reviews` | Customer ratings and written reviews linked to products |
| `search` | Full-text search, filter and sort endpoints (price, latest, alpha, views) |
| `i18n` | Locale detection, translation message files, language-switch API |

---

## 🗄️ Data Architecture

### Core Data Models

| Model | Key Fields and Relationships |
|---|---|
| `User` | id, email, role (customer/seller/admin), is_active, date_joined |
| `SellerProfile` | user (FK), store_name, description, total_downloads |
| `Category` | id, name, slug, parent (self-FK for hierarchy) |
| `Product` | id, seller (FK), category (FK), title, slug, price, file, views, downloads |
| `Order` | id, customer (FK), payment_gateway, status, total_amount, created_at |
| `OrderItem` | id, order (FK), product (FK), price_at_purchase |
| `Review` | id, customer (FK), product (FK), rating (1–5), comment, created_at |
| `Download` | id, order_item (FK), token, expires_at |

### File Storage

- Uploaded scripts and product thumbnails stored in Django `MEDIA_ROOT`
- Download files served via signed expiring URLs (token-gated endpoint)
- Static assets (JS, CSS bundles) served from `STATIC_ROOT` or a CDN

---

## 💰 Payment Gateway Integration

Three payment gateways support global and regional customers. The Order service handles gateway selection, initiates payment sessions, and processes webhook callbacks to confirm orders.

| Gateway | Integration Pattern |
|---|---|
| **PayPal** | REST SDK — creates payment order, redirects to PayPal hosted page, captures on return |
| **Razorpay** | Orders API — creates Razorpay order, renders `checkout.js`, validates signature on server |
| **Stripe** | Payment Intents API — creates intent server-side, confirms via `Stripe.js` on client, webhook for final status |

### Common Checkout Flow

1. Customer selects items and clicks Checkout
2. React sends cart payload to `POST /api/orders/initiate/`
3. Order service creates a pending Order record and initiates payment with selected gateway
4. Customer completes payment on gateway page / embedded widget
5. Gateway sends webhook to `POST /api/orders/webhook/<gateway>/`
6. Order service verifies webhook signature, marks order as Paid
7. Download tokens are generated; customer redirected to Order Success page
8. On failure, order remains Pending and customer is redirected to Order Failure page

---

## 🛠️ Technology Stack

| Technology | Version | Role |
|---|---|---|
| Python | 3.12 | Runtime for all Django backend code |
| Django | 4.1 | Web framework — ORM, admin, routing, middleware |
| Django REST Framework | 3.x | API layer — serializers, viewsets, JWT auth, permissions |
| React | 18.2 | SPA frontend — component rendering, state management, routing |
| Bootstrap | 5.2 | UI component library and responsive grid system |
| PostgreSQL | 14 | Primary relational database for all platform data |
| pgAdmin | 4 | Web-based database administration and query tool |
| Node.js | LTS | Required to build and run the React frontend (npx, npm) |
| Ubuntu | 22 LTS | Production server OS — stable, long-term supported |
| psycopg2-binary | latest | Python adapter connecting Django to PostgreSQL |

---

## ⚙️ Environment Setup

### Backend (Django API)

```bash
# 1. Install Python 3.12

# 2. Install virtualenv
pip install virtualenv

# 3. Create virtual environment
python3 -m venv env

# 4. Activate virtual environment
source env/bin/activate

# 5. Install Django
pip install Django

# 6. Create Django project
django-admin startproject backend_api

# 7. Run development server
python3 manage.py runserver

# 8. Install PostgreSQL — https://www.postgresql.org/docs/

# 9. Install pgAdmin 4 — https://www.pgadmin.org/

# 10. Install PostgreSQL adapter
pip install psycopg2-binary

# 11. Install Django REST Framework
pip install djangorestframework
```

### Frontend (React)

```bash
# 1. Install Node.js (LTS) — https://nodejs.org/

# 2. Create React app
npx create-react-app chittafrontend

# 3. Start development server
npm start

# 4. Install Bootstrap
npm install bootstrap
```

Then import Bootstrap in `src/index.js`:

```javascript
import 'bootstrap/dist/css/bootstrap.min.css';
```
---

![image alt](https://github.com/Chittaranjanbehera123/LuxuryMultiVendorEcommerce-ReadMe.md/blob/8dc9bbc11e7a047d3280ab2855c197c19199dd72/Screenshot%20(137).png)
![image alt](https://github.com/Chittaranjanbehera123/LuxuryMultiVendorEcommerce-ReadMe.md/blob/aefa1156a826944a0881b217165c17ec310c8413/Screenshot%20(138).png)

## 🔒 Security Considerations

- All API endpoints enforced with DRF permission classes (`IsAuthenticated`, `IsAdminUser`, custom `IsSellerUser`)
- JWT access tokens expire after a short window (15–60 min); refresh tokens stored securely
- Payment webhook signatures verified server-side before any order state change
- Download files never exposed at a public URL — served via one-time signed tokens
- `SECRET_KEY`, database credentials, and gateway API keys stored in environment variables — never in source code
- CSRF protection enabled for session-based admin; CORS restricted to known frontend origins
- PostgreSQL access restricted to localhost / private network; pgAdmin behind VPN or SSH tunnel
- Ubuntu server hardened with UFW firewall, fail2ban, and regular security updates

---

## 📈 Scalability & Future Considerations

- Introduce **Redis** for caching popular categories, homepage data, and session tokens
- Add **Celery** task queue for async jobs — email delivery, post-purchase webhooks, report generation
- Move file storage to **object store** (AWS S3 / Cloudflare R2) as product catalogue grows
- Containerise with **Docker** and Docker Compose for consistent dev-to-production parity
- Introduce a **CDN** (Cloudflare / AWS CloudFront) for static assets and React build files
- Consider **read replicas** for PostgreSQL as query load increases on the product catalogue
- Add comprehensive **API logging and monitoring** (Sentry, Prometheus + Grafana)

---
![image alt](https://github.com/Chittaranjanbehera123/LuxuryMultiVendorEcommerce/blob/e61b71e981bfe3b002316901bfb47f5a65e6b7af/ChatGPT%20Image%20Apr%204%2C%202026%2C%2007_03_52%20AM.png)

*© 2026 Chittaranjan Behera — Multivendor eCommerce Platform*
