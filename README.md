# Cookie Clicker Moderno 🍪✨

Una versión moderna, elegante y estilizada del clásico juego estilo **Cookie Clicker**, diseñada con una interfaz oscura con efecto *glassmorphism*, animaciones fluidas y efectos visuales y sonoros interactivos.

---

## 🌟 Características Principales

- **Diseño Moderno & Glassmorphism**: Interfaz con estilo traslúcido, resplandores de fondo animados y tipografía limpia (`Outfit`).
- **Galleta SVG Interactiva**: Gráfico vectorial estilizado con pepitas de chocolate, sombras dinámicas y animación de pulsación (*feedback hápico/visual*).
- **Contador Dinámico**: Muestra en tiempo real el número de galletas y la producción por segundo (CPS).
- **Efectos Flotantes (Partículas)**: Cada vez que haces clic en la galleta, se generan números flotantes animados con la cantidad cosechada (+1, +2, etc.).
- **Síntesis de Audio (Web Audio API)**: Efecto de sonido sintetizado al hacer clic sin necesidad de archivos externos MP3/WAV.
- **Tienda de Mejoras**:
  - **Super Clic ⚡**: Aumenta la cantidad de galletas obtenidas por cada clic.
  - **Cursor Automático 🤖**: Genera 1 galleta por segundo automáticamente.
  - **Abuela Repostera 👵**: Genera 8 galletas por segundo.
  - **Fábrica Neon 🏭**: Genera 40 galletas por segundo.
- **Persistencia de Datos**: Tu progreso se guarda automáticamente en el almacenamiento local de tu navegador (`localStorage`).
- **Controles de Audio y Reinicio**: Puedes silenciar los sonidos o reiniciar tu partida en cualquier momento.

---

## 🚀 Cómo Ejecutar la Aplicación

No requiere instalaciones complejas ni servidores de compilación (como Node.js o React). Es una aplicación web pura (**HTML5 + CSS3 + JavaScript JS ES6**).

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` directamente en tu navegador web preferido (Chrome, Firefox, Safari, Edge, etc.).

O bien, si usas un servidor local como `Live Server` en VS Code, simplemente inicia el servidor apuntando al archivo `index.html`.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y SVG inline interactivo.
- **CSS3**: Variables CSS, Flexbox, CSS Grid, Glassmorphism (`backdrop-filter`), animaciones `@keyframes`.
- **JavaScript (Vanilla ES6+)**:
  - Manipulación del DOM y lógica de juego.
  - **Web Audio API** para la generación de sonido interactivo.
  - **LocalStorage API** para la persistencia del estado de juego.

---

## 🎮 Instrucciones de Juego

1. **Haz clic en la galleta gigante** central para conseguir tus primeras galletas.
2. Reúne suficiente galletas para comprar **Mejoras** en el panel lateral/inferior.
3. Las mejoras aumentan tus clics manuales o producen galletas de forma automática cada segundo (CPS).
4. ¡Diviértete desbloqueando todas las mejoras!
