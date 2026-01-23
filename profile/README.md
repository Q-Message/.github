#  Q-Message: Quantum-Resistant Messaging Ecosystem

Bienvenido al ecosistema de **Q-Message**, un proyecto de mensajería instantánea diseñado para enfrentar los retos de seguridad de la era de la computación cuántica. Desarrollado íntegramente como **Trabajo de Fin de Grado (TFG)** para el Ciclo Superior de **Desarrollo de Aplicaciones Multiplataforma (DAM)**.

##  Visión del Proyecto
Q-Message no es solo un chat; es una implementación práctica de **Criptografía Post-Cuántica (PQC)** en entornos móviles. El objetivo principal es garantizar la privacidad de los usuarios incluso ante la futura amenaza de la computación cuántica, utilizando una arquitectura Full Stack robusta y escalable.

---

##  Arquitectura del Sistema

El ecosistema se divide en dos componentes principales que trabajan en armonía:

### 1. [Q-Message Server](https://github.com/Q-Message/q-message-server) (Backend)
El núcleo del sistema, encargado de la orquestación y la persistencia.
- **Stack:** Node.js, Express, Socket.io, PostgreSQL.
- **Funciones:** Gestión de usuarios, autenticación JWT, manejo de mensajes offline y comunicación bidireccional en tiempo real.

### 2. [Q-Message Android](https://github.com/Q-Message/q-message-android) (Frontend - *In Progress*)
Cliente móvil nativo para una experiencia de usuario fluida y segura.
- **Stack:** Java, Android SDK, Retrofit, Socket.io-client.
- **Funciones:** Cifrado en el dispositivo, gestión de contactos, notificaciones push y almacenamiento local seguro.

---

##  Pilares de Seguridad

* **Cifrado Post-Cuántico (PQC):** Implementación de algoritmos resistentes a ataques cuánticos para el intercambio de mensajes.
* **End-to-End Encryption (E2EE):** El servidor nunca tiene acceso al contenido en claro de los mensajes.
* **Autenticación Stateless:** Uso de JSON Web Tokens (JWT) para sesiones seguras y eficientes.
* **Protección de Infraestructura:** Seguridad activa mediante Rate Limiting, Helmet.js y validación estricta de esquemas de datos.

---

##  Tecnologías Principales

| Capa | Tecnologías |
| :--- | :--- |
| **Backend** | Node.js, Express, PostgreSQL |
| **Mobile** | Java (Android Nativo) |
| **Real-time** | Socket.io (WebSockets) |
| **DevOps** | Nginx, Docker, Git |

---

##  Autores
Este proyecto es el resultado del esfuerzo y aprendizaje durante el ciclo de **DAM**. 

- **Hugo Palencia** - *Full Stack Developer* - [LinkedIn](https://www.linkedin.com/in/hugo-palencia-buitrago-5208a6383/) | [GitHub Personal](https://github.com/hugopalencia)
- **Manuel Arrojo**
  
---

> Prototipo desarrollado en **Escuela CES (Madrid)**. El código está disponible bajo licencia MIT con fines educativos y de investigación.

