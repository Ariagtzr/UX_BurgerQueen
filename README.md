# Burguer Queen 

## Resumen

Burguer Queen es un proyecto que busca una propuesta para un negocio en la cadena de alimentos de comida rápida para mejorar el servicio y hacerlo más ágil se busca con ello recrear un ambiente más efectivo de trabajo en el que no sea complicado utilizar una web app para hacer un pedido. Dentro del presente proyecto se realizo una mejor forma de generar pedidos a la que se acostumbra en este tipo de lugares con comandas que tienen muchos pasos a seguir y que no te dan accesibilidad en nuestra forma de hacer un pedido. Durante el transcurso de la investigación profundizamos en la forma de trabajo de un encargado de barra para comida rápida para validar si los procesos que incluimos eran los adecuados.


## Contexto

Para contextualizar el presente trabajo se analiza la investigación que se tiene de la INEGI con respecto a los trabajadores de restaurantes en comida rápida:

En nuestro país, de acuerdo con la ENOE, al tercer trimestre de 2017 la población con esta ocupación es cercana a 1.6 millones de personas, de las cuales 57% son mujeres y 43% hombres. Además, 53% de estos ocupados preparan comida rápida en establecimientos y 47% la elaboran y venden de manera ambulante.  
De cada mil ocupados en la República Mexicana, 30 son preparadores de comida rápida. De acuerdo con el lugar de residencia de estos ocupados, ocho entidades federativas (Estado de México, Jalisco, Veracruz de Ignacio de la Llave, Ciudad de México, Guanajuato, Michoacán de Ocampo, Puebla y Guerrero), concentran poco más de la mitad de ellos en el país (54.4 por ciento). 

Si se considera el nivel educativo entre los que preparan comida rápida en establecimientos y los que la preparan y venden de manera ambulante, se observa que es más alto el nivel de instrucción entre los primeros: de cada 100 son 65 los que cuentan con educación básica, 32 tienen educación post básica y solo tres no cuentan con instrucción. En el caso de los que preparan y venden de manera ambulante, de cada 100 son 74 quienes tienen educación básica, 18 con post básica y ocho sin instrucción.

Las jornadas de trabajo más largas entre los preparadores de comida rápida las experimentan los que trabajan en establecimientos, pues 64.8% laboran más de 35 horas a la semana. En el caso de los que preparan y venden alimentos en forma ambulante, 57.4% laboran más de 35 horas a la semana y 42.6% menos de 35 horas a la semana.

Los preparadores de comida rápida ganan en promedio 32 pesos por hora trabajada. Entre los que la preparan en establecimientos el promedio es de 30.8 pesos y para los que lo hacen en forma ambulante es de 33.5 pesos por hora. Si se toma en consideración el nivel de ingresos por salario mínimo3 mensual que perciben las personas con estas ocupaciones, destaca que de cada 100 de estos ocupados, 60 ganan entre uno y dos salarios mínimos y nueve no perciben ingresos.
La investigación que se lleva a cabo en México por parte de [Mercawise](https://www.mercawise.com/estudios-de-mercado-en-mexico/encuesta-sobre-comida-rapida
), nos permite dirigir nuestros esfuerzos a lo que realmente están pidiendo de igual forma los clientes.
En esta investigación se muestra gráficamente lo siguiente:
- De una muestra de 100 encuestados de la república mexicana con un rango de edades de 25-34 años son los usuarios que más consumen comida rápida.
- En un 47% gasta de presupuesto en comida rápida de $100 a $200 pesos. 
- En un 82% de los encuestados valoran más la calidad en los alimentos en los establecimientos de comida rápida, apariencia del lugar en segundo lugar y la rapidez en el servicio como tercer lugar.

![encuesta](https://i.ibb.co/9w09bYy/muestra.jpg)
![encuesta](https://i.ibb.co/VJfTKLK/fracuencia.jpg)
![encuesta](https://i.ibb.co/ScwWWzj/presu.jpg)
![encuesta](https://i.ibb.co/9t4B3QP/valoran.jpg)
![encuesta](https://i.ibb.co/9gWP9K7/cadena-fav.jpg)

Por lo cual elegimos generar un modelo de negocio en el cual tengamos contacto aún con los clientes ya que a pesar de que valoran la rapidez también nos dimos cuenta que requieren al menos una atención personalizada entonces buscamos un modelo de negocio como mencionamos en nuestro objetivo general accesible.

Para  nuestra investigación se obtienen los requerimientos tanto de la curricula de UX tanto de la de Front end para poder relacionar todos los requerimientos:

### Requerimientos

Entender cómo se realizan los pedidos en un restaurante similar a BQ y cuáles son las necesidades del personal de cocina y del personal de atención al público (meser@s y cajer@s).
Ideal si dentro de la investigación toman fotos de las formas en que se toman pedidos actualmente.
Diseñar la versión para tablets de esta aplicación, teniendo en cuenta el modo de uso de esta tablet (por ej. El uso de la pantalla táctil) y los distintos tipos de usuarios.
El diseño se debe adaptar a dos tamaños de tablets 9.7 y 7 pulgadas.
Crear un ícono para poder agregar la pantalla al home de la tablet. Puedes usar appicon y agregar las especificaciones para el equipo de desarrollo.
El estado actual del pedido siempre visible mientras tomamos un pedido.
Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
Testear e iterar los diseños con personal de restaurantes similares a BQ.
Entregar las especificaciones de diseño al equipo de desarrollo en Figma, Zeplin ó XD.

### UI

#### Hito 1: Tomar pedidos

* Ingresar nombre del cliente.
* Filtrar _menú_ por _desayuno_ y _resto del día_.
* Agregar ítem al pedido.
* Eliminar ítem del pedido.
* Mostrar _resumen_ de pedido con todos los items y el total.
* Enviar a cocina (esto debe guardar el pedido).

#### Hito 2: Ver/atender pedidos

* Vista de pedidos pendientes
* Marcar pedido como listo
* Ver historial de pedidos

#### Hito 3: Autenticación

* Inicio de sesión
* Restaurar contraseña

### UX

Entender cómo se realizan los pedidos en un restaurante similar a BQ y cuáles son las necesidades del personal de cocina y del personal de atención al público (meser@s y cajer@s).
Ideal si dentro de la investigación toman fotos de las formas en que se toman pedidos actualmente.
Diseñar la versión para tablets de esta aplicación, teniendo en cuenta el modo de uso de esta tablet (por ej. El uso de la pantalla táctil) y los distintos tipos de usuarios.
El diseño se debe adaptar a dos tamaños de tablets 9.7 y 7 pulgadas.
Crear un ícono para poder agregar la pantalla al home de la tablet. Puedes usar appicon y agregar las especificaciones para el equipo de desarrollo.
El estado actual del pedido siempre visible mientras tomamos un pedido.
Necesitamos hacer una web app, así será accesible y funcionará bien en tablets iOS y Android.
Testear e iterar los diseños con personal de restaurantes similares a BQ.
Entregar las especificaciones de diseño al equipo de desarrollo en Figma, Zeplin ó XD.

* Debe **verse bien y funcionar bien en tablets**.
* **No queremos una app nativa**, sino una web app que se pueda _agregar a la
  pantalla de inicio_ como PWA.
* Queremos botones grandes para fácil uso en pantallas táctiles (touch screens).
* Queremos el estado actual del pedido siempre visible mientras tomamos un
  pedido.
* Queremos que sea accesible y que funcione bien en tablets iOS y Android.


## Problema

Para poder elegir entre las muchas problemáticas que existen dentro de un restaurante de cómida rápida tuvimos que realizar una entrevista a profundidad a una joven de 26 años que trabajó en Domino’s, ella nos dio todos sus puntos de vista y así elegimos una problemática clara. Utilizamos la herramienta de Empathy Map para poder ver los pains y gains del sistema que ella controlaba así como las emociones que tenía en su trabajo.

![problema](https://i.ibb.co/2nMXwKL/empathy-map.jpg)

Algunos de los problemas que pudimos ver con Daniela fueron los siguientes:

- La falta de capacitación laboral por parte de la empresa hizo que Daniela aprendiera a prueba y error.
- Los botones en el sistema eran confusos, ya que explicaba que cuando era para repartir o para comer en el lugar no estaban bien especificados.
- La cancelación del pedido era complicada, y por la indecisión del cliente por política se cobraba al mesero.
- No estaban actualizadas las promociones, ni había filtros para encontrarlas por lo cual era muy complicado y tardado llegar a la promoción.
- El sistema estaba en ingles por lo que era complicado para ella entender.
-Así como era una molestia para el que atendía como para el cliente que no se sabía si habían ciertos ingredientes sino hasta que se hacía el pedido en cocina.

## Objetivos

**General**
Realizar un MVP de Android y IOS basada en la accesibilidad: perceptibilidad, operatividad, simplicidad e indulgencia, creado para los meseros teniendo en cuenta a los demás stakeholders.

**Específicos**
- Realizar research para analizar correctamente la data para obtener el problema verdadero
- Tener el conocimiento que nos permita implementar un prototipo de alta fidelidad para nuestro usuario principal.
- Se pretende testear el prototipo de baja fidelidad para agregar al de alta todas las cualidades exigidas por el usuario.


## Stakeholders

Para poder revisar el panorama actual de un empleado de comida rápida tuvimos que investigar su entorno y con quien se rodea, por lo cual utilizamos la herramienta de stakeholders map para que cualquier movimiento que generamos en el prototipo e incluyamos la interacción de igual forma con los demás personajes.

![stakeholders](https://i.ibb.co/Ky1DHwS/stakeholdermap.png)

### Visitas de campo
Logramos obtener información a través de nuestra entrevista con Daniela ella nos dio los siguientes datos:

PAINS:
- No se les da ticket a los clientes
- Tiene demasiados botones
- No tiene filtros
- Promociones desordenadas
- Sin actualización de promociones
- Las promos se tienen que recordar ya que son con código.
- No hay avisos del área de cocina si no hay algún ingrediente
- Para cancelar un producto que no requiere el cliente es un problema el trámite.
- Para llenar la dirección del cliente se confunde mucho.
- La capacitación es a prueba y error.
- Muchos procesos se delegan al gerente 
- No hay estructura en pedidos ni tiempos

GAINS:
- Que se acomoden los botones en secciones
- Botones de diferentes colores
- Postres ordenados
- Todo en español
- Promos en existencia
- Capacitación divertida 
 
### KPI’S Cuantitativos
Para poder realizar una medición correcta de nuestra interfaz tenemos que testearla con usuarios clave, por ellos se realizó una prueba de usabilidad y se midió el tiempo en que se finaliza la tarea principal que es “Realizar un pedido”. 



### Insights

El encargado de barra desea una web app que genere de forma rápida y ágil su proceso de pedido porque indica que cuando tiene que modificar algún pedido por indecisión de sus clientes, pierde tiempo llamando al gerente, por lo cual decidimos agregar un formulario que apareciera de menu y que así se tomara mucho menos tiempo el usuario de nuestra app en registrar y además agregamos el botón de eliminar y editar para que ellos tengan la facilidad de hacer bien las cosas, recordando la seguridad a nuestro gerente de que no se podrá hacer ningún fraude ya que todo movimiento que realice el empleado estará monitoreado.

El encargado de barra necesita revisar las promociones en tiempo y forma, así como poder filtrar esto ya que nos comenta que es muy difícil encontrar una promo si es que el establecimiento tiene muchas promociones y no genera una actualización correcta. Por esto decidimos ingresar en nuestra web app un apartado sólo para promociones y se puedan agregar al pedido, y filtre por nombre de promoción.

El encargado de barra nos menciona que le urge hacer un corte de caja rápido y sin problemas con el gerente, por lo cual se genera un apartado para que al finalizar la jornada de trabajo el empleado pueda realizar el cierre con la información que ya se registró durante el día.

El encargado de barra nos menciona que sus compañeros que van iniciando tienen problemas con la capacitación ya que no hay como tal ellos aprenden con el método de prueba y error, así que para que ellos no fallen y puedan estudiar mientras se trabaja les agregamos el manual de procedimientos para que ellos realicen correctamente su trabajo.

### Benchmark

Aplicaciones para realizar pedidos en restaurantes de comida rápida: Teniendo conocimiento acerca de la competencia podemos hacer una medición de lo que les resulta más valioso a nuestros clientes.


![benchmark](https://i.ibb.co/ChdQpyj/benchmark.jpg)

Nos percatamos de que muchos de los inconvenientes que se tenían en otras cadenas de comida rápida tenían los mismos errores en sus sistemas.


## Retos de Diseño



1.       La primera propuesta se da con la intención de cumplir la necesidad principal de nuestro cliente que es la generación de pedidos. 
2.       El segundo reto será lograr que nuestro usuario pueda registrar todos sus pedidos para que cuando finalice su jornada laboral únicamente de clic a un botón para que envíe su información.
3.  El siguiente reto será que a partir de una categoría de promociones se puedan filtrar y encontrar mucho más rápido la promoción que se desea ingresar en el pedido.
 
4.       El cuarto reto será que nuestro cliente pueda modificar y eliminar de su pedido algún producto que el cliente ya no desee.

**Argumentos de los retos de diseño:**
- Algo que pudimos notar con nuestros KPIS es que muchos de los productos que se ofrecen son similares y no resuelven el generar el pedido de forma más ágil.
-  
### Diagrama de Flujos

El diagrama de flujos inicial fue el siguiente:


![diagrama de flujos]()

## Prototipo de Alta Fidelidad
