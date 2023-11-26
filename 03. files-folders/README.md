# Comandos de manipulación de archivos y carpetas

### Crear y editar archivos

- `touch`: Crear un archivo vacío o actualizar la fecha de modificación.

  - Ejemplo: `touch [nombre_del_archivo]`

- `nano` o `vim`: Editar un archivo en un editor de texto en la terminal.
  - Ejemplo: `nano [nombre_del_archivo]` o `vim [nombre_del_archivo]`

### Ver el contenido de un archivo

- `cat`: Mostrar el contenido completo de un archivo.

  - Ejemplo: `cat [nombre_del_archivo]`

- `tail`: Se utiliza para mostrar las últimas líneas de un archivo.
  - Ejemplo : `tail -n 10 [nombre_del_archivo]`

### Copiar, mover y renombrar archivos

- `cp`: Copiar archivos.

  - Ejemplo: `cp [archivo_origen] [destino]`

- `mv`: Mover o renombrar archivos.
  - Ejemplo: `mv [archivo_origen] [destino]`

### Eliminar archivos

- `rm`: Eliminar archivos.
  - Ejemplo: `rm [nombre_del_archivo]`

### Crear y editar directorios

- `mkdir`: Crear un nuevo directorio.
  - Ejemplo: `mkdir [nombre_del_directorio]`

### Copiar, mover y renombrar directorios

- `cp -r`: Copiar directorios y su contenido de manera recursiva.

  - Ejemplo: `cp -r [directorio_origen] [destino]`

- `mv`: Mover o renombrar directorios.
  - Ejemplo: `mv [directorio_origen] [destino]`

### Eliminar directorios

- `rmdir`: Eliminar un directorio vacío.

  - Ejemplo: `rmdir [nombre_del_directorio]`

- `rm -r`: Eliminar un directorio y su contenido de manera recursiva.
  - Ejemplo: `rm -r [nombre_del_directorio]`
