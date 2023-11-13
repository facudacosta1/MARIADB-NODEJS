# CRUD BÁSICO CON NODEJS

Para trabajar en este proyecto deberás realizar lo siguiente:
1- Abre la terminal y ejecuta el comando `npm install`, el cual instalará todas las dependencias del proyecto. Sin este paso no podrás trabajar.
2- A continuación ejecuta el comando `npm run dev`, el cual inicia el servidor en "modo desarrollo" utilizando nodemon.
3- Puedes comenzar a trabajar en app.js y realizar lo solicitado.

## Primeros pasos con MariaDB
Luego de descargar MARIA DB lo basico es ingresar a Heidi HS, ingresar contraseña del root y tenemos disponible para crear una nueva tabla.

Lo siguiente es hacer click derecho crear nuevo>tabla ingresar el nombre de la tabla y dentro de la misma click derecho>agregar columna y nos permite ingresar los tipos de datos que se van a utilizar

## Ejemplo de comandos en SQL para consultas a la BD

Los comandos se aplican en la seccion "consulta" y se corren con F9 o el boton ejecutar SQL

INSERT INTO people (name,lastname, email) VALUE (               ---------> CREATE
"Alfredo","Robert", "example@jap.com"
);

#SELECT id, name, lastname, email FROM people WHERE name="Pepe" ---------> READ

#UPDATE people SET NAME="Pepe2" WHERE id=2;                     ---------> UPDATE

DELETE FROM people WHERE id=2;                                  ---------> DELETE
