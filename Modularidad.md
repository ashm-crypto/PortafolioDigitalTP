[Regresar](UNIDAD3.md)

# 📗 MODULARIDAD

- [Concepto](#Concepto)
- [Funciones](#Funciones)
- [Pase de parametros](#Pase-de-parametros)
  
## Concepto
La programación modular es un modelo de diseño de software basado en la técnica de "divide y vencerás". Cuando un desarrollador se enfrenta a algoritmos extensos la modularización permite fraccionar ese programa de gran escala en subprogramas mucho más pequeños.
A estos bloques de construcción se les conoce como funciones, procesos, rutinas, subrutinas o procedimientos.

## Funciones
Son un conjunto de sentencias estructuradas que responde a un proposito único. Se dividen en dos:
- Funciones predeterminadas: Son funciones que ya vienen integradas en el entorno a través de librerías del sistema.
- Funciones definidas: Son funciones diseñadas desde cero por el programador y deben de estar ancladas a un programa principal o función conductora (main).

Su sintaxis consta de la cabecera y el cuerpo, la cabeza indica el tipo de dato que va a retornar la función, su nombre y la lista de parámetros que necesita recibir para operar.
El cuerpo, en cambio, contiene las variables locales de acceso restringido y el conjunto de instrucciones encerradas entre llaves que ejecutan la tarea.


## Pase de parametros
### Por valor
Realiza una copia exacta de un contenido de la variable original y se la entrega a la función. El módulo trabaja únicamente con esa copia dentro de su propio bloque de memoria. Esto quiere decir que cualquier modificación que se realice dentro de la función no altera ni afecta al dato original que se encuentra en el programa principal.

## Ejemplo
Una tienda departamental quiere mostrar a sus clientes en una pantalla interactiva cuántos puntos de recompensa obtendrían si se inscribieran a la promoción "Doble Puntuación". Sin embargo, como es solo una simulación previa, el saldo real de puntos del cliente no debe modificarse en el sistema principal.

<img width="555" height="268" alt="image" src="https://github.com/user-attachments/assets/ebcda367-bb5b-40d3-acb4-33372eab0790" />


Salida

<img width="262" height="32" alt="image" src="https://github.com/user-attachments/assets/bee1bef0-3620-474a-b0b6-90408ff71ff8" />

### Por referencia
Comparte la dirección de memoria exacta donde se aloja el dato original. La función no tranaja con una copia, sino que opera directamente sobre la misma variable del programa principal.

## Ejemplo
En un videojuego, un personaje tiene una estadística de fuerza base. Al seleccionar una habilidad especial, la interfaz calcula temporalmente cuánto daño causaría si su fuerza se duplicara. No obstante, la fuerza base del personaje en su ficha de perfil debe permanecer intacta.

<img width="492" height="258" alt="image" src="https://github.com/user-attachments/assets/9dc0ea48-3640-48f9-9b82-28762d8753eb" />


Salida

<img width="249" height="36" alt="image" src="https://github.com/user-attachments/assets/6349edef-a7a7-47c9-81ac-c0af0442f612" />


[Volver al inicio](#modularidad)
