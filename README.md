# Datos-Visualizacion

## Objetivo

La visualización científica es la transformación de datos científicos y abstractos en imágenes. Es una forma especial de la visualización. Este proyecto muestra un análisis estadístico de datos sobre sismos en Colombia desde 1993-2017 con manitud mayor a 4.0.  

## Contenido.

+ **ProyectoBorrador.ipynb**: Al comenzar este proyecto fue fácil practicar con los datos dados por el profesor y utilizados en la mayoría de las clases: `sismos-1993-2017.csv`. Por lo tanto, este archivo contiene la forma de graficar las tres animaciones de python que se generaron:  

    + **Figura1.mp4**: Muestra los sismos como barras en coordenadas polares en el pasar de los años.  
    
    + **Figura2.mp4**: Es un mapa que revela la ubicación de los sismos como puntos cuyos tamaños y color se reacionan con las magnitudes.  
    
    + **Figura3.mp4**: Representa la posible relación entre las magnitudes y profundidades de los sismos.  
    
    
+ **Datos.ipynb**: En este archivo se explica cómo fue la obtención y manipulación de los datos de la página de la Red Sismológica Nacional de Colombia RSNC y que posteriormente se denominó `sismos.xls` que debido a problemas de lectura, se interpretó con pandas como un archivo HTML.


+ **ProyectoFinal.ipynb**: Después de haber practicado con las tres figuras, se resumen o se colocan en un único ax donde se reproducen al mismo tiempo y es más clara la comparación y comprendimiento de la información. Este archivo generó: `Proyecto.mp4` donde se observa la animación de las tres gráficas. Esta parte del proyecto si utilizó el archivo actualizado descargado RSNC y explicado en el anterior archivo.


+ **AnálisisEstadístico.ipynb**: Este notebook representa una descripción estadística o un resumen de los datos. También representa gráficas de probabilidades y la explicación de cómo las figuras o animaciones representados revelan información.
