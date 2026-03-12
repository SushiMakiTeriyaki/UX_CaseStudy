# DIU26
Prácticas Diseño Interfaces de Usuario (Tema: .... ) 

* [Guiones de prácticas](GuionesPracticas/)
* [Guía para crea tu Case Study](Guia_CaseStudy.md)
* Sala de la Fama [DIU Hall of fame](https://github.com/mgea/DIU/tree/master/hall_of_fame) donde se pueden encontrar Case Study destacados de otros años.




Actualizado: 26/02/2026




## Paso 0 My UX-Case Study
![Método UX](img/caseStudy.png) 
-----

>>> Este documento es el esqueleto del Case Study que explica el proceso de desarrollo de las 5 prácticas de DIU. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. Elimine este tipo de texto / comentarios desde la práctica 1 conforme proceda a cada paso


>>> Hay que Publicar de forma incremental "my Case Study" en Github... Es el momento de dejar este documento para que sea evaluado y calificado como parte de la práctica
>>> Documente bien la cabecera y asegurese que ha resumido los pasos realizados para el diseño de su producto

Grupo: DIU1_SushiMakiTeriyaki.  Curso: 2025/26 

Nombre del Proyecto: 

**Sushi Maki**

Descripción: 

Sushi Maki es una propuesta nueva en Granada que une lo mejor de dos mundos: la **rapidez** de un sitio de hamburguesas con la **calidad** de un restaurante japonés de nivel. Todo se gestiona desde una aplicación que te permite elegir cómo quieres comer: sentado tranquilamente en el buffet, pidiendo algo rápido para llevar o recibiéndolo en casa.

Logotipo: 

>>> Si diseña un logotipo para su producto en la práctica 3 pongalo aqui, a un tamaño adecuado. Si diseña un slogan añadalo aquí

Miembros y nombre del equipo:
 * :bust_in_silhouette:  Germán Delgado Fernández     :octocat:     
 * :bust_in_silhouette:  Javier Miñán Molina     :octocat: https://github.com/jminmol

>>> Los equipos son de 2 personas. Identifícaros con el nombre del Grupo y los enlaces a los perfiles de GitHub de cada integrante

----- 

<br>

# Proceso de Diseño 





<br>

## Paso 1. UX User & Desk Research & Analisis 

Para el desarrollo de esta plataforma, hemos analizado la convergencia entre la **automatización del servicio** y la **personalización del cliente**. Hemos dividido la experiencia en tres áreas muy claras, pensando siempre en la facilidad del usuario:

---

### 1. Restaurante de Alto Nivel con Zona Buffet
Esta sección está diseñada para quienes buscan disfrutar de la experiencia completa con reserva previa. El núcleo tecnológico es la **tablet inteligente** integrada en la mesa:

* **Perfil automático:** Al llegar, la tablet te identifica al instante a través del correo electrónico de tu reserva.
* **Filtro inteligente de carta:** La oferta se adapta a tus necesidades. Si indicas en la App que tienes alergias (ej. marisco) o preferencias (ej. no picante), la tablet **oculta automáticamente** esos platos. Además, puedes gestionar tus secciones de **Favoritos** o **Eliminados** para personalizar tu menú.
* **Precios dinámicos:** El sistema actualiza el coste del buffet de forma transparente según el calendario (diario, fin de semana o festivos).

### 2. Zona Rápida: Pedir, Recoger y Listo
Un espacio optimizado para usuarios con poco tiempo que no quieren renunciar a la calidad.

* **Máquinas de autopedido:** Sin colas en el mostrador. El usuario selecciona su sushi en pantallas táctiles de forma visual y rápida.
* **Flexibilidad de consumo:** El local cuenta con una zona de mesas exclusiva para esta modalidad, permitiendo elegir entre comer allí mismo o la opción *take-away*. Es la agilidad del *fast-food* aplicada al sushi premium.

### 3. Servicio a Domicilio: Tu Sushi Favorito en Casa
Para disfrutar de la experiencia sin desplazamientos, con un control total sobre el pedido.

* **Selección pieza a pieza:** A diferencia del menú buffet, aquí el usuario puede configurar su pedido con total precisión, eligiendo exactamente las piezas que desea.
* **Seguimiento en tiempo real:** Gestión integral desde la App, permitiendo monitorizar el estado del pedido desde la cocina hasta la entrega en el domicilio.

---

### 💳 Ecosistema de Fidelización Unificado
Lo que hace único a **Sushi Maki** es que todos sus servicios están conectados para premiar al cliente:

* **Unificación:** Uses el servicio que uses, siempre acumulas puntos en una sola cuenta.
* **Identificación sencilla:**
   * **En Mesa/Domicilio:** Los puntos y descuentos se gestionan solos al estar logueado en la App.
   * **En Máquina:** Basta con escanear el **código QR** generado por tu aplicación antes de pagar.
* **Ahorro progresivo:** El sistema de "Puntos de Regalo" incentiva la recurrencia; cuanto más interactúas con la marca (en cualquier canal), mayores son los beneficios en tus siguientes pedidos.


### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

El proyecto seleccionado para la investigación es “Sushi Maki”, un concepto de restauración innovador en Granada que fusiona la cocina japonesa de alta calidad con la eficiencia tecnológica. Aunque nuestro enfoque principal es el desarrollo de la plataforma digital (App y tablets), nos acercamos a este proyecto desde una perspectiva de usuarios habituales de gastronomía asiática, lo que nos permite identificar de primera mano las frustraciones comunes en los buffets tradicionales y en los servicios de comida rápida.

El objetivo principal de esta investigación es, además de garantizar una experiencia de usuario fluida y sin errores, validar cómo la tecnología puede personalizar la alimentación (especialmente en usuarios con alergias) y optimizar los tiempos de espera. Buscamos maximizar el uso de la aplicación tanto para reservas como para pedidos rápidos, logrando que el sistema de fidelización por puntos sea el motor que incentive la recurrencia de los clientes en cualquiera de nuestras tres modalidades (Buffet, Zona Rápida y Delivery).

Enlace al archivo: [Research Plan](./P1/User%20Research%20Plan/UserResearchPlan.md) 


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

Para definir nuestra propuesta, en la que fusionamos dos modelos de consumo, hemos analizado dos referentes locales en Granada que representan los extremos de nuestro modelo de negocio: el restaurante tradicional/buffet y el fast-casual temático.

**Natural Sushi:** con un modelo de negocio clásico y cuidado. Es un lugar que transmite calidad y elegancia, ideal para reservar mesa, ir con tiempo y disfrutar de una velada tranquila. Sin embargo su presencia digital suele ser muy estática y tradicional. No contempla un flujo de usuario ágil para comida rápida; el cliente está forzado a invertir mucho tiempo en el proceso de consumo, perdiendo al público que busca inmediatez.

**Ramen Shifu:** con un modelo de negocio Fast-casual / Comida rápida temática. Es altamente atractivo para un público joven y que no buscan una esperiencia gastronomica elevada. Este modelo ahuyentan al cliente que busca una experiencia gastronómica "premium", una cena formal y elegante o simplemente disfrutar de la comida con tranquilidad.

**Decisión:** Nos hemos decantado por analizar a fondo la web de Ramen Shifu para nuestra Revisión de Usabilidad. Hemos tomado esta decisión porque se queda en un punto medio de lo que queremos ofrecer. No es el servicio más rápido posible ni tampoco ofrece una experiencia gastronomica única por lo que es un caso perfecto para analizar y poder mejorarlo. 

**Conclusión:** Nuestro proyecto pretende "arreglar" este enfoque tradicional de Natural Shusi, mantendremos la elegancia para el usuario que quiere reservar mesa y comer tranquilo, pero añadiremos un enfoque secundario, ágil y rápido, para el usuario que busca pedir rapidamente en el local o hasta con el movil a domicilio sin perder tiempo en exceso, mejorando lo que ofrece Ramen Shifu

<img width="1020" height="859" alt="image" src="https://github.com/user-attachments/assets/d67e8549-fef3-43fd-9a60-c4d72f273588" />



### 1.c Personas
![Método UX](img/Persona.png) 
-----
**Persona 1: John Smith**

John es un analista financiero estadounidense que trabaja en remoto desde Granada. Representa nuestro **caso extremo** para la zona *Fast-Food*: un usuario hiperconectado, asocial y muy exigente que valora su tiempo por encima de todo. Su objetivo es comer sushi de alta calidad sin perder un solo minuto en interacciones tradicionales (esperar mesa, pedir a un camarero o esperar la cuenta). Si nuestra plataforma y el flujo automatizado del restaurante son lo suficientemente rápidos e intuitivos para que John complete su pedido sin frustrarse, habremos garantizado el éxito para cualquier usuario local que busque inmediatez.

<img width="841" height="767" alt="image" src="https://github.com/user-attachments/assets/f5dd3370-c3bc-4a46-bced-f16f9a43a762" />


**Persona 2: Sofía García**

Sofía es una creadora de contenido granadina enfocada en el apoyo al comercio local. Representa nuestro caso extremo para la zona de Buffet Premium: una usuaria que huye de las prisas, valora la parte social de las comidas y detesta la masificación. Su prioridad es disfrutar de una experiencia personalizada y tranquila, donde pueda controlar al detalle lo que consume. Si nuestra interfaz y el sistema de reserva logran que Sofía se sienta en control de su tiempo y libre de interrupciones externas, habremos garantizado el éxito para cualquier usuario que busque una comida exclusiva, segura y de alta calidad.

<img width="1600" height="1500" alt="Sofia" src="https://github.com/user-attachments/assets/38691f76-a5a4-4f74-9611-412c1dcf7e8a" />


>>> Junto con la captura de pantalla de la ficha de la persona, haz una breve descripción de la misma. Recuerda que son dos. Los recursos de imagen deberán estar dentro de la carpeta P1/ Cuando termines, borra esta línea.  


### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

**Justificación de las experiencias seleccionadas:**

Hemos diseñado dos *User Journey Maps* que representan los dos extremos de nuestro modelo de negocio híbrido. Hemos elegido estas dos experiencias porque reflejan situaciones muy habituales en el día a día y justifican la necesidad de tener una plataforma bimodal:

**1. John Smith (Perfil Ágil / Fast-Food):**
Esta experiencia refleja un escenario cada vez más común en las ciudades: profesionales o estudiantes que tienen el tiempo hipermedido pero que no quieren renunciar a comer con calidad. Hemos mapeado este viaje porque pone a prueba la eficiencia de nuestro diseño. Demuestra que existe un dolor real en el usuario impaciente al que le frustran los procesos tradicionales lentos, justificando así la creación de nuestro flujo de pedido rápido, automatizado y sin fricciones.

<img width="1172" height="763" alt="image" src="https://github.com/user-attachments/assets/50cc9912-0a0c-4a87-bad1-eeeb1f1d038d" />

Enlace al archivo: [John Journey Map](P1/User%20Journey%20Map/UJM%20John.pdf)

**2. Sofía García (Perfil Pausado / Social / Buffet Premium):**
Esta experiencia representa el otro polo de nuestro modelo: el cliente que busca en la gastronomía un refugio y un evento social. Hemos seleccionado este viaje porque justifica la parte más tecnológica y personalizada de nuestra zona de buffet. El mapeo de Sofía demuestra que la tecnología sirve para dar autonomía y seguridad al comensal. Muestra la necesidad de integrar filtros de alérgenos y preferencias en la tablet para eliminar la presión, el agobio, y la duda para elegir, validando que Sushi Maki puede ser, al mismo tiempo, un entorno de máxima calma y control para el usuario.
 
<img width="7486" height="4592" alt="UJM Sofia" src="https://github.com/user-attachments/assets/118c254f-3edc-4f8c-a453-81580b8acd50" />

Enlace al archivo: [Sofia Journey Map](P1/User%20Journey%20Map/UJM%20Sofia.png)


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

* **Enlace al documento:** [Usability Review](P1/Usability%20Review/Usability-review-template.pdf)
* **URL y competidor evaluado:** https://www.ramenshifu.com/
* **Valoración numérica obtenida:** 64 / 100 (Moderate)

**Comentario sobre la revisión:**
Tras realizar la evaluación heurística mediante el checklist, el competidor ha obtenido una puntuación de 64/100, lo que indica una usabilidad "Moderada". Esto significa que los usuarios pueden completar las tareas principales, pero la experiencia tiene un margen de mejora significativo.

* **Puntos fuertes detectados:** Visualmente la web es atractiva para alguna personas demasiado llamativas, la página de inicio deja claro el concepto. Esto atrae a perfiles bastante neutros sin tener encuenta los peculiares.
* **Puntos débiles detectados:** Hemos encontrado varias fricciones que afectan gravemente a usuarios impacientes (como nuestro perfil de Fast-Food, John), no mostrar la carta facilmente es perjudicial para atraer clientes con este perfil. La web no tiene demasiada funcionalidad es muy escueta y simple.

## Paso 2. UX Design  

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

>>> Comenta con un diagrama los aspectos más destacados a modo de conclusion de la práctica anterior. De qué carece la competencia?? Tu diagrama puede ser una figura subida a la carpeta P2/


 Interesante | Críticas     
| ------------- | -------
  Preguntas | Nuevas ideas
  
    
>>> Explica el Problema y plantea una hipótesis. Es decir, explica aquí qué 
>>> se plantea como "propuesta de valor" para un nuevo diseño de aplicación propio


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

>>> Propuesta de valor, pero ahora en vez de un texto es un ScopeCanvas que has subido a P2/ y enlazado desde aqui. Tambien vale una imagen miniatura del recurso.
>>> No olvides que tu propuesta ya tiene un nombre corto y puedes actualizar la cabecera de este archivo



### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

>>> Definir "User Map" y "Task Flow" ... enlazar desde P2/ y describir brevemente


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

>>> Identificar términos para diálogo con usuario (evita el spanglish) y la arquitectura de la información. Es muy apropiado un diagrama tipo sitemap y una tabla que se ampliaría para llevar asociado la columna iconos (tanto para la web como para una app). 

Término | Significado     
| ------------- | -------
  Login  | acceder a plataforma


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

>>> Plantear el diseño del layout para Web/movil (organización y simulación). Describa la herramienta usada 

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




