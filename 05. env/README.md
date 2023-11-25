# Comandos para variables

### Mostrar variables de entorno

- `env`: Mostrar todas las variables de entorno.

- `echo $VARIABLE`: Mostrar el valor de una variable de entorno específica.
  - Ejemplo: `echo $HOME`

### Establecer variables de entorno

- `export VARIABLE=valor`: Establecer el valor de una variable de entorno.
  - Ejemplo: `export MI_VARIABLE="Hola, mundo"`

### Modificar variables de entorno

- `export VARIABLE=nuevo_valor`: Modificar el valor de una variable de entorno existente.
  - Ejemplo: `export PATH=$PATH:/ruta/nueva`

### Eliminar variables de entorno

- `unset VARIABLE`: Eliminar una variable de entorno.
  - Ejemplo: `unset MI_VARIABLE`

### Variables específicas

- `$HOME`: Ruta al directorio de inicio del usuario.

- `$USER` o `$LOGNAME`: Nombre del usuario.

- `$PATH`: Lista de directorios donde el sistema busca comandos.

- `$PWD`: Ruta al directorio de trabajo actual.
