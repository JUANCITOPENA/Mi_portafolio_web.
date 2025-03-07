# Curso: Crea tu primera web con ayuda de IA Generativa (Gemini)

**Duración:** 4-6 semanas | **Nivel:** Principiante | **Formato:** Teórico-práctico

**Objetivos del curso:**
- ✔ Aprender los fundamentos de HTML, CSS y JavaScript.
- ✔ Utilizar Gemini para generar código y resolver problemas de desarrollo web.
- ✔ Crear una página web funcional con diseño responsivo.
- ✔ Implementar interactividad básica con JavaScript.
- ✔ Publicar la web en internet.

## Módulos del curso:

### Módulo 1: Introducción al desarrollo web y la IA Generativa

**¿Qué es el desarrollo web? (Front-end vs. Back-end)**
El desarrollo web es el proceso de crear sitios web para Internet. Se divide principalmente en dos partes:
- **Front-end (lado del cliente):** Se ocupa de la parte visual e interactiva de un sitio web, lo que ves y con lo que interactúas en tu navegador. Tecnologías principales: HTML, CSS y JavaScript.
- **Back-end (lado del servidor):** Se ocupa de la lógica del servidor, la base de datos y la gestión de la información. Tecnologías: Python, Java, PHP, Node.js, bases de datos, servidores, etc. (No cubierto en este curso).

**¿Cómo puede ayudar Gemini en el desarrollo web?**
Gemini puede ser tu copiloto en el desarrollo web:
- Generar código HTML, CSS y JavaScript automáticamente.
- Explicar conceptos y resolver dudas de programación.
- Sugerir ideas de diseño y funcionalidades.
- Ayudar a depurar código (encontrar errores).
- Acelerar el proceso de aprendizaje y desarrollo.

**Instalación de herramientas básicas (VS Code, navegador, Gemini)**
1. **VS Code (Editor de código):**
    - Descargar desde: [https://code.visualstudio.com/](https://code.visualstudio.com/)
    - Instalar según tu sistema operativo (Windows, macOS, Linux).
2. **Navegador web (Chrome, Firefox, etc.):**
    - Ya tienes uno instalado, ¡utiliza tu favorito! (Recomendamos Chrome o Firefox para desarrollo web).
3. **Gemini:**
    - Gemini es accesible a través de la web (Gemini Advanced o Google AI Studio) o APIs (más avanzado, no necesario para este curso inicial). Para este curso, usaremos la interfaz web de Gemini (puedes acceder a través de [https://gemini.google.com/app](https://gemini.google.com/app)).

**Configuración de un entorno de trabajo básico**
1. Crea una carpeta en tu ordenador llamada "mi-primera-web".
2. Abre VS Code.
3. Ve a "Archivo" > "Abrir carpeta..." y selecciona la carpeta "mi-primera-web".
4. Dentro de VS Code, crea un nuevo archivo llamado "index.html" (Clic derecho en el panel izquierdo > "Nuevo archivo").

**Ejercicio: Pedir a Gemini que explique los conceptos básicos de HTML, CSS y JavaScript.**
1. Abre Gemini en tu navegador ([https://gemini.google.com/app](https://gemini.google.com/app)).
2. Escribe en el chat: "Explícame los conceptos básicos de HTML, CSS y JavaScript para un principiante."
3. Lee las explicaciones de Gemini y toma notas. ¡Pregunta a Gemini si algo no queda claro!

### Módulo 2: Creando la estructura de la web con HTML

**¿Qué es HTML y cómo funciona?**
HTML (HyperText Markup Language) es el lenguaje de marcado que define la estructura básica de una página web.
- Se basa en "etiquetas" (tags) que indican el tipo de contenido (texto, imagen, enlace, etc.).
- El navegador lee el HTML y muestra la página web visualmente.
- Ejemplo básico de HTML:
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>Mi primera página web</title>
    </head>
    <body>
        <h1>¡Hola, mundo!</h1>
        <p>Este es mi primer párrafo.</p>
    </body>
    </html>
    ```

**Etiquetas básicas y estructura de una página web**
- `<!DOCTYPE html>`: Indica que es un documento HTML5.
- `<html>`: Etiqueta raíz del documento HTML.
- `<head>`: Contiene metadatos (información sobre la página), como el título.
    - `<title>`: Define el título que aparece en la pestaña del navegador.
- `<body>`: Contiene el contenido visible de la página web.
    - `<h1>` a `<h6>`: Encabezados de diferentes niveles (h1 es el más importante).
    - `<p>`: Párrafo de texto.
    - `<a>`: Enlace (hipervínculo).
    - `<img>`: Imagen.
    - `<div>`: Contenedor genérico para agrupar elementos.
    - `<span>`: Contenedor genérico en línea para agrupar texto.
    - `<form>`: Formulario para recoger datos del usuario.
    - `<input>`: Campo de entrada de formulario (texto, botón, etc.).
    - `<button>`: Botón.
    - `<ul>`, `<ol>`, `<li>`: Listas no ordenadas, listas ordenadas y elementos de lista.

**Generación automática de código HTML con Gemini**
1. Abre Gemini.
2. Escribe: "Genera el código HTML básico para una página web con un título, un encabezado principal, un párrafo de bienvenida y una imagen."
3. Copia el código HTML que genere Gemini.
4. Pégalo en tu archivo "index.html" en VS Code.
5. Guarda el archivo (Ctrl+S o Cmd+S).
6. Abre el archivo "index.html" en tu navegador (clic derecho en el archivo en VS Code > "Abrir con Live Server" si tienes la extensión instalada, o simplemente abre el archivo desde tu explorador de archivos).

**Enlaces, imágenes y formularios básicos**
- **Enlaces (`<a>`):**
    - `<a href="URL_DEL_ENLACE">Texto del enlace</a>`
    - Ejemplo: `<a href="https://www.google.com">Visita Google</a>`
- **Imágenes (`<img>`):**
    - `<img src="URL_DE_LA_IMAGEN" alt="Texto alternativo">`
    - Ejemplo: `<img src="imagen.jpg" alt="Mi imagen">` (La imagen debe estar en la misma carpeta que "index.html" o usar una URL web).
- **Formularios básicos (`<form>`, `<input>`, `<button>`):**
    ```html
    <form>
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre"><br><br>
        <button type="submit">Enviar</button>
    </form>
    ```

**Ejercicio: Usar Gemini para generar una plantilla HTML de una página personal y modificarla.**
1. Abre Gemini.
2. Escribe: "Genera una plantilla HTML para una página web personal que incluya una sección de 'Sobre mí', una sección de 'Proyectos' y una sección de 'Contacto'."
3. Copia el código HTML.
4. Pégalo en "index.html", reemplazando el contenido anterior.
5. Modifica el contenido (texto, imágenes, enlaces) para personalizar tu página personal.
6. Guarda y visualiza en el navegador.

### Módulo 3: Estilizando la web con CSS

**Conceptos básicos de CSS (colores, fuentes, márgenes, paddings)**
CSS (Cascading Style Sheets) se utiliza para dar estilo y apariencia visual a las páginas web.
- **Colores:** `color` (color del texto), `background-color` (color de fondo).
- **Fuentes:** `font-family` (tipo de letra), `font-size` (tamaño de letra), `font-weight` (grosor de letra).
- **Márgenes:** `margin` (espacio alrededor del elemento, fuera del borde).
- **Rellenos (Paddings):** `padding` (espacio dentro del elemento, entre el borde y el contenido).

**Selectores y clases**
- **Selectores:** Indican a qué elementos HTML se aplicarán los estilos CSS.
    - Selector de etiqueta: `p { ... }` (estilos para todos los párrafos `<p>`).
    - Selector de clase: `.clase { ... }` (estilos para elementos con `class="clase"`).
    - Selector de ID: `#id { ... }` (estilos para el elemento con `id="id"`).
- **Clases:** Atributos HTML que permiten agrupar elementos y aplicarles estilos CSS comunes.
    - `<p class="texto-destacado">Este párrafo es destacado.</p>`
    - En CSS: `.texto-destacado { font-weight: bold; color: blue; }`

**Diseño responsivo con CSS Grid y Flexbox**
- **Diseño responsivo:** La web se adapta a diferentes tamaños de pantalla (ordenador, móvil, tableta).
- **CSS Grid y Flexbox:** Sistemas de diseño CSS para crear layouts flexibles y responsivos. (Temas más avanzados, pero importantes para webs modernas).
    - **Flexbox:** Ideal para layouts unidimensionales (filas o columnas).
    - **CSS Grid:** Ideal para layouts bidimensionales (filas y columnas).
- Para principiantes, entender los conceptos básicos de CSS y cómo aplicarlos es el primer paso.

**Generación de estilos con Gemini**
1. Abre Gemini.
2. Escribe: "Sugiere estilos CSS para una página web personal que tenga un encabezado azul, párrafos con fuente Arial y enlaces de color verde."
3. Gemini puede generar código CSS.
4. Para aplicar los estilos, puedes:
    - **CSS en línea (no recomendado para proyectos grandes):**  `<p style="color: blue;">Texto azul</p>` (directamente en la etiqueta HTML).
    - **CSS interno (en la etiqueta `<style>` en `<head>`):**
        ```html
        <head>
            <style>
                h1 { color: blue; }
                p { font-family: Arial; }
                a { color: green; }
            </style>
        </head>
        ```
    - **CSS externo (archivo ".css" separado, recomendado para proyectos grandes):**
        1. Crea un nuevo archivo llamado "estilos.css" en la misma carpeta que "index.html".
        2. Pega el código CSS generado por Gemini en "estilos.css".
        3. Enlaza el archivo CSS a "index.html" en la sección `<head>`:
            ```html
            <head>
                <link rel="stylesheet" href="estilos.css">
            </head>
            ```

**Ejercicio: Pedir a Gemini sugerencias de estilos y aplicarlos a la web.**
1. Abre Gemini.
2. Escribe: "Dame ideas de estilos CSS para mejorar el diseño de una página web personal. Quiero que sea visualmente atractiva y fácil de leer."
3. Pide a Gemini que genere el código CSS para los estilos que te gusten.
4. Aplica los estilos a tu página web (usando CSS interno o externo).
5. Experimenta con diferentes estilos y colores.

### Módulo 4: Añadiendo interactividad con JavaScript

**Introducción a JavaScript**
JavaScript es un lenguaje de programación que permite añadir interactividad y dinamismo a las páginas web.
- Se ejecuta en el navegador del usuario (lado del cliente).
- Permite manipular el contenido de la página web, responder a acciones del usuario (clics, movimientos del ratón, etc.), y realizar tareas más complejas.

**Manipulación del DOM**
DOM (Document Object Model) es una representación estructurada de la página web como un árbol de objetos.
- JavaScript puede acceder y modificar el DOM para cambiar el contenido, estilos y estructura de la página web en tiempo real.
- Ejemplo: Cambiar el texto de un párrafo, ocultar un elemento, añadir un nuevo elemento.

**Eventos y funciones básicas**
- **Eventos:** Acciones que ocurren en la página web (clic de botón, carga de página, movimiento del ratón, etc.).
- **Funciones:** Bloques de código JavaScript que se ejecutan cuando ocurre un evento o cuando se les llama.
- Ejemplo:
    ```javascript
    function cambiarColor() {
        document.body.style.backgroundColor = 'yellow'; // Cambia el color de fondo del body a amarillo
    }
    ```

**Uso de Gemini para generar scripts interactivos**
1. Abre Gemini.
2. Escribe: "Genera código JavaScript para crear un botón que al hacer clic cambie el color de fondo de la página a verde."
3. Gemini generará el código JavaScript.
4. Para añadir JavaScript a tu página web, puedes:
    - **JavaScript en línea (no recomendado):** `<button onclick="alert('¡Hola!')">Haz clic</button>` (directamente en la etiqueta HTML).
    - **JavaScript interno (en la etiqueta `<script>` en `<body>` o `<head>`):**
        ```html
        <body>
            <button id="miBoton">Cambiar color</button>
            <script>
                document.getElementById('miBoton').addEventListener('click', function() {
                    document.body.style.backgroundColor = 'green';
                });
            </script>
        </body>
        ```
    - **JavaScript externo (archivo ".js" separado, recomendado):**
        1. Crea un nuevo archivo llamado "script.js" en la misma carpeta que "index.html".
        2. Pega el código JavaScript generado por Gemini en "script.js".
        3. Enlaza el archivo JavaScript a "index.html" antes de cerrar `</body>`:
            ```html
            <body>
                <button id="miBoton">Cambiar color</button>
                <script src="script.js"></script>
            </body>
            ```

**Ejercicio: Crear un botón que cambie el color del fondo usando código generado con Gemini.**
1. Abre Gemini.
2. Pide a Gemini que genere el código HTML para un botón y el código JavaScript para que al hacer clic en el botón, cambie el color de fondo a un color de tu elección.
3. Crea los archivos "index.html" y "script.js" si no los tienes.
4. Pega el código HTML del botón en el `<body>` de "index.html".
5. Pega el código JavaScript en "script.js" y enlaza "script.js" a "index.html".
6. Abre "index.html" en el navegador y prueba el botón.

### Módulo 5: Publicando la web

**Introducción a GitHub Pages, Vercel y Netlify**
Plataformas para publicar tu web en internet de forma gratuita (para proyectos sencillos como este curso):
- **GitHub Pages:** Directamente desde repositorios de GitHub. Ideal si usas Git y GitHub. [https://pages.github.com/](https://pages.github.com/)
- **Vercel:** Plataforma muy popular para Front-end. Fácil de usar y conectar con repositorios Git. [https://vercel.com/](https://vercel.com/)
- **Netlify:** Similar a Vercel, otra excelente opción para alojar webs estáticas y Front-end. [https://www.netlify.com/](https://www.netlify.com/)
- Para este curso, puedes elegir la plataforma que prefieras. GitHub Pages es una buena opción si ya tienes cuenta en GitHub. Vercel y Netlify son muy intuitivas para principiantes.

**Cómo subir archivos y hacer cambios (Ejemplo con GitHub Pages - los pasos son similares en Vercel y Netlify)**
1. **Crea una cuenta en GitHub** ([https://github.com/](https://github.com/)).
2. **Crea un nuevo repositorio** en GitHub (público o privado).
3. **Sube los archivos de tu web** ("index.html", "estilos.css", "script.js", imágenes, etc.) a tu repositorio de GitHub. Puedes hacerlo directamente desde la interfaz web de GitHub o usando Git desde la línea de comandos (más avanzado).
4. **Activa GitHub Pages** en la configuración de tu repositorio (Settings > Pages).
5. **Elige la rama** desde donde se publicará la web (normalmente "main" o "master").
6. **Espera unos minutos** a que GitHub Pages publique tu web.
7. **Visita la URL** que te proporciona GitHub Pages (normalmente `https://<tu-usuario-github>.github.io/<nombre-repositorio>/`).

**Últimos ajustes antes del lanzamiento**
- Revisa tu web en diferentes navegadores y dispositivos (si es posible) para asegurar que se ve bien.
- Corrige errores o detalles de diseño que quieras mejorar.
- ¡Asegúrate de que todos los enlaces e imágenes funcionan correctamente!

**Cómo seguir aprendiendo con Gemini**
- ¡Gemini puede seguir siendo tu tutor! Pregúntale dudas, pide ejemplos de código más avanzados, solicita ideas para mejorar tu web.
- Puedes pedirle a Gemini que te explique conceptos más avanzados de HTML, CSS y JavaScript, o incluso que te introduzca a frameworks como React, Vue o Angular (más allá del alcance de este curso inicial, pero son los siguientes pasos en el desarrollo Front-end).
- Explora la documentación oficial de HTML, CSS y JavaScript (puedes pedirle enlaces a Gemini).
- ¡Practica mucho! La mejor forma de aprender es creando proyectos propios.

**Ejercicio: Publicar la web y compartir el enlace con otros compañeros.**
1. Elige una plataforma (GitHub Pages, Vercel, Netlify).
2. Sigue los pasos para publicar tu web.
3. Comparte el enlace de tu web con tus compañeros y ¡celebra tu primera web creada con ayuda de IA!

## Proyecto Final: Tu primera web con ayuda de IA
- Crea una página web personal o sobre un tema que te guste, aplicando todo lo aprendido en el curso y utilizando Gemini como herramienta de apoyo.
- ¡Sé creativo! Añade diferentes secciones, estilos personalizados, interactividad con JavaScript.
- Publica tu proyecto final y compártelo.

## Certificado:
- Al completar el curso y el proyecto final, recibirás un certificado de finalización. (Este curso es un ejemplo, el certificado real dependerá de la plataforma donde se imparta el curso).

¡Felicidades por completar el curso "Crea tu primera web con ayuda de IA Generativa (Gemini)"! Esperamos que hayas dado tus primeros pasos en el emocionante mundo del desarrollo web. ¡Sigue practicando y aprendiendo!
