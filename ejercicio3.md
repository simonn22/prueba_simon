# Ejercicio 3

![alt text](img/ejercicio3_1.png)<br>
Se crea una nueva rama local llamada primera y se ejecuta el comando git branch para listar las ramas y comprobar que se ha creado correctamente.

![alt text](img/ejercicio3_2.png)<br>
Nos movemos a la nueva rama primera utilizando git checkout y creamos un archivo de texto vacío llamado 1.txt.

![alt text](img/ejercicio3_3.png)<br>
Se preparan los cambios con git add . y se realiza un commit para guardar definitivamente la creación del archivo en el historial de la rama.

![alt text](img/ejercicio3_4.png)<br>
Volvemos a la rama principal (main) y fusionamos la rama primera. La fusión se realiza sin conflictos (tipo Fast-forward) porque main no tenía cambios adicionales.

![alt text](img/ejercicio3_5.png)<br>
Se elimina la rama primera con el comando git branch -d porque ya hemos integrado sus cambios en la principal y no la necesitamos.

![alt text](img/ejercicio3_6.png)<br>
Se crea una nueva rama llamada segunda y se vuelve a listar con git branch para verificar que ahora existe junto a la principal.

![alt text](img/ejercicio3_7.png)<br>
Estando en la rama segunda, se renombra el archivo 1.txt como 1coma4.txt usando el comando mv y se registra este cambio con un nuevo commit.

![alt text](img/ejercicio3_8.png)<br>
Regresamos a la rama principal (main) y abrimos el archivo original 1.txt con el editor de texto Nano para modificar su contenido.

![alt text](img/ejercicio3_9.png)<br>
Tras hacer el commit de la modificación en main, intentamos fusionar la rama segunda y se produce un conflicto, ya que un mismo archivo ha sido modificado en una rama y eliminado/renombrado en la otra.

![alt text](img/ejercicio3_10.png)<br>
Se realiza un commit para dejar constancia de la resolución del conflicto y se completan las fusiones necesarias para que la rama principal quede perfectamente actualizada con los cambios.
