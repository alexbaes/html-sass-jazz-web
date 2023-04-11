# JazzMusicWeb :computer:

## Descripción
Este repositorio consiste en una práctica realizada durante el Master de Desarrollo de Aplicaciones y Sitios Web de la UOC, correspondiente a la asignatura de Herramientas HTML y CSS. 
El sitio se creó a partir de UOC Boilerplate, una plantilla de HTML y CSS. Su objetivo es proporcionar un paquete básico y moderno de desarrollo web frontend basado en Parcel e que incluye un compilador Sass, un transpilador ES6, minificadores, un transformador de imágenes y herramientas de desarrollo. Esta es la versión 3.x del Boilerplate de la UOC, disponible desde el semestre UOC 2020-2.
<br><br>
Los objetivos de la práctica eran:
* Desarrollar un sitio web responsive con HTML5 y CSS3
* Familiarizarse con el uso de la terminal (se utilizó Ubuntu en un sistema Windows).
* Aprender a instalar NPM y NodeJs.
* Conocer Parcel
* Familiarizarse con Github
* Aprender a validar el código HTML y CSS (Validator.w3.org)
* Analizar el rednimiento del sitio web (Google Page Speed).

## Autor
**Àlex Barberà Escribà**

* [LinkedIn](https://linkedin.com/in/alexbaes)

## Ver ejemplo en vivo
- [Jazz Music Web](https://gentlejazz.netlify.app/)

## Instalación
El proyecto requiere tener instalado [Node.js](http://nodejs.org/) >= 14.15.x
Clone este repositorio con `git clone`, o descargue un archivo .zip usando el botón verde superior derecho.
Usando la Terminal, navegue a la carpeta del proyecto y ejecute `npm install`.

## Características
* Utiliza el paquete de módulos [Parcel v2](https://v2.parceljs.org).
* Secuencias de comandos de NPM para un rápido desarrollo y creación de producción (ver Comandos a continuación).

### Hojas de estilo

* [Sass/SCSS](https://sass-lang.com) para la compilación de CSS.
* Características de [PostCSS](https://postcss.org/):
     * Transpilar CSS moderno con [`postcss-preset-env`](https://preset-env.cssdb.org/features).
     * Agregue automáticamente el prefijo CSS a las propiedades no compatibles con [`autoprefixer`] (https://autoprefixer.github.io/).
     * Minimice y optimice automáticamente el código CSS en la compilación de producción con `@parcel/optimizer-cssnano`.

### Scripts

* Permitir JavaScript moderno (ES201x/ES8/ES7/ES6…) que se transpila automáticamente a ES5 y se minimiza en compilaciones de producción, con [Babel](https://babeljs.io/).

### Imágenes

* Transformación de imágenes con [`@parcel/transformer-image`](https://v2.parceljs.org/recipes/image/) (basado en [`sharp`](https://sharp.pixelplumbing.com/) ). No lo use en esta versión, ya que puede causar fallas en las implementaciones de Netlify.

## Cómo usar este proyecto

El contenido se encuentra dentro de la carpeta `src/`. Si no desea cambiar la configuración o no está seguro de lo que está haciendo, no edite archivos fuera de la carpeta `src/`.

Ejecute siempre los siguientes comandos durante la etapa de desarrollo y para compilaciones de producción. Tenga en cuenta que se espera que todos los proyectos creados con este modelo se compilen usando `npm run build` antes de publicarse.

### Comandos

| Comando | Descripción |
|---------|-------------|
| `npm run dev` | Ejecuta un servidor web local para el desarrollo y abre el navegador para mostrarlo. Compila automáticamente estilos y scripts cada vez que se cambia un archivo en `src/` y vuelve a cargar el navegador en vivo. Esto es lo que *debe ejecutarse* en la etapa de desarrollo. |
| `npm run compilación` | Compila, minimiza y optimiza los archivos en la carpeta de activos. Los archivos compilados y optimizados generados se encuentran en la carpeta `dist/`. Esto es lo que *debe ejecutarse* antes de publicar el proyecto. Este es también el comando de compilación que ejecutarán los servicios de implementación externos, como Netlify. Los archivos publicables se ubican en la carpeta `dist/`. |
| `npm run clean` | Elimina la carpeta actual `/dist` y las carpetas de caché. |
| `npm run test` | Muestra un mensaje de éxito si todo funciona como se esperaba. |

## Contactar
Si quieres contactar puedes escribirme a *alex@baesaudiovisual.com*



