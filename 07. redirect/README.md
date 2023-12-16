# Operadores para redireccionar

### 1. `>`

El operador > en la línea de comandos se utiliza para redirigir la salida estándar de un comando hacia un archivo o para crear y escribir en un archivo. Este operador toma la salida del comando a su izquierda y la redirige hacia el archivo especificado a su derecha, creando o sobrescribiendo el archivo si ya existe.

```bash
echo "Hola, mundo" > archivo.txt
```

### 2. `>>`

El operador >> en la línea de comandos se utiliza para redirigir la salida estándar de un comando hacia un archivo, pero a diferencia de >, >> añade la salida al final del archivo en lugar de sobrescribir su contenido.

```bash
echo "Nueva línea" >> archivo.txt
```
