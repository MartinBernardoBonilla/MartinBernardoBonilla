![Backend Status](https://img.shields.io/badge/Backend-Running-success?style=for-the-badge&logo=node.js)
![Frontend Status](https://img.shields.io/badge/Frontend-Live-blue?style=for-the-badge&logo=vercel)
![Docker](https://img.shields.io/badge/DevOps-Docker--Ready-2496ED?style=for-the-badge&logo=docker)

# 🛍️ Biye — Plataforma E-commerce Fullstack
**Desarrollo de alto impacto con Flutter, Node.js y Mercado Pago**

**Biye** es un ecosistema de e-commerce diseñado para gestionar el flujo completo de ventas, desde la navegación de productos hasta la conciliación de pagos en tiempo real. Este proyecto demuestra la implementación de arquitecturas escalables y la integración profunda de servicios de pago.

---

## ✨ Demo en Vivo
- 📱 **Frontend (Web/Mobile):** [biye-app.vercel.app](https://biye-app.vercel.app)
- ⚙️ **API Backend:** [Railway Production](https://biye-ecommerce-production.up.railway.app)

---

## 🚀 Características Técnicas & Pagos

✅ **Ecosistema de Pagos Mercado Pago:**
- **Checkout Pro & QR:** Flujos de pago online y presenciales completamente funcionales.
- **Sincronización Avanzada:** Implementación de **Webhooks + Polling inteligente** para garantizar que el estado del pedido sea siempre exacto.
- **Resiliencia:** Sistema de **Fallback automático** e **Idempotencia** en transacciones para evitar duplicaciones y errores de red.

✅ **Arquitectura de Software:**
- **Frontend:** Implementación de *Clean Architecture* con gestión de estado a través de **BLoC (Hydrated)** para persistencia local.
- **Backend:** Estructura modular basada en Express y ES Modules, optimizada para alta concurrencia.
- **Seguridad:** Autenticación robusta con JWT, gestión de roles y Rate Limiting.

---

## 🧠 Stack Tecnológico

### **Interfaz (Frontend)**
- **Flutter + Dart**
- **BLoC & Hydrated BLoC** (Persistencia de estado)
- **Integración Nativa:** URL Launcher y generación dinámica de QR.

### **Servicios (Backend)**
- **Node.js (v22) + Express**
- **MongoDB + Mongoose** (Modelado de datos complejo)
- **Redis** (Optimización de caché y sesiones)

### **⚙️ DevOps & Infraestructura**
- **Docker & Docker Compose:** Contenedorización multi-etapa para entornos consistentes.
- **CI/CD:** Despliegue automatizado en **Railway** (Backend) y **Vercel** (Frontend).
- **Entorno de Dev:** Configuración de túneles **Ngrok** para pruebas de Webhooks en tiempo real.

---

## ⚙️ Instalación Local

```bash
# 1. Clonar el repositorio
git clone https://github.com/MartinBernardoBonilla/biye-ecommerce.git
cd biye-ecommerce

# 2. Configurar y levantar Backend
cd backend
npm install
cp .env.example .env
npm run dev

# 3. Iniciar Frontend
cd ../frontend
flutter pub get
flutter run
