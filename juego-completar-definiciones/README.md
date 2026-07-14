# Desafío: Completar Definiciones 📝🧠⚡

Este proyecto es una aplicación web interactiva de tipo "completar textos" (fill-in-the-blank) diseñada para consolidar la terminología técnica fundamental de la informática. Ha sido desarrollado especialmente para los alumnos del **Taller de Informática de la EPA Sedaví**.

## 🕹️ Dinámica del Juego

El juego plantea un reto de asociación de conceptos y comprensión lectora estructurado de la siguiente manera:

1. **Lectura y Comprensión:** El alumno lee una definición técnica que tiene dos huecos en blanco (`[[1]]` y `[[2]]`).
2. **Selección de Píldoras:** Debajo de cada frase, se presentan grupos de botones tipo "píldora" con opciones posibles. Al pulsar una opción, esta se coloca automáticamente en el hueco correspondiente.
3. **Mecánica de Corrección y Acierto Parcial:** Al pulsar **"Corregir Ejercicio"**, el sistema evalúa las respuestas. Cuenta con un sistema avanzado de evaluación:
   * **Acierto total:** La tarjeta se ilumina en verde y muestra una explicación didáctica detallada (*feedback*).
   * **Acierto parcial:** Si solo una de las dos palabras es correcta, la tarjeta avisa al alumno de que va por buen camino pero que debe revisar una de sus opciones.
   * **Fallo absoluto:** Ilumina la tarjeta en rojo y anima al alumno a repasar el concepto técnico.
4. **Partidas Infinitas al Azar:** El juego baraja de forma aleatoria una base de datos con 50 combinaciones de conceptos diferentes, extrayendo únicamente 8 para cada ronda.

## 🚀 Características Didácticas

* **Gran Variedad Temática (50 Desafíos):** Las definiciones cubren áreas críticas del aprendizaje digital:
  * **Hardware Interno:** Placa base, sockets, procesadores, fuentes, disipadores y buses de datos.
  * **Periféricos y Cables:** Teclados, ratones, pantallas, HDMI y estándares USB.
  * **Software y Sistemas:** Sistemas operativos, aplicaciones, extensiones de archivo y controladores (drivers).
  * **Ciberseguridad e Internet:** Uso de contraseñas robustas, routers, virus y técnicas de phishing.
* **Diseño Limpio y Accesible:** Los textos cuentan con un tamaño de fuente adaptado y colores contrastados (paleta moderna basada en grises suaves e índigo) para evitar la fatiga visual de los alumnos.
* **Gamificación y Recompensa:** Los éxitos de ronda completa (8/8) son celebrados en pantalla mediante una animación dinámica de confeti.
* **Modo Pizarra Digital (Profesor):** Incorpora un atajo secreto de resolución automática (pulsando el icono de la llave `🔑` en el pie de página o mediante la combinación de teclas `Alt + D`) para facilitar explicaciones dinámicas frente a la clase.

## 🛠️ Tecnologías y Estructura

* **Estructura y Estilos:** HTML5 semántico y CSS3 moderno empleando variables nativas (*custom properties*) para una gestión limpia de estados (correcto, incorrecto, advertencia).
* **Lógica:** JavaScript Nativo (Vanilla JS) sin dependencias, diseñado con un algoritmo de generación de distractores aleatorios para asegurar que las opciones de las píldoras cambien en cada ronda.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*