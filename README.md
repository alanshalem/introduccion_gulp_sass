# SASS Y GULP

## QUE ES GULP?

> Gulp automatiza Tareas en JavaScript

Gulp nos permitirá automatizar tareas que son repetitivas en Desarrollo Web tales como:

- Compilar SASS y JavaScript
- Crear Imágenes mas ligeras o la versión webp
- Minificar y mejorar nuestro código para producción.

## QUE SE REQUIERE PARA UTILIZAR GULP?

> Node.js y NPM

- GULP UTILIZA JAVASCRIPT
- GULP UTILIZA PIPES -> Un pipe es una acción que se ejecuta, una vez finalizada se ejecuta otra y otra; el orden en que se ejecutan es definido por ese pipe.

LINK GULP: https://gulpjs.com/
LINK NODEJS: https://nodejs.org/es/download/

---

---

## QUE ES SASS?

> SASS es CSS con Superpoderes

-`SASS = Syntactically Awesome StyleSheet`.
-SASS ofrece muchas opciones que CSS no ofrece.
-Se le considera un estándar de la industria (LESS ya no se utiliza tanto hoy en día).
-Compatible con muchos frameworks CSS.

## VENTAJAS DE SASS

-Mejor orden y estructura
Características que no existen en CSS o con mejor soporte

- Soporta código CSS
- Menos Código ya que utiliza algo llamado "anidación"

## DESVENTAJAS DE SASS

-Una nueva sintaxis por aprender.

- Se debe compilar con una herramienta especial, no es nativo en el navegador.
- La anidacion puede causar problemas

## SINTAXIS DE SASS

-Variables:

    $color: #e1e1e1;
    $separacion: 5rem;
    $fuente: Arial, Helvetica;

-Anidación

    div
    	display: flex
    	h1
    		margin-top: 10rem;
    	p
    		margin-top: 10rem;

Extension de archivos SASS (.sass) ❌

    .header
    	display: flex;
    	.logo
    		margin-top: 10rem;

Extension de archivos SCSS (.scss) ✔️

    .header{
    	display: flex;
    	.logo{
    		margin-top: 10rem;
    	}
    }

## SASS se compila

No es soportado nativamente por el navegador, por lo tanto deberá ser compilado a un archivo .css
Para compilarlo existen diferentes opciones siendo webpack y Gulp las mas populares.
