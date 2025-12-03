  # Tecnológico de Software
  ## Materia: Fundamentos de álgebra
  ## Alumno: Jesus Fernando Castro Hernandez
  ## Grupo: 1-A
  ## Fecha: 22/11/25
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
### Estructura de las imagenes
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

<img width="821" height="695" alt="image" src="https://github.com/user-attachments/assets/758b0491-f09f-4c87-af94-8bd696c0630b" />
<img width="999" height="684" alt="image" src="https://github.com/user-attachments/assets/a2ae999a-9176-4352-a340-d9a5c43dbc7b" />


---

### 3. Suma de matrices

La suma se realizó seleccionando las dos matrices originales (por ejemplo, Imagen 1 y Imagen 2) con:
```excel
=Matriz1!A1 + Matriz2!A1
```
<img width="999" height="684" alt="image" src="https://github.com/user-attachments/assets/553c7cdb-5130-477b-a81a-524503bda624" />

---

### 4. Resta de matrices

Para calcular la diferencia entre dos matrices:

```excel
=Matriz1!A1 - Matriz2!A1
```
<img width="936" height="601" alt="image" src="https://github.com/user-attachments/assets/e68b7caf-c975-47f6-a107-ddc87643605a" />

---

### 5. Multiplicación escalar

Para multiplicar una matriz por un número (ejemplo: 3), en una nueva hoja se usó:

```excel
=Matriz1!A1 * 3
```
<img width="1123" height="674" alt="image" src="https://github.com/user-attachments/assets/8c9f64d3-3af8-44b8-8491-8ebe8992f45a" />


---

### 6. Composición de matrices (Multiplicación de matrices)

La multiplicación entre matrices se realizó usando la función:


```excel
=MMULT(Matriz1!A1:AD30, Matriz2!A1:AD30)
```
<img width="953" height="673" alt="image" src="https://github.com/user-attachments/assets/3b62bb9f-899f-4c7f-bfea-7d5913c6c94c" />

  
  









