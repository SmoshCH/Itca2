# clase 3


guia 3 

1 

```php
<?php

// Crear un arreglo de 50 elementos con números aleatorios
$elementos = [];
for ($i = 0; $i < 50; $i++) {
    $elementos[] = rand(1, 100); // Puedes ajustar el rango de los números aleatorios según tus necesidades
}

// Inicializar las variables para el número mayor y menor
$mayor = $elementos[0];
$menor = $elementos[0];

// Iterar sobre el arreglo para encontrar el número mayor y menor
foreach ($elementos as $numero) {
    if ($numero > $mayor) {
        $mayor = $numero;
    }
    if ($numero < $menor) {
        $menor = $numero;
    }
}

// Mostrar el resultado
echo "El número mayor es: $mayor<br>";
echo "El número menor es: $menor";

?>
```

2 

```php
<?php

// Definir la matriz de 6x5
$matriz = [
    [3, -5, 2, 10, -8],
    [-1, 7, -4, 6, 9],
    [0, -3, 5, -2, 4],
    [-6, 8, -9, 1, 3],
    [2, 4, -7, 12, -10],
    [-4, 6, 1, -8, 7]
];

// Recorrer la matriz y mostrar los números negativos
echo "Números negativos en la matriz:<br>";
foreach ($matriz as $fila) {
    foreach ($fila as $numero) {
        if ($numero < 0) {
            echo "$numero ";
        }
    }
}
?>
```

3

```php
<?php

// Definir las notas de los alumnos en un arreglo multidimensional
$notas_alumnos = array(
    array(85, 90, 75, 80), // Alumno 1
    array(70, 65, 80, 75), // Alumno 2
    array(95, 85, 90, 88)  // Alumno 3
);

// Función para calcular el promedio de un conjunto de notas
function calcularPromedio($notas) {
    $total = 0;
    $cantidad = count($notas);
    
    foreach ($notas as $nota) {
        $total += $nota;
    }
    
    return $total / $cantidad;
}

// Validar las notas de los alumnos y calcular promedios
for ($i = 0; $i < count($notas_alumnos); $i++) {
    $alumno = $i + 1;
    $notas = $notas_alumnos[$i];
    $error = false;

    // Validar que todas las notas sean mayores que 0
    foreach ($notas as $nota) {
        if ($nota <= 0) {
            echo "Error: Las notas del alumno $alumno deben ser mayores que 0.<br>";
            $error = true;
            break;
        }
    }

    // Si no hay errores, calcular y mostrar el promedio
    if (!$error) {
        $promedio = calcularPromedio($notas);
        echo "El promedio del alumno $alumno es: $promedio<br>";
    }
}

?>
```

4

```php
<?php

// Declarar los vectores vectorA y vectorB
$vectorA = array(1, 2, 3, 4, 5, 6, 7);
$vectorB = array(7, 6, 5, 4, 3, 2, 1);

// Inicializar el vectorC para almacenar la suma de vectorA y vectorB
$vectorC = array();

// Calcular vectorC = vectorA + vectorB
for ($i = 0; $i < count($vectorA); $i++) {
    $vectorC[$i] = $vectorA[$i] + $vectorB[$i];
}

// Mostrar los vectores y su suma
echo "vectorA = [".implode(", ", $vectorA)."]<br>";
echo "vectorB = [".implode(", ", $vectorB)."]<br>";
echo "vectorC = [".implode(", ", $vectorC)."]<br>";

?>
```


