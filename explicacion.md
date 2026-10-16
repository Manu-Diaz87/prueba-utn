## Comandos Para iniciar un Repo en Github.

1. git init: Inicializa un repositorio LOCAL. Se ejecuta una única vez por carpeta/proyecto.
2. git add index.html : Este comando nos permite agregar a lo que se denomina 'staggin area' (area de pre-guardado) los archivos sobre los cuales estamos trabajando.
3. git commit -m "Se agregaron parrafos e imagenes": Este comando es el que guarda de forma definitiva todos los cambios que hayamos realizado.
4. git branch -M main: Me permite renombrar una rama. 
5. git remote add origin https://github.com/ManuDiaz87/prueba-git.git: Me va a permitir conectar mi repositorio LOCAL con el repositorio REMOTO (github). Este comando se ejecuta una sola vez, la conexión ya va a quedar establecida.
6. git push -u origin main: Me permite subir los cambios 'committeados' en mi repo LOCAL hacía el repo REMOTO. Se debe ejecutar cada vez que se hayan realizado cambios y querramos subirlo al repo en github.

- Los comandos que se utilizan para guardar y subir cambios del repositorio son: el 2, 3 y 6.
    - git add .: para establecer los cambios en el staggin area (area de preguardado)
    - git commit -m "comentario": para guardar de forma definitiva en el repo LOCAL.
    - git push -u origin main: subo lo que acabo de guardar, al repo REMOTO.
     