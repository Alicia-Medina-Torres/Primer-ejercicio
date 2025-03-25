# Primer-ejercicio

Mini Proyecto 1: Procesamiento de Operaciones Matemáticasasdf
Este proyecto genera operaciones matemáticas aleatorias (suma, resta, multiplicación, división y potenciación), las procesa y guarda los resultados en archivos CSV.

# Estructura del Proyecto

    mini-proyecto-1/  
    │  
    ├── data/  
    │   ├── math_operations.csv          # Archivo con operaciones generadas  
    │   └── math_operations_totalizado.csv  # Archivo con operaciones + resultados  
    │  
    ├── main.py                          # Script principal  
    └── README.md                        # Este archivo  


# Requisitos

1.    Python 3.8+
2.    Librerías necesarias:

    pip install pandas

3.    Ejecutar el programa:

    python main.py


# Menú Principal

Al ejecutar main.py, se muestra un menú con las siguientes opciones:

1.    Lectura y Procesamiento de Datos

Genera un archivo math_operations.csv con 1000 operaciones aleatorias (SUM, SUB, MUL, DIV, POW).

Guarda el archivo en ./data/.

2.    Actualización del Archivo CSV

Toma las operaciones generadas, las procesa y calcula sus resultados.

Guarda un nuevo archivo math_operations_totalizado.csv con las operaciones y sus resultados.

Si un resultado es mayor a 1,000,000, se marca como "Muy Largo".

Si hay una división por cero, se guarda como None.

3.    Salir

Termina la ejecución del programa.

# math_operations_totalizado.csv

Contiene las operaciones junto con sus resultados:

    operation	operand_1	operand_2	Resultado
    SUM	10	20	30
    DIV	100	5	20.0
    POW	2	8	256
    DIV	10	0	None
    MUL	5000	5000	Muy Largo
