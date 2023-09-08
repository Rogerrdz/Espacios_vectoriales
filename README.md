# Librería de Espacios Vectoriales Complejos

Esta librería proporciona una serie de funciones para trabajar con espacios vectoriales complejos. Incluye operaciones básicas como suma, inverso aditivo, multiplicación por un escalar, así como operaciones más avanzadas como suma de matrices, matriz inversa, transpuesta, conjugada y adjunta, producto interno de vectores, norma de un vector, distancia entre vectores, valores y vectores propios de una matriz, y comprobación de matriz unitaria y hermitiana.

## Funciones Disponibles

- `suma_vec(c1, c2)`: Suma dos vectores complejos.
- `inverso_ad_v(c)`: Calcula el inverso aditivo de un vector complejo.
- `mult_vect_esc(e, v)`: Multiplica un vector complejo por un escalar.
- `suma_mat(mat1, mat2)`: Suma dos matrices complejas.
- `inv_ad(mat)`: Calcula la inversa aditiva de una matriz compleja.
- `mult_esc(k, mat)`: Multiplica una matriz compleja por un escalar.
- `traspuesta_mat(mat)`: Calcula la matriz traspuesta de una matriz compleja.
- `conjugada_mat(mat)`: Calcula la matriz conjugada de una matriz compleja.
- `adjunta_mat(mat)`: Calcula la matriz adjunta de una matriz compleja.
- `product_mat(mat1, mat2)`: Multiplica dos matrices complejas.
- `accion_mat(mat, vect)`: Realiza la acción de una matriz compleja sobre un vector complejo.
- `produc_interno_vec(vector_1, vector_2)`: Calcula el producto interno de dos vectores complejos.
- `norma_vector(vec)`: Calcula la norma de un vector complejo.
- `distancia_vect(vect_1, vect_2)`: Calcula la distancia entre dos vectores complejos.
- `val_vec_prop_mat(mat)`: Calcula los valores y vectores propios de una matriz compleja.
- `unitaria(mat)`: Verifica si una matriz es unitaria.
- `hermitiana(mat)`: Verifica si una matriz es hermitiana.
- `producto_tensor(mat1, mat2)`: Calcula el producto tensor de dos matrices o vectores complejos.

## Uso

Puedes utilizar estas funciones en tu código Python para realizar operaciones en espacios vectoriales complejos. Asegúrate de importar la librería `numpy` para que las funciones funcionen correctamente.

Ejemplo de uso:

```python
import numpy as np
from Libreria_Espacios_Vectorial_Complejos_1 import *

# Ejemplo de suma de vectores complejos
vector1 = [1+2j, 3-1j, 0+2j]
vector2 = [-1+0j, 4+3j, 2-2j]
resultado = suma_vec(vector1, vector2)
print(resultado)
