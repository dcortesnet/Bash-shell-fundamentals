# Comandos de manipulación de archivos y carpetas

### 1. `touch`

El comando touch es utilizado para crear archivos vacíos y actualizar las marcas de tiempo de archivos existentes. Su función principal es crear un archivo sin necesidad de contenido

```bash
$ touch [nombre_del_archivo]
```

### 2. `cp`

El comando cp se utiliza para copiar archivos y directorios. Su nombre proviene de "copy" (copiar). Este comando permite crear duplicados de archivos o directorios, ya sea en el mismo directorio o en otro directorio especificado.

```bash
$ cp [archivo_origen] [destino]
```

### 3. `mv`

El comando mv se utiliza para mover o renombrar archivos y directorios. Su nombre proviene de "move" (mover). Este comando permite cambiar la ubicación de un archivo o directorio o cambiar su nombre.

```bash
$ mv [archivo_origen] [destino]
```

### 4. `rm`

El comando rm se utiliza para eliminar (borrar) archivos y directorios. Su nombre proviene de "remove" (eliminar). Es un comando poderoso y debes usarlo con precaución, ya que los archivos eliminados con rm no se envían a la papelera de reciclaje y se pierden de forma permanente.

```bash
$ rm [nombre_del_archivo]
$ rm -r [nombre_del_directorio]/* # Recursivo
```

### 5. `mkdir`

El comando mkdir se utiliza para crear (o hacer) un nuevo directorio (carpeta). El nombre mkdir es una abreviatura de "make directory" (crear directorio).

```bash
$ mkdir [nombre_del_directorio]
$ mkdir -p [nombre_del_directorio]/[nombre_del_directorio] # Anidado
```

### 6. `nano`

Nano es un editor de texto en la línea de comandos. Es una herramienta ligera que ofrece una interfaz de usuario amigable y es comúnmente utilizada en sistemas Unix y Linux.

```bash
$ nano
```

- Algunos comandos básicos de nano son:

  - Ctrl + O: Guardar el archivo.
  - Ctrl + X: Salir del editor.
  - Ctrl + G: Mostrar ayuda.