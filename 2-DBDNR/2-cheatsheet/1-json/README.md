# JSON Cheat sheet.

Aquí encontraremos links importantes: [json](https://www.json.org/json-en.html), <br>

# Sintaxis básica de JSON.

```json
{
  //Clave    Valor 
  "nombre": "Til",
  "edad": 80,
  "ciudad": "Oceano",
  "casado": false,
  //Array
  "hobbies": ["comer", "leer", "viajar"],
  //Objeto
  "direccion": {
    "calle": "Calle Principal",
    "numero": 123,
    "codigo_postal": "28001"
  }
}
```

- JSON no acepta comentarios.

- Claves <br>
Las claves deben ir entre comillas dobles ", y seguidas de dos puntos : <br>

- Tipo de datos <br>
Los valores pueden ser de tipo string (entre comillas dobles), number, boolean, array (encerrados entre corchetes [] y separados por comas), o incluso otro objeto JSON. <br>

- Objetos<br>
Un objeto JSON se encierra entre llaves {}. <br>
Dentro del objeto, los pares clave-valor están separados por comas ,. <br>
Los objetos JSON pueden anidarse, como en el caso de la clave "direccion", que tiene otro objeto JSON anidado.

### Ejemplos

-1 
 ```json
{
  "nombre": "Til",
  "edad": 80,
  "ciudad": "Oceano",
  "casado": false,
  "hobbies": ["comer", "leer", "viajar"],
  "direccion": {
    "calle": "Calle Principal",
    "numero": 123,
    "codigo_postal": "28001"
  }
}
```
