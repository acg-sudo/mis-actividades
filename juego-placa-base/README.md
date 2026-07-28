# Desafío: La Placa Base. El Corazón del Sistema. ❤️🖥️⚡

Este proyecto es una aplicación web interactiva de asociación y reconocimiento visual diseñada para evaluar e identificar los componentes fundamentales de una placa base (*motherboard*). Ha sido desarrollado especialmente para los alumnos del **Taller de Informática de la EPA Sedaví**.

## 🕹️ Dinámica del Juego

El juego plantea un reto visual interactivo de asociación directa entre la imagen esquemática de la placa base y sus componentes reales:

1. **Selección del Banco de Opciones:** El alumno selecciona una opción del banco lateral de palabras (como *CPU, Memoria RAM, Pila, Conector Ethernet RJ-45*, etc.).
2. **Asignación por Número:** Tras seleccionar la opción, la asigna a una de las 14 tarjetas numeradas de la parte inferior. Al hacerlo:
   * La opción del banco queda marcada como "usada" para evitar duplicados.
   * La tarjeta asignada muestra automáticamente una miniatura descriptiva en detalle del componente correspondiente.
   * *Mecánica de liberación:* Hacer clic sobre una tarjeta ya asignada la libera y devuelve la palabra al banco de opciones.
3. **Mecánica de Corrección y Feedback Visual:** Al pulsar **"✅ Comprobar Respuestas"**, el sistema evalúa la totalidad del mapa:
   * **Acierto:** La tarjeta individual se ilumina en verde.
   * **Fallo:** La tarjeta se ilumina en rojo y revela la solución correcta.
   * **Completado:** Si se identifican con éxito los 14 componentes, la imagen principal cambia automáticamente a la versión resuelta (`placabasesol.jpg`) y se activa una celebración con animación de confeti.

## 🚀 Características Didácticas

* **Mapa Visual Interactivo (14 Componentes Esenciales):**
  1. CPU (Procesador)
  2. Disipador CPU
  3. Conector alimentación placa (ATX)
  4. Memoria RAM (Slots DIMM)
  5. Pila (CR2032)
  6. Conectores para Discos (SATA)
  7. Conectores Tarjetas Expansión (PCI Express)
  8. BIOS
  9. Conectores Tarjeta Gráfica Dedicada
  10. Conectores Audio
  11. Conector Ethernet RJ-45
  12. Conectores USB
  13. Conectores Vídeo (HDMI/VGA/DisplayPort)
  14. Conectores PS/2
* **Doble Apoyo Visual:** Cada casilla cuenta con una pequeña captura detallada del componente en cuestión (`imgplacabase/1.jpg` a `14.jpg`) para afianzar el reconocimiento físico además del conceptual.
* **Diseño Responsivo en 2 Bloques:** Layout moderno en *Grid* que coloca la imagen esquemática principal y el banco de opciones en la parte superior, y distribuye las tarjetas de respuesta en filas adaptables en la zona inferior.
* **Modo Pizarra Digital (Profesor):** Incorpora un atajo secreto de resolución automática (pulsando el icono de la llave `🔑` en el pie de página o mediante la combinación de teclas `Alt + D`) con mensajes de alerta informativos para dinamizar explicaciones frente al alumnado.

## 🛠️ Tecnologías y Estructura

* **Estructura y Estilos:** HTML5 semántico y CSS3 con variables personalizadas (*custom properties*) para adaptar temas de color según el estado (correcto, incorrecto, seleccionado).
* **Lógica:** JavaScript Nativo (Vanilla JS) sin dependencias externas pesadas, salvo la librería externa `canvas-confetti` para la animación de victoria.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*