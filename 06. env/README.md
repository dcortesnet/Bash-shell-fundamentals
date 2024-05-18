# Comandos para variables

### 1. `env`

El comando env se utiliza para mostrar o modificar el entorno de ejecución de un programa. El entorno de ejecución incluye variables de entorno que afectan el comportamiento y configuración del sistema y las aplicaciones.

```bash
$ env
$ echo $[VARIABLE] # Mostrar el valor de una variable de entorno específica.
```

- Variables por defecto
  - `$HOME`: Ruta al directorio de inicio del usuario.
  - `$USER` o `$LOGNAME`: Nombre del usuario.
  - `$PATH`: Lista de directorios donde el sistema busca comandos.
  - `$PWD`: Ruta al directorio de trabajo actual.

### 2. `export`

El comando export se utiliza para establecer o exportar variables de entorno. Cuando creas una variable en una sesión de terminal, esa variable no está disponible automáticamente para otros procesos o sesiones de terminal. El comando export se utiliza para hacer que una variable de entorno sea accesible para procesos secundarios.

```bash
export [VARIABLE]=[valor_variable] # Establecer el valor de una variable de entorno.
export [VARIABLE]=[nuevo_valor_variable] # Modificar el valor de una variable de entorno existente.

```

### 3. `unset`

El comando unset se utiliza para eliminar variables de entorno o deshacer asignaciones de variables. Cuando usas unset seguido por el nombre de una variable, elimina esa variable de la sesión de la terminal actual.

```bash
$ unset [VARIABLE]
```
