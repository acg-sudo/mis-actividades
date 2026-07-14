# Desafío: Asesor de Compras y Hardware 🛒💻

Este proyecto es una aplicación web interactiva y gamificada diseñada para que los estudiantes del **Taller de Informática de la EPA Sedaví** consoliden sus conocimientos de hardware de una forma práctica, amena y realista. El simulador los pone en el papel de un asesor técnico de tienda que debe recomendar la configuración ideal a diferentes perfiles de clientes y superar un control de calidad técnico.

## 🕹️ Dinámica del Juego y Actividades

El simulador se divide en dos fases pedagógicas consecutivas que guían al alumno desde la empatía con las necesidades del cliente hasta la asimilación de conceptos teóricos puros:

1. **🕵️‍♂️ Parte 1: Atención a Clientes (Casos Prácticos):** El alumno se enfrenta a un panel dinámico con 3 clientes aleatorios (extraídos de un banco de 12 casos reales). Cada cliente describe sus necesidades cotidianas en lenguaje coloquial (desde tareas de oficina básicas hasta edición de vídeo pesado en 4K o juego competitivo). El estudiante debe seleccionar la configuración de hardware idónea y equilibrada para cada perfil.
2. **✅ Parte 2: Test Técnico Exprés (Verdadero o Falso):** Una vez que el alumno asesora correctamente a todos los clientes, se desbloquea el acceso a la segunda pantalla. Consiste en un test rápido de 6 preguntas de Verdadero o Falso elegidas al azar de un banco de 20 enunciados sobre mitos de hardware, mantenimiento de equipos y arquitectura general de ordenadores.

---

## 🚀 Características Didácticas

* **Algoritmo de Mezcla Fisher-Yates:** Para garantizar la rejugabilidad y evitar que los alumnos memoricen el orden, el motor del juego utiliza una implementación limpia del algoritmo Fisher-Yates que desordena las preguntas y opciones de forma matemática y aleatoria en cada partida.
* **Glosario Técnico Integrado (Tooltips Accesibles):** Los conceptos más complejos (como *cuello de botella*, *imágenes RAW*, *procesadores ARM* o *tasa de refresco*) están destacados con un subrayado especial. Al pasar el ratón (en PC) o pulsar con el dedo (en móviles), se despliega un bocadillo explicativo simplificado. El sistema CSS adaptado mediante media queries evita que el tooltip se quede "atascado" al interactuar en pantallas táctiles.
* **Modo Pizarra / Maestro (🔑):** Al hacer clic en el emoji de la llave en el pie de página o presionar el atajo de teclado `Alt + D`, se activa un "Modo Profesor" invisible a simple vista. Este modo habilita un botón para resolver de forma automática los retos en pantalla, facilitando las explicaciones colectivas y debates en el aula.
* **Efectos Visuales Gratificantes:** Conseguir resolver con éxito la fase técnica activa una cascada de confeti dinámico programado nativamente en canvas para celebrar el logro del alumno.

---

## 🛠️ Tecnologías y Estructura

* **Formato Single-File (Todo en uno):** El proyecto está estructurado en un único archivo autónomo (`index.html`), lo que facilita enormemente su distribución directa a los alumnos sin necesidad de dependencias, servidores o instalaciones locales complejas.
* **Diseño Adaptable (Responsive):** La interfaz está optimizada con botones tipo "píldora" gigantes y un diseño limpio y espaciado, pensado específicamente para facilitar la navegación a alumnos senior en todo tipo de pantallas (ordenadores, tabletas y proyectores de clase).

---
*Diseñado con ♥ por el **Profe Adna** para hacer de la informática un concepto accesible, útil y divertido para todos.*