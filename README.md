# SASS
Proyecto creado a partir del crash course: https://www.youtube.com/watch?v=roywYSEPSvc

Desarrollado con Visual Studio Code, utilizando SASS.

SASS es un preprocesador para CSS desarrollado en 2007. Permite crear estilos CSS 
utilizando estructuras de programación en lugar de reglas estáticas.

Entre otras ventajas:
* Reduce la repetición de código CSS
* Permite crear hojas más compactas, manejables y reutilizables.
* Mejora el tiempo de desarrollo.

** Creación de variables** 

Podemos por un lado declarar variables, que pueden ser utilizadas en cualquier parte del documento.
```
$color-primario: #333;
body{
  color: color-primario
}
```

** Anidación **
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

Podemos crear mixins e importarlos en cualquier parte de la hoja.

## Partials ##

Es posible declarar parte de una hoja de estilos e incluirla en otras hojas.
Para ello podemos crear un fichero scss e importarlo desde otra hoja de estilos.

## Herencia ##

Podemos hacer que un estilo herede las características de otro y extenderlo a nuestro gusto,
añadiendo nuevas características o sobreescribiendo otras.

## Operadores ##

Es posible utilizar operadores numéricos dentro de los estilos para realizar diferentes cálculos.

** Funciones de color **

Podemos trabajar sobre colores directamente, utilizando funciones como oscurecer, saturar, alfa, etc.
para, a partir de un color base, crear otro automáticamente.

Instalamos un compilador, que realmente cambiará el código por código CSS. 

Creamos un HTML y le asociamos un archivo CSS que tendremos en otra carpeta.

La hoja de estilos CSS no la editaremos, sino que se generará a partir de otro archivo que tendrá por extensión SCSS.

Cosas que podemos hacer:




