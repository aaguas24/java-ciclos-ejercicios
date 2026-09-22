# Ejercicios de ciclos en Java

Este repositorio contiene ejercicios para practicar los ciclos `while`, `do while` y `for` en Java.

## Objetivos

- Comprender cuándo utilizar cada tipo de ciclo.
- Practicar condiciones y contadores.
- Resolver problemas con ciclos simples y anidados.
- Validar datos introducidos por el usuario.

## Ejercicios con `while`

### 1. Contador ascendente

Solicita un número entero positivo y muestra los números desde `1` hasta ese número usando `while`.

**Ejemplo:**

```text
Entrada: 5
Salida: 1 2 3 4 5
```

### 2. Suma de números

Solicita números continuamente y acumula su suma. El ciclo debe terminar cuando el usuario introduzca `0`.

**Ejemplo:**

```text
Entrada: 4, 8, 3, 0
Salida: La suma es 15
```

### 3. Contraseña

Solicita una contraseña hasta que el usuario introduzca correctamente `java123`. Al final, muestra un mensaje de acceso concedido y la cantidad de intentos realizados.

### 4. Número positivo

Solicita números hasta que el usuario introduzca un número positivo. Si introduce un número negativo o cero, indica que debe intentarlo nuevamente.

### 5. Adivina el número

Crea un número secreto, por ejemplo `7`, y pide al usuario que lo adivine. Indica si el número introducido es mayor, menor o igual al número secreto. El programa termina cuando el usuario acierta.

## Ejercicios con `do while`

### 6. Menú de opciones

Crea un menú que se repita hasta que el usuario seleccione la opción `4`:

```text
1. Saludar
2. Mostrar fecha
3. Mostrar mensaje
4. Salir
```

Cada opción debe realizar una acción diferente.

### 7. Calculadora básica

Crea una calculadora que permita realizar operaciones repetidamente:

```text
1. Sumar
2. Restar
3. Multiplicar
4. Dividir
5. Salir
```

Solicita dos números para cada operación y controla el caso de división entre cero.

### 8. Validar calificación

Solicita una calificación entre `0` y `10`. Mientras el valor sea inválido, vuelve a pedirlo. Cuando sea válida, muestra un mensaje indicando que fue registrada correctamente.

### 9. Juego de lanzamiento de dado

Simula el lanzamiento de un dado usando un número aleatorio entre `1` y `6`. Después de cada lanzamiento, pregunta si el usuario desea lanzar nuevamente. El programa continúa mientras responda `s`.

### 10. Cajero automático

Crea un programa con un saldo inicial de `$1000`. El menú debe permitir:

```text
1. Consultar saldo
2. Depositar dinero
3. Retirar dinero
4. Salir
```

Valida que no se pueda retirar más dinero del saldo disponible ni depositar cantidades negativas.

## Ejercicios con `for`

### 11. Números pares

Muestra todos los números pares del `2` al `100`.

### 12. Tabla de multiplicar

Solicita un número y muestra su tabla de multiplicar del `1` al `10`.

**Ejemplo:**

```text
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

### 13. Factorial

Solicita un número entero positivo y calcula su factorial.

**Ejemplo:**

```text
Entrada: 5
Salida: 120
```

Recuerda que `5! = 5 × 4 × 3 × 2 × 1`.

### 14. Contar dígitos

Solicita un número entero positivo y determina cuántos dígitos tiene.

**Ejemplo:**

```text
Entrada: 82745
Salida: El número tiene 5 dígitos
```

### 15. Suma de múltiplos

Solicita un número `n` y calcula la suma de todos los múltiplos de `3` entre `1` y `n`.

**Ejemplo:**

```text
Entrada: 10
Operación: 3 + 6 + 9
Salida: 18
```

## Ejercicios combinados

### 16. Número primo

Solicita un número entero positivo y determina si es primo. Un número primo solo es divisible entre `1` y él mismo. Utiliza un ciclo `for` para comprobar sus divisores.

**Ejemplos:**

```text
7  -> Es primo
10 -> No es primo
```

### 17. Mayor y menor de varios números

Solicita `10` números usando un ciclo `for`. Al finalizar, muestra el número mayor, el número menor y el promedio.

### 18. Menú con estadísticas

Solicita números hasta que el usuario introduzca `0`. Al finalizar, muestra cuántos números introdujo, cuántos fueron positivos, cuántos negativos y la suma total. Utiliza `while` o `do while`.

### 19. Triángulo de asteriscos

Solicita un número de filas y muestra un triángulo utilizando ciclos anidados.

**Entrada:**

```text
5
```

**Salida:**

```text
*
**
***
****
*****
```

### 20. Tablas de multiplicar

Muestra las tablas de multiplicar del `1` al `10`, usando ciclos `for` anidados.

**Salida parcial:**

```text
Tabla del 1
1 x 1 = 1
1 x 2 = 2

Tabla del 2
2 x 1 = 2
2 x 2 = 4
```

## Orden recomendado

1. Ejercicios 1, 6 y 11.
2. Ejercicios 2, 8 y 12.
3. Ejercicios 3, 7 y 13.
4. Ejercicios 5, 10 y 16.
5. Ejercicios 17, 18, 19 y 20.

## Recomendaciones

- Resuelve cada ejercicio en una clase independiente.
- Utiliza `Scanner` para leer datos del usuario.
- Prueba casos válidos y no válidos.
- Evita consultar soluciones antes de intentar resolver el problema.
- Comenta las partes importantes de tu código.
