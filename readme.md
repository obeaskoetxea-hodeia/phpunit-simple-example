Un ejemplo simple de PHPUnit
========================

Este es un ejemplo simple de pruebas unitarias en PHP con PHPUnit. Utilicé estos ejemplos como parte de una charla dada en Sheffield PHP el 18 de enero de 2018. La charla se ha escrito en una publicación de blog: [PHPUnit: What, Why, How?](https://andy-carter.com/blog/phpunit-what-why-how).

Siéntete libre de descargar este repositorio y darle una oportunidad a las pruebas unitarias.

Como se menciona en mi publicación de blog, intenta agregar un segundo caso de prueba para el método `Average::median` para probar cuando se pasa un conjunto de números par al método.

Si tienes éxito en eso, entonces intenta tomar un enfoque de desarrollo guiado por pruebas para agregar un nuevo método a `Average` para calcular el promedio modal escribiendo una prueba primero.

Comenzando
---------------

Clona este repositorio y luego ejecuta Composer:-

```
composer install
```

Entonces podrás ejecutar las pruebas unitarias utilizando:-

```
./vendor/bin/phpunit
```
