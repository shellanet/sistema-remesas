# 💎 Global-Flow | Plataforma Web de Remesas & Conversión de Divisas

> **Aplicación web Full-Stack (Serverless) para la gestión y cálculo dinámico de remesas con API REST propia e ingesta de datos en tiempo real.**

---

## 🌐 Demo en Vivo

* 📱 **App Cliente (Calculadora Interactiva):** [Ver Aplicación en Vivo](https://shellanet.github.io/sistema-remesas/)
* ⚙️ **Panel de Administración (Modo Sandbox):** [Ver Panel Admin](https://shellanet.github.io/sistema-remesas/admin.html)

---

## 🚀 Características Principales

* **API REST Propia (Data Ingestion Service):** Microservicio propio desplegado en la infraestructura de Google Cloud para la ingesta, formateo y suministro de tasas de cambio actualizadas.
* **Sincronización en Tiempo Real:** Actualización instantánea de las tasas de cambio de soles (PEN) y bolívares (VES) mediante **Firebase Realtime Database**.
* **Lógica de Niveles Dinámicos (Profit Guardian):** Algoritmo automatizado que clasifica los envíos en tres niveles (*Mini, Estándar y VIP*) aplicando márgenes preferenciales según el volumen transaccionado.
* **Seguridad y Modo Sandbox:** Configuración de reglas de seguridad en la nube con soporte de autenticación en segundo plano para proteger el entorno de producción y permitir un conmutador de pruebas para evaluaciones de código.
* **Diseño Responsivo & UX Moderna:** Interfaz desarrollada con Tailwind CSS, animaciones interactivas y retroalimentación visual al instante.

---

## 🛠️ Tecnologías Utilizadas

* **Front-end:** HTML5, JavaScript (ES6+ Modules), Tailwind CSS.
* **Backend & API Services:** **API REST propia (Google Cloud Platform / Cloud Infrastructure)**, Firebase Realtime Database, Firebase Authentication (Serverless).
* **DevOps & Hosting:** Git, GitHub, GitHub Pages (CI/CD automático).

---

## 📦 Estructura del Proyecto

```text
sistema-remesas/
├── index.html        # Aplicación para el cliente final (Calculadora)
├── admin.html        # Panel de administración de tasas con conmutador Sandbox
└── README.md         # Documentación técnica del proyecto
