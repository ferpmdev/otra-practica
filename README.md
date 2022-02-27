# otra-practica

### git init

Se usa para iniciar un repositorio local.

### git config

Una vez que inicializamos un repositorio debemos configurarlo con el **git config.name** y el **git config.user**.

### git config -l

Nos va a permitir ver un listado de las configuraciones de nuestro repositorio.

### git add (+ nombre del archivo)

No sirve para agregar un archivo a la zona de preparación.

### git commit -m "(nuestro mensaje descriptivo)"

Con este comando lo que hacemos es dejar asentado el cambio que acabamos de hacer en nuestro proyecto.
Git va a crear un registro el cual nos va a permitir luego, si queremos regresar en el tiempo.

### git log

Éste comando nos permite ver un listado de todos los comités que venimos realizando.

### git status

Es para ver dónde estoy parado.

### git clone (+ url del repo)

Una vez que creé un repositorio remoto indica puedo clonarlo localmente y luego para luego después sincronizarlo con el siguiente comando.

### git remote add origin (+ url del repo)

Éste comando nos permite vincular nuestro repositorio local con un repositorio remoto.

### git branch -M main

Éste comando nos va a permitir modificar el nombre de la rama **master** como rama **main**.
Es importante aclarar que este comando va a ser posible ejecutarlo una vez que hagamos hecho un commit.

### git branch (nombre de rama)

Sirve para crear una nueva rama.

### git push origin :(nombre de la rama)

Nos permite borrar una rama remota. Ojo es muy importante los dos puntos.

### git checkout (nombre de rama)

Sirve para dirijirse y comenzar a trabajar en la rama que se menciona en el comando.

### git checkout -b (nombre de la nueva-rama)

Sirve para crear una nueva rama y ya situarse en ella para comenzar a trabajar.
