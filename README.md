# 🏗️ Ferremas Platform – Frontend

Este repositorio corresponde al FRONTEND de la plataforma Ferremas, desarrollado con Angular.
La aplicación consume servicios expuestos por un Gateway en Express, el cual a su vez se comunica con un backend principal desarrollado en Java.

Este frontend representa la capa de presentación del sistema, orientada a usuarios finales.

--------------------------------------------------

<details>
<summary><strong>🧠 ¿Qué es Ferremas Platform – Frontend?</strong></summary>

Ferremas Platform – Frontend es una aplicación web desarrollada con Angular que permite:

✔ Visualizar productos de ferretería
✔ Navegar por categorías
✔ Interactuar con el sistema mediante una interfaz moderna
✔ Consumir datos desde un Gateway API
✔ Separar completamente la lógica visual del backend

Este repositorio es parte de un sistema distribuido compuesto por tres capas:

- Frontend (Angular)
- Gateway / API (Express)
- Backend de negocio (Java)

</details>

--------------------------------------------------

<details>
<summary><strong>📌 Funcionalidades principales</strong></summary>

🛒 Interfaz de productos
- Visualización de productos
- Uso de imágenes y recursos estáticos
- Organización por categorías

📂 Navegación estructurada
- Arquitectura modular de Angular
- Separación de componentes, páginas y utilidades

🌐 Consumo de API
- Comunicación con Gateway Express
- Preparado para integración con servicios REST

🖥️ Renderizado del lado del cliente
- SPA (Single Page Application)
- Experiencia fluida de usuario

</details>

--------------------------------------------------

<details>
<summary><strong>🛠 Tecnologías utilizadas</strong></summary>

- Angular – Framework principal
- TypeScript – Lenguaje base
- HTML – Vistas
- SCSS / CSS – Estilos
- Node.js – Entorno de desarrollo
- npm – Gestión de dependencias

</details>

--------------------------------------------------

<details>
<summary><strong>📂 Estructura del proyecto</strong></summary>

ferremas-platform-frontend/
├── angular.json
├── package.json
├── server.ts
├── tsconfig.json
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── assets/
│   │   └── images/
│   └── environments/
└── README.md

</details>

--------------------------------------------------

<details>
<summary><strong>🔗 Relación con otros repositorios</strong></summary>

Este frontend NO se comunica directamente con el backend Java.

Flujo de comunicación:

Frontend (Angular)
   ↓
Gateway API (Express)
   ↓
Backend de negocio (Java)

Repositorios relacionados:
- ferremas-platform-gateway (Express)
- ferremas-platform-backend (Java)

</details>

--------------------------------------------------

<details>
<summary><strong>🚀 Cómo ejecutar el proyecto localmente</strong></summary>

1. Requisitos
- Node.js (versión LTS)
- npm
- Angular CLI

2. Clonar el repositorio

git clone https://github.com/tu-usuario/ferremas-platform-frontend.git

3. Instalar dependencias

npm install

4. Ejecutar en desarrollo

ng serve

5. Acceder desde el navegador

http://localhost:4200

Nota: El Gateway Express debe estar en ejecución para el consumo de datos reales.

</details>

--------------------------------------------------

<details>
<summary><strong>📄 Licencia</strong></summary>

Repositorio de uso académico y demostrativo.
Puede ser modificado libremente para fines educativos o de práctica profesional.

</details>
