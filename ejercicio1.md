# Ejercicio 1

## Simón Jiménez Crespo

### Paso 1: Crear e iniciar el repositorio de forma local

![git init](img/git_init.png)
<br>
Se crea un nuevo directorio llamado prueba2_simon, se accede a su interior y se inicializa un repositorio Git vacío mediante el comando git init.

![crear archivos](img/crear_archivos.png)
<br>
Se crean dos archivos de texto (archivo1.txt y archivo2.txt) y se les inserta contenido básico utilizando el comando echo y redirección.

### Paso 2: Conectar con el repositorio remoto

![git remote add](img/git_remote_add.png)
<br>
Se vincula el repositorio local recién creado con un repositorio remoto alojado en GitHub utilizando el comando git remote add origin.

### Paso 3: Subir repositorio local a GitHub

![git commit y git push](img/git_commit.png)
<br>
Se añaden los archivos creados al área de preparación, se realiza el primer commit del repositorio y se suben los cambios iniciales al servidor remoto.

### Paso 4: Clonar el repositorio en otra máquina

![git clone remoto](img/git_clone_remoto.png)
<br>
Se clona un repositorio remoto de GitHub en el equipo local y, a continuación, se configuran el nombre y el correo electrónico globales del usuario para Git.

### Paso 5: Modificar archivo 2 y crear archivo 3. Subirlo

![git push tras los cambios](img/git_push_remoto.png)
<br>
Se modifican y crean archivos de texto, se añaden al área de preparación, se registra un nuevo commit y se suben los cambios al repositorio remoto en la rama principal.

### Paso 6: Descargar los cambios en la máquina linux remota

![git pull en remoto](img/git_pull.png)
<br>
Se ejecuta el comando git pull para descargar y sincronizar los últimos cambios del repositorio remoto en el repositorio local, actualizando dos archivos de texto.
