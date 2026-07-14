# Desafío: Detective Técnico del PC 🕵️‍♂️🖥️🚨

Este proyecto es una aplicación web interactiva y gamificada que simula un entorno de soporte técnico real. Su objetivo es entrenar el pensamiento lógico y la capacidad de diagnóstico de los estudiantes del **Taller de Informática de la EPA Sedaví** mediante la resolución de problemas informáticos del día a día.

## 🕹️ Dinámica del Juego

El simulador reta al alumno a actuar como un verdadero técnico de soporte:

1. **Lectura del Caso:** Cada tarjeta presenta un síntoma o problema real que experimenta un usuario (por ejemplo, sonidos metálicos extraños, reinicios por temperatura o bloqueos al abrir pestañas).
2. **Diagnóstico:** El alumno debe analizar la situación y seleccionar una de las píldoras de respuesta con el diagnóstico o solución adecuada.
3. **Mecánica de Selección Intuitiva:** Al pulsar una píldora de opción, esta se marca como activa. Es posible cambiar de opinión pulsando otra opción o deseleccionarla haciendo clic de nuevo sobre ella para dejar el caso en blanco.
4. **Casos Dinámicos al Azar:** Al presionar **"Siguiente Ronda (Azar)"**, el sistema selecciona de manera aleatoria un conjunto de 8 casos únicos extraídos de una robusta base de datos con 40 problemas de diagnóstico.

## 🚀 Características Didácticas

* **Amplio Banco de Casos (40 Problemas Reales):** Los retos están divididos en dos grandes categorías conceptuales:
  * **Casos de Diagnóstico (🔍):** Enfocados en identificar el componente averiado o la causa del fallo a partir de descripciones cotidianas de los usuarios.
  * **Casos de Inspector (🚨):** Retos lógicos donde se analizan síntomas complejos de hardware, configuraciones del sistema operativo y situaciones de emergencia.
* **Feedback Formativo Detallado:** Al corregir, las tarjetas se iluminan en verde (acierto) o rojo (error). En caso de acierto, se despliega una explicación técnica explicativa (*feedback*) que consolida el porqué de la solución.
* **Gamificación Integrada:** Lograr una ronda perfecta (8/8 aciertos) recompensa al estudiante con una celebración animada de confeti dinámico en pantalla.
* **Modo Pizarra (Secretos del Profesor):** Diseñado para facilitar explicaciones colectivas en clase. Pulsando el botón secreto de la llave `🔑` en el pie de página, o mediante el atajo de teclado `Alt + D`, se activará el "Modo Profe" que resuelve automáticamente la ronda activa.

## 🛠️ Tecnologías y Estructura

* **Maquetación y Estilos:** HTML5 semántico y CSS3 con diseño responsivo, adaptado con botones grandes y espaciados optimizados para evitar la fatiga visual de los alumnos.
* **Animaciones de Transición:** Efectos sutiles de desplazamiento e iluminación al interactuar con las tarjetas y las opciones.
* **Lógica:** JavaScript Nativo (Vanilla JS) y uso de la biblioteca ligera `canvas-confetti` para las celebraciones.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*