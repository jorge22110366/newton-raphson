# newton-raphson
Este es un programa de métodos numéricos.
Introduciendo al tema…

En este proyecto se planteó a partir de un método que se ve en métodos numéricos, una materia la cual nos ayuda a deducir múltiples raíces matemáticas y el acercamiento a una raíz 0. En este caso vamos a hacerlo guiado a un método llamado “método de bisección”. El método de bisección es un algoritmo de búsqueda de raíces que trabaja dividiendo el intervalo a la mitad y seleccionando el subintervalo que tiene la raíz. Esto se logra llevar a cabo a través de varias interaciones que son aplicadas en un intervalo para por medio de ello encontrar la raíz de la función. Este es uno de los métodos más sencillos y de fácil intuición para resolver ecuaciones en una variable, también conocido como método del intervalo medio, este se basa en el teorema del valor intermedio, el cual establece que toda función continua f en un intervalo cerrado [a, b] toma todos los valores que se hallan entre f(a) y f (b). Esto es que todo valor entre f(a) y f (b) es la imagen de al menos un valor del intervalo [a, b].En caso de que f(a) y f (b) tengan signos opuestos, el valor cero sería un valor intermedio entre f (j) y f (e), por lo que con certeza existe un p en [a, b] que cumple f (p)=0. De esta forma, se asegura la existencia de al menos una solución de la ecuación f (a)=0.
EL METODO CONSISTE 
El método de Newton-Raphson es un algoritmo utilizado para encontrar aproximaciones sucesivas de las raíces de una función. Es un método iterativo que puede converger rápidamente hacia una solución cercana.

El método de Newton-Raphson se basa en la idea de que una función se puede aproximar por su tangente en un punto cercano a una raíz. La tangente a la curva en ese punto se extiende hasta el eje x, y la intersección de esa recta con el eje x proporciona una mejor aproximación de la raíz.

El algoritmo del método de Newton-Raphson se puede resumir en los siguientes pasos:

Selecciona un punto inicial cerca de la raíz deseada.
Calcula la derivada de la función en ese punto.
Utiliza la fórmula de la recta tangente para encontrar la intersección con el eje x.
Este punto de intersección se convierte en el nuevo punto de partida para el siguiente cálculo.
Repite los pasos 2, 3 y 4 hasta que se alcance la precisión deseada o se haya alcanzado el número máximo de iteraciones.
En cada iteración, el método de Newton-Raphson mejora la aproximación a la raíz. La fórmula general para la iteración es:

x_(n+1) = x_n - f(x_n)/f'(x_n)

Donde x_n es la aproximación actual de la raíz, f(x_n) es el valor de la función evaluada en x_n, y f'(x_n) es la derivada de la función evaluada en x_n.

Es importante destacar que el método de Newton-Raphson puede no converger si el punto inicial está lejos de la raíz o si la función presenta comportamientos complicados cerca de la raíz, como puntos de inflexión o tangentes horizontales. También es posible que el método converja a una raíz incorrecta si hay múltiples raíces cercanas. Por lo tanto, se recomienda tener en cuenta estas consideraciones y realizar pruebas para verificar la convergencia y la precisión del método.
DESARROLLADORES DEL PROGRAMA 
JORGE ALEJANDRO MARTINEZ ALVAREZ DEL CASTILLO    22110366
JOSE RAMON GONZALEZ MARTIN 22110361

