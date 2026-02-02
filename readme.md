## Parte 1
![imagen1](capturas/Captura1.png)
Aquí podemos ver cómo me muevo al Escritorio, creo la carpeta 00_Lab_Git, entro en ella, e inicializo un repositorio local.
---
## Parte 2
![imagen2](capturas/Captura2.png)
---
Vamos a GitHub, entramos en nuestra cuenta y le damos al botón "Create repository".
---
![imagen3](capturas/Captura3.png)
---
Nombramos nuestro repositorio, importante que venga sin readme.md creado.
---
![imagen4](capturas/Captura4.png)
---
Copiamos el enlace proporcionado después de crearlo.
---
![imagen5](capturas/Captura5.png)
---
Volvemos a la terminal y escribimos ``` git remote add origin ``` seguido por el enlace.
Y para confirmar que funciona, usamos ``` git remote -v ``` y si vemos "origin" seguido por el enlace del repositorio GitHub, lo hemos conectado correctamente.
---
## Parte 3
![imagen6](capturas/Captura6.png)
---
Podemos ver cómo creo un "archivo.txt" con ``` echo ```, lo muevo a staging, y hago un commit.
---
![imagen7](capturas/Captura7.png)
---
Por último, lo subo al repositorio en GitHub.
---
## Parte 4
![imagen8](capturas/Captura8.png)
---
Creamos la rama "development", nos movemos a ella, y editamos con el bloc de notas el "archivo.txt".
---
![imagen9](capturas/Captura9.png)
---
Podemos ver que lo he creado con el texto "Entrega Git".
---
![imagen10](capturas/Captura10.png)
---
Escribimos una frase debajo.
---
![imagen11](capturas/Captura11.png)
---
Le damos a cerrar el bloc de notas, y guardamos el "archivo.txt" con sus cambios.
---
![imagen12](capturas/Captura12.png)
---
Lo pasamos a staging, y hacemos un commit.
---
![imagen13](capturas/Captura13.png)
---
Igual que antes, hacemos un push para subirlo al repositorio en GitHub.
---
![imagen14](capturas/Captura14.png)
---
Podemos ver que GitHub nos avisa que hemos hecho un push desde la rama "development" y nos pide que comparemos y pulleemos este push. No tocamos nada ya que si lo hacemos nos mezcla ambas ramas automáticamente y buscamos mezclarlas luego.
---
![imagen15](capturas/Captura15.png)
---
Podemos ver que el "archivo.txt" sigue exactamente igual de como lo creamos en la rama "master".
---
## Parte 5
![imagen16](capturas/Captura16.png)
---
Nos movemos de vuelta a la rama "master" y mezclamos la rama "development" con la rama en la que estamos, que es "master", si fuesen a haber conflictos, los arreglamos, pero en este caso no ocurre. Por último, hacemos un push desde la rama "master" para subir todo ya mezclado.
---
![imagen17](capturas/Captura17.png)
---
Ahora, cuando miramos el "archivo.txt" en nuestro repositorio de GitHub, se vé como hemos mezclado las ramas y por ende el contenido del archivo.
