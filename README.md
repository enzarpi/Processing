# Big Data Processing - Examen Final

Este proyecto contiene la resolución de los ejercicios del examen final para la asignatura de procesamiento de datos en Big Data. Los ejercicios están desarrollados en Scala utilizando Apache Spark.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

. ├── src │ ├── main │ │ └── scala │ │ └── examen │ │ ├── Examen.scala # Contiene la implementación de los 5 ejercicios │ │ └── Main.scala # Programa principal para ejecutar los ejercicios │ └── test │ ├── resources │ │ └── ventas.csv # Datos de ejemplo para el Ejercicio 5 │ └── scala │ └── examen │ └── examenTest.scala # Tests unitarios para verificar los ejercicios ├── build.sbt # Configuración del proyecto con SBT └── README.md # Documentación del proyecto


## Ejercicios

### Ejercicio 1: Filtrar y Ordenar Estudiantes
Filtra estudiantes con una calificación mayor a 8 y los ordena de forma descendente según la calificación.

### Ejercicio 2: Clasificación de Números (Par o Impar)
Clasifica una lista de números en "Par" o "Impar" usando UDFs.

### Ejercicio 3: Promedio de Calificaciones
Calcula el promedio de calificaciones por estudiante utilizando un `join` entre dos DataFrames.

### Ejercicio 4: Conteo de Palabras
Cuenta las ocurrencias de palabras en una lista utilizando RDDs.

### Ejercicio 5: Cálculo de Ingresos Totales por Producto
Calcula el ingreso total por producto basado en los datos del archivo `ventas.csv`.

### Tests:
Contiene los tests, para verificar el correcto funcionamiento de los ejercicios.
examenTest.scala
