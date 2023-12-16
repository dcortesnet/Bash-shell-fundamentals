# Comandos de manipulación de archivos y carpetas

### 1. `touch`

El comando touch es utilizado para crear archivos vacíos y actualizar las marcas de tiempo de archivos existentes. Su función principal es crear un archivo sin necesidad de contenido

```bash
touch [nombre_del_archivo]
```

### 2. `cat`

El comando cat se utiliza para concatenar y mostrar el contenido de archivos. Su nombre proviene de "concatenate" (concatenar), pero se utiliza comúnmente para imprimir el contenido de uno o varios archivos en la salida estándar (generalmente la pantalla o la consola).

```bash
cat [nombre_del_archivo]
```

### 3. `tail`

El comando tail se utiliza para mostrar las últimas líneas de un archivo de texto. Es particularmente útil para monitorear archivos de registro en tiempo real o para ver las últimas actualizaciones en archivos de registro o cualquier otro archivo de texto.

```bash
tail -n 10 [nombre_del_archivo]
```

### 4. `cp`

El comando cp se utiliza para copiar archivos y directorios. Su nombre proviene de "copy" (copiar). Este comando permite crear duplicados de archivos o directorios, ya sea en el mismo directorio o en otro directorio especificado.

```bash
cp [archivo_origen] [destino]
```

### 5. `mv`

El comando mv se utiliza para mover o renombrar archivos y directorios. Su nombre proviene de "move" (mover). Este comando permite cambiar la ubicación de un archivo o directorio o cambiar su nombre.

```bash
mv [archivo_origen] [destino]
```

### 6. `rm`

El comando rm se utiliza para eliminar (borrar) archivos y directorios. Su nombre proviene de "remove" (eliminar). Es un comando poderoso y debes usarlo con precaución, ya que los archivos eliminados con rm no se envían a la papelera de reciclaje y se pierden de forma permanente.

```bash
rm [nombre_del_archivo]
rm -r [nombre_del_directorio]/* # Recursivo
```

### 7. `mkdir`

El comando mkdir se utiliza para crear (o hacer) un nuevo directorio (carpeta). El nombre mkdir es una abreviatura de "make directory" (crear directorio).

```bash
mkdir [nombre_del_directorio]
mkdir -p [nombre_del_directorio]/[nombre_del_directorio] # Anidado
```
