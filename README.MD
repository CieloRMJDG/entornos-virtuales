# 🥪 Proyecto A 

## 📘 Descripción
Este proyecto muestra un algoritmo básico en Python que explica los pasos para preparar un sándwich.  
El objetivo es practicar la estructura de funciones y la ejecución de código dentro de un entorno virtual.


## ⚙️ Instalación y configuración

1. Crear un entorno virtual:
   ```bash
   python -m venv venv_1
```

2. Activar el entorno virtual:

   * En Windows:

     ```bash
     venv_1\Scripts\activate
     ```
   * En Linux/Mac:

     ```bash
     source venv_1/bin/activate
     ```

3. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Ejecutar el programa:

   ```bash
   python src/algoritmo_a.py
   ```

## 🧠 Funcionalidad principal

El archivo `algoritmo_a.py` contiene una función llamada `preparar_sandwich()` que imprime paso a paso el proceso de preparar un sándwich:

``` python
def preparar_sandwich():
    pasos = [
        "1. Tomar dos rebanadas de pan.",
        "2. Untar mayonesa en una rebanada.",
        "3. Colocar jamón y queso.",
        "4. Agregar lechuga y tomate.",
        "5. Poner la otra rebanada encima.",
        "6. Cortar el sándwich por la mitad.",
        "7. ¡Servir y disfrutar!"
    ]
    for paso in pasos:
        print(paso)
```

## 🧩 Librerías utilizadas

* `numpy`
* `pandas`
* `python-dateutil`
* `pytz`
* `six`
* `tzdata`


# 📊 Proyecto B - Algoritmo de Cálculos con Datos

## 📘 Descripción
Este proyecto utiliza las librerías **NumPy** y **Pandas** para realizar operaciones con datos numéricos.  
El propósito es aprender cómo manejar y analizar datos dentro de un entorno virtual independiente.


## ⚙️ Instalación y configuración

1. Crear un entorno virtual:
   ```bash
   python -m venv venv_2
````

2. Activar el entorno virtual:

   * En Windows:

     ```bash
     venv_2\Scripts\activate
     ```
   * En Linux/Mac:

     ```bash
     source venv_2/bin/activate
     ```

3. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Ejecutar el programa:

   ```bash
   python src/algoritmo_b.py
   ```

## 🧠 Funcionalidad principal

El archivo `algoritmo_b.py` realiza operaciones matemáticas y de análisis de datos simples, usando las librerías NumPy y Pandas.

Ejemplo de código:

```python
import numpy as np
import pandas as pd

def calcular_promedio():
    datos = np.array([10, 20, 30, 40, 50])
    promedio = np.mean(datos)
    print(f"El promedio de los datos es: {promedio}")

calcular_promedio()
```

## 🧩 Librerías utilizadas

* `numpy`
* `pandas`
* `python-dateutil`
* `pytz`
* `six`
* `tzdata`

## 🧾 Autor

Proyecto desarrollado por Cielo Rodriguez 





