<div align="center">

  # 🧮 GEOMETRY MATH

  ![Badge Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=for-the-badge)
  ![Badge Tecnologia](https://img.shields.io/badge/Tecnología-HTML5%20%7C%20CSS3%20%7C%20JS-007ACC?style=for-the-badge)
  ![Badge Genero](https://img.shields.io/badge/Género-Arcade%20%2F%20Runner%20%2F%20Puzzle-ff2fd0?style=for-the-badge)

  *Un runner de plataformas veloz donde las matemáticas son tu única vía de escape.*

</div>

---

## 📖 Descripción General

* **¿De qué trata?:** **Geometry Math** combina la dinámica frenética de los juegos de plataformas retro con el cálculo mental en tiempo real. El jugador controla a un cubo que avanza sin detenerse a través de un escenario neón mientras enfrenta operaciones matemáticas continuas.
* **Objetivo del jugador:** Resolver **10 operaciones matemáticas consecutivas** (sumas, restas, multiplicaciones y divisiones) sin cometer ningún error ni agotar la barra de tiempo.
* **Mecánica principal:** El personaje oscila constantemente entre 4 carriles verticales. El jugador debe calcular la respuesta matemática en pantalla y presionar la acción de salto en el instante exacto en que el cubo esté alineado con el bloque que contiene la respuesta correcta.

---

## 🎮 Género y Estilo

* **Géneros:** Arcade / Runner / Puzzle Educativo
* **Estilo Visual:** Neón Cyberpunk / Retro 2D con animaciones dinámicas en CSS3.

---

## ⌨️ Controles

| Acción | Teclado | Ratón / Pantalla Táctil |
| :--- | :--- | :--- |
| **Fijar respuesta / Saltar** | `ESPACIO` o `FLECHA ARRIBA` | Clic en la pantalla / Clic en el botón **⬆ SALTAR** |

---

## 🖼️ Capturas de Pantalla

| Vistas del Videojuego |
| :--- |
| **1. Pantalla Inicial**<br>![Pantalla Inicial](img/inicioGM.png) |
| **2. Momento de Gameplay**<br>![Momento de Gameplay](img/gameplayGM.png) |
| **3. Mecánica Principal**<br>![Mecánica Principal](img/mecanicaGM.png) |
| **4. Pantalla de Victoria**<br>![Pantalla de Victoria](img/victoriaGM.png) |
| **5. Pantalla de Derrota**<br>![Pantalla de Derrota](img/derrotaGM.png) |

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **HTML5 Canvas & DOM:** Estructuración de pantallas y elementos de interfaz.
* **CSS3:** Estilizado neón con variables CSS, animaciones mediante `@keyframes` y diseño *responsive*.
* **JavaScript (Vanilla):** Bucle principal de ejecución (`requestAnimationFrame`), lógica del algoritmo de cálculo matemático aleatorio y control de colisiones por tiempo.

---

## 🤖 Elementos Desarrollados con Apoyo de IA

* **Diseño Conceptual y Estética (Gemini):**
  * Definición de la estructura general, temática y flujo de juego.
  * Generación de la paleta de colores y estilos CSS para lograr el acabado visual neón/cyberpunk.
* **Programación y Construcción de Código (Claude):**
  * Desarrollo integral de la arquitectura del juego en HTML5 y JavaScript.
  * Implementación del bucle principal (`gameLoop`), gestión del temporizador y algoritmo de generación de distractores matemáticos.

---

## 💡 Aprendizajes y Futuras Mejoras

* **Principales Aprendizajes:**
  * Sincronización del bucle del juego (`gameLoop`) mediante estampa de tiempo (`performance.now()`).
  * Manipulación de la interfaz sin el uso de librerías externas.
* **Mejoras planteadas para la versión 2.0:**
  * Implementación de efectos de sonido (SFX) para aciertos, errores y saltos.
  * Selector de dificultades (Fácil, Normal, Difícil) con menor margen de tiempo por nivel.
  * Guardado de récords de tiempo en `localStorage`.
