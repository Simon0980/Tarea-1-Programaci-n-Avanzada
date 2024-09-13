# Tarea-1-Programaci-n-Avanzada
Tarea 1 Programación Avanzada

# Pregunta Teóricas

## 1

Es un esquema o modelo que sigue un conjunto particular de ideas o patrones. Este incluye teorías, métodos de investigación, principios y normas que establecen qué se considera una aportación válida en un área específica. Es como se orientan los modelamientos un problema en programación. Dentro de estos se encuentran los paradigmas imperativos, que son de los más antiguos y están estrechamente relacionados con la arquitectura de la máquina. Se basan en una secuencia de instrucciones que modifican el estado del programa paso a paso.

## 2

Es un enfoque para organizar programas modulares, representando conceptos del mundo real mediante la abstracción de datos y agrupación de infomración. Consiste en agrupar información y comportamientos relacionados dentro de objetos, que tienen su propio estado local y saben cómo gestionarlo. Las interacciones entre objetos se realizan mediante llamadas a métodos, que actúan como mensajes enviados entre ellos. Además, múltiples objetos pueden ser instancias de un mismo tipo, y diferentes tipos pueden establecer relaciones entre sí. 

## 3 

La recursividad es que una función se llama a sí misma hasta alcanzar una condición base, mientras que la iteración repite un bloque de código hasta que se cumple una condición de parada. La notación big O puede verse como un calculo de la eficiencia del problema en términos de tiempo. La complejidad de la recursividad puede ser más alta dependiendo del problema (en términos de Big O), mientras que la iteración tiende a ser más predecible ya que generalmente depende del tamaño de los datos en el input.

##4

Un algoritmo con complejidad O(1) tiene un tiempo de ejecución constante, lo que significa que el tiempo no cambia aunque el tamaño de la entrada si lo haga. En cambio, un algoritmo O(n) tiene un tiempo de ejecución que crece de manera lineal con el tamaño de los datos.

## 5 

Se obtiene calculando la complejidad de cada una de sus etapas y luego combinando esos resultados.

## 6

Si el algoritmo divide el problema de forma recursiva, se ve la condición que debe cumplir para que no se resuelva recursivamente, es decir, el caso base. Después se tiene la recursión que divide el problema en x cantidad de subproblemas de tamaño n/q en un problema de tamaño a<n. Así, se calcula el Teorema del maestro como T(n) = x*T(n/q) + C*(n^r), y dependiendo de los valores de p y q^r, se obtienen notaciones big O que dan cuenta de la complejidad de un programa.
