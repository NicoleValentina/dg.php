# PHP

### Introducción

PHP es un lenguaje de programación de código abierto, [nacido para-](http://php.net/manual/es/history.php.php) y [usado en](http://spectrum.ieee.org/computing/software/the-2016-top-programming-languages) el desarrollo de sitios web de contenido dinámico. 

PHP se ejecuta del lado del servidor, afectando al documento completo antes de que éste sea enviado al [cliente](https://es.wikipedia.org/wiki/Cliente_(inform%C3%A1tica)). Esta es su principal diferencia con JavaScript, que se ejecuta del lado del [cliente](https://es.wikipedia.org/wiki/Cliente_(inform%C3%A1tica)), afectando al [DOM](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n#DOM_y_JavaScript).

Como PHP se ejecuta [del lado del servidor](https://es.wikipedia.org/wiki/Script_del_lado_del_servidor): Nunca aparece al “ver código fuente”, ni en la consola (no existe una Consola de PHP en los navegadores). Por eso, para compartir tus script en PHP puedes usar servicios como [codepad](http://codepad.org/)… Y para resolver muchas dudas existe [Stackoverflow](http://stackoverflow.com/questions/tagged/php), además del sitio con [referencias oficiales de PHP](http://php.net/manual/es/langref.php).

Para que se ejecute PHP, en esta clase **deben tener instalado [MAMP](https://www.mamp.info/en/) en sus computadores**. Ese programa nos permite montar un servidor local, para trabajar con **Apache** (servidor HTTP), **MySQL** (sistema de gestión de bases de datos) y **PHP** (lenguaje de programación).

Para trabajar con PHP debemos usar documentos con extensión `*.php`, los que se pueden crear de la misma manera que normalmente se crean los documentos `*.html`: trabajando con cualquier editor de código.

Dentro de los documentos con extensión `*.php` tenemos que usar etiquetas de apertura y cierre particulares, que son `<?php` y `?>` (las instrucciones que estén entre estas etiquetas serán filtradas e interpretadas en el [servidor](https://es.wikipedia.org/wiki/Servidor)).

Entre `<?php` y `?>` se pueden escribir una o varias instrucciones. Si se escriben varias, éstas deben separarse mediante punto y coma `;`. Y si necesitan escribir comentarios de una línea, deben anteponer un doble slash `//`. Por ejemplo: 

```
<?php 
//primero defino una variable
$inception = "película escrita, producida y dirigida por Christopher Nolan ";
//luego imprimo el contenido de la variable
print $inception;
?>
```

Como notaron en el ejemplo, las variables en PHP se declaran con un signo peso pegado al nombre de la variable. Será muy necesario poner atención a esta y otras [diferencias de PHP con JavaScript](http://profesor.faco.cl/diferencias.php).
