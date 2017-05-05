# PHP

### Introducción

PHP es un lenguaje de programación de código abierto, [nacido para-](http://php.net/manual/es/history.php.php) y [usado en](http://spectrum.ieee.org/computing/software/the-2016-top-programming-languages) el desarrollo de sitios web de contenido dinámico. 

PHP se ejecuta del lado del servidor, afectando al documento completo antes de que éste sea enviado al cliente. Esta es su principal diferencia con JavaScript, que se ejecuta del lado del [cliente](https://es.wikipedia.org/wiki/Cliente_(inform%C3%A1tica)), afectando al [DOM](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n#DOM_y_JavaScript).

Como PHP se ejecuta [del lado del servidor](https://es.wikipedia.org/wiki/Script_del_lado_del_servidor): Nunca aparece al “ver código fuente”, ni en la consola (no existe una Consola de PHP en los navegadores). Por eso, para compartir tus script en PHP puedes usar servicios como [codepad](http://codepad.org/)… Y para resolver muchas dudas existe [Stackoverflow](http://stackoverflow.com/questions/tagged/php), además del sitio con [referencias oficiales de PHP](http://php.net/manual/es/langref.php).

Para que se ejecute PHP, en esta clase **deben tener instalado [MAMP](https://www.mamp.info/en/) en sus computadores**. Ese programa nos permite montar un servidor local, para trabajar con **Apache** (servidor HTTP), **MySQL** (sistema de gestión de bases de datos) y **PHP** (lenguaje de programación).

Para trabajar con PHP, usen páginas con extensión `*.php`. Estas se pueden crear de la misma manera que normalmente se crean páginas `*.html`: trabajando con cualquier editor de código. Pero en este trabajo tenemos que usar etiquetas de apertura y cierre particulares, que son `<?php` y `?>`. Las instrucciones que estén entre estas etiquetas serán filtradas e interpretadas en el [servidor](https://es.wikipedia.org/wiki/Servidor).

Entre `<?php` y `?>` se pueden escribir una o varias instrucciones. Si se escriben varias, éstas deben separarse mediante punto y coma `;`.
