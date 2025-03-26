# Flujo básico en Git. Local.

En esta práctica comenzarás a trabajar en Git. Crearás un repositorio vacío al que le añadirás un fichero con cuatro commits: 

- Crear repositorio 
- Añadir seguimiento del archivo 
- Commit del archivo
   1. Mi nombre 
   2. Mi correo 
   3. Mis hobbies 
   4. Mi imagen 


Sigue paso a paso, responde y adjunta pantallazos en este README.md

1. Crea un directorio/carpeta vacía con el nombre de esta práctica.
   1. Abre git bash en un directorio/carpeta vacía (menú contextual).
   2. Ejecuta git sin argumentos. Mostrará los comandos básicos git.  Indica los distintos apartados.

   ![alt text](image.png)

   Enseña una lista con los comandos básicos como Configuración, creacion de repositorios ...



Trabajar con ramas
   3. Ejecuta git status y git log antes de crear ningún repositorio. Explica lo mostrado. 
   ![alt text](image-1.png)

   Git log dice que no hay commits y git status dice que no hay directorios en la carpeta

2. Crea un repositorio vacío

![alt text](image-2.png)

   1. Muestra el contenido del directorio .git (dir .git)
   ![alt text](image-3.png)

   2. Ejecuta git status y git log. Indica la rama sobre la que trabajas y explica lo mostrado. git status
   ![alt text](image-4.png)

   El git status dice que estoy en la rama "master" y el git log dice que no la rama "master" no tiene commits aún.

   3. Crea el fichero sobremi.html. Añade tu nombre y apellidos en un elemento de una lista

   ![alt text](image-5.png)

   1. Muestra el estado del directorio de trabajo. Explica lo mostrado git status

   ![alt text](image-6.png)
   Dice que no se ha añadido ningun commit pero que hay archivos que no están siendo seguidos?

3. Ejecuta git diff y git diff --staged git diff

![alt text](image-7.png)

No dice nada creo que porque no ha cambiado nada.

   1. Añade el cambio al repositorio con git add

   ![alt text](image-8.png)

   2. Ejecuta git diff y git diff --staged git diff
   ![alt text](image-9.png)

   3. Confirma el cambio al repositorio git commit con el mensaje "mi nombre" git commit

   ![alt text](image-10.png)

   4. Ejecuta git diff y git diff --staged
   ![alt text](image-11.png)

5. Añade tu correo electrónico

![alt text](image-12.png)

   1. Ejecuta git diff y git diff --staged git diff
   
   ![alt text](image-13.png)

   2.  Añade el cambio al repositorio git commit -a con el mensaje "mi correo" git commit

   ![alt text](image-14.png)

   3.  Ahora tienes dos commits. Vuelve al estado anterior mediante git checkout HEAD^ 

   ![alt text](image.png)
   
6.  Abre el editor para mostrar el nuevo estado del directorio de trabajo git status

![alt text](image-1.png)

   1.  Vuelve al estado con nombre y correo mediante git checkout sha-1

   ![alt text](image-2.png)

    No se porque no me funciona
    
7.  Abre el editor para mostrar el nuevo estado del directorio de trabajo.
   1.  Indica el cambio git status 
6. Añade tus hobbies con el mensaje "mis hobbies" en el commit git commit
7. Añade una imagen tuya con el mensaje "mi imagen" en el commit git commit
   

   De  interés:
   - [2. Fundamentos de Git](https://git-scm.com/book/es/v2/Fundamentos-de-Git-Obteniendo-un-repositorio-Git)
