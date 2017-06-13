# Casos de Prueba para la Tarea 3

En este repositorio se incluyen casos de prueba para probar el funcionamiento
de la tarea 3 de _Estructura de Datos_ (2017-1)

## Modo de uso
- Descargar la última versión de los casos de uso [aquí][latest]

- Ejecutar su programa como se indica en el enunciado de la tarea
  ```bash
  ./ejecutable < caso_de_prueba_específico.dat
  ```

- Para facilitar la comparación entre su output y la solución, guardar la salida
  de su programa en un archivo con el _operador_ `>`
  ```bash
  ./ejecutable < caso_prueba.dat > output.dat
  # Ahora el output de su programa queda guardado en output.dat
  ```

- Para comparar su resultado con la solución, se recomienda usar la herramienta
  `diff` de `git`, que muestra las diferencias entre los archivos, usando una
  interfaz colorida.
  ```bash
  git diff --no-index --minimal --word-diff solucion_real.dat output.dat
  ```
  Dicho comando indicará las diferencias entre la solución y su archivo, en
  el caso de que estas existan. (Se marca con rojo lo eliminado del archivo
  de solución, y con verde el texto con el que se reemplazó lo eliminado)

- En caso de no tener `git` instalado, lo puede instalar (en Ubuntu) con
  ```bash
  sudo apt install -y git
  ```

## Notas extra
- Con el tiempo, es posible que se agreguen más casos de prueba, por lo que debe
  revisar este repositorio periódicamente.

[latest]: https://github.com/mweitzman/casos_edd_3/releases/latest
