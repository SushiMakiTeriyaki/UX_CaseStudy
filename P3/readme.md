# DIU - Practica 3

## Mi UX-Case Study (diseño)
Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento

## Moodboard
Este moodboard recoge la identidad visual del proyecto Sushi Maki, un restaurante japonés orientado a ofrecer alta cocina accesible para todo tipo de perfiles, con especial énfasis en la experiencia del usuario.
Aquí se definen los pilares visuales y de comunicación del proyecto:

* Paleta de colores que transmite modernidad, calidez y elegancia
* Tipografías (Montserrat y Manrope) seleccionadas por su legibilidad y estilo contemporáneo
* Logo e identidad de marca con un diseño limpio y minimalista, representa lo más basico del restaurante shusi y los palillos 
* Inspiración de diseño basada en restaurantes similare que proporcionan servicios de alto nivel
* Perfiles de usuario muestran sus necesidades y motivaciones reales
* UX Writing: "Alta cocina japonesa, a tu ritmo", una frase que identifica la esencia del restarante la calidad de la comida y su preocupación por el cliente, que todo el mundo pueda independientemente del tiempo quue dispongan

#### Moodboard:

<img width="1315" height="861" alt="image" src="https://github.com/user-attachments/assets/842b358c-7a99-44db-8df6-3e44a4329029" />


## Landing Page
La landing page de Sushi Maki es la carta de presentación digital del restaurante, diseñada para transmitir la identidad de marca y captar la atención del usuario desde el primer momento.

Estructura de la página:
* Parte superior: imagen principal del restaurante acompañada del UX Writting de marca "Alta cocina japonesa, a tu ritmo", con llamada a la acción para poder realizar las diferentes acciones en la página.
* Una sección donde se puede apreciar el mapa indicando donde esta el local si se pulsase se abriría directamente google maps con el camino a seguir para poder llegar.
* Para dar enfasis en porque elegirnos tenemos una sección dedicada a los aspectos en los que destacamos. Con tres motivos clave que destacan el servicio exprés, la calidad de los ingredientes y la experiencia sin interrupciones.
* Una sección dedicada a como contactarnos donde se puede ver el teléfono con su horario y el correo.
* Una sección de preguntas frecuentes que resuelve las dudas más comunes sobre reservas, alérgenos, tiempo de servicio, pedidos a domicilio y eventos...

Decisiones de diseño
La página sigue la paleta de colores y tipografía definidas en el moodboard (Montserrat y Manrope), manteniendo una estética minimalista y elegante coherente con la identidad visual de Sushi Maki. Se ha priorizado la experiencia del usuario, especialmente de perfiles con poco tiempo disponible y usuarios con necesidades alimentarias específicas.

Como se menciona en el guión de prácticas había que usar las herramientas en figma que integran IA. Para ello en primer lugar probé una herramienta con la cual no logre nada no obstante busque otra, esta fue Wireframe Designer. Pero los resultados que esperaba no eran ni mucho menos los esperados probé diferentes prompts ya que con el primero no me gusto el resultado, estos son los prompts que usé:

#### Prompt 1:

"A modern, elegant, and dark-mode landing page for a premium sushi restaurant app called Sushi Maki. Top section (Hero): A large catchy headline, a subtitle, and a primary CTA button. Middle section: A large placeholder to display a smartphone app mockup. Bottom section: A 3-column features area. Visual style: Sleek, high-end, using dark charcoal background (#1A1A1A), terracotta accents for buttons (#E65100), and sage green details (#75A47F). Typography style: Clean sans-serif and elegant serif."

#### Prompt 2:

Genera una landing page minimalista en modo oscuro para el restaurante 'Sushi Maki' en Granada. Estilo moderno y limpio. Estructura:

1. Cabecera (Hero): Un título grande, un subtítulo descriptivo y un botón grande de color naranja.
2. Imagen Central: Un espacio grande vacío en el centro para colocar un teléfono móvil.
3. Características (3 columnas): Una sección debajo con 3 columnas iguales con iconos simples y texto corto. le he puesto eso

Pero en ambas ocasiones el resultado fue el mismo y no nos gusto nada por lo que se optó por hacerlo manualmente con los requisitos que se piden.

#### Landing Page:

<img width="273" height="929" alt="image" src="https://github.com/user-attachments/assets/640ce709-620c-4b40-ba28-103fa7974f65" />


## Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado.

Para garantizar una experiencia de usuario coherente y escalable, se ha desarrollado un sistema de diseño basado en componentes atómicos y patrones funcionales que responden a nuestra propuesta bimodal.  

#### 1. Componentes Atómicos: Estilo Visual

Se han definido las bases visuales de la aplicación para potenciar la identidad de la marca y la usabilidad en dispositivos táctiles:  
* Paleta de Colores Semántica:
  * Rojo Sushi (#E63946): Utilizado como color de acción principal en botones críticos como "Añadir" y "Pagar".
  * Verde Wasabi (#87D272): Reservado para la seguridad alimentaria, indicando platos "Sin alérgenos" y confirmaciones de filtros activos.
  * Crema (#E7EBE6): Empleado en fondos y tipografía para asegurar una estética limpia y de alta gama.
También se han usado otros colores como para establecer el color de los botones (Color Salmon #FDA29F) o para el fondo de la cabera (Color Gris claro #E7EBE6).

* Tipografía: Se utiliza Montserrat para la identidad de marca (logotipo) y para los textos en botones, garantizando legibilidad y peso visual.


#### 2. Patrones de Interfaz (IU)
Basándonos en los perfiles de usuario detectados, se han implementado los siguientes patrones:  
* Selector Bimodal: Componente ubicado en la cabecera que permite al usuario alternar globalmente entre el Modo Fast (velocidad y simplicidad) y el Modo Safe (detalle y seguridad).
* Menú de Navegación Fijo (Header): Actúa como centro neurálgico persistente. Incluye el logotipo como retorno a inicio, el selector bimodal y acciones globales como el carrito con indicador de ítems y el perfil de usuario.
* Bimodal Product Cards: Tarjetas dinámicas que adaptan su carga informativa. El Modo Safe destaca alérgenos en verde e información técnica, mientras que el Modo Fast prioriza la imagen, el precio y la conversión rápida.
* Search Bar & Smart Filters: Sistema de búsqueda predictiva que, en el Modo Safe, funciona como un filtro sanitario resaltando productos aptos y ocultando riesgos. En el Modo Fast, prioriza el historial del usuario para acelerar la compra.
* Jerarquía de Acciones (Botones):
  * Botón Principal: Diseño sólido en Rojo Sushi para acciones de avance. Incluye variantes para estados Default, Hover y Pressed.
  * Botón Secundario: Diseño de fondo transparente con borde rojo para acciones de retroceso o cancelación, minimizando errores accidentales.
* Filter Chips / Toggles de Seguridad: Selectores binarios para necesidades dietéticas que cambian a verde al activarse, señalizando visualmente la aplicación de un filtro de seguridad.
* Formulario de Pago: Cuadrícula simplificada para facilitar el uso táctil. Ofrece autocompletado inteligente en el Modo Fast y etiquetas claras con opciones de revisión total en el Modo Safe.

Enlace al archivo: [Guidelines](P3/Guidelines/Guidelines.pdf)


## Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders

El mockup constituye el prototipo de alta fidelidad de Sushi Maki, donde se han integrado todos los componentes y patrones definidos en las Guidelines  para simular flujos de usuario reales en un entorno de tablet.  

#### 1. Simulación de Tareas y Flujos
El prototipo permite validar la eficacia de la propuesta bimodal mediante la ejecución de tareas críticas:
* Conmutación de Experiencia: Gracias al selector bimodal, el usuario puede alternar entre el Modo Fast y el Modo Safe. Esta transición utiliza Smart Animate para reflejar visualmente cómo la interfaz se simplifica o se detalla según el perfil.
* Selección de Producto: Se simula la interacción con las cartas de productos bimodales, permitiendo al usuario visualizar la información técnica en el modo de seguridad o proceder a una compra rápida en el modo de agilidad.
* Proceso de Pago (Checkout): El flujo culmina en el formulario de pago, donde se puede probar el patrón de autocompletado para el perfil Fast o la revisión asistida para el perfil Safe.

#### 2. Interactividad y Estados
Para lograr un realismo de nivel profesional, se han configurado los estados de los componentes atómicos:
* Botones Dinámicos: Tanto el Botón Principal como el Secundario responden a las acciones del usuario mediante estados de Hover y Pressed.
* Validación de Filtros: Los Filter Chips cambian de estado y color (hacia el Verde Wasabi) al ser activados , proporcionando una confirmación visual inmediata de que se está aplicando un filtro de seguridad alimentaria.

#### 3. Valor Estratégico
Este mockup no es solo una representación visual, sino una herramienta de validación que permite:
* Verificar la consistencia de la Paleta de Colores (Rojo Sushi, Verde Wasabi y Crema) en un flujo de navegación real.
* Evaluar la legibilidad de la tipografía Montserrat en los elementos de acción y navegación.
* Demostrar a los stakeholders cómo la arquitectura de información se adapta dinámicamente para reducir la carga cognitiva del usuario.

Finalmente se adjunta un video de prueba de uso:

https://github.com/user-attachments/assets/b87e3735-b198-4b5a-8180-14ed859d98aa

Enlace a los wireframes formato tablet finalizado usable: [pinche aqui](https://www.figma.com/design/NYHnoISLFfCcMScfGPko04/BocetosTablet?node-id=47-211&t=53uQteTkBxEiQLGE-1 )


<br>

## Briefing

Proceso de diseño

El proceso de esta práctica ha partido directamente de los resultados obtenidos en la fase de investigación anterior, donde definimos dos perfiles de usuario opuestos John (perfil ágil) y Sofía (perfil pausado y seguro) y mapeamos sus experiencias para identificar los puntos críticos reales. Esto nos ha permitido tomar decisiones de diseño fundamentadas desde el primer momento, evitando soluciones genéricas.
La práctica se ha estructurado en cinco fases encadenadas: moodboard, landing page, design system, layout hi-fi y este briefing. Cada fase ha alimentado a la siguiente, garantizando coherencia visual y funcional en todo el proceso.

Herramientas utilizadas

Figma ha sido la herramienta principal que se ha utilizado (como se ha indicado en las clases). Se ha usado para el diseño del moodboard, el landing, el design system y el layout. Usando en todo momento componentes atómicos para facilitar futuros cambios de diseño.

Puntos fuertes del diseño

* Identidad visual clara y coherente: la paleta de colores cálidos, la tipografía elegante y el logotipo minimalista transmiten de forma efectiva los valores de Sushi Maki en todos los puntos de contacto.
* Diseño bimodal: la arquitectura de la app contempla desde el inicio dos modos de uso, Modo Rápido para John y Modo Safe para Sofía. Lo que garantiza que ningún perfil de usuario quede desatendido.
* Sistema de alérgenos integrado: uno de los diferenciadores más relevantes del diseño, directamente extraído de las necesidades reales detectadas en la investigación.
* Design system escalable: el uso de tokens de color, escala tipográfica modular y componentes atómicos permite que el sistema pueda crecer sin perder consistencia.

## Conclusiones

Esta práctica ha demostrado que un proceso de diseño bien fundamentado en investigación previa reduce significativamente el número de decisiones arbitrarias. El uso combinado de Figma y herramientas de IA ha resultado eficaz para acelerar las fases más creativas: redacción, ideación visual y prototipado sin sacrificar la coherencia del resultado final. El principal reto ha sido mantener el equilibrio entre la estética premium que exige el perfil de Sofía y la simplicidad funcional que necesita el perfil de John, algo que el diseño bimodal ha resuelto de forma satisfactoria.
