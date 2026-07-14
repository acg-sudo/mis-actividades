# Desafío: Ergonomía y Cuidado del PC 🧑‍💻🔋

Este proyecto es una aplicación web interactiva y gamificada diseñada para que los estudiantes del **Taller de Informática de la EPA Sedaví** consoliden sus conocimientos sobre salud digital, prevención de riesgos posturales y mantenimiento preventivo del hardware de una forma lúdica y práctica. El simulador los reta a resolver diferentes situaciones cotidianas de forma segura.

## 🕹️ Dinámica del Juego y Actividades

El simulador plantea una experiencia ágil y directa basada en la toma de decisiones rápidas mediante tarjetas interactivas:

1. **📋 Rondas de 8 Retos al Azar:** En cada partida, el sistema selecciona **8 preguntas aleatorias** de un banco completo de 35 casos reales divididos en temáticas clave:
   * **Cuidado del Hardware:** Escenarios sobre la prevención de cortocircuitos por líquidos, acumulación de polvo en la torre, gestión de baterías de portátiles, apagado seguro del equipo, uso correcto de pendrives y picos de tensión por tormentas.
   * **Ergonomía y Salud:** Casos prácticos enfocados en la postura recomendada (soporte lumbar, altura de la pantalla, uso de periféricos externos), regulación de la iluminación ambiental para evitar reflejos, distancia ocular saludable y la regla de descansos visuales.
2. **🎯 Sistema de Selección e Interacción:** El alumno interactúa con botones de diseño limpio para elegir la opción que considere correcta de forma visual e intuitiva. Al pulsar en "Corregir Desafío", el simulador evalúa las respuestas mostrando el *feedback* explicativo de cada caso.

---

## 🚀 Características Didácticas

* **Algoritmo de Mezcla Fisher-Yates:** Para asegurar que las clases sean dinámicas y los alumnos no memoricen el orden de las respuestas, se implementa una mezcla matemática aleatoria tanto en la elección de las 8 tarjetas de la ronda como en el orden interno de sus opciones de respuesta.
* **Feedback Educativo Instantáneo:** Al corregir, cada tarjeta se ilumina en verde (correcto) o rojo (incorrecto) y despliega una explicación concisa (*feedback*) que refuerza el porqué de esa norma de cuidado o postura ergonómica.
* **Modo Pizarra / Maestro (🔑):** En el pie de página se incluye un acceso oculto a través del emoji de la llave o usando el atajo de teclado **`Alt + D`**. Esto activa el "Modo Profesor", que preselecciona automáticamente las opciones correctas en la pantalla, facilitando las explicaciones conjuntas y los debates en el aula.
* **Efectos Visuales Gratificantes:** Completar una ronda con un 100% de aciertos premia al alumno con un mensaje de éxito y una lluvia de confeti animado mediante la librería `canvas-confetti`.

---

## 🛠️ Tecnologías y Estructura

* **Formato Single-File (Todo en uno):** El juego está desarrollado en un único archivo autónomo (`index.html`), lo que simplifica su distribución, permitiendo abrirlo en cualquier ordenador o tableta sin necesidad de internet (salvo para la carga estética de fuentes y el confeti) ni de instalaciones complejas.
* **Diseño Limpio y Accesible:** La interfaz presenta tipografías claras, iconos vectoriales representativos en cada tarjeta y botones grandes de fácil pulsación, pensados especialmente para una navegación cómoda para el perfil de estudiantes senior.

---
*Diseñado con ♥ por el **Profe Adna** para hacer de la informática un concepto accesible, útil y divertido para todos.*