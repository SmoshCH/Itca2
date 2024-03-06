# Mongo Installation

- Instalación de Mongo DB, guia de instalación [Guia 2.pdf](https://github.com/SmoshCH/Itca2/files/14495551/Guia.2.pdf)<br>


1. Verificar si el puerto que utiliza Mongo DB (27017) esta disponible, Si no hay que cerrar proceso.<br>

- Entrar a http://portquiz.net:27017/ , para ver si el puerto esta disponible, si esta disponible debara verse así.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/1eb88ed8-3a79-43b4-8381-0d918b463ebc)<br>

- Si no está disponible hay que cerrar el puerto con el siguiente proceso en el CMD<br>
```cmd
::Verificar puertos utilizados 
netstat 

::Encuentra información del puerto 
netstat -ano | findstr :27017

::Cierra la acción que tiene el puerto utilizado y lo deja libre.
taskkill /F /PID ###(Escribir numero de PID)##
```
<br>
2. Descargar Mongo DB desde [Mongo DB](https://www.mongodb.com/try/download/community).<br>
Dar click en Select package.<br>

![image](https://github.com/SmoshCH/Itca2/assets/84145465/786e5fab-fbdd-45c4-9c95-4572e321b6ab)<br>
Dar click en download.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/162ad47c-3164-4f69-a22f-63111cc909d7)<br>
Correr instalador de Mongo DB con permisos de administrador.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/22c8f825-11b2-4827-b0a0-38f0a95ee24d)<br>
Dar click en siguiente.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/c67a530f-90d8-4d52-b8a2-3cec631ed40b)<br>
[X] Marcar en caja de aceptar terminos y condiciones, y dar en siguiente.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/9618848d-dacc-4c6f-a446-93bc1dfdb4b3)<br>
Seleccionar complete, y click en next.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/ed0356c8-3a84-4066-be35-4697b267a7a0)<br>
Seleccionar next.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/e8fef84a-a19d-4ab7-a92e-d4880fd8435d)<br>
[x] Marcar casilla Install as a service, y dar click en next.<br> 
![image](https://github.com/SmoshCH/Itca2/assets/84145465/bf1154ef-ba7e-474a-8d62-298eff780b52)<br>
Click en siguiente.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/48e4af1b-9d09-442f-bdf4-6df069e7951b)<br>
Esperar proceso de terminado.<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/2a3c9840-b7e2-4179-83fe-f36c41c312fb)<br>
Fin de la instalación de Mongo DB.<br>

3. Descargar Shell para Mongo DB desde [MongoDB Shell](https://www.mongodb.com/try/download/shell).<br>

Click en download<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/ce54ff7d-dbb1-4508-8308-1b3339417419)<br>
Click izquierdo para descomprimir carpeta<br> 
![image](https://github.com/SmoshCH/Itca2/assets/84145465/f3841706-2217-457b-a878-a2d0363dcf3d)<br>
Cortar carpeta descomprimida<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/3e6dc5e5-5e0a-4b63-9c0a-9587c1f4abeb)<br>
Pegar carpeta descomprimida en carpeta en DiscoC:/Archivos de Programa/MongoDB/Server<br>
C:\Program Files\MongoDB\Server<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/903b34f9-4586-4ec8-b722-6a42e450ab26)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/33e56855-64a2-4d95-8f1a-53cca321effe)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/96105f28-e289-4b0f-a929-ce45515de080)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/c17ed773-0a25-407d-9845-d80fe67488b5)<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/d0e07219-f48d-4471-a6cb-6ca534ecfc70)<br>
Fin de la instalación de MongoDB shell<br>

4. Ajustes adicionales y agregación de variables de entorno.<br>

- Crear carpeta Data/db en la carpeta Disco Local C: <br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/f2ffa425-9e79-4a49-98fb-6692fdb90d97)<br>
- Crar carpeta db adentro de carpeta Data<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/05c8c778-77a5-4a53-b9dc-bc1e3a0878ed)<br>
<br>
<br>

- Agregación de variables de entorno.
- Copiar direccion de carpeta bin de mongoDB.<br>
C:\Program Files\MongoDB\Server\7.0\bin<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/b8e64e90-d3ff-4f2d-b748-4b416762fc6b)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/2056d997-bb96-4154-b372-d469d23e4b22)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/6e542085-6ee0-41eb-8ad6-679c6c46b596)
![image](https://github.com/SmoshCH/Itca2/assets/84145465/7e467589-2259-42f6-803e-f1ead048080c)<br>
![image](https://github.com/SmoshCH/Itca2/assets/84145465/87592104-05ea-4bde-9449-76d9cce262e9)<br>

- Agregar variable de entorno Path de variables de usuario y de sistema.
  Este equipo> propiedades> configuración avanzada de sistema> variables de entorno.<br>
  Click izquierdo en carpeta Este equipo > propiedades.<br>
  ![image](https://github.com/SmoshCH/Itca2/assets/84145465/1987a849-7272-4778-b0ad-84cd42aa164b)<br>
  Click izquierdo en configuración avanzada de sistema.<br>
  ![image](https://github.com/SmoshCH/Itca2/assets/84145465/3677292b-1b73-423a-b972-259d64bc781f)<br>
  CLick en Variables de entorno.<br>
  ![image](https://github.com/SmoshCH/Itca2/assets/84145465/672bd5cc-4b74-4c2c-8b60-113c69c2d9cb)<br>
  Dar Doble click en path.<br>
  ![image](https://github.com/SmoshCH/Itca2/assets/84145465/b63e9953-e107-4fa4-9d96-e8f2266073d0)<br>
  Dar doble click en un campo en blanco y pegar la direccion de bin y click en aceptar<br>
C:\Program Files\MongoDB\Server\7.0\bin<br>
  ![image](https://github.com/SmoshCH/Itca2/assets/84145465/b1ec2116-9f89-4a5e-a759-b2543bf1b6e9)




  
  








  







