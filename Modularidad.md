[Regresar](UNIDAD3.md)

# MODULARIDAD
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

<img width="607" height="290" alt="image" src="https://github.com/user-attachments/assets/4dc80b7e-eb85-4ec8-828a-c50cc15a63b1" />

### Por referencia
Comparte la dirección de memoria exacta donde se aloja el dato original. La función no tranaja con una copia, sino que opera directamente sobre la misma variable del programa principal.

<img width="686" height="255" alt="image" src="https://github.com/user-attachments/assets/a23a980e-e812-48d7-879f-560857cef8b6" />
