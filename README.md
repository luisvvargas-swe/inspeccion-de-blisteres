# Inspección de blísteres

[Abrir el simulador](https://luisvvargas-swe.github.io/inspeccion-de-blisteres/) · [Portafolio de Luis Vargas](https://luisvvargas-swe.github.io/)

Laboratorio de visión artificial que analiza los píxeles de una imagen sintética de diez cavidades para identificar tabletas presentes, cavidades vacías y posibles fracturas. Está implementado con JavaScript y Canvas 2D y se ejecuta completamente en el navegador.

## Probarlo

Abre `index.html` en un navegador actual. Elige una muestra y activa o desactiva las marcas para comparar la imagen original con el resultado de la inspección.

| Muestra | Tabletas íntegras | Observación |
| --- | --- | --- |
| Completa | 10 de 10 | Diez cavidades ocupadas. |
| Una cavidad vacía | 9 de 10 | Cavidad vacía en fila 1, columna 4. |
| Cavidad vacía y fractura | 8 de 10 | Cavidad vacía en fila 1, columna 4, y fractura en fila 2, columna 2. |

El generador dibuja las tabletas y el detector lee la imagen en diez regiones fijas. Para cada región estima la fracción de píxeles oscuros. Los umbrales están ajustados a estas muestras sintéticas.

## Autoría y procedencia

Luis Armando Vargas Peña · Proyecto personal de portafolio, con asistencia de IA en la implementación. La experiencia de Luis en inspección industrial con YOLOv8 y OpenCV inspiró esta recreación didáctica. El simulador emplea código independiente e imágenes generadas en el navegador. Los conteos de esta tabla corresponden únicamente a sus tres muestras.
