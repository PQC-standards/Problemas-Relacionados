# Sobre el nuevo estándar de encapsulado de clave (KEM) post–cuántico

![image](https://github.com/user-attachments/assets/65c9aa92-a7f1-4685-9d1e-272ca69c054c)

**Realizado por:**  
[Gabriel Vacaro Goytia](https://github.com/Gabrielvcg) (gabvacgoy@alum.us.es)  
[Ignacio Warleta Murcia](https://github.com/ignaciowarleta) (ignwarmur@alum.us.es) <br>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PQC-standards/Problemas-Relacionados/main)
![example workflow](https://github.com/PQC-standards/Problemas-Relacionados/actions/workflows/notebook-test.yml/badge.svg)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5426d46a29ee439a8a58929da4363fa8)](https://app.codacy.com/gh/PQC-standards/Problemas-Relacionados/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) <br>
![Python](https://img.shields.io/badge/python-3.8-blue)
![Versión](https://img.shields.io/badge/versión-1.0.5-blue)
![Última actualización](https://img.shields.io/github/last-commit/PQC-standards/Problemas-Relacionados)



En este repositorio se encuentran todos los notebooks sobre los problemas relacionados a la criptografía basada en retículos. En los cuales se han desarrollado tanto herramientas para trabajar con las primitivas matemáticas como implementaciones de problemas más complejos. Todo explicado desde un punto de vista didáctico, con el objetivo de un acercamiento más cercano a la materia.

Este repositorio ha sido desplegado en Binder y puede lanzarse sin instalar nada pulsando el botón "Binder" al inicio del README.



## Contenido

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)

## Descripción del Proyecto

Este repositorio contiene los anexos sobre problemas relacionados realizados para el TFG «Sobre el nuevo estándar de encapsulado de clave (KEM) post–cuántico» del departamento de matemáticas de la ETSII. Realizado por Gabriel Vacaro e Ignacio Warleta, alumnos de ingeniería informática - ingeniería del software.

El proyecto tiene como objetivo complementar el trabajo de documentación e investigación que se ha realizado sobre el nuevo estándar del NIST KYBER-KEM de una forma didáctica. De forma que se pueda entender completamente la primitiva matemática en la que se basa la mayoría de algoritmos de criptografía post-cuántica, los retículos. Así como los problemas en los que se sustentan estos algoritmos.

Se recomienda mirar antes los notebook **Reticulos** y **Anillos** del repositorio **Fundamentos-Teoricos**

Los elementos principales del repositorio incluyen:

- Notebook sobre problemas relacionados con los retículos, donde se encuentran las implementaciones de los problemas **CVP**, **SVP** y **LWE**, explicados paso a paso.
- Notebook sobre problemas relacionados con los anillos, donde se encuentran las implementaciones de los problemas **MLWE** y **RLWE**, explicados paso a paso.

## Instalación

Para ejecutar este proyecto, podemos lanzarlo desde Binder o, para una instalacion en local, debemos seguir estos pasos:

1. Instalar Miniconda en el siguiente enlace: [https://docs.conda.io/projects/conda/en/stable/](https://docs.conda.io/projects/conda/en/stable/)

2. Iniciar el ejecutable **AnacondaPrompt** o una ventana de la terminal para crear un entorno virtual específico:  
   ```bash
   conda create -n <env-name>

3. Activar el entorno virtual creado
   ```bash
   conda activate <env-name>

4. Descargar dependencias necesarias:
   ```bash
   conda install matplotlib
   conda install numpy
   pip install lattpy
   pip install scikit-learn

5. Descargar jupyter notebook:
   ```bash
   pip install jupyter

6. Ejecutarlo con el comando:
   ```bash
   jupyter notebook

7. Clonar este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/PQC-standards/Problemas-Relacionados.git

## Uso

Una vez completados los pasos de instalación, puedes utilizar los notebooks de este repositorio para explorar y entender las primitivas matemáticas y los problemas relacionados con la criptografía post-cuántica. Sigue los pasos a continuación:

1. Iniciamos el entorno virtual:
   ```bash
   conda activate <env-name>

2. Iniciamos el servidor Jupyter Notebook:
   ```bash
   jupyter notebook

3. Selecciona un notebook

Desde la interfaz de Jupyter Notebook, navega al directorio donde clonaste este repositorio y selecciona el notebook que deseas explorar:<br>

  - Notebook sobre LattPy para aprender sobre retículos y su implementación en Python.
  - Notebook sobre problemas relacionados con los retículos, como CVP, SVP, y LWE, explicados paso a paso.
  - Notebook sobre problemas relacionados con los anillos, como MLWE y RLWE, con implementaciones detalladas.

4. Ejecuta las celdas del notebook:
   
Sigue las instrucciones y explicaciones proporcionadas en el notebook. Cada celda contiene código y comentarios diseñados para facilitar la comprensión de los conceptos.

5. Experimenta:
   
Modifica el código o los parámetros según sea necesario para explorar los conceptos más a fondo.

## Contribución

Si quieres contribuir a este proyecto, nos encantaría tu ayuda. Sigue estas pautas para colaborar:

1. Haz un fork de este repositorio para tener tu propia copia.
   
2. Crea una rama para tu contribución:
   ```bash
   git checkout -b feature/nuevamejora

3. Realiza los cambios en la rama. Asegúrate de que sean claros y estén bien documentados.

4. Haz commit de tus cambios:
   ```bash
   git commit -m "Añadir descripción breve del cambio"

5. Sube tus cambios a tu repositorio remoto:
   ```bash
   git push origin feature/nueva-mejora

6. Crea una pull request hacia este repositorio explicando detalladamente los cambios que has realizado.
   








