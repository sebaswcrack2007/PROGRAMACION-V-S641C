# StudentFlow · Frontend 🚀

Interfaz de usuario web para **StudentFlow**, un sistema de gestión académica diseñado para optimizar el control de materias, tareas y recordatorios de los estudiantes.

Este módulo cliente está construido con **HTML5, CSS3 y JavaScript Vanilla**, implementando una arquitectura modular basada en componentes de vistas y un cliente HTTP personalizado (`apiFetch`) para sincronizarse fluidamente con el backend de la aplicación.

---

## 🛠️ Tecnologías y Herramientas

* **HTML5 / CSS3:** Estructura semántica y diseño responsivo adaptado a paneles de control modernos.
* **JavaScript (ES6 Modules):** Lógica del cliente, manipulación del DOM y consumo asíncrono de APIs (`async/await`).
* **Arquitectura Cliente-Servidor:** Comunicación mediante peticiones HTTP RESTful conectadas al backend en Node.js/Express.

---

## 📂 Estructura del Proyecto

```text
studentFlow_front/
├── public/
│   ├── css/
│   │   ├── styles.css             # Estilos globales y variables
│   │   └── llamados-completos.css # Estilos específicos para vistas de datos
│   ├── js/
│   │   ├── api/
│   │   │   ├── http.js            # Cliente HTTP centralizado (apiFetch)
│   │   │   └── materias.js        # Endpoints de materias (cliente)
│   │   ├── config.js              # Configuración global (URLs base y tiempos)
│   │   └── llamadosCompletos/     # Scripts lógicos por entidad (listar, crear, etc.)
│   ├── llamadoCompleto/           # Vistas HTML (listar, crear, actualizar materias/recordatorios)
│   └── index.html                 # Página de bienvenida / redirección
└── package.json
