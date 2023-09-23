---
marp: true
theme: gaia
---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)
# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente
#### *Patricio Cifredo*
###### 2º DAW IES Rafael Alberti, DWEC Proyecto 1

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

<style scoped>
{
  font-size: 25px
}
</style>

### ÍNDICE

1. Modelos de Programación en Entornos Cliente/Servidor

2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y         Limitaciones de Ejecución. Compatibilidad con Navegadores Web

3. Lenguajes de Programación en Entorno Cliente

4. Características de los Lenguajes de Script. Ventajas y Desventajas

5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML

6. Herramientas de Programación

---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 1. Modelos de Programación en Entornos Cliente/Servidor

<style scoped>
{
  font-size: 28px
}
</style>


*Existen múltiples modelos de arquitecura web, entre ellos:*

* **Aplicaciones de página única (SPA)** &rarr; Un solo archivo HTML que se actualiza de forma dinámica

* **Aplicaciones Web progresivas (PWA)** &rarr; Se pueden instalar en el dispositivo como una app nativa, pero se accede a a través de un navegador 

*  **Modelo Vista Controlador (MVC)** &rarr; *Modelo* (esquema lógico),*Vista* (información que se muestra al usuario), *Controlador* (efectúa las peticiones)

* **Modelo Vista-modelo-de-Vista (MVVM**) &rarr; Separación de la interfaz gráfica de usuario respecto a la lógica y servicio de la aplicación.

---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 1. Modelos de Programación en Entornos Cliente/Servidor

<style scoped>
{
  font-size: 28px
}

img[alt~="center"] {
  display: block;
  margin: 0 auto;
}

</style>


Existen también los modelos por capas:

![width:600px height:350px center](https://upload.wikimedia.org/wikipedia/commons/e/ea/Tres_capas.PNG)


---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

<style scoped>
{
  font-size: 28px
}

img[alt~="center"] {
  display: block;
  margin: 0 auto;
}

</style>

##### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y       Limitaciones de Ejecución. Compatibilidad con Navegadores Web

Para ejecutar código *JavaScript* podemos:

* Enlazar un archivo HTML con uno JavaScript mediante la etiqueta ``` <script> ```
* Ejecutarlo directamente en la consola del navegador
![width:280px height:250px center](https://qph.cf2.quoracdn.net/main-qimg-8a5906cd9433e55b95b624f810604dfb-pjlq)

---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

<style scoped>
{
  font-size: 28px
}
</style>

##### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y       Limitaciones de Ejecución. Compatibilidad con Navegadores Web

* La mayoría de navegadores (**Chrome, firefox, Safari, Edge, Opera etc.**) son compatibles con alguna de las versiones de JavaScript.

* Aun así, la compatibilidad con **ECMAScript 2024** (versión actual) y de sus APIs varia de uno a otro. 

* Según developer.mozilla.org (2023), **Firefox** es uno de los navegadores con mejor implementación de las APIs de JavasCript (posible sesgo del estudio)

---

![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 3. Lenguajes de Programación en Entorno Cliente

<style scoped>
{
  font-size: 32px
}

</style>

Tres de los más usados son:

* JavaScript

* TypeScript

* Swift

Otros: VBScript. Y aunque más enfocados a back-end: Python, Ruby, Dardo y PHP

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 4. Características de los Lenguajes de Script. Ventajas 

<style scoped>
{
  font-size: 32px
}

</style>

Respecto a los lenguajes tradicionales tienen las siguientes ventajas:

*  Su uso es muy extendido (muchos recursos)
*  Ofrecen funciones y librerias (simplifican)
*  Reducen el número de errores en el código
*  Facilitan el desarrollo de grandes proyectos

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 4. Características de los Lenguajes de Script. Desentajas 

<style scoped>
{
  font-size: 32px
}

</style>

Por el contrario tienen las siguientes desventajas:

* El rendimiento y la velocidad de ejecución de los mismos es menor
* Suelen tener más problemas de compatibilidad
* Incapacidad de los lenguajes de scripts para desarrollar aplicaciones 

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML

<style scoped>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

![width:550px height:350px center](https://d8it4huxumps7.cloudfront.net/bites/wp-content/banners/2023/8/64dcc893c5140_html_vs_css.jpg?d=1200x800)

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

##### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML

<style scoped>
{
  font-size: 20px
}
</style>

Pequeño ejemplo de programa JavaScript ejecutado de dos formas diferentes:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
     <meta name="autor" content="Patricio">
    <title>Ejemplo del trabajo</title>
  </head>
  <body>
    <script src="ejemplo.js"></script>
  </body>
  <footer></footer>
</html>
```
![1695369461306](image/P1_CifredoReyesPatricio_DWEC/1695369461306.png)

---
![width:100px height:100px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

###### 6. Herramientas de Programación

<style scoped>
{
  font-size: 31px
}
</style>

* **Visual Studio Code (VS Code)**: Editor de texto con funciones de IDE gracias a la integración de extensiones que amplian sus funcionalidades

* **Github**: Basada en Git. Sirve a su vez como repositorio en la nube y como sistema de control de versiones

* **Chrome DevTools**: Conjunto de herramientas de desarrollo que están incluidas en el propio navegador
---
###### 6. Herramientas de Programación

<style scoped>
{
  font-size: 35px
}
</style>

* **React.js:** Librería JavaScript que "permite crear interfaces de usuario para aplicaciones webs a partir de componentes" (es.react.dev). Muy enfocada al desarrollo de SPA.


* **Bootstrap**: Framework de frontend basado en plantillas

* **Angular**: Framework de TypeScript. Angular permite la creación de PWA (páginas web progresivas), y por tanto multiplataforma, de forma rápida y sencilla a través de plantillas de código ya optimizadas.


---

<style scoped>
{
  color: #FFA500;
  text-align: center;
}
</style>

# ¡GRACIAS POR VUESTRA ATENCIÓN! 

![width:300px height:300px](https://iesrafaelalberti.es/wp-content/uploads/2021/11/imago-iesra-1.png)

---

# 8. Referencias e imágenes

<style scoped>
{
  font-size: 22px
}
</style>

Logo IES ALBERTI --> Copyright de IES RAFAEL ALBETI (Cádiz). Extraído de: https://iesrafaelalberti.es/ 

Foto Modelo por capas --> Copyright de William Fernando. Extraída de https://es.wikipedia.org/wiki/Arquitectura_multicapa#/media/Archivo:Tres_capas.PNG

Imagen consola Chrome --> Copyright Javier Revuelta. Extraída de https://es.quora.com/D%C3%B3nde-est%C3%A1-la-consola-de-Javascript-en-Google-Chrome

https://developer.mozilla.org/es/ 

Foto HTML VS CSS --> Copyright de unstop.com. Extraída de https://d8it4huxumps7.cloudfront.net/bites/wp-content/banners/2023/8/64dcc893c5140_html_vs_css.jpg?d=1200x800

developer.chrome.com (2016) 

es.react.dev