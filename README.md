# CRUD_PHP


<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/fondo.png" alt="cabecera">
 CRUD en php, utilizando xampp con un servidor apache y mysql, con diseño en bootstrap 4
 CRUD in php, using xampp with an apache server and mysql, with bootstrap 4 design

    ## C-CREATE (CREAR)
    ## R-READ (LECTURA)
    ## U-UPDATE (ACTRUALIZAR)
    ## D-DELETE (BORRAR)

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/resu.jpg" alt="resumen">

- Contenido/Contents
     - [DIAGRAMA-DIAGRAMS](#DIAGRAMA-DIAGRAMS)
     - [REQUISITOS-REQUIREMENTS](#REQUISITOS-REQUIREMENTS)
     - [BASEDEDATOS-DATABASE](#BASEDEDATOS-DATABASE)
     - [IMAGENES-IMAGES](#IMAGENES-IMAGES)
  

  ## DIAGRAMA-DIAGRAMS
[ES]
```mermaid
sequenceDiagram
 autonumber
 Usuario->>Controlador: Solicita
 Controlador->>Modelo: Llama
 Modelo->>Base de datos: Pide
 
Base de datos ->>Modelo: Retorna
 Modelo->>Controlador: Retorna
 Controlador->>Vista: Procesa y envía
 Vista->>Usuario: Procesa y envía
```
[ENG]
```mermaid
sequenceDiagram
 autonumber
User ->> Controller: Request
Controller ->> Model: Flame
Model ->> Database: Request
 
Database ->> Model: Returns
Model ->> Controller: Returns
Controller ->> Vista: Process and send
View ->> User: Process and send
```


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
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2"width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3"width="100%">


To create the database we need to create the following tables with their specifications in phpmyadmin:

- Create a database called php in it you will have to create a table called records
>IMPORTANT: you must have the root user, without password and the server must be localhost example: **mysql: host = localhost; dbname = php "," root "," "**

- In the records table we must create the following columns with their corresponding type of information:

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db1.JPG" alt="db1" width="50%" style="vertical-align:middle">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db2.jpg" alt="db2" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/db3.jpg" alt="db3" width="100%">


  ## IMAGENES-IMAGES

<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f1.JPG" alt="f1" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f2.JPG" alt="f2" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f3.JPG" alt="f3" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f4.JPG" alt="f4" width="100%">
<img src="https://github.com/RodrigoSendinoSanz/CRUD_PHP/blob/main/imagenes/f5.JPG" alt="f5" width="100%" style="vertical-align:middle">
