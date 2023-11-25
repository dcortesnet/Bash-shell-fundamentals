## Ejemplos de comandos con pipe

### Sintaxis Básica

La sintaxis básica para utilizar un pipe es:

```bash
comando1 | comando2
```

### Concatenar y filtrar archivos utilizando pipe

- `cat`: Concatenar el contenido de varios archivos y enviarlo a `grep` para filtrar líneas que contengan la palabra "error":
  ```bash
  cat archivo1.txt archivo2.txt | grep "error"
  ```
