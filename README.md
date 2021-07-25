<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/fondo.png" alt="cabecera">

# CRUD_PHP

 CRUD en php, utilizando xampp con un servidor apache y mysql, con diseño en bootstrap 4
 CRUD in php, using xampp with an apache server and mysql, with bootstrap 4 design
 
## C`REATE (CREAR)`
## R`READ(LECTURA)`
## U`UPDATE(ACTRUALIZAR)`
## D`DELETE(BORRAR)`

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/resu.jpg" alt="resumen">

- Contenido/Contents
     - [DIAGRAMA-DIAGRAMS](#DIAGRAMA-DIAGRAMS)
     - [REQUISITOS-REQUIREMENTS](#REQUISITOS-REQUIREMENTS)
     - [BASEDEDATOS-DATABASE](#BASEDEDATOS-DATABASE)
     - [IMAGENES-IMAGES](#IMAGENES-IMAGES)
  

  ## DIAGRAMA-DIAGRAMS
[ES]

[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG5Vc3VhcmlvLT4-Q29udHJvbGFkb3I6IFNvbGljaXRhXG4gQ29udHJvbGFkb3ItPj5Nb2RlbG86IExsYW1hXG4gTW9kZWxvLT4-QmFzZSBkZSBkYXRvczogUGlkZVxuIFxuQmFzZSBkZSBkYXRvcyAtPj5Nb2RlbG86IFJldG9ybmFcbiBNb2RlbG8tPj5Db250cm9sYWRvcjogUmV0b3JuYVxuIENvbnRyb2xhZG9yLT4-VmlzdGE6IFByb2Nlc2EgeSBlbnbDrWFcbiBWaXN0YS0-PlVzdWFyaW86IFByb2Nlc2EgeSBlbnbDrWEiLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/edit##eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAgQWxpY2UtPj4rSm9objogSGVsbG8gSm9obiwgaG93IGFyZSB5b3U_XG4gICAgQWxpY2UtPj4rSm9objogSm9obiwgY2FuIHlvdSBoZWFyIG1lP1xuICAgIEpvaG4tLT4-LUFsaWNlOiBIaSBBbGljZSwgSSBjYW4gaGVhciB5b3UhXG4gICAgSm9obi0tPj4tQWxpY2U6IEkgZmVlbCBncmVhdCFcbiAgICAgICAgICAgICIsIm1lcm1haWQiOiJ7XG4gIFwidGhlbWVcIjogXCJkZWZhdWx0XCJcbn0iLCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9)


[ENG]

[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gYXV0b251bWJlclxuVXNlciAtPj4gQ29udHJvbGxlcjogUmVxdWVzdFxuQ29udHJvbGxlciAtPj4gTW9kZWw6IEZsYW1lXG5Nb2RlbCAtPj4gRGF0YWJhc2U6IFJlcXVlc3RcbiBcbkRhdGFiYXNlIC0-PiBNb2RlbDogUmV0dXJuc1xuTW9kZWwgLT4-IENvbnRyb2xsZXI6IFJldHVybnNcbkNvbnRyb2xsZXIgLT4-IFZpc3RhOiBQcm9jZXNzIGFuZCBzZW5kXG5WaWV3IC0-PiBVc2VyOiBQcm9jZXNzIGFuZCBzZW5kIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/edit##eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG5Vc3VhcmlvLT4-Q29udHJvbGFkb3I6IFNvbGljaXRhXG4gQ29udHJvbGFkb3ItPj5Nb2RlbG86IExsYW1hXG4gTW9kZWxvLT4-QmFzZSBkZSBkYXRvczogUGlkZVxuIFxuQmFzZSBkZSBkYXRvcyAtPj5Nb2RlbG86IFJldG9ybmFcbiBNb2RlbG8tPj5Db250cm9sYWRvcjogUmV0b3JuYVxuIENvbnRyb2xhZG9yLT4-VmlzdGE6IFByb2Nlc2EgeSBlbnbDrWFcbiBWaXN0YS0-PlVzdWFyaW86IFByb2Nlc2EgeSBlbnbDrWEiLCJtZXJtYWlkIjoie1xuICBcInRoZW1lXCI6IFwiZGVmYXVsdFwiXG59IiwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)

  ## REQUISITOS-REQUIREMENTS

> **Note:** Se quiere utilizar xampp - You need to use xampp.


##Pasos-Steps

- Pon la carpeta PHP en la ruta **C:\xampp\htdocs**
- Inicia el servidor **Apache** y el servidor **MySQL** en xampp
- En un navegador accede a la ruta **http://localhost/PHP/** para acceder a los proyectos y accede a **http://localhost/phpmyadmin/** para ver la base de datos

- Put the PHP folder in the path **C:\xampp\htdocs**
- Start the **Apache** server and **MySQL** server in xampp
- In a browser go to the path **http://localhost/PHP/** to access the projects and go to **http://localhost/phpmyadmin/** to see the database

  ## BASEDEDATOS-DATABASE

Para crear la base de datos necesitamos crear las siguientes tablas con sus especificaciones en phpmyadmin:

- Crear una base de datos llamada php en ella tendras que crear una tabla llamada registros
>IMPORTANTE: se debe tener el usuario root, sin contraseña y el servidor ha de ser localhost ejemplo:**mysql:host=localhost;dbname=php","root",""**

- En la tabla registros debemos crear las siguientes columnas con su correspondiente tipo de informacion:

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db1.JPG" alt="db1" width="50%" style="vertical-align:middle">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2"width="50%"  style="vertical-align:middle>
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3"width="100%">


To create the database we need to create the following tables with their specifications in phpmyadmin:

- Create a database called php in it you will have to create a table called records
>IMPORTANT: you must have the root user, without password and the server must be localhost example: **mysql: host = localhost; dbname = php "," root "," "**

- In the records table we must create the following columns with their corresponding type of information:

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db1.JPG" alt="db1" width="100%" style="vertical-align:middle">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2" width="50%" style="vertical-align:middle>
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3" width="100%">


  ## IMAGENES-IMAGES

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f1.JPG" alt="f1" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f2.JPG" alt="f2" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f3.JPG" alt="f3" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f4.JPG" alt="f4" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f5.JPG" alt="f5" width="50%" style="vertical-align:middle">
