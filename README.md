# SASS
Proyecto creado a partir del crash course: https://www.youtube.com/watch?v=roywYSEPSvc

Desarrollado con Visual Studio Code, utilizando SASS.

## ¿Qué es SASS? 

SASS es un lenguaje que permite extender las características de CSS, aportando nuevas funcionalidades.
Para ello utiliza un preprocesador para CSS, que se encarga de generar código CSS a partir del lenguaje SASS.
De este modo, podemos crear estilos CSS utilizando estructuras de programación en lugar de reglas estáticas.

## ¿Cómo funciona?

Necesitaremos e instalamos un compilador, que realmente cambiará el código por código CSS. 
Creamos un HTML y le asociamos un archivo CSS que tendremos en otra carpeta.

La hoja de estilos .CSS no la editaremos, sino que se generará a partir de otro archivo que tendrá por extensión SCSS,
que será el que contendrá el código SASS.

## Ventajas ## 

Entre otras ventajas:
* Reduce la repetición de código CSS
* Permite crear hojas más compactas, manejables y reutilizables.
* Mejora el tiempo de desarrollo.

Cosas que podemos hacer:

## Creación de variables ## 

Podemos por un lado declarar variables, que pueden ser utilizadas en cualquier parte del documento.
```
$color-primario: #333;
body{
  color: color-primario
}
```

##  Anidación ## 
Los estilos se pueden anidar:
```
nav{
  ul{
    list-style: none;
  }
  
  a {
    display:block;
  }
}
```
## Mixins ## 

Se trata un conjunto de declaraciones CSS agrupadas que se pueden reutilizar en cualquier lugar del site.
También se les puede pasar parámetros.

## Partials ##

Es posible declarar parte de una hoja de estilos e incluirla en otras hojas.
Para ello podemos crear un fichero scss e importarlo desde otra hoja de estilos.

## Herencia ##

Podemos hacer que un estilo herede las características de otro y extenderlo a nuestro gusto,
añadiendo nuevas características o sobreescribiendo otras.

## Operadores ##

Es posible utilizar operadores numéricos dentro de los estilos para realizar diferentes cálculos.

##  Funciones de color ## 

Podemos trabajar sobre colores directamente, utilizando funciones como oscurecer, saturar, alfa, etc.
para, a partir de un color base, crear otro automáticamente.






