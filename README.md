##  Contexto del Proyecto

Este proyecto consiste en la **simulación numérica de la transferencia de calor en estado transitorio** sobre una placa bidimensional. El objetivo principal fue modelar la evolución térmica de la placa desde un estado inicial hasta alcanzar el equilibrio, considerando interacciones complejas con el entorno.

###  Modelación Física y Matemática
A diferencia de modelos simplificados, esta simulación integra múltiples mecanismos de transferencia de calor:

1. **Conducción Interna**: Modelada mediante la discretización de las ecuaciones diferenciales parciales (EDP) espaciales utilizando el método de diferencias finitas con el enfoque de Crank Nicolson.
2. **Convección**: Se implementó el enfriamiento por interacción con el fluido circundante, siguiendo la Ley de Enfriamiento de Newton.
3. **Radiación Térmica**: Se incluyó la pérdida de energía por radiación (proporcional a $T^4$), lo que introduce una no-linealidad importante en el sistema y aumenta la complejidad del cálculo numérico.
