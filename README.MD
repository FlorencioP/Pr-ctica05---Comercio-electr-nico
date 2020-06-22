a.	Nombre de la base de datos (estructura de la base de datos)
La base de datos de nuestra pagina comercial esta bajo el nombre de “wordpress”, contiene un total de 55 tablas, a continuación, se muestra la estructura de las tablas más importantes.

wp_comments.
En esta tabla se guardan todos los comentarios realizados sobre nuestros productos.

![1](/READMEIMG/1.png?raw=true "Title")

wp_posts.
En esta tabla se guardan todos los posts realizados de la pagina.

![2](/READMEIMG/2.png?raw=true "Title")

wp_terms.
En esta tabla se guardan todas las etiquetas de nuestros productos.

![3](/READMEIMG/3.png?raw=true "Title")

wp_users.
En esta tabla se guardan los usuarios de nuestra página web.

![4](/READMEIMG/4.png?raw=true "Title")

wp_wc_order_stats.
Aquí se guarda la información de los pedidos realizados.

![5](/READMEIMG/5.png?raw=true "Title")

b.	El desarrollo de cada uno de los requerimientos antes descritos.
Luego de haber escogido un tema para la página, la creación del contenido de esta también es sencillo, para la creación de la paginas, basta con entrar a la pestaña de páginas que hay en WordPress, ahí se pueden crear y organizar las páginas. Empezamos primero con la página de “Conócenos” para añadir la información se tienen que ir añadiendo bloques, estos se parecen bastante las etiquetas que normalmente se usarían en HTML.

![6](/READMEIMG/6.png?raw=true "Title")

De ahí el desarrollo de la mayoría de los cuadros de información se basa en crear un header y luego poner un párrafo de información, de ahí destacan 2 cuadros: El de ubicación y el Formulario de contacto.

Para la ubicación se usó Google maps, al compartir la ubicación se puede seleccionar una salida de código la cual luego debe ser insertado en un cuadro de código que el WordPress ofrece.

![7](/READMEIMG/7.png?raw=true "Title")


Para el Cuadro de formulario se usó el plugin WPForms Lite.

![8](/READMEIMG/8.png?raw=true "Title")

Desde este plugin se puede crear una tabla y luego se la puede referenciar desde un cuadro de texto al editar la página.

![9](/READMEIMG/9.png?raw=true "Title")

Una vez se crea la tabla se hace click en incrustar y ahí se mostrará le código que referencia a esta tabla el cual luego se puede añadir en un cuadro de texto al editar la pagina para que esta aparezca ahí.

![10](/READMEIMG/10.png?raw=true "Title")

Para el ingreso de productos, seleccionamos la pestaña de productos y desde ahí se pueden manejar todos los platillos que estan ingresados y también da la posibilidad de agregar nuevos.

![11](/READMEIMG/11.png?raw=true "Title")

Para agregar a un producto dentro de una categoría se necesita crear una categoría y luego al estar creando un producto o editándolo simplemente marcar las categorías que el creador cree que es a la que pertenece el producto, estas categorías se pueden seleccionar desde un cuadro ubicado a la izquierda dentro del menú de creación/edición del producto.

![12](/READMEIMG/12.png?raw=true "Title")

Así que crearían los productos y se los clasificaría por categorías.

![13](/READMEIMG/13.png?raw=true "Title")

Para lo que viene siendo los productos más vendidos del negocio, El Plugin WooCommerce nos ayuda en este aspecto, basta con añadir un cuadro y seleccionar “Productos más vendidos” dentro de la pestaña de WooCommerce (En este caso se lo añadió a la página de inicio).

![14](/READMEIMG/14.png?raw=true "Title")

Lo mismo seria para mostrar los productos que estén actualmente en oferta.

![15](/READMEIMG/15.png?raw=true "Title")

Al momento de la compra, WooCommerce se encarga de verificar si se esta realizando la compra con un usuario registrado, en caso de que no lo esté el plugin impide la compra hasta que el usuario inicie sesión, para lograr esto se debe seleccionar los respectivos cuadros dentro de la pestaña de WooCommerce en ajustes.

![16](/READMEIMG/16.png?raw=true "Title")

Con esto se aplica en control necesario al momento de intentar comprar algo de la tienda.

Para poder desplegar la pagina se tuvo que comprar un dominio en internet (Para agilizar las cosas esta fue una decisión en grupo). El dominio conseguido está bajo el nombre de http://cisa.nuvarmi.club/ y para publicar la pagina en ese dominio se debe acceder al menú de ajustes e introducir la dirección ahí.

![17](/READMEIMG/17.png?raw=true "Title")

c.	La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cual, se puede generar fotografías instantáneas (pantallazos). 
Para lo que viene siendo el CSS, al utilizar WordPress se nos facilita la aplicación de un CSS, desde la pestaña de Apariencia se escogió usar Foody, ya que va con el tema de un restaurante.

![18](/READMEIMG/18.png?raw=true "Title")

Al aplicarse se tuvieron que hacer cambios en el CCS para poder lograr la apariencia de la página deseada, se tuvo que ingresar al editor de temas y realizar ahí los cambios necesarios. 

![19](/READMEIMG/19.png?raw=true "Title")

Así quedo la página de nuestro restaurante al final:

![20](/READMEIMG/20.png?raw=true "Title")

![21](/READMEIMG/21.png?raw=true "Title")

![22](/READMEIMG/22.png?raw=true "Title")

d.	La evidencia del correcto funcionamiento de cada uno de los puntos requeridos. 
Así se muestra la página de “Conócenos” (donde se encuentra toda la información requerida) luego de publicarla.

![23](/READMEIMG/23.png?raw=true "Title")

Así quedaría el posicionamiento de la tienda por medio de Google Maps:

![24](/READMEIMG/24.png?raw=true "Title")

Y por ultimo el Formulario de contacto, donde cualquier usuario pudiese comunicarse con nosotros independientemente si tiene cuenta registrada o no (Nota: El ingreso de un correo electrónico es obligatorio)

![25](/READMEIMG/25.png?raw=true "Title")

En la pestaña de menú se mostrarán todos los productos registrados y también sus categorías, el usuario puede ir seleccionando los productos que desea comprar desde aquí.

![26](/READMEIMG/26.png?raw=true "Title")

Al haber configurado los cuadros de texto con las opciones que da WooCommerce (En este caso, productos más vendidos y con descuento) a entrar a la página de inicio se muestran dichos productos.
Nota: La imagen a continuación tiene un zoom de 67%.

![27](/READMEIMG/27.png?raw=true "Title")

Y para finalizar, Se puede evidenciar desde el principio el funcionamiento de nuestro Domino:

![28](/READMEIMG/28.png?raw=true "Title")
