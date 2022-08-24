# Arreglos estáticos
## Arreglos unidimensionales
La declaración de un arreglo estático unidimensional en lenguaje C se realiza de la siguiente forma.

``` C
[data type] variable [dimension];
```

por ejemplo:

``` C
int arrayI[10];
char arrayS[14];
...
```

### Actividad 1
Realice un programa en C que genere una lista de los primeros 10 números pares, deberá imprimirlos en orden inverso.

- posteriormente deberá modificar el valor almacenado en el índice correspondiente al último dígito de su número cuenta por -1, por ejemplo:
```markdown
| 2 | 4 | 6 | 8 | 10 | 12 | 14 | 16 | 18 | 20 |
```

Número de cuenta 410092686
```markdown
| 2 | 4 | 6 | 8 | 10 | 12 | -1 | 16 | 18 | 20 |
```

## Arreglos bidimensionales
La declaración de un arreglo bidimensional estático en lenguaje C se realiza de la siguiente forma.

``` C
[data type] variable [dimension1][dimension2];
```

por ejemplo:

``` C
int arrayI[10][5];
char arrayS[14][3];
...
```

### Actividad
Considere el  siguiente arreglo matricial:

```markdown
| Nombre   | Edad | Calificación |
|----------|------|--------------|
| Alberto  | 22   | 9            |
| Fernando | 19   | 4            |
| Brenda   | 34   | 7            |
```

Realice un programa que acepte una lista máxima de 20 alumnos, el arreglo deberá ser de 20x3, la primera columna deberá tener un espacio de 25 caracteres, la segunda y tercera deberá aceptar números enteros.

- El programa después de capturar los datos (no necesariamente deberán ser los 20 registros), deberá devolver el promedio de edad y de calificación grupal.
- El programa deberá imprimir los nombres de los alumnos en sentido inverso al que fueron ingresados o se encuentran almacenados.
