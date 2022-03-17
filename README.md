
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: git config --global user.email miqgel7@gmail.com 

2. ¿Qué es un Pull Request?
Respuesta: Es el metodo que se utiliza para avisar al propietario del repo que hemos forkeado para que vea los cambios del repositorio original y con lo cual si acepta sera cambiada la información en el repo original.

3. ¿Para qué sirve HEAD en GIT?
Respuesta: Es el puntero el cual nos indica en que posición nos encontramos dentro de una rama y un commit.

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: 4 y son:  untracked, unstaged, staged,traked

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: El hash del commit

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: git reset --hard HEAD~3

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: Un conflicto seria al mergear o rebasear un archivo en el cual afectaria a las mismas lineas de ese archivo, eso generaria un conflicto.

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: rm -rf .git/

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git remote add origin url

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: 
