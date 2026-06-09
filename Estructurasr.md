[Regresar](UNIDAD2.md)
# ESTRUCTURAS REPETITIVAS

## WHILE
Un bucle while es una estructura de control que ejecuta un bloque de código de forma repetitiva cuando una condición es verdadera. Si la condición es falsa el ciclo se detiene.

Se utiliza cuano no se conoce de antemano el número de repeticiones que realizará un programa, la condición se evalúa antes de cada repetición, es por esto que el bloque de código no se ejecuta si la primera vez que se evalúa la condición es falsa. Es muy importante el uso de un incremento o decremento, si no se lo implementa el programa entrará en un bucle infinito.

Su estructura en diagrama de flujo es:

<img width="421" height="319" alt="image" src="https://github.com/user-attachments/assets/37ec8ae4-eb15-42b4-93ce-6d10f1dad0b3" />

Su sintaxis básica es:

```
while (condición){
  <acción 1>
}
```
[Volver al inicio](#indice)

## DO-WHILE
Es una estructura de control que ejecuta un bloque de código de forma repetitiva cuando la condición es falsa o verdadera, a diferencia de while tradicional, el bloque se ejecuta mínimo una vez antes de verificar una condición. Si la condición se cumple se repite el bucle y si no, sale del ciclo.

Su estructura en diagrama de flujo es:

<img width="360" height="307" alt="image" src="https://github.com/user-attachments/assets/c284f986-8d66-4af4-a85a-9fa9f79c5d3b" />

Su sintaxis básica es:

```
do {
  <acción 1>
} while (condición);

```
[Volver al inicio](#indice)

## FOR
Es una estructura de control que permite ejecutar un bloque de código repetitivo sabiendo el número de iteraciones que va a realizar, este tiene tres componentes, la inicialización dónde se le asigna un valor a la variable, después va la condición y por último va el incremento o decremento.

Su estructura en diagrama de flujo es:
<img width="295" height="214" alt="image" src="https://github.com/user-attachments/assets/4b4f5f39-d61e-4037-bd03-e52ea02ad26b" />

Su sintaxis básica es:

```
for (inicialización, condición, inc|dec){
  <acción 1>
}
```

[Volver al inicio](#indice)
