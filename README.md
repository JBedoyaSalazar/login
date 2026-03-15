# 🔐 Sistema de Autenticación con Firebase – React + Vite

![Vite](https://img.shields.io/badge/Vite-Frontend_Tool-646CFF?logo=vite\&logoColor=white)
![React](https://img.shields.io/badge/React-UI_Library-61DAFB?logo=react\&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-Authentication-FFCA28?logo=firebase\&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript\&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success)

Aplicación web desarrollada con **React** utilizando **Vite** como entorno de desarrollo que implementa un sistema completo de **autenticación de usuarios con Firebase Authentication**.

El proyecto demuestra cómo integrar un frontend moderno con servicios en la nube para gestionar **registro, inicio de sesión, control de sesión y cierre de sesión de usuarios**, aplicando buenas prácticas de organización de componentes y manejo de estados.

Además, se implementa navegación entre vistas mediante **React Router**, permitiendo un flujo de autenticación funcional dentro de la aplicación.

---

# 🌐 Demo del Proyecto

Puedes probar la aplicación desplegada aquí:

**🔗 Demo:**
[[AQUÍ VA EL LINK DEL DEPLOY EN NETLIFY]](https://loginfirebaseprueba.netlify.app/)

---

# 📌 Características

* Registro de usuarios con **email y contraseña**
* Inicio de sesión autenticado con Firebase
* Manejo de errores durante autenticación
* Cierre de sesión seguro
* Navegación entre páginas usando **React Router**
* Componentes reutilizables
* Arquitectura modular
* Interfaz simple enfocada en el flujo de autenticación

---

# 🧠 Aprendizajes Obtenidos

Durante el desarrollo del proyecto se implementaron conceptos importantes para la construcción de aplicaciones web modernas.

Entre los principales aprendizajes se encuentran:

* Integración de **Firebase Authentication** dentro de una aplicación React.
* Conexión entre el frontend y una **API externa (Firebase)**.
* Implementación completa del flujo de autenticación:

  * Registro de usuario
  * Inicio de sesión
  * Persistencia de sesión
  * Cierre de sesión
* Manejo de **promesas y operaciones asincrónicas**.
* Gestión del estado de autenticación dentro de la interfaz.
* Creación de **componentes reutilizables en React**.
* Uso de **React Router** para navegación entre vistas.
* Organización de un proyecto React en módulos escalables.

Este proyecto sirve como base para desarrollar aplicaciones más complejas que requieran **sistemas de autenticación seguros y escalables**.

---

# 🛠️ Tecnologías Utilizadas

* **Vite** — entorno de desarrollo moderno y rápido
* **React** — biblioteca para interfaces de usuario
* **React Router DOM** — navegación entre páginas
* **Firebase Authentication** — autenticación de usuarios
* **JavaScript (ES6+)**
* **CSS Modules** — encapsulamiento de estilos
* **Node.js** — entorno para gestión de dependencias
* **npm** — gestor de paquetes



# 🧩 Arquitectura del Proyecto

El proyecto sigue una estructura modular para mantener separación de responsabilidades y facilitar la escalabilidad.


src
│
├── components
│   └── InputControl
│       ├── InputControl.jsx
│       └── InputControl.module.css
│
├── pages
│   ├── Home
│   │   ├── Home.jsx
│   │   └── Home.module.css
│   │
│   ├── Login
│   │   ├── Login.jsx
│   │   └── Login.module.css
│   │
│   └── Signup
│       ├── Signup.jsx
│       └── Signup.module.css
│
├── firebase.js
├── App.jsx
└── main.jsx


Esta organización permite:

* Separar **componentes reutilizables**
* Mantener **vistas independientes**
* Facilitar mantenimiento y escalabilidad del código



# ⚙️ Instalación del Proyecto

### 1️⃣ Clonar el repositorio

bash
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git


### 2️⃣ Entrar a la carpeta del proyecto

bash
cd TU-REPOSITORIO


### 3️⃣ Instalar dependencias

bash
npm install


### 4️⃣ Ejecutar el entorno de desarrollo

bash
npm run dev


La aplicación se ejecutará en:


http://localhost:5173



# 🔑 Configuración de Firebase

Para ejecutar el proyecto correctamente es necesario crear un proyecto en **Firebase** y configurar las credenciales en el archivo:


firebase.js


Ejemplo de estructura:

javascript
import { initializeApp } from "firebase/app"

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
}

export const app = initializeApp(firebaseConfig)


Las credenciales se obtienen desde el **panel de Firebase Console**.

---

# 🚀 Despliegue

El proyecto puede desplegarse fácilmente en plataformas modernas de hosting como:

* **Netlify**
* **Vercel**
* **Firebase Hosting**

Este proyecto está desplegado en:

**🔗 https://loginfirebaseprueba.netlify.app/ **

---

# 📚 Posibles Mejoras Futuras

El proyecto puede evolucionar incorporando nuevas funcionalidades:

* Protección de rutas privadas
* Persistencia de sesión automática
* Recuperación de contraseña
* Autenticación con Google
* Manejo global de estado con Context API
* Mejora de UI/UX

---

# 👨‍💻 Autor

Proyecto desarrollado con fines educativos para comprender el funcionamiento de **sistemas de autenticación en aplicaciones web modernas** utilizando React y Firebase.

---

# 📄 Licencia

Este proyecto es de uso educativo y puede ser utilizado como referencia para implementar **sistemas de autenticación en aplicaciones React**.
