# Branching and merging

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**branch_time**_

  Abrir el terminal y utilizar el comando mkdir + nombre del directorio(branch_time).
  
2. Cámbiate a dicho directorio.

  Se pone el comando cd + la direccion de dicho directorio.
  
3. Inicializa un repositorio vacío.
  
  Utilizamos el comando git init para iniciar el repositorio.
  
4. Crea un fichero llamado first.txt después añade y haz commit con un solo comando.
  
  Ponemos el comando nano + el nombre del fichero(first.txt).
  
5. Crea una nueva rama llamada _**amazing_feature**_.
  
  Ponemos en el terminal los comandos;
  git branch amazing_feature
  git checkout amazing_feature
  
6. Cámbiate a dicha rama.
  
  Para cambiar de rama utilizamos git checkout + nombre de la rama.
  
7. Crea un nuevo fichero llamado best.txt con el contenido "this is the best file".
  
    Ponemos el comando nano + el nombre del fichero(best.txt) y dentro del fichero ponemos "this is the best file".
  
8. Añade el fichero al área de preparación.

   git add  best.txt
   
9. Haz commit del fichero con el mensaje "added best.txt".
  
  Poner los siguientes comandos:
  git add added best.txt
  git commit -m 'Comentario'
  
10. Vuelve a la rama master.
  
  git checkout NOMBRE_RAMA_ORIGINAL.
  
11. Une (merge) la rama feature a la rama master.
  
  git merge [--no-ff] RAMA_ORIGINAL
  
12. Borra la rama feature.
  
  git branch -d feature.
  
13. Crea la rama _**conflict**_ y cámbiate a ella con un solo comando.
  
  Ponemos en el terminal el comando git checkout -b + nombre de la rama (conflict)
  
14. Crea tu propio conflicto al mezclar dos ramas! Para ello trabaja en el mismo fichero en dos ramas separadas y une (merge) las dos ramas. Arregla los conflictos y finaliza la unión. En el mundo real nunca intentarás crear un conflicto en una unión de ramas, pero es importante que no te sientas intimidado por los conflictos al realizar una unión de ramas y ser capaz de arreglarlos con confianza.
  
