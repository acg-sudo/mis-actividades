# Desafío: Identificar Componentes del PC 🧩🖥️🔍

Este proyecto es una aplicación web interactiva y visual diseñada para que los alumnos aprendan a reconocer físicamente los componentes de hardware internos y externos de un ordenador. Ha sido desarrollado especialmente para los estudiantes del **Taller de Informática de la EPA Sedaví**.

## 🕹️ Dinámica del Juego

El simulador reta al alumno a asociar imágenes reales de hardware con sus nombres técnicos:

1. **Selección del Componente:** El alumno selecciona una de las etiquetas del banco de palabras en la parte superior.
2. **Asociación Visual:** Al hacer clic sobre la tarjeta que muestra la imagen física del componente, se le asigna el nombre seleccionado.
3. **Mecánica de Corrección de Errores:** Si el alumno cambia de opinión, puede liberar un nombre haciendo clic en la tarjeta asignada, lo que devuelve la etiqueta al banco superior.
4. **Rondas de Azar ilimitadas:** Al pulsar **"Siguiente Ronda (Azar)"**, el juego selecciona aleatoriamente un conjunto de 8 componentes de entre una base de datos de más de 30 imágenes para que cada intento sea un reto totalmente diferente.

## 🚀 Características Didácticas

* **Amplia Base de Datos de Hardware:** Contiene más de 30 piezas de hardware para identificar, incluyendo conectores específicos (ATX 24 pines, cables SATA), ranuras de la placa base (Socket, ranuras DIMM, PCIe), puertos externos e internos y periféricos de uso común.
* **Control de Enlaces Rotos (Sistema Fallback):** Las tarjetas de imágenes cuentan con un sistema inteligente de seguridad que, en caso de fallo en la ruta local de alguna imagen, carga un icono alternativo automático desde un servidor de confianza, garantizando que el juego nunca quede inutilizado.
* **Evaluación Formativa:** Al corregir el ejercicio, el sistema muestra de forma clara los aciertos en verde y los errores en rojo con un panel de retroalimentación indicando el nombre correcto del componente fallado.
* **Gamificación y Recompensa:** Al conseguir identificar correctamente el 100% de los elementos de la ronda, el juego despliega un efecto visual de confeti dinámico en pantalla.
* **Modo Profesor / Pizarra Digital:** Diseñado para facilitar la corrección grupal en el aula mediante un botón secreto (revelado al pulsar la llave `🔑` en el pie de página) o a través del atajo rápido de teclado `Alt + D`, que resuelve de forma inmediata la ronda activa.

## 🛠️ Tecnologías y Estructura

* **Estructura:** HTML5 semántico y CSS3 responsivo adaptado para pantallas táctiles, tablets y ordenadores de aula.
* **Estilos Dinámicos:** Efectos visuales de escalado y sombras en las tarjetas de componentes para una experiencia de usuario fluida y moderna.
* **Lógica:** JavaScript Nativo (Vanilla JS) y uso de la biblioteca ligera `canvas-confetti` para las celebraciones de éxito.

---
*Diseñado con ♥ por el **Profe Adna** para potenciar el aprendizaje técnico de sus alumnos.*