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

<img width="618" height="288" alt="image" src="https://github.com/user-attachments/assets/814c9ba3-bcba-4cc3-9297-cb38489b4b52" />

Salida

<img width="324" height="33" alt="image" src="https://github.com/user-attachments/assets/fdd3a71a-50f9-4356-b6f1-afeaf1c127fc" />


### Por referencia
Comparte la dirección de memoria exacta donde se aloja el dato original. La función no tranaja con una copia, sino que opera directamente sobre la misma variable del programa principal.

<img width="608" height="326" alt="image" src="https://github.com/user-attachments/assets/bca8560a-7a3b-434e-a60c-5f2130451702" />

Salida

<img width="315" height="39" alt="image" src="https://github.com/user-attachments/assets/8a07dd89-2d9b-4093-beb9-6ec368c03451" />

[Volver al inicio](#modularidad)
