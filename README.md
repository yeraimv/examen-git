# examen-git
## EJERCICIO 1
### Antes de empezar
Primero he clonado el repositorio que he creado en GitHub
![Alt text](git_clone.png)

### Crear un TXT
![Alt text](crear_txt.png)

### Añadir TXT al staged area
![Alt text](git_add.png)

### Registrar los cambios
![Alt text](git_commit.png)

### Confirmar cambios y guardar en repositorio
![Alt text](git_push.png)

### Traer los cambios realizados en main
![Alt text](git_pull.png)

### Volver al estado original cuando aún no se ha hecho add
![Alt text](git_checkout.png)

### Si ya se ha hecho el add y quiero volver a una versión anterior
![Alt text](reset_checkout.png)

### Volver a una versión concreta
Para volver a una versión concreta copiaré el hash que me da GitHub
![Alt text](last_checkout.png)

## EJERCICIO 2
### Pull del repositorio de la práctica 1
He hecho un pull del repositorio de la práctica 1 en el directorio correspondiente, para trabajar sobre el mismo.
![Alt text](ex2_pull.png)

### Comprobar que haya varios commits
![Alt text](log.png)

### Ver el contenido del README
![Alt text](cat_readme.png)

### Volver al primer commit
![Alt text](primer_commit.png)

### Comprobar el estado de README en el primer commit

Antes de esto hice un add, un commit y un push ya que sino no me permitía hacer el checkout porque se cargaría el README actual que estaba editando.
![Alt text](ex2_checkout_cat.png)

### Comprobar que estoy en la rama Initial commit
![Alt text](Ex2_log.png)

### Me muevo al segundo commit
![Alt text](Ex2_backto2ndcommit.png)

### Vuelvo al main y compruebo que esté todo en orden
![Alt text](Ex2_returntomain.png)

## EJERCICIO 3
Directorio de trabajo (Working directory): El directorio de trabajo es la ruta física en la que se encuentra tu repositorio. (Ejemplo: C:/Users/Máximo/Desktop/mi-repo-favorito).

Area de preparación (Staging area): El staging area contiene la información y los datos de nuestro repositorio en un momento concreto, previo a subir los cambios al repositorio en la nube.
Cuando hacemos "git add" estamos colocando nuestros archivos en el staging area antes de hacer commit y push.

Repositorio local (Directorio .git): Es nuestro repositorio dentro de la máquina en la que estamos trabajando. 
Lo contrario sería el repositorio que se encuentra en el servidor de GitHub/GitLab, ya que está en la nube. 
Cuando hacemos un pull estamos recogiendo lo que hay subido en el servidor para tenerlo en local y poder editarlo. Una vez editado, hacemos un push para subir al servidor los cambios que hemos hecho de manera local. 