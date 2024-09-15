La primera sección del archivo "Desarrollo.ipynb" contiene la sección teórica en la cual se responden las siguientes preguntas:
• ¿Qué es un paradigma de programación?
• ¿En qué se basa la programación orientada a objetos?
• ¿Cuál es la diferencia entre recursividad e iteración, y cómo se relaciona esto con la notación
  big 𝑂?
• explicar la diferencia de rendimiento entre 𝑂(1) y 𝑂(𝑛)
• ¿Cómo se calcula el orden en un programa que funciona por etapas?
• ¿Cómo se puede determinar la complejidad temporal de un algoritmo recursivo?

Adicionalmente, se discute el denominado "Teorema Maestro" y sus usos en el cálculo de la complejidad temporal de los algoritmos.

En la segunda parte se realiza la implementación de 2 métodos para el cálculo de todos los caminos posibles entre 2 puntos separados por una distancia de (m,n) , con:
• m: espacios de separación hacia abajo
• n: espacios de separación hacia la derecha

El primer método está basado en el cálculo de todas las permutaciones únicas entre (m+n) elementos de un conjunto de m veces a y n veces d, y su posterior transformación a valores numéricos.
El segundo método está basado en el recorrido recursivo del conjunto de datos. 

Ambos métodos son comparados mediante casos homólogos y los resultados son graficados para su mejor apreciación.
