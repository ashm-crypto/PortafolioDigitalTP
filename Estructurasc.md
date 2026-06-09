[Regresar](#UNIDAD2.md)

<a id="indice"></a>

# ESTRUCTURAS CONDICIONALES

- [Estructuras condicionales simples](#Estructuras-condicionales-simples)
- [Estructuras condicionales dobles](#Estructuras-condicionales-dobles)
- [Estructuras condicionales múltiples](#Estructuras-condicionales-múltiples)
  
## Estructuras condicionales simples
Las estructuras condicionales simples permiten a un programa tomar decisiones y ejecutar diferentes bloques de código según se cumpla o no la condición lógica, si la condición es verdadera ejecuta el bloque de código. Si es falso el programa salta a la siguiente instrucción.
<br>
### IF
Un if es una estructura condicional que permite a un programa tomar deciosiones.
Su estructura en diagrama de flujo es:

<img width="522" height="357" alt="image" src="https://github.com/user-attachments/assets/311ff6ae-0239-462f-bfbf-64974723d2ca" />

Su sintaxis básica es:
``` 
if (condicion){
  <acción 1>;
{
``` 
[Volver al inicio](#indice)

## Estructuras condicionales dobles
Las estructuras condicionales dobles ejecutan diferentes bloques de código, si la condición es verdadera realiza una acción y si la condición es falsa realiza una acción alternativa, a diferencia de una estructura simple, que solo se ejecuta cuano la condición es verdadera, la estructura doble asegura que el sistema ejecutará un bloque.

### IF-ELSE
Un if-else es una estructura condicional doble, su estructura en diagrama de flujo es:

<img width="535" height="316" alt="image" src="https://github.com/user-attachments/assets/7235ff5b-a412-4052-a666-f5813250c71d" />

Y sintaxis básica es:

```
if (condicion){
  <acción 1>;
] else {
  <acción 2>;
```
[Volver al inicio](#indice)

## Estructuras condicionales múltiples
Las estructuras condicionales múltiples evalúan una variable y ejecutan diferentes bloques de código según el valor que tome. Se basa en el cumplimiento de una condición pero en lugar de evaluar si la condición es verdadera o falsa, lo que hace es tomar una variable y evaluar que valor exacto tiene y dependiendo de ese valor el programa salta al caso que coincida y ejecuta el bloque de código.

### SWITCH/CASE
Es una estructura condicional múltiple, sus componentes principales son:
1. Switch: Es el encargado de evaluar la variable.
2. Case: Representa un valor en específico, si ese valor coincide con el evaluado se ejecuta el bloque de código.
3. Break: Detiene la ejecución para salir del switch.
4. Default: Se ejecuta cuando la varibale no coincide con ninguno de los casos anteriores.

Su estructura en diagrama de flujo es:

<img width="850" height="362" alt="image" src="https://github.com/user-attachments/assets/995e6263-069d-43ef-b0a5-30894ddf1d15" />

Y su sintaxis básica es:

```
switch (variable){
  case 1:
    <acción 1>;
    break;
  case 2:
    <acción 2>
    break;
  default
    <acción 3>
}
```

### IF-ELSE IF
Un if - else if es una estructura condicional que permite tomar decisiones múltiples, evalúa una serie de condiciones en cadena y ejecuta unicamente el bloque de código de la cóndición verdadera.

Su estructura en diagrama de flujo es:

<img width="421" height="305" alt="image" src="https://github.com/user-attachments/assets/161638a0-b8a3-480d-8258-4a2ed5ab5c47" />

Y su sintaxis básica es:

```
if (condición 1){
  <acción 1>
} else if (condición 2) {
  <acción 2>
} else {
  <acción 3>
```
[Volver al inicio](#indice)
