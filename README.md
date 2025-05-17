# 📦 eCommerce FRONT

**Front-end en React para tiendas online**, front complementario a ecommerce-api.

---

## 🚀 Tecnologías utilizadas

- **React** – Biblioteca principal para construir interfaces de usuario.
- **Styled-components** – Estilos dinámicos con CSS-in-JS.
- **Ant Design (AntD)** – Sistema de componentes UI.
- **React Router** – Manejo de rutas y navegación.
- **Formik + Yup** – Manejo y validación de formularios.
- **Redux** – Gestión global del estado.
- **Axios** – Cliente HTTP para consumir APIs.

---

## 📁 Estructura del proyecto

```
src/
├── assets/         # Recursos como imágenes o íconos
├── components/     # Componentes reutilizables
├── pages/          # Páginas principales (Home, Checkout, etc.)
├── redux/          # Store, slices y middleware
├── routes/         # Definición de rutas con React Router
├── services/       # Lógica para consumir APIs con Axios
├── styles/         # Estilos globales y temas
├── utils/          # Utilidades generales
└── App.js          # Componente principal
```

---

## ⚙️ Instalación

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/ecommerce-front.git
   cd ecommerce-front
   ```

2. Instalá las dependencias:
   ```bash
   npm install
   # o
   yarn install
   ```

3. Configurá tus variables de entorno (`.env`):

4. Ejecutá el proyecto en modo desarrollo:
   ```bash
   npm start
   ```

---

## 📌 Features principales

- Página de inicio dinámica con productos destacados.
- Carrito de compras con Redux.
- Checkout con validaciones.
- Formulario de login y registro con validaciones personalizadas.
- Diseño responsive y accesible con AntD y styled-components.
- Integración lista para conectarse a una API REST de eCommerce.

--- 

## 🛠️ Personalización

- Cambiá el tema de AntD en `styles/theme.js`.
- Configurá rutas o navegación desde `routes/`.
- Añadí endpoints o lógica de negocio en `services/`.

