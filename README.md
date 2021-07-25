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

[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gYXV0b251bWJlclxuVXN1YXJpby0-PkNvbnRyb2xhZG9yOiBTb2xpY2l0YVxuIENvbnRyb2xhZG9yLT4-TW9kZWxvOiBMbGFtYVxuIE1vZGVsby0-PkJhc2UgZGUgZGF0b3M6IFBpZGVcbiBcbkJhc2UgZGUgZGF0b3MgLT4-TW9kZWxvOiBSZXRvcm5hXG4gTW9kZWxvLT4-Q29udHJvbGFkb3I6IFJldG9ybmFcbiBDb250cm9sYWRvci0-PlZpc3RhOiBQcm9jZXNhIHkgZW52w61hXG4gVmlzdGEtPj5Vc3VhcmlvOiBQcm9jZXNhIHkgZW52w61hIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOmZhbHNlfQ)](https://mermaid-js.github.io/mermaid-live-editor/edit##eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG5cblVzdWFyaW8tPj5Db250cm9sYWRvcjogU29saWNpdGFcbiBDb250cm9sYWRvci0-Pk1vZGVsbzogTGxhbWFcbiBNb2RlbG8tPj5CYXNlIGRlIGRhdG9zOiBQaWRlXG4gXG5CYXNlIGRlIGRhdG9zIC0-Pk1vZGVsbzogUmV0b3JuYVxuIE1vZGVsby0-PkNvbnRyb2xhZG9yOiBSZXRvcm5hXG4gQ29udHJvbGFkb3ItPj5WaXN0YTogUHJvY2VzYSB5IGVudsOtYVxuIFZpc3RhLT4-VXN1YXJpbzogUHJvY2VzYSB5IGVudsOtYSIsIm1lcm1haWQiOiJ7XG4gIFwidGhlbWVcIjogXCJkZWZhdWx0XCJcbn0iLCJ1cGRhdGVFZGl0b3IiOmZhbHNlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6ZmFsc2V9))

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

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db1.JPG" alt="db1" width="50%" >
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2" width="50%" >
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3"width="100%">


To create the database we need to create the following tables with their specifications in phpmyadmin:

- Create a database called php in it you will have to create a table called records
>IMPORTANT: you must have the root user, without password and the server must be localhost example: **mysql: host = localhost; dbname = php "," root "," "**

- In the records table we must create the following columns with their corresponding type of information:

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db1.JPG" alt="db1" width="50%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2" width="50%" >
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3" width="100%">


  ## IMAGENES-IMAGES

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f1.JPG" alt="f1" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f2.JPG" alt="f2" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f3.JPG" alt="f3" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f4.JPG" alt="f4" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f5.JPG" alt="f5" width="50%">
