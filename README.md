  # Tecnológico de Software
  ## Materia: Fundamentos de álgebra
  ## Alumno: Jesus Fernando Castro Hernandez
  ## Actividad \#20 - Documentacion de Matrices en Excel con Git Branches
  
  ---

## Objetivo
El propósito de esta actividad es trabajar con matrices dentro de Excel, representando imágenes mediante números, y aplicar operaciones fundamentales de álgebra lineal como:

- Transposición  
- Suma  
- Resta  
- Multiplicación escalar  
- Composición (multiplicación de matrices)

---

## Programación de la hoja de Excel

### 1. Diseño de las matrices (imágenes pixeladas)
Cada matriz fue creada en un programa de generacion de pixeles
```link
https://github.andrewt.net/mosaic/
```

en una hoja distinta de Excel, en una cuadrícula de *de distinto tamaño*.  

Aplicamos *Formato condicional* para colorear cada valor siguiendo esta ruta:

Inicio → Formato condicional → Nueva regla → Formato de celdas que contengan


Asignanando una escala de 3 colores **(Negro, gris y blanco)** para cada número.

---

### 2. Transposición de las matrices

Para cada matriz original (ejemplo: en la hoja Imagen 1), se generó su transpuesta en otra hoja (Transpuesta 1).

Para transponer una matriz completa se utilizó la función:

```excel
=TRANSPONER(Matriz1!A1:AD30)
```
---

### 3. Suma de matrices

La suma se realizó seleccionando las dos matrices originales (por ejemplo, Imagen 1 y Imagen 2) con:
```excel
=Matriz1!A1 + Matriz2!A1
```

---

### 4. Resta de matrices

Para calcular la diferencia entre dos matrices:

```excel
=Matriz1!A1 - Matriz2!A1
```

---

### 5. Multiplicación escalar

Para multiplicar una matriz por un número (ejemplo: 3), en una nueva hoja se usó:

```excel
=Matriz1!A1 * 3
```


---

### 6. Composición de matrices (Multiplicación de matrices)

La multiplicación entre matrices se realizó usando la función:


```excel
=MMULT(Matriz1!A1:AD30, Matriz2!A1:AD30)
```
  
  









