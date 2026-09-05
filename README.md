# Lucy Fast Food

## Descripción
Lucy Fast Food es un sistema web académico que cumple dos funciones principales:

1. **Publicidad**: mostrar al público los productos disponibles en la tienda de comida rápida mediante un catálogo digital.
2. **Gestión interna**: permitir que el personal autorizado, mediante autenticación en el login, registre nuevos productos y ventas.

---

## Funcionalidades
- **Acceso público**:
  - Visualización del listado de productos.
  - Catálogo digital con estilo llamativo y menú en cascada.

- **Acceso restringido (login)**:
  - Registro de productos.
  - Registro de ventas.
  - Consulta de historial de ventas.

---

## Estructura del proyecto
- `index.html` → Página principal.
- `login.html` → Formulario de autenticación con fondo temático.
- `dashboard.html` → Panel de control para personal autorizado.
- `productos.html` → Listado de productos (visible a todos).
- `form-producto.html` → Registro de productos (solo personal logueado).
- `ventas.html` → Listado de ventas (solo personal logueado).
- `form-venta.html` → Registro de ventas.
- `css/style.css` → Estilos globales con colores llamativos.
- `img/fastfood-bg.jpg` → Imagen de fondo para login.

---

## Control de acceso
- **Usuarios no autenticados** → solo pueden ver productos.
- **Usuarios autenticados** → acceden a las secciones de registro y ventas.

---

## Tecnologías utilizadas
- **HTML5** para la estructura.
- **CSS3** para estilos y diseño responsivo básico.
- **Git/GitHub** para control de versiones y flujo profesional con ramas (`feature/ECC`, `develop`, `master`).

---

## Flujo de trabajo en Git
1. Desarrollo en la rama `feature/ECC`.
2. Integración mediante Pull Requests hacia `develop` y `master`.

---

## Futuras mejoras
- Conectar productos y ventas a una base de datos.
- Ampliar el catálogo con imágenes dinámicas.

---

2026 Lucy Fast Food - Proyecto académico
