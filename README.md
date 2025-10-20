# RDSLP - Red Social de Lenguajes de Programación y Lógica de Programación

Una plataforma web educativa diseñada para enseñar lógica de programación y lenguajes de programación.

## 📁 Estructura del Proyecto

```
rdslp-simple/
├── index.html              # Página principal
├── css/
│   └── styles.css          # Estilos globales
├── js/
│   └── main.js             # Funcionalidad JavaScript
├── pages/
│   ├── tipos-lenguajes.html    # Tipos de lenguajes de programación
│   ├── lenguajes.html          # Lenguajes populares
│   └── logica.html             # Lógica de programación
└── README.md               # Este archivo
```

## 🚀 Cómo Desplegar

### Opción 1: Servidor Local Simple (Python)

Si tienes Python instalado:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Luego abre en tu navegador: `http://localhost:8000`

### Opción 2: Servidor Local Simple (Node.js)

Si tienes Node.js instalado:

```bash
npx http-server
```

### Opción 3: Servidor Local Simple (PHP)

Si tienes PHP instalado:

```bash
php -S localhost:8000
```

### Opción 4: Desplegar en Hosting

1. **Hosting Gratuito (Netlify, GitHub Pages, Vercel)**
   - Sube los archivos a un repositorio de GitHub
   - Conecta el repositorio con Netlify o Vercel
   - Automáticamente se desplegará

2. **Hosting Compartido**
   - Descarga los archivos
   - Sube mediante FTP a tu servidor web
   - Accede a través de tu dominio

3. **Servidor Propio**
   - Copia los archivos a `/var/www/html` (Apache) o similar
   - Reinicia el servidor web
   - Accede a través de tu IP o dominio

## 📄 Archivos Principales

### index.html
Página principal con:
- Presentación del proyecto RDSLP
- Características principales
- Información del equipo
- Detalles académicos
- Navegación a otras páginas

### pages/tipos-lenguajes.html
Información sobre:
- Lenguajes compilados, interpretados e híbridos
- Paradigmas de programación
- Tabla comparativa de lenguajes

### pages/lenguajes.html
Detalles de 8 lenguajes populares:
- Python
- JavaScript
- Java
- C++
- C#
- Go
- Rust
- TypeScript

### pages/logica.html
Conceptos fundamentales:
- Variables y tipos de datos
- Estructuras de control
- Bucles e iteración
- Funciones
- Arrays/Listas
- Objetos y estructuras
- Algoritmos comunes
- Buenas prácticas

## 🎨 Características de Diseño

- **Responsive**: Funciona en móviles, tablets y escritorio
- **Moderno**: Diseño limpio y profesional
- **Accesible**: Navegación intuitiva
- **Rápido**: Archivos HTML/CSS/JS puros sin dependencias
- **Fácil de mantener**: Código bien estructurado y comentado

## 🔧 Personalización

### Cambiar Colores

Edita `css/styles.css` y modifica las variables CSS:

```css
:root {
    --primary: #3d5afe;           /* Color principal */
    --primary-dark: #1e88e5;      /* Color principal oscuro */
    --accent: #ff6f00;            /* Color de acento */
    --text-dark: #1a1a1a;         /* Texto oscuro */
    --text-light: #666;           /* Texto claro */
    --bg-light: #f5f5f5;          /* Fondo claro */
    --bg-white: #ffffff;          /* Fondo blanco */
}
```

### Cambiar Contenido

Edita los archivos HTML directamente:
- `index.html` para la página principal
- `pages/*.html` para las páginas educativas

### Agregar Nuevas Páginas

1. Crea un nuevo archivo en `pages/nombre.html`
2. Copia la estructura de cualquier página existente
3. Modifica el contenido
4. Agrega un enlace en la navegación del `index.html`

## 📱 Compatibilidad

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Navegadores móviles

## 📋 Requisitos

- Ninguno para usar
- Navegador web moderno
- Servidor web (para desplegar)

## 🎓 Contenido Educativo

El sitio incluye:
- Clasificación de lenguajes de programación
- Paradigmas de programación
- 8 lenguajes populares con ejemplos
- Conceptos fundamentales de lógica
- Algoritmos comunes
- Buenas prácticas de programación

## 👤 Información del Proyecto

- **Nombre**: RDSLP (Red Social de Lenguajes de Programación y Lógica de Programación)
- **Desarrollador Principal**: Ricardo Jaraba Gallego
- **Asignatura**: Lenguajes de Programación y POO
- **Modalidad**: Prototipo
- **Año**: 2025

## 📝 Licencia

Este proyecto es educativo y está disponible para uso libre.

## 🤝 Contribuciones

Para mejorar el contenido educativo, puedes:
- Agregar más lenguajes de programación
- Incluir ejemplos de código
- Expandir los conceptos de lógica
- Mejorar el diseño visual

## 📞 Contacto

Ricardo Jaraba Gallego
Desarrollador Principal del Proyecto RDSLP

---

**Última actualización**: Octubre 2025

