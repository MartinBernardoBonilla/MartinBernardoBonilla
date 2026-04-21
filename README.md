# 🛍️ Biye — Plataforma E-commerce Fullstack
**Flutter** + **Node.js** + **MongoDB** + **Mercado Pago**

[![Vercel](https://img.shields.io/badge/Frontend-Vercel-000000?style=for-the-badge&logo=vercel)](https://biye-app.vercel.app)
[![Railway](https://img.shields.io/badge/API-Railway-0B0D0E?style=for-the-badge&logo=railway)](https://biye-ecommerce-production.up.railway.app)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**Biye** es una plataforma de comercio electrónico moderna y genérica, diseñada para ser adaptable a cualquier tipo de negocio. Ofrece un sistema de pagos robusto e integral, con una arquitectura limpia lista para escalar.

---

## ✨ Demo en Vivo
- 📱 **Frontend (Web):** [Ver Demo](https://biye-app.vercel.app)
- ⚙️ **API Backend:** [Railway Production](https://biye-ecommerce-production.up.railway.app)

---

## 🚀 Características Principales

✅ **Sistema de Pagos Mercado Pago:**
- QR para pago presencial y Checkout Pro online.
- Sincronización vía **Webhooks + Polling inteligente**.
- **Idempotencia** garantizada en transacciones.
- Fallback automático ante fallas de red.

✅ **Arquitectura & Seguridad:**
- Frontend: Clean Architecture + BLoC (Hydrated).
- Backend: Modular con Express + ES Modules.
- Autenticación JWT segura y Rate Limiting.
- Contenedorización total para desarrollo y producción.

---

## 🛠️ Stack Tecnológico

### **Interfaz (Frontend)**
- **Flutter + Dart**
- **BLoC** (Gestión de estado profesional)
- **qr_flutter** & **url_launcher**

### **Servicios (Backend)**
- **Node.js (v22) + Express**
- **MongoDB + Mongoose**
- **Redis** (Optimización de caché)
- Mercado Pago SDK Oficial

### **🚀 DevOps & Infraestructura**
- **Docker & Docker Compose**
- **Railway** (Backend CD)
- **Vercel** (Frontend CI)
- **Ngrok** (Túneles para Webhooks en desarrollo)

---

## ⚙️ Cómo Ejecutar Localmente

```bash
# 1. Clonar
git clone [https://github.com/MartinBernardoBonilla/biye-ecommerce.git](https://github.com/MartinBernardoBonilla/biye-ecommerce.git)
cd biye-ecommerce

# 2. Levantar Backend
cd backend
npm install
cp .env.example .env # Configura tus credenciales
npm run dev

# 3. Iniciar Frontend
cd ../frontend
flutter pub get
flutter run
💳 Tarjetas de Prueba (Sandbox)MarcaNúmeroCVVVencimientoVisa4509 9535 6623 370412311/25Mastercard5031 7557 3453 060412311/25👨‍💻 AutorMartín Bernardo Bonilla - Fullstack DeveloperLinkedInPortfolio WoodStackMIT © 2026 Martín Bernardo Bonilla
