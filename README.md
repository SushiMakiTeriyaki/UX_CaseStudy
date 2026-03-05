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

Sushi Maki

Descripción: 

Sushi Maki es una propuesta nueva en Granada que une lo mejor de dos mundos: la rapidez de un sitio de hamburguesas con la calidad de un restaurante japonés de nivel. Todo se gestiona desde una aplicación que te permite elegir cómo quieres comer: sentado tranquilamente en el buffet, pidiendo algo rápido para llevar o recibiéndolo en casa.

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

Para el desarrollo de esta plataforma, hemos analizado la convergencia entre la automatización del servicio y la personalización del cliente. Hemos dividido la experiencia en tres áreas muy claras, pensando siempre en la facilidad del cliente:

1. Restaurante alto nivel con zona Buffet
 Esta parte es para los que vienen a disfrutar del buffet con reserva previa. La clave aquí es la tablet de la mesa:

   Perfil automático: Al llegar, la tablet ya sabe quién eres porque te reconoce por el correo de tu reserva.
   
   Filtro de comida: Lo mejor es que la carta se adapta a ti. Si le dices a la App que eres alérgico al marisco o que no te gusta el picante, la tablet no muestra esos platos. De igual forma puedes añadir a la sección de favoritos o  eliminados diferentes platos.
   
   Precios claros: El sistema cambia el precio del buffet solo según si es fin de semana, festivo o diario.


3. Zona Rápida: Pedir, recoger y listo
 Hemos creado un espacio pensado para la gente que tiene poco tiempo.

   Máquinas de autopedido: En lugar de esperar cola en un mostrador, vas directo a una pantalla, eliges tu sushi y pagas.
   
   Flexibilidad: Puedes sentarte en unas mesas preparadas específicamente para esta zona o llevártelo a donde quieras. Es sushi de alta calidad con la velocidad de la comida rápida.
   
   
5. Servicio a Domicilio: Tu sushi favorito en casa
 Si prefieres no moverte, la aplicación te permite pedir exactamente las piezas que quieras, una a una.

  Selección pieza a pieza: A diferencia del buffet, aquí tienes el control total para elegir exactamente las piezas que te apetecen, creando tu combinación ideal a medida.
  
  Seguimiento en tiempo real: Todo el proceso, desde la cocina hasta que el repartidor llega a tu puerta, se gestiona desde la App para que sepas exactamente cuándo llega tu cena.


Todo conectado: Lo bueno es que uses el servicio que uses, siempre acumulas puntos.
Puntos de regalo: Si pides por la máquina del local, escaneas tu código QR; si reservas mesa o pides a casa, como ya estás logueado en la App, los descuentos se te guardan solos. Así, cuanto más comes en Sushi Maki (sea donde sea), menos pagas en tu siguiente pedido.


### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

>>> Describe el plan en tu User Research (cómo se plantea la selección de usuarios). Borra esta línea cuando lo tengas.  


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

Para definir nuestra propuesta donde fusionamos ambos aspectos de la comida, hemos analizado dos referentes locales en Granada que representan los extremos de nuestro modelo de negocio: el restaurante tradicional/buffet y el fast-casual temático.

Por un lado tenemos Natural Sushi con un modelo de negocio clásico y cuidado. Un lugar que transmite calidad y elegancia. Ideal para ir con tiempo, reservar mesa para una cena tranquila y disfrutar de la velada. Sin embargo su web suele ser muy estática y tradicional. No cuenta con un servicio de comida rápida par aquella gente que no tiene mucho tiempo y quiere algo rápido, debes gasta mucho tiempo forzosamente si quieres ir a comer.

Por otro lado tenemos a Ramen Shifu con un modelo de negocio Fast-casual / Comida rápida temática. Muy interesante a simple vista mantiene una identidad visual muy potente (estética anime/callejera). Muy atractivo para público joven y pedidos rápidos. Sin embargo este modelo aleja a clientes que buscan tranquilidad y disfrutar de la comida, la sobrecarga visual y rápidez por pedir que implica estos lugares aleja a estas personas que buscan una experiencia "premium" o una cena más formal y relajada.

Decisión: Nos hemos decantado por analizar a fondo la web de Natural Sushi para nuestra Revisión de Usabilidad. Hemos tomado esta decisión porque representa muy bien la "base" de nuestro producto (sushi de calidad y experiencia de sala elegante para esa gente que quiere disfrutar de la comida), pero carece por completo de la bimodalidad que queremos implementar, esa comida rápida que no lleve mucho tiempo. Nuestro proyecto pretende "arreglar" este enfoque tradicional: mantendremos la elegancia para el usuario que quiere reservar mesa y comer tranquilo (como en Natural Sushi), pero añadiremos un enfoque secundario, ágil y con toques anime , para el usuario que busca pedir rapidamente en el local o hasta con el movil a domicilio.



### 1.c Personas
![Método UX](img/Persona.png) 
-----

>>> Junto con la captura de pantalla de la ficha de la persona, haz una breve descripción de la misma. Recuerda que son dos. Los recursos de imagen deberán estar dentro de la carpeta P1/ Cuando termines, borra esta línea.  


### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

>>> Describe el porqué de las dos experiencias de usuario contadas en el journey map. Por ejemplo, reflexiona si te parece que son habituales. Enlaza con los recursos journey que están en la carpeta P1/. Borra esta linea del template cuando termines.  


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

>>>  El objetivo es revisar la usabilidad del competidor seleccionado. Usamos un checklist de verificación. Tras usarlo, subelo a la carpeta P1/ Ofrece aquí un parrafo para:
>>> - Enlace al documento:  (xls/pdf) 
>>> - URL y Valoración numérica obtenida: 
>>> - Comentario sobre la revisión:  (puntos fuertes y débiles detectados)

<br>

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




