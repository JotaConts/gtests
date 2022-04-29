Estados de los arvhivos:
Working directory: Archivos o codigo recién creado
Staging área (git add): Se confirman las modificaciones y quedan en estado de preparación.
Repository (git commit): Los archivos están finalmente confirmados en el repositorio.

Comandos aprendidos
1) git init (para crear el repositorio .git)
2) git status (para conocer el estdo de los archivos que estamos haciendo seguimiento)
3) git add file_name (para iniciar el seguimiento del archivo indicado)
-->git add . (hace un add para todos los archivos de la carpeta raíz)

4) git config --global user.mail "mi_email@email.com"
5) git config --global user.name "mi_email@email.com"

6) git commit (agrego los cambios insertando un mensaje, luego dae ESC y escribir ":wq" sin las comillas para guardar y salir)

7) git log (devuelve datos de los commits hechos)
8) git diff file_name (muestra las diferencias que hay entre la versión actual y la anterior)

9) git checkout --file_name (para revertir los cambios que aún no se han enviado al stagin area)

10) archivo gitignore: Todo archivo agregado en la carpeta raíz tendrá un seguimiento en la carpeta .git
                        Si existen archivos que queremos que que git ignore por completo, debemos crear
                        un archivo llamado .gitignore donde escribiremos todos los archivos que queremos ignorar.

11) git branch new_branch_name  (un branch es una rama del código, permite desarrollar mi parte del codigo
                                y hacer commits dentro de ella sin afectar aún al código maestro)

12) git branch (muestra las ramas que existen)
13) git checkout branch_name (ingresa a la rama correspondiente)

14) git merge branch_name (una vez en la rama master, este comando une los cambios de una rama a la master)

15) git pull origin master (descargar la última versión del master, luego podemos hacer el push)
16) git push origin master (subir los cambios al github)

****
6to cambio de prueba para ver funcionamiento de jenkins
