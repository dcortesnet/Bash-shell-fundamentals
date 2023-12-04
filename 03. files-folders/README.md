# Comandos de manipulación de archivos y carpetas

### Crear y editar archivos

- `touch [nombre_del_archivo]`: Crear un archivo vacío o actualizar la fecha de modificación.
- `nano  [nombre_del_archivo]` : Editar un archivo en un editor de texto en la terminal.

### Ver el contenido de un archivo

- `cat [nombre_del_archivo]`: Mostrar el contenido completo de un archivo.
- `tail -n 10 [nombre_del_archivo]`: Se utiliza para mostrar las últimas líneas de un archivo.

### Copiar, mover y renombrar archivos

- `cp [archivo_origen] [destino]`: Copiar archivos.
- `mv [archivo_origen] [destino]`: Mover o renombrar archivos.

### Eliminar archivos

- `rm [nombre_del_archivo]`: Eliminar archivos.`
- `rm -r [nombre_del_directorio]/*`: Eliminar todos los archivos de un directorio de forma recursiva.

### Crear y editar directorios

- `mkdir [nombre_del_directorio]`: Crear un nuevo directorio.
- `mkdir -p [nombre_del_directorio]/[nombre_del_directorio]`: Crear un nuevo directorio anidado.

### Copiar, mover y renombrar directorios

- `cp -r [directorio_origen] [destino]`: Copiar directorios y su contenido de manera recursiva.
- `mv [directorio_origen] [destino]`: Mover o renombrar directorios.

### Eliminar directorios

- `rmdir [nombre_del_directorio]`: Eliminar un directorio vacío.
- `rm -r [nombre_del_directorio]`: Eliminar un directorio y su contenido de manera recursiva.
