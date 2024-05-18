# Comandos para visualización de archivos y carpetas

### 1. `ls`

El comando "ls" es utilizado para listar el contenido de un directorio. Su nombre proviene de "list" (listar). Cuando ejecutas ls en la línea de comandos, obtienes una lista de archivos y directorios en el directorio actual.

```bash
$ ls # Listar archivos y directorios en el directorio actual.
$ ls -l # Listar archivos y directorios en formato detallado.
$ ls -a # Listar todos los archivos, incluyendo los ocultos.
$ ls -R # Realiza un listado de manera recursiva, es decir, incluye los archivos y directorios de los subdirectorios.
$ ls *.sh # Realiza un listado de todos los archivos en el directorio actual que tienen la extensión ".sh"
```

### 2. `cat`

El comando cat se utiliza para concatenar y mostrar el contenido de archivos. Su nombre proviene de "concatenate" (concatenar), pero se utiliza comúnmente para imprimir el contenido de uno o varios archivos en la salida estándar (generalmente la pantalla o la consola).

```bash
$ cat [nombre_del_archivo]
```

### 3. `tail`

El comando tail se utiliza para mostrar las últimas líneas de un archivo de texto. Es particularmente útil para monitorear archivos de registro en tiempo real o para ver las últimas actualizaciones en archivos de registro o cualquier otro archivo de texto.

```bash
$ tail -n 10 [nombre_del_archivo]
```