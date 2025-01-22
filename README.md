"# Days_1_6-Hackathon" 

# General E-commerce website

A fully responsive and feature-rich e-commerce website leveraging modern web technologies like Tailwind CSS, ShadCN UI, and Sanity CMS, deployed seamlessly on Vercel.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup and Installation](#setup-and-installation)
5. [Dynamic Features](#dynamic-features)
6. [Deployment](#deployment)
7. [Folder Structure](#folder-structure)
8. [Screenshots](#screenshots)
9. [License](#license)

---

## **Project Overview**

This project is a modern e-commerce platform built with the following goals:

- Delivering a responsive and user-friendly shopping experience.
- Utilizing dynamic routing to support product-specific pages.
- Efficient data storage and retrieval using Sanity CMS.
- Ensuring performance, scalability, and a seamless checkout process.

---

## **Features**

### Core Features:
- **Dynamic Routing:** Automatically generated routes for products and categories.
- **Add to Cart & Checkout:** Robust cart management system with a secure checkout flow.
- **Responsive Design:** Fully optimized for mobile, tablet, and desktop devices.
- **Data Management:** Real-time integration with Sanity CMS for managing product data.

### Performance:
- Optimized using Tailwind CSS for lightweight and fast styling.
- Web vitals such as LCP, TBT, and CLS ensure top-tier user experience.

---

## **Technologies Used**

### Frontend:
- **Tailwind CSS**: For rapid UI development with utility-first CSS classes.
- **ShadCN UI**: To ensure visually consistent and reusable components.
- **Naxt.js**: Core framework for building the UI.

### Backend:
- **Sanity CMS**: Used for content management and real-time data storage.

### Deployment:
- **Vercel**: For fast and reliable website hosting.

---

## **Setup and Installation**

### Prerequisites:
- Node.js (v16 or above)
- Git

### Steps:
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd project-folder
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Add environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
     NEXT_PUBLIC_SANITY_DATASET=production
     NEXT_PUBLIC_SANITY_TOKEN=token
     ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the app in your browser at `http://localhost:3000`.

---

## **Dynamic Features**

1. **Dynamic Routing**:
   - Automatically generates individual pages for each product or category using dynamic path configurations.

2. **Add to Cart**:
   - Users can add products to their cart with real-time updates.

3. **Checkout Process**:
   - Secure checkout system with form validation.

4. **Responsive Design**:
   - Optimized layouts and UI components for all device sizes.

---

## **Deployment**

This project is deployed on Vercel. Visit the live site here: [https://marketplace-builder-hackathon-2025-8pia.vercel.app/]

### Steps to Deploy:
1. Push the code to GitHub or any version control system.
2. Connect the repository to Vercel.
3. Configure environment variables in the Vercel dashboard.
4. Deploy the site.

---

## **Folder Structure**

```plaintext
.
📦 root-directory
├── 📁 public
│   ├── 📁 images
│   │   ├── logo.png
│   │   └── banners/
│   └── favicon.ico
├── 📁 src
│   ├── 📁 app
│   │   ├── 📁 cart
│   │   │   └── page.js
│   │   ├── 📁 home
│   │   │   └── page.js
│   │   ├── 📁 checkout
│   │   │   └── page.js
│   │   ├── 📁 category
│   │   │   └── page.js
│   │   └── 📁 product
│   │       └── page.js
│   ├── 📁 components
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── Button.jsx
│   │   ├── Card.jsx
│   │   ├── NewArrival.jsx
│   │   └── Selling.jsx
│   ├── 📁 hooks
│   │   ├── useCart.js
│   │   └── useProductFilter.js
│   ├── 📁 lib
│   │   ├── apiHelpers.js
│   │   ├── sanityClient.js
│   │   └── utilities.js
│   ├── 📁 sanity
│   │   ├── 📁 lib
│   │   │   └── sanity.js
│   │   ├── 📁 schema
│   │   │   ├── product.js
│   │   │   ├── category.js
│   │   │   └── index.js
│   │   └── 📁 types
│   │       └── schemaTypes.js
│   └── 📁 types
│       ├── cart.d.ts
│       ├── product.d.ts
│       └── user.d.ts
├── .env.local
├── .gitignore
├── next.config.js
├── package.json
├── postcss.config.js
└── tailwind.config.js



---


## **License**

This project is licensed under the [MIT License](LICENSE). Feel free to use and adapt it as needed.

---


