# Installation and more

1. Instalación de Mongo DB<br>

- Verificar si el puerto que utiliza Mongo DB (27017) esta disponible, Si no hay que cerrar proceso.<br>

```cmd
::Verificar puertos utilizados 
netstat 

::Encuentra información del puerto 
netstat -ano | findstr :27017

::Cierra la acción que tiene el puerto utilizado y lo deja libre.
taskkill /F /PID 1234
```
<br>
- Descargar Mongo DB desde [Mongo DB](https://www.mongodb.com/try/download/community).<br>
Dar click en Select package.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/786e5fab-fbdd-45c4-9c95-4572e321b6ab)<br>
Dar click en download.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/162ad47c-3164-4f69-a22f-63111cc909d7)<br>
Correr instalador de Mongo DB con permisos de administrador.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/22c8f825-11b2-4827-b0a0-38f0a95ee24d)<br>




