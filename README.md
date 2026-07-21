# PERN Stack Product Manager - Frontend Client

[![React](https://img.shields.io/badge/React-19-blue?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6-purple?logo=vite)](https://vite.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![React Router](https://img.shields.io/badge/React_Router-v7-CA4245?logo=react-router)](https://reactrouter.com/)

A modern, highly responsive, and type-safe single-page application (SPA) designed to manage products, availability, and attributes. Built with **React 19**, **TypeScript**, **Vite**, and styled with **Tailwind CSS v4**, this application interacts with a REST API to perform full CRUD operations.

## 🚀 Live Demo & Repository links

- **Live Deployment:** [PERN Product Manager Preview](https://pern-type-script-administrador-de-p.vercel.app/)
  > [!NOTE]
  > Since the backend is hosted on a free hobby plan, the first request may take up to **50 seconds** to wake up the server spin-up.
- **Backend API Repository:** [ProductManager-PERN_Server](https://github.com/CamiloVelasquezBotero/ProductManager-PERN_Server)

---

## ✨ Key Features

- **Route-based Data Fetching:** Built with React Router DOM's **Data APIs** (`loader`, `action`, and `<Form>` elements) to streamline client-side data mutations and fetching without unnecessary useEffect chains.
- **Form Schema Validation:** Integrates **Valibot** for lightweight, robust client-side validation to guarantee data integrity.
- **UI State & UX:** Interactive status toggle buttons, responsive forms, clean error boundaries, and modern design cards.
- **Performance Optimization:** Selective re-rendering and efficient state handling across components to ensure fluid performance.
- **REST API Integration:** Fully integrated with the backend services using custom **Axios** clients.

---

## 🛠️ Tech Stack & Dependencies

- **Framework:** React 19 (via Vite)
- **Language:** TypeScript
- **Styling:** Tailwind CSS (v4)
- **Routing & State Management:** React Router DOM (v7)
- **Data Validation:** Valibot
- **HTTP Client:** Axios

---

## 💻 Installation & Setup

Follow these steps to run the client application locally:

### 1. Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18.x or higher recommended)
- [npm](https://www.npmjs.com/) or another package manager

### 2. Clone the Repository
```bash
git clone https://github.com/CamiloVelasquezBotero/ProductManager-PERN_Client.git
cd ProductManager-PERN_Client
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Configure Environment Variables
Create a file named `.env.local` in the root folder and configure the URL of your backend API:
```env
VITE_API_URL=http://localhost:4000
```

### 5. Running the Application
To launch the development server:
```bash
npm run dev
```
Open your browser and navigate to the address shown in your terminal (typically `http://localhost:5173`).

### 6. Production Build
To create a production-optimized build:
```bash
npm run build
```
You can preview the built production app locally using:
```bash
npm run preview
```

---

## 📂 Project Structure

```text
src/
├── components/   # Reusable UI components (Product details, Form fields, etc.)
├── layouts/      # Application layouts and structure
├── views/        # Page views (Products Dashboard, NewProduct, EditProduct)
├── services/     # Axios client configurations and API connection functions
├── types/        # TypeScript interfaces and schemas
└── utils/        # Helper utility functions
```