# 🌐 Sitio Web de Repuestos Vehiculares

Proyecto web con HTML, CSS y JavaScript que presenta una página de inicio, una sección de productos y un formulario de contacto.

---

## 🧱 Estructura del sitio
- **index.html:** Página principal del sitio.
- **productos.html:** Lista de productos disponibles.
- **contacto.html:** Formulario de contacto.
- **css/estilos.css:** Estilos personalizados.
- **js/script.js:** Lógica funcional con JavaScript.

---

## 🚀 Publicación
El sitio está desplegado en **GitHub Pages**:  
👉 [https://tuusuario.github.io/sitio-vehiculos/](https://kendry05.github.io/gitpage/)

---

## ⚙️ Automatización con GitHub Actions
Se usa un flujo de trabajo (`deploy.yml`) que publica automáticamente el sitio cada vez que se hace un *push* a la rama `main`.

---

## 🌿 Ramas del proyecto
- **main:** versión estable y publicada.
- **desarrollo:** rama donde se trabaja antes de integrar a `main`.

---

## 🧠 Uso de Issues
Los *issues* se utilizan para planificar tareas, registrar errores o proponer mejoras.  
Ejemplo de issue en Markdown:

```markdown
# 🐞 Error: no carga el formulario de contacto

## Descripción
El formulario no envía los datos correctamente.

### Pasos para reproducir
1. Abrir `contacto.html`.
2. Llenar los campos y presionar “Enviar”.

### Resultado esperado
Mostrar mensaje “Formulario enviado correctamente”.

### Resultado actual
No ocurre ninguna acción.

### Etiquetas
`bug`, `frontend`
