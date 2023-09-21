# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

###### *Por Patricio Cifredo Reyes*

## 0. Introducción

El presente trabajo tiene como finalidad servir de introducción al área del Desarrollo Web en entornos de clientes. Para ello, realizaremos una investigación y estudio de sus conceptos básicos, sus principales modelos y de las distintas tecnologías y herramientas asociadas.

## 1. Modelos de la arquitectura Web

Según *García Escobedo (2012)*, los modelos de arquitecturas web establecen las relaciones existentes que se producen entre las diversas partes que componen las aplicaciones webs. 

Por tanto, es lógico pensar en que existirán diversas formas de que estos elementos se interrelacionen y es que desde los orígenes de las aplicaciones webs han ido apareciendo diversos enfoques. 

Algunos de ellos son:

* Aplicaciones de página única (SPA): Como bien indica *Vergara (2023)* en el portal *itdo.com*, las aplicaciones de una sola página (SPA) son aplicaciones webs que cargan un solo archivo HTML que luego va actualizando  de forma dinámica a medida que se usa la aplicación.
Un ejemplo de esto podría ser *Gmail* ya que en todo momento la web se va actualizando sin que salgamos de ella.

* Aplicaciones Web progresivas (PWA): Este tipo de webs utilizan distintas herramientas y tecnologías para replicar muchas de las funciones de aplicaciones. Se pueden instalar en el dispositivo deseado pero se accede a ellas a través de un navegador (aunque no es necesaria conexión para usarlas). Por tanto las PWA: "Difuminan la barrera entre la web y las aplicaciones, pudiendo realizar tareas que generalmente solo las aplicaciones nativas podían llevar a cabo." *Ramírez (2018)*. 

*Facebook*, podría considerarse una PWA, ya que podemos usarlo desde el navegador y en su versión web puede recibir notificaciones como si de la app nativa se tratase.

* Modelo Vista Controlador: Esta arquitectura se basa en tres componentes:
> + a) un Modelo, es decir, el gestor de la información según un esquema lógico
> + b) una Vista, que es la información que se muestra al usuaria/o 
> + c) un Controlador, que efectúa las peticiones al modelo según la interacción con la vista.


![Figura 1. Diagrama del Modelo Vista Controlador](https://codingornot.com/wp-content/uploads/2017/10/mvc-modelo-vista-controlador.png)
##### Figura 1. Diagrama del Modelo Vista Controlador. *García (2017) Copyright Miriam García/codingornot.com*

Una tecnología basada en este modelo es la herramienta *ASP.NET MVC Framework*

* Modelo Vista-modelo-de-Vista (MVVM): Al contrario que el modelo anterior este se basa en una separación de la interfaz gráfica de usuario de la lógica y servicio de la aplicación. Como bien indican al respecto en un artículo de 2023 de *Microsoft Learn*  esto facilita el desarrollo y mantenimiento de la web.
Algunos ejemplos de frameworks para el desarrollo de webs en modelo MVVM son *Angular, Aurelia, Jellyfish y Mvvmzero*.


Tamkbién existen los modelos por "capas". El *departamento de Informática de la Universidad de Valladolid* hace diferencia entre:

*Modelo de 2 capas: El cliente se comunica directamente con la base de datos pero asume el grueso del procesamiento y de la aplicación en su equipo (fat client). Las peticiones al servidor se hacen mediante SQL, que devolverá la información pertinente. También existe un enfoque *fat server* en el que el servidor es el que tiene el mayor peso de la aplicación, pero es menos común.

*Modelo de 3 capas: Este modelo es más reciente que el de dos capas y consiste en implementar una capa intermedia entre el cliente y el servidor de la aplicación, residiendo la información y los datos de la misma en otros servidores diferentes.

Es uno de los modelos más utilizados para el desarrollo web. Podemos suponer que una web moderna como *Amazon* se sustentará en él. Teniendo una parte fina de cliente que contiene su interfaz gráfica, un servidor de aplicación que contenga la lógica de compra-venta de la web y otros servidores a parte con toda la información de usuarios, transacciones, productos etc.

## 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web:

Para que un navegador ejecute un script de Javascript, debemos escribir el mismo en un archivo con extensión *js*, el cuál enlazaremos a un documento *html*, mediante la etiqueta "script", que luego abriremos con el navegador de preferencia. Veamos un ejemplo gráfico realizado en *VSCODE*.

![1695229466799](https://res.cloudinary.com/practicaldev/image/fetch/s--Kd_4bI3_--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/zbaylzi3lb2jpixr1epr.png)
##### Figura 2. Fotografía de un documento HTML con un archivo Javascript asociado mediante la etiqueta **script src=""**. Copyright de Gooding Hannah (2020), extraído de https://dev.to/hannahgooding/vs-code-shortcuts-and-tricks-that-i-wish-i-knew-sooner-3mcj


Aun así, es muy común que hoy en día los propios navegadores tengan integrados una consola para desarrolladoras y desarrolladores que permita usar y ejecutar JavaScript. Como se indica en la entrada *"Running JavaScript in the Browser Console"* (2023) de la web *codeacademy.com* , la consola permite ejecutar JS dentro de la página, modificar su estructura (DOM) y ver la información que el navegador recopile.


La mayoría de navegadores (*Chrome, firefox, Safari, Edge, Opera etc.*) son compatibles con alguna de las versiones de JavaScript. Aun así, la compatibilidad con ECMAScript 2021 (versión actual) y de sus APIs varia de uno a otro. Según *developer.mozilla.org* (2023) Firefox es uno de los navegadores con mejor implementación de las APIs de JavasCript, tanto en android como en PC.

Una posible solución a la hora de resolver problemas de compatibilidad JavaScript con el navegador deseado sería utilizar alguna herramienta de compilación/transpilación que nos "traduzca" nuestro script actual a la versión que necesitamos para nuestro navegador. 

Según la web *byby.dev (2023)* algunas de las opciones más pupulares son *Babel*, *Build* o *TypeScript.*

Si nos encontramos en el la fase de diseño y desarrollo de la misma, quizá sería más sensato usar recursos de JavaScript que sepamos que son soportados por el navegador en el que se van a usar. Para ello existen herramientas online como caniuse.com que nos permitirá saber qué navegadores aceptan determinada función.
Aun así, la mejor opción siempre será emplear frameworks que faciliten el desarrollo de un diseño compatible con varios navegadores. Entre los frameworks de JavaScript más conocidos encontramos algunos como  *React JS*, *Vue JS* o * Angular JS*.

## 3. Lenguajes de Programación en Entorno Cliente

https://blog.hubspot.es/website/que-es-desarrollo-web


## 7. Bibliografía

https://www.itdo.com/blog/pwa-vs-spa-cual-elegir/

https://www.xataka.com/basics/que-es-una-aplicacion-web-progresiva-o-pwa Ramírez 2018

https://codingornot.com/mvc-modelo-vista-controlador-que-es-y-para-que-sirve García 2017

https://learn.microsoft.com/es-es/dotnet/architecture/maui/mvvm

https://www.infor.uva.es/~fdiaz/sd/2005_06/doc/SD_TE02_20060305.pdf uni valladolid

https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs 

https://byby.dev/js-transpilers 

https://www.codecademy.com/article/running-javascript-in-the-browser-console

