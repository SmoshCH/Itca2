# PHP Cheat sheet.

Aquí encontraremos links importantes: [OverApi](https://overapi.com/php), <br>

# Sintaxis básica de PHP.

### Etiquetas de apertura y cierre
```php
<?php 
    // Código PHP aquí
?>
```
### Comentarios
```php
// Este es un comentario de una sola línea en PHP`

/*
   Este es un comentario de múltiples líneas.<br>
   Puedes escribir varias líneas de comentarios aquí.<br>
*/
```

### Variables

```php
$Entero = 25;
$Decimal = 10.99;
$String = "Nombre";
$Boleano = true;
$Nulo = null;
```

### Impresión en pantalla 
```php
$nombre = "Til";

echo "Hola, $nombre"; // Imprime: Hola, Til
echo "Nombre: ".$nombre."<br>"; //Imprime: Nombre: Til. (y luego da salto de línea.)
```

### Arrays
```php
$colores = array("rojo", "verde", "azul");
```

### Objetos
```php
class Persona {
    public $nombre;
    public $edad;
}

$persona = new Persona();
$persona->nombre = "Til";
$persona->edad = 80;
```





