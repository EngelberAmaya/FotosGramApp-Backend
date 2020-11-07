# FotosGramApp-Backend

Este es el código necesario para establecer el backend conectado a MongoDB usando Mongoose. Para ser usado en la App FotosGramApp-Front, en la cual tiene los servicios de login, creación y modificación de usuarios usando token. De igual manera tiene un método para encriptar la contraseña en el momento de crear un usuario.

Para ejecutarlo, es necesario reconstruir los módulos de node usando el comando

```
npm install
```


Para ejecutar la aplicación debe realizar:

1) Debe tener instalado typescript, y ejecutar el comando en la carpeta del proyecto, para generar la carpeta dist

```
tsc -w

```


2) Usando esa información, luego ejecutar en la carpeta del proyecto

```
nodemon dist/  ó node dist/

```
