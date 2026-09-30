# Agenda de Contactos Web 📇

Aplicación web desarrollada con **HTML5**, **CSS3** y **JavaScript (ES6+)** para consultar y agregar contactos en un servicio de agenda remoto. Presenta una interfaz de estilo editorial con tipografía refinada, diseño adaptativo y retroalimentación visual inmediata mediante *skeleton loaders*.

---

## 🎨 Características

- **Consumo de API REST**:
  - `GET`: Obtiene y lista de forma asíncrona todos los contactos guardados en el servidor[cite: 3].
  - `POST`: Envía nuevos registros (`nombre`, `apellido`, `telefono`) en formato JSON[cite: 3].
- **Skeleton Screen**: Pantalla de carga animada que mejora la experiencia de usuario mientras se obtienen los datos[cite: 3].
- **Manejo de Estados**:
  - Deshabilitación temporal de botones durante peticiones en curso[cite: 3].
  - Mensajes dinámicos de éxito y error según el estado HTTP de la respuesta[cite: 3].
  - Contador dinámico de registros[cite: 3].
- **Diseño Adaptativo y Accesible**:
  - Layout construido con CSS Grid y Flexbox que se ajusta a móviles[cite: 3].
  - Soporte para preferencias del sistema como `prefers-reduced-motion`[cite: 3].

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Formulario estructurado con tipos de campo nativos (`tel`, `text`)[cite: 3].
- **CSS3**: Layout fluido, variables CSS, animaciones `@keyframes` y diseño responsivo[cite: 3].
- **JavaScript (ES6+)**: Promesas, `async/await`, Fetch API y manipulación dinámica del DOM[cite: 3].

---

## 🌐 API Integrada

El proyecto consume la siguiente API pública de prueba:
- **Endpoint**: `http://www.raydelto.org/agenda.php`[cite: 3]

---

## 📁 Estructura del Proyecto

```text
.
└── index.html     # Estructura, estilos y lógica de integración con la API
```
