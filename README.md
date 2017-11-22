# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/lyft.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto:

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza la tipografía `Montserrat`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes:

  - Botones, hover: `#FF00BF`
  - Fondo de `footer`: `#333447`
  - Título del formulario: `#352384`
  - Texto del formulario: `#728099`
  - Gradiente morado: `linear-gradient(#76278F, #2B1E66);`

* Para el footer, deberás tomar en cuenta que tiene un hover y se ve como en la
  siguiente imagen:

  ![Lyft - Footer](docs/footer.gif)

  Además, los íconos deberás obtenerlo de `Icomoon`.

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios, videos de Youtube). No te preocupes, estamos seguros
  que los afrontarás con éxito, de igual forma aquí unos tips:

  - Estos son los videos de Youtube:
    * https://www.youtube.com/watch?v=fLSmUWOYpKw
    * https://www.youtube.com/watch?v=V7j8Aqxmbs8
    * https://www.youtube.com/watch?v=xj2VWLV0xCU
  - Para agregar los videos, averigua sobre la etiqueta `iframe`.
  - Para el formulario, revisa las etiquetas como `form` e `input`.

* Puedes ver el [sitio original](https://www.lyft.com/), sin embargo, su diseño
  ya ha cambiado en ciertas partes, así que tu fuente de verdad es la imagen que
  muestra el objetivo de este reto.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Estructura de carpetas y archivos
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible

## Instrucciones

1.- Escribir nuestro código en un bloque principal, este se llamará: claas: "all"
2.- En el boddy establecemos su background con el degradado proporcionado, esto para mejor manipulación.
3.- Para el menú principal, crearemos una lista horizontal, estará con posición fixed, esta pisición nos indica que el bloque donde nos movamos, nos mostrara el menú en la parte superior.
4.- Cada sección esta divida por bloques, en esta uilizamos 7, y el menú principal.
5.- En el form, solo se pide el número telefonico, indicado esto en nuestro código de html, se manipula los estilos en css para darle propiedades visuales a la páigina de lyft.
6.- Para los videos se copian los links de YT, de la parte "Insertar", se manipula el tamaño en html, para ajustarse a la pantalla, se acomoda con floats, junto con el texto.
7.- En el bloque final se almacenan listas ordenadas, imágenes de logos y otras redes sociales, en un contenedor para poder manipularlo correctamente, para que puedan estar alineados de forma horizontal, usamos inline-block,
    para los ultimos links, creamos una lista ordenada que dejaremos como lista vertical, cambiamos las propiedades de los bloques para que todos puedan estar alineados (son 4).
8.- Se insertan los logos, de las redes sociales:
    Para los logos se descargo de fontawesome la carpeta, se linkeo con el sitio original, se indico en nuestro documento la ruta y se copiaron los enlaces según la red social.
9.- Se establecen propiedades hover de los links en css.    
10.- Usamos un salto de linea al final, que vamos a modificar de igual forma en css.
