# 🛒 Trendora - Frontend

Trendora is a modern web platform designed to simplify the exchange of second-hand goods. This repository houses the **frontend** of Trendora, crafted with contemporary web technologies to deliver an intuitive, fast, and user-friendly marketplace experience.
---

## 🚀 Features

✅ **User-Friendly Interface** - A seamless and intuitive UI for buyers and sellers.  
✅ **Product Listings** - Users can list, browse, and purchase second-hand products.  
✅ **Category-Based Navigation** - Browse products by category for quick access.  
✅ **Secure Authentication** - Login and register using Custom Authentication.  
✅ **Real-Time Search & Filters** - Advanced search and filtering for better discovery.   
✅ **Mobile Responsiveness** - Optimized for all screen sizes and devices.

---

## 🛠 Tech Stack

| Technology        | Purpose                             |
| ----------------- | ----------------------------------- |
| **Next.js 15**    | Frontend framework                  |
| **ShadCN UI**     | Modern UI components                |
| **Tailwind CSS**  | Utility-first styling               |
| **Custom Auth**   | User authentication & authorization |

---

## 📂 Project Structure

```
resellbd-frontend/
│-- public/         # Static assets (images, icons, etc.)
│-- src/
|   |── actions     # Auth Action
│   ├── app/        # Application-level components and pages
│   ├── components/ # Reusable UI components
│   ├── constants/  # Constant values used throughout the app
│   ├── context/    # Context API
│   ├── lib/        # Utility functions and helper libraries
│   ├── providers/  # Context and global state providers
│   ├── types/      # TypeScript type definitions
│   ├── hooks/      # Custom React hooks
│   ├── services/   # API and service-related functions
│-- middleware.ts   # Middleware configuration
│-- .env           # Environment variables
│-- .gitignore     # Git ignore file
│-- package.json   # Dependencies & scripts
│-- README.md      # Project documentation
```

---

## ⚙️ Installation & Setup

### Steps to Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/rafiferdos/trendora.git
   ```
2. **Navigate to the project directory**
   ```sh
   cd trendora
   ```
3. **Install dependencies**
   ```sh
   npm install
   ```
4. **Set up environment variables**
   Update `.env` with:
   ```env
   NEXT_PUBLIC_BASE_API=https://swap-nest-server-seven.vercel.app/api
   ```
5. **Start the development server**
   ```sh
   npm run dev
   ```

---

## 🔧 Available Scripts

| Command         | Description                       |
| --------------- | --------------------------------- |
| `npm run dev`   | Starts the development server     |
| `npm run build` | Builds the project for production |
| `npm run start` | Runs the production build         |
| `npm run lint`  | Checks for linting errors         |

---

## 🌐 API Integration

- **Backend Base URL**: `NEXT_PUBLIC_BACKEND_URL`
- **Endpoints Used:**
  - `GET /listings` → Fetch all products
  - `GET /listings/:id` → Fetch product details
  - `PATCH /listings/:id` → Update product data
  - `DELETE /listings/:id` → Delete product
  - `POST /listings` → Add a new product
  - `POST /transactions` → Place an order

---

## 🔐 Authentication & Security

- Custom Authentication is used for user login & registration.
- JWT (JSON Web Token) is implemented for secure API calls.
- Role-based access control (RBAC) for admin and users.
- HTTPS enforced for secure communication.

---

## 🎨 UI/UX Design

- **Modern Design** - Uses ShadCN UI & Tailwind CSS for a clean, responsive layout.

---

Github Client Link: https://github.com/rafiferdos/trendora

Github Server Link: https://github.com/Humayun1318/SwapNest-server

Live Link: https://trendora-black.vercel.app/

---
