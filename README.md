# Modelado de Ruido Markoviano y Marco de Extracción de Parámetros para Dispositivos Cuánticos

Este repositorio contiene los Notebooks de Jupyter en Python utilizados para la obtención de datos en el reciente artículo de investigación:

**Brand, D., Sinayskiy, I. y Petruccione, F.**  
*Modelado de ruido Markoviano y marco de extracción de parámetros para dispositivos cuánticos*.  
Sci Rep 14, 4769 (2024).  
[https://doi.org/10.1038/s41598-024-54598-5](https://doi.org/10.1038/s41598-024-54598-5)

## Estructura de los Notebooks

Los cuatro notebooks incluidos en este repositorio tienen una estructura similar, pero están especializados para diversos procedimientos experimentales. La estructura general es la siguiente:

- **Conexión a computadoras cuánticas de IBM y definiciones de constantes**  
- **Creación de circuitos cuánticos y ejecución en el backend de los mismos**  
- **Mitigación de errores**  
- **Gráficas de resultados**  
- **Cálculos numéricos**  
- **Gráficas de resultados predichos**  
- **Optimización de parámetros**  
- **Gráficas de resultados ajustados**  
- **Extracción de parámetros del hardware**

## Requisitos

Los notebooks son interactivos y pueden ejecutarse en cualquier servidor de Jupyter. Fueron creados utilizando **Python 3.9.5**, y todos los paquetes necesarios están listados en el archivo `requirements.txt`.

## Cómo Usar

1. Instala los requisitos utilizando el siguiente comando:  
   ```bash
        pip install -r requirements.txt
    ```