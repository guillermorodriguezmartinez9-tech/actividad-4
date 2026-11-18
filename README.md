# Implementación y Análisis de un Sistema de Modulación en Amplitud (AM)

## Introducción
La modulación en amplitud (AM) es una técnica fundamental en las telecomunicaciones que permite transmitir señales de información de baja frecuencia a través de largas distancias, variando la amplitud de una onda portadora de alta frecuencia en proporción directa al mensaje original[cite: 1]. 

El presente proyecto tiene como objetivo implementar y analizar computacionalmente un sistema de modulación AM mediante el uso de Python y sus librerías científicas (`NumPy`, `SciPy` y `Matplotlib`)[cite: 1]. A lo largo de esta simulación, se examinará el comportamiento de la señal modulada tanto en el dominio del tiempo como en el de la frecuencia mediante la Transformada Rápida de Fourier (FFT)[cite: 1]. Asimismo, se evaluará el desempeño y la vulnerabilidad del sistema ante condiciones reales de transmisión, tales como la presencia de ruido blanco gaussiano, la atenuación por pérdida de potencia y la distorsión generada por fenómenos de sobremodulación[cite: 1].

## Contenido del repositorio
* `modulacion_am.py`: Código fuente en Python con la generación de la señal mensaje, modulación AM, análisis espectral (FFT) y simulación de ruido, atenuación y distorsión[cite: 1].

## Requisitos para ejecutar
```bash
pip install numpy scipy matplotlib
