# Portafolio personal — Karen Jiménez

## 🎯 Objetivo del proyecto
Página web de presentación personal (perfil / currículum digital) desarrollada con
**Bootstrap 5**, aplicando HTML5 semántico, diseño responsive y personalización propia
mediante `style.css`. El sitio presenta mi perfil como docente del Colegio Genius
Americano y estudiante de Ingeniería en Sistemas de la Información y Ciencias de la
Computación en la Universidad Mariano Gálvez, sede Jutiapa.

## ▶️ Cómo ejecutar la página
1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` directamente en el navegador (doble clic), **o**
   sirve la carpeta con una extensión tipo *Live Server* en VS Code para recarga en vivo.
3. No requiere instalación de dependencias: Bootstrap 5, Bootstrap Icons y las
   fuentes de Google Fonts se cargan por CDN, con conexión a internet.

## 🧩 Componentes de Bootstrap utilizados
- **Navbar** responsive (`navbar-expand-lg`, `navbar-toggler`, `collapse`) con anclas a cada sección.
- **Grid system** (`container`, `row`, `col-*`) en todas las secciones.
- **Cards** para los tres proyectos destacados.
- **List Group** para la lista de habilidades.
- **Badges** (nivel de dominio) y **Rounded Pills** (categoría) dentro de cada habilidad.
- **Botones** (`btn`) personalizados con variantes propias (`btn-fuchsia`, `btn-outline-fuchsia`).

## 🎨 Elementos personalizados con CSS (`css/style.css`)
- Paleta de color propia en variables CSS (`:root`): fucsia/magenta (`--fuchsia`),
  violeta (`--violet`), tinta oscura (`--ink`) y acento dorado (`--gold`).
- Tipografía combinada: **Space Grotesk** (encabezados), **Work Sans** (cuerpo) y
  **JetBrains Mono** (detalles tipo "comentario de código").
- Sombras, radios de borde y espaciados propios (no se usa `!important` en ningún selector).
- Animaciones: transición al pasar el cursor sobre tarjetas y botones (`translateY`),
  y un anillo giratorio decorativo alrededor de la foto de perfil, deshabilitado
  automáticamente si el usuario tiene activado *reducir movimiento*.
- Estados de foco visibles (`:focus-visible`) para navegación accesible por teclado.

## 🧠 Decisiones de diseño
- **Doble identidad como hilo conductor**: el diseño combina un lenguaje "de aula"
  (tarjetas cálidas, tipografía redondeada) con un lenguaje "de código" (acentos en
  fucsia/violeta, tipografía monoespaciada en detalles), reflejando el perfil de
  docente + estudiante de ingeniería.
- **Accesibilidad básica**: etiquetas `aria-label` en el menú y en los íconos de
  redes sociales, texto alternativo en las imágenes, contraste cuidado entre texto
  y fondo, y foco de teclado visible.
- **Responsive verificado** en 320px, 768px y 1280px sin generar scroll horizontal
  (ver capturas en `/capturas`).

## 💻 Proyectos incluidos
- **TRIXIS** — compilador lingüístico bilingüe EN↔ES, React 18 + Vite.
- **AstroScript** — mini compilador con lenguaje de programación propio, temática espacial.
- **Battleship** — implementación del clásico juego Hundir la flota.

## 📸 Capturas responsive
Disponibles en la carpeta `/capturas`:
- `captura320px.png`
- `captura768px.png`
- `captura1280px.png`