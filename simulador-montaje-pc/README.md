# Simulador de Montaje de PC 🖥️🔧⚡

Este proyecto es un simulador web interactivo y guiado paso a paso para aprender a ensamblar los componentes internos y externos de un ordenador estándar de oficina. Ha sido diseñado especialmente para los alumnos del **Taller de Informática de la EPA Sedaví**.

## 🕹️ Fases del Simulador

El juego guía de forma secuencial al alumno a través de tres grandes etapas tecnológicas:

1. **Fase 1: Ensamblaje de la Placa Base:** Instalación ordenada del Procesador (CPU), aplicación de Pasta Térmica, colocación del Disipador, inserción de los módulos de Memoria RAM y montaje de la Tarjeta Gráfica.
2. **Fase 2: Integración en el Chasis (Torre):** Fijación de la placa madre armada en el gabinete, instalación del almacenamiento de estado sólido (Disco SSD), colocación de la Fuente de Alimentación y su posterior cableado energético estructural.
3. **Fase 3: Cableado del Escritorio y Periféricos:** Acomodación del Teclado y Ratón USB en la mesa de trabajo, conexión del cable de vídeo HDMI a la torre y acople del cable de corriente alterna a la toma eléctrica general.

## 🚀 Características Didácticas

* **Consola Interactiva Dinámica:** Un panel superior actúa como tutor en tiempo real, indicando la función de cada pieza colocada y guiando sobre cuál es el siguiente paso lógico.
* **Control de Errores Secuenciales:** Si un alumno intenta forzar una pieza fuera de su orden lógico o en una zona de colisión errónea, el sistema le notifica visualmente el fallo y le recuerda la secuencia técnica correcta.
* **Modo Desarrollador / Profesor:** Al pulsar el icono de la herramienta (`🔧`) en el pie de página, se activan de forma transparente las cajas y coordenadas de colisión (*hitboxes*) de los componentes sobre el lienzo, ideal para explicaciones en la pizarra digital.
* **Sección de Reflexión Profesional:** Al finalizar el hardware interno o el periférico, la interfaz expone lecturas didácticas que invitan al alumno a reflexionar sobre configuraciones avanzadas para entornos de trabajo técnicos (RAID, fibra óptica, edición 4K).

## 🛠️ Tecnologías y Estructura

* **Estructura:** HTML5 y lógica en JavaScript Nativo (Vanilla JS) controlado por máquinas de estado puntuales según la fase.
* **Diseño:** CSS3 con variables nativas (*custom properties*) para una paleta limpia y animaciones controladas por pulsos cinéticos en las fichas prioritarias.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*