# Usability Report

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF017nhV-TFmNER2OM8UbXtdN6xwAKBYrv0i6onNfKu6Yn0BV0RK6aiOroeXl73LSY-B0&usqp=CAU" alt="usability Download png" style="height:150px" />

### Evaluación de usabilidad de la cafetería: Gravity Brew (Caso B)

**Fecha:** 28 de Mayo de 2026  
**Proyecto Evaluado:** Gravity Brew (Competidor - Caso B)
**Enlace a GitHub:** [Repositorio GazeMapping]([https://github.com/mgea/GazeMapping](https://github.com/Mamarco13/DIU2_Solanum))

### Realizado por:
**Equipo de Evaluación UX/UI - DIU**  
Somos un equipo especializado en el análisis de interfaces de usuario y optimización de la experiencia digital. En esta evaluación aplicamos técnicas cualitativas y biométricas (Eye Tracking) para medir la eficiencia y el diseño del Caso B frente a nuestra propuesta.

---

## 1. RESUMEN EJECUTIVO (Executive Summary)

- **Objetivo:** Evaluar la usabilidad y accesibilidad de la aplicación web de la cafetería de especialidad **Gravity Brew** (Caso B) para identificar fricciones críticas y compararla con nuestra propuesta de diseño **Sushi Maki** (Caso A).
- **Metodología:** Evaluamos a 3 usuarios (P4, P5 y P6) utilizando técnicas biométricas de **Eye Tracking** (a través de **GazeMapping**), recopilación de datos cuantitativos de usabilidad con la **escala SUS (System Usability Scale)** y auditorías automatizadas de accesibilidad web (**WAVE**).
- **Principales Hallazgos:**
  1. **Falta Crítica de Información de Contacto:** El 100% de los usuarios del Caso B fracasó en la tarea común de buscar el contacto del local debido a que la web no incluye ningún número, email, dirección ni redes sociales.
  2. **Bajo Contrase y Ceguera de Elementos Clave:** La tipografía dorada/gris sobre fondo oscuro provocó fallos de visibilidad en elementos esenciales; el botón principal "Reservar mesa" pasó completamente desapercibido para P5 y P6.
  3. **Inactividad en Filtros de Alérgenos:** Los filtros superiores de la carta son ignorados sistemáticamente o reciben mínima atención, comportándose como una zona ineficaz del menú.
- **Resultado Global:** **Gravity Brew** obtuvo una puntuación SUS de **79.17/100** (Calificación: **Bueno / Good**). Aunque estéticamente es atractiva, el diseño de Gravity Brew presenta debilidades estructurales de usabilidad.

---

## 2. Metodología y Reclutamiento

### Perfil de los Participantes (Caso B)
Para la evaluación de Gravity Brew contamos con 3 participantes finales que no tenían experiencia previa en estudios de usabilidad, pero sí contaban con familiaridad en apps similares:
- **P4:** 21 años, masculino, nivel de competencia digital alto.
- **P5:** 22 años, femenino, nivel de competencia digital medio.
- **P6:** 24 años, masculino, nivel de competencia digital alto.

### Escenario de la Prueba
Los usuarios interactuaron con el prototipo móvil en pantallas de alta resolución (1920x1080) bajo luz natural. Realizaron tres tareas principales:
1. **Tarea Libre Exploratoria:** Navegar y evaluar la propuesta visual inicial.
2. **Acción Específica:**
   - **P4:** Añadir un *Galaxy Matcha* al pedido.
   - **P5:** Intentar realizar una reserva de mesa.
   - **P6:** Localizar y ver la información del próximo evento.
3. **Acción Común:** Buscar la información de contacto de la cafetería.

### Herramientas Utilizadas
- **GazeMapping:** Registro de coordenadas de la mirada (Gaze) y pulsaciones (Clics).
- **Cuestionario SUS (Tally):** Recopilación y normalización de la percepción subjetiva de usabilidad.
- **WAVE Tool:** Evaluación y validación de las pautas de accesibilidad WCAG.

---

## 3. Resultados del Cuestionario SUS (Datos Cuantitativos)

- **Gravity Brew (Caso B - 79.17):** Experimentó una caída significativa en la **Pregunta 3** (Facilidad de uso, 6.67/10) y la **Pregunta 6** (Inconsistencias en el sistema, 7.5/10). La distribución de sus accesos directos y la duplicidad de caminos (botón principal vs menú inferior) desorientaron levemente a los participantes.

---

## 4. Análisis de Eye Tracking (Datos Biométricos)

### Análisis de Pantallas e Interacciones de la Mirada

#### Pantalla Home (Inicio)
- **Focos de Atención:** La identidad visual intermedia (eslogan "Tu pausa entre estrellas") y la taza de café concentran fijaciones moderadas a altas. La tarjeta del próximo evento "Noches Indie Acústicas" actúa como el elemento más potente de la parte inferior, registrando la mayor densidad de fijaciones del test en P6 y P4.
- **Zonas de Silencio:** El logotipo superior no registró fijaciones en P5 ni P6. El botón principal **"Reservar mesa"** fue completamente ignorado por P5 y apenas recibió calor en la periferia en P6, lo que indica un fallo de visibilidad grave. La barra "¿Qué quieres hacer?" recibió un escaneo extremadamente superficial a excepción del botón "Eventos" en P6 y "Platos" en P5.

#### Pantalla Menú / Carta
- **Focos de Atención:** Los usuarios centraron su actividad cognitiva únicamente en el contenido de texto (precios, descripciones, etiquetas), ignorando por completo las fotos de las bebidas. El **Galaxy Matcha** y el **Orbit Caramel** acumularon los puntos de calor más densos de la carta, seguidos por el Nebula Latte.
- **Zonas de Silencio:** Los filtros de alérgenos sufrieron un desinterés casi total; "Sin lactosa" y "Sin gluten" no registraron fijaciones. La barra de navegación inferior mostró atención selectiva: P5 la utilizó intensamente para orientarse ("Reservas" y "Eventos"), mientras que P6 solo miró "Perfil".

---

## 5. Auditoría de Accesibilidad

La evaluación técnica automatizada de Gravity Brew con WAVE detectó barreras significativas agrupadas según los principios WCAG:

- **Perceptible (Error de Contraste - 1.4.3 AA):** Se detectaron 3 errores de contraste muy bajo en los textos principales de la cabecera y el pie de página. El tono grisáceo y dorado se funde con el fondo oscuro, bloqueando la lectura para personas con problemas de visión o bajo luz brillante.
- **Operable (Broken ARIA reference - 2.1.1 A):** Un error crítico de referencia ARIA inválida en los enlaces interactivos rompe el foco de navegación para personas que dependen de navegación por teclado o tecnologías asistenciales.
- **Comprensible (Orphaned Form Label - 3.3.2 A):** Etiquetas de formulario sin enlace explícito al input de datos. Los lectores de pantalla no leen de manera descriptiva qué debe rellenar el usuario en las cajas de texto.
- **Robusto (Saturación ARIA - 4.1.2 A):** Acumulación excesiva de 74 atributos ARIA artificiales en una sola vista móvil simulada. Sobrecarga el código de forma inútil y arriesga incompatibilidades con futuros lectores de pantalla.

---

## 6. Conclusiones y Recomendaciones (Actionable Insights)

| **Prioridad** | **Hallazgo** | **Recomendación de Mejora** |
| :--- | :--- | :--- |
| **Alta (Crítica)** | El cuestionario SUS refleja dudas de flujo (6.67) y el Eye Tracking muestra el fracaso total al buscar el contacto de la cafetería. | Diseñar e integrar una sección limpia de **Contacto** (con teléfono, dirección, horario y mapa) vinculada al menú de navegación inferior. |
| **Alta (Crítica)** | 3 errores críticos de contraste impiden ver el botón "Reservar mesa" (biométricamente ignorado por P5 y P6). | Reemplazar las fuentes tipográficas doradas y grises por tonos más luminosos (blanco o crema), asegurando el ratio WCAG de contraste mínimo de 4.5:1. |
| **Media** | Navegación rota por teclado e inputs mal identificados por el software de lectura asistencial. | Vincular explícitamente las etiquetas `<label>` con sus `<input>` usando la propiedad `for`, y corregir las referencias de los identificadores ARIA en el código HTML. |
| **Media** | Exceso de 74 etiquetas ARIA artificiales que inestabilizan la semántica del prototipo. | Refactorizar el código reemplazando divs anidados artificiales por elementos nativos de HTML5 semántico (`<header>`, `<nav>`, `<main>`, `<button>`, `<footer>`). |
| **Baja** | Nula interacción con los filtros superiores de alérgenos de la carta (Zonas de Silencio). | Aumentar el contraste visual del fondo de las píldoras de filtro y agregar micro-animaciones (escala o cambio de color) en el hover/active para incitar su uso. |
