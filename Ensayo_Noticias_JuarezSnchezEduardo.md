Tecnológico Nacional de México. 

Campus Tláhuac. 

<a name="_page0_x77.00_y220.00"></a>Materia: Desarrollo FrondEnd 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.001.jpeg)

**Alumnos(s):** Juárez Sánchez Eduardo **Docente:** Cordero Ocampo Martin Ramon **Grupo:** 7s2 

**Fecha:** 08/04/2024 

**Carrera:** Ing. Sistemas Computacionales **Practica:** Programa WEB 

Contenido 

[Materia: Desarrollo FrondEnd.................................................................................................... 1 ](#_page0_x77.00_y220.00)[Resumen sobre la página web de noticias "NotiNovedades" ................................................. 3 ](#_page2_x77.00_y67.00)[Introduccion ........................................................................................................................... 4 ](#_page3_x77.00_y67.00)[Cuerpo .................................................................................................................................. 5 ](#_page4_x77.00_y73.00)[Árbol de desarrollo ............................................................................................................. 5 ](#_page4_x77.00_y105.00)[App.css .............................................................................................................................. 6 ](#_page5_x77.00_y81.00)[Pagina ............................................................................................................................... 7 ](#_page6_x77.00_y67.00)[Conclusión. ......................................................................................................................... 12 ](#_page11_x77.00_y67.00)[Referencias ......................................................................................................................... 12 ](#_page11_x77.00_y185.00)

<a name="_page2_x77.00_y67.00"></a>Resumen sobre la página web de noticias "NotiNovedades" 

"NotiNovedades" es una plataforma en línea dedicada exclusivamente a ofrecer noticias de diversos temas de manera rápida y accesible. Con un enfoque en la actualidad y la relevancia de la información, la página proporciona una interfaz intuitiva que permite a los usuarios acceder a una amplia gama de noticias de interés general. Los usuarios podrán explorar noticias según la categoría, la ubicación y la relevancia del tema. La plataforma ofrece una experiencia de lectura sin complicaciones, permitiendo a los usuarios encontrar información relevante de manera rápida y eficiente. Además de la función básica de presentar noticias, "NotiNovedades" se compromete a garantizar la confidencialidad y la seguridad de la información del usuario. Se implementarán medidas de protección de datos para salvaguardar la privacidad de los usuarios en todo momento. Con un diseño moderno y una navegación intuitiva, "NotiNovedades" tiene como objetivo proporcionar una experiencia informativa sin contratiempos para los usuarios interesados en mantenerse al día con las últimas novedades. La página se convertirá en un recurso confiable para aquellos que desean acceder a noticias de manera eficiente y conveniente. 

<a name="_page3_x77.00_y67.00"></a>Introduccion 

Bienvenido a "NotiNovedades Actuales", tu plataforma en línea dedicada exclusivamente a mantenerte al día con las últimas noticias de diversos temas. En un mundo donde la información es crucial y estar informado es esencial, entendemos la importancia de brindar una solución eficiente y accesible para acceder a las noticias que necesitas. 

En "NotiNovedades Actuales", hemos creado una experiencia de lectura diseñada para adaptarse a tu estilo de vida ocupado. Ya no tendrás que buscar en múltiples sitios web o revisar largas listas de noticias. Con nuestra plataforma intuitiva y fácil de usar, puedes explorar, seleccionar y leer noticias relevantes con solo unos pocos clics. 

Nuestro objetivo es ofrecerte más que solo un lugar para leer noticias. Nos esforzamos por proporcionarte un espacio donde puedas mantenerte informado de manera rápida y segura, sin sacrificar la calidad de la información. En "NotiNovedades Actuales", priorizamos tu comodidad y bienestar, asegurándonos de que tu experiencia de lectura sea lo más fluida y sin estrés posible. 

Ya sea que estés interesado en noticias de tecnología, política, deportes o cultura, estamos aquí para ayudarte a encontrar la información que necesitas, en el momento y lugar que mejor te convenga. Confía en nosotros para hacer que mantenerte al día con las noticias sea una tarea sencilla y sin complicaciones. 

Únete a nosotros en "NotiNovedades Actuales" y descubre una nueva forma de acceder a las noticias: conveniente, eficiente y centrada en ti. Mantenerte informado es nuestra prioridad, y estamos aquí para apoyarte en cada paso del camino. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.002.jpeg)

<a name="_page4_x77.00_y73.00"></a>Cuerpo 

<a name="_page4_x77.00_y105.00"></a>Árbol de desarrollo. 

En esta captura Podemos observar todos los archivos que se requieren, para el funcionamiento del proyecto. Como parte fundamental, se encuentra la carpeta “components” la cual aloja todos los componentes del proyecto los cuales aportan la estructura y distribución de la página web. ![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.003.png)![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.004.png)

<a name="_page5_x77.00_y81.00"></a>App.css 

El archivo App.css en programación, específicamente en el contexto de desarrollo web utilizando tecnologías como HTML, CSS y JavaScript, es un archivo que se utiliza para definir estilos CSS específicos para una aplicación web en particular. 

En el desarrollo de aplicaciones web modernas, especialmente aquellas creadas utilizando frameworks como React.js, Vue.js, Angular, etc., es común estructurar el código CSS en archivos separados para mantener la organización y la modularidad del código. El archivo App.css suele ser el lugar donde se definen estilos generales para la aplicación, como la apariencia de los componentes principales, estilos de diseño de página, colores comunes, fuentes, márgenes y paddings estándar, entre otros. 

Separar los estilos en archivos CSS individuales permite una mejor organización del código, facilita la reutilización de estilos entre componentes y ayuda a mantener un código más limpio y mantenible. Además, el archivo App.css generalmente se importa en el archivo principal de la aplicación (por ejemplo, index.js o App.js en el caso de React.js) para que los estilos definidos allí se apliquen a toda la aplicación. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.005.jpeg)

Imagen 1.1 importación de componentes

<a name="_page6_x77.00_y67.00"></a>Pagina 

Este código define un componente de React llamado  NewContainer . Este componente representa un contenedor de artículos de noticias y está compuesto por tres instancias del componente  NewArticle , cada una con su propio título y texto de noticia. El contenedor está diseñado para mostrar los artículos de noticias con un estilo específico, incluyendo un fondo oscuro, texto en color claro y un título destacado en color naranja suave. Cada artículo de noticia dentro del contenedor está encapsulado en un componente  NewArticle , el cual se importa desde otro archivo llamado  NewArticle.js . Este código demuestra cómo organizar y presentar una lista de artículos de noticias dentro de una interfaz de usuario de React. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.006.jpeg)

Imagen 1.2 Contenedor de articulo noticias 

Este código define un componente de React llamado  NewArticle , el cual recibe dos propiedades ( title  y  text ). Este componente representa un artículo de noticia individual y está compuesto por un título ( <h2> ) y un párrafo de texto ( <p> ). El título y el texto del artículo se insertan dinámicamente utilizando las propiedades recibidas. El artículo tiene un estilo específico, incluyendo una altura fija, un borde inferior de 2 píxeles de ancho en un tono de gris azulado y un margen inferior para separar visualmente los artículos. Además, el título del artículo tiene estilos adicionales que cambian el color del texto cuando se pasa el cursor sobre él. Este componente está diseñado para ser reutilizable y se puede utilizar dentro de otros componentes de React, como en el  NewContainer  mencionado anteriormente, para representar cada artículo de noticias de manera individual. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.007.jpeg)

Imagen 1.3  

Este código define un componente de React llamado  NavBar . Este componente representa la barra de navegación de una aplicación web y está compuesto por una lista de elementos  <li>  que contienen enlaces  <a>  a diferentes secciones de la página, como "Home", "New", "Popular", "Trending" y "Categories". Los estilos y la disposición de la barra de navegación están definidos en el código CSS mediante clases de Tailwind CSS, como  hidden ,  sm:flex ,  text-[18px] ,  sm:w- [438px] ,  sm:place-content-around ,  sm:text-[16px] , y  sm:items-center , entre otros. 

Además de la lista de enlaces, hay una imagen ( <img> ) que representa un ícono de menú de hamburguesa. Esta imagen se importa desde el archivo  icon- menu.svg  ubicado en el directorio de activos ( ../assets/images/ ) y se muestra solo en dispositivos pequeños ( sm:hidden ), lo que sugiere que se trata de un ícono de menú desplegable para dispositivos móviles. 

En resumen, el componente  NavBar  muestra una barra de navegación con enlaces a diferentes secciones de la página y un ícono de menú de hamburguesa en dispositivos móviles para una navegación más intuitiva. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.008.jpeg)

Imagen 1.4 Creación del icono menu 

Este código define un componente de React llamado  MainArticle . Este componente representa el artículo principal de una página web y está compuesto por una imagen y un contenido relacionado. 

La imagen del artículo principal se carga dinámicamente dependiendo del ancho de la pantalla del dispositivo. Se importan dos imágenes diferentes: una para dispositivos móviles ( imageMobile ) y otra para dispositivos de escritorio 

( imageDesktop ). Dentro de un elemento  <picture> , se utilizan las etiquetas 

` `<source>  para definir las imágenes de acuerdo con el ancho de la pantalla del dispositivo. Esto garantiza que se muestre la imagen más adecuada según el dispositivo del usuario. 

Después de la imagen, hay un contenedor  <div>  con dos columnas ( sm:flex ), una para el título y otra para el contenido del artículo. En la columna del título 

( flex-1 py-6 ), se muestra un título ( <h2> ) con estilos de tamaño de fuente grandes y negrita. En la otra columna ( flex-1 ), se muestra un párrafo de texto ( <p> ) que describe el contenido del artículo y un botón ( <button> ) para leer más. 

En resumen, el componente  MainArticle  muestra el artículo principal de una página web, adaptando la imagen y el contenido según el dispositivo del usuario para proporcionar una experiencia de usuario óptima. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.009.jpeg)

Imagen 1.5 Carga dinámica de la imagen. 

Este código define un componente de React llamado  Header . Este componente representa la cabecera de una página web y está compuesto por dos elementos principales: un logo y la barra de navegación ( NavBar ). 

El logo se importa desde el archivo  logo.svg  ubicado en el directorio de activos 

( ../assets/images/ ). Se muestra como una imagen utilizando la etiqueta  <img>  con el atributo  src  que hace referencia al archivo de imagen y el atributo  alt  que proporciona un texto alternativo para accesibilidad. 

La barra de navegación se incluye utilizando el componente  NavBar , que se importa desde el archivo  NavBar.js . Este componente define la estructura y el contenido de la barra de navegación, incluyendo enlaces a diferentes secciones de la página. 

En conjunto, el componente  Header  organiza el logo y la barra de navegación en una estructura de cabecera ( <header> ) utilizando flexbox para alinearlos horizontalmente y proporcionar un margen inferior ( mb-8 ) para separar la cabecera del contenido principal de la página. 

![](Aspose.Words.0e59ff1f-4998-4416-9499-d1f30061755b.010.png)

Imagen 1.5 Carga dinámica de la imagen. 

<a name="_page11_x77.00_y67.00"></a>Conclusión. 

En resumen, la aplicación web está diseñada para ofrecer una experiencia de usuario completa, que incluye navegación intuitiva, acceso rápido a noticias relevantes y contenido destacado de manera eficiente, adaptándose a diferentes dispositivos para garantizar una experiencia óptima para todos los usuarios 

<a name="_page11_x77.00_y185.00"></a>Referencias 

React: APRENDE a hacer esta página usando REACT + Tailwind.( 22 jun 2023) Recuperado 18 de Marzo del 2024. [https://www.youtube.com/watch?v=UMVb8b_VJwo&ab_channel=CodingTube ](https://www.youtube.com/watch?v=UMVb8b_VJwo&ab_channel=CodingTube)

React: APRENDE a hacer esta página usando REACT + Tailwind Pt2.( 29 jun 2023) Recuperado 18 de Marzo del 2024. [https://www.youtube.com/watch?v=S-7ojizDxdw&t=595s&ab_channel=CodingTube ](https://www.youtube.com/watch?v=S-7ojizDxdw&t=595s&ab_channel=CodingTube)
