# Desafío: Conceptos Informáticos (Rondas al Azar) 🖥️🧠⚡

Este proyecto es una aplicación web interactiva diseñada para repasar, consolidar y autoevaluar conceptos teóricos fundamentales del mundo del hardware, el software y las unidades de medida digital. Ha sido desarrollado especialmente para los alumnos del **Taller de Informática de la EPA Sedaví**.

## 🕹️ Dinámica del Juego

El juego plantea un sistema de correspondencia de definiciones dinámico y cambiante en cada partida:

1. **Selección del Concepto:** El alumno hace clic sobre uno de los conceptos del banco superior de opciones (las etiquetas dinámicas).
2. **Asignación a la Tarjeta:** El alumno hace clic en la tarjeta de definición correspondiente al concepto que ha seleccionado para vincularlos.
3. **Liberación y Corrección:** Si el alumno se equivoca antes de validar, puede volver a hacer clic en la tarjeta asignada para liberar el término y devolverlo al banco de opciones. Al finalizar las asignaciones, el botón **"Corregir Desafío"** evalúa el rendimiento del estudiante en tiempo real.
4. **Rondas Aleatorias Infinitas:** Con el botón **"Siguiente Ronda (Azar)"**, el juego baraja la base de datos de preguntas y extrae un conjunto de 8 desafíos completamente distintos para que cada partida sea única.

## 🚀 Características Didácticas

* **Banco de Preguntas Extenso y Variado:** Cuenta con una base de datos de más de 50 preguntas que abarcan desde el hardware físico (CPU, RAM, GPU, buses) hasta unidades de almacenamiento (Bit, Byte, MB, GB, TB) y la lógica binaria.
* **Uso de Iconografía Vectorial Estable:** Las tarjetas utilizan la librería de iconos FontAwesome en lugar de imágenes pesadas, lo que garantiza tiempos de carga ultrarrápidos y total estabilidad visual sin riesgo de enlaces caídos.
* **Control Visual de Respuestas (Feedback Dinámico):** Al corregir, las tarjetas correctas se iluminan en verde y las incorrectas en rojo, mostrando además de forma transparente cuál era la respuesta correcta para facilitar el autoaprendizaje.
* **Lluvia de Confeti de Celebración:** Al lograr un pleno de 8/8 aciertos en una ronda, el sistema premia visualmente el esfuerzo con una animación dinámica de confeti sobre el lienzo.
* **Modo Profesor / Llave Maestra:** Al pulsar sobre el discreto icono de la llave (`🔑`) en el pie de página o usar el atajo de teclado (`Alt + D`), se activa un botón de resolución automática para facilitar correcciones grupales rápidas en la pizarra digital de clase.

## 🛠️ Tecnologías y Estructura

* **Estructura y Animaciones:** HTML5 semántico y CSS3 con variables nativas para un diseño limpio, moderno, completamente adaptable a dispositivos móviles (*responsive design*) y apto para ser incrustado en Blogger.
* **Lógica:** JavaScript Nativo (Vanilla JS) sin dependencias externas complejas, utilizando únicamente la librería ligera `canvas-confetti` para las celebraciones.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*