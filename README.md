# TP de Programación en Python: Funciones, Scope y Retornos

Trabajo práctico de la Tecnicatura Superior en Desarrollo de Software. Reúne cuatro ejercicios de **predicción de código** en Python, donde hay que analizar qué hace cada programa antes de ejecutarlo y explicar por qué.

El tema central es el **alcance de las variables (scope)** cuando el código se divide en dos módulos (`funciones.py` y `programa.py`): cada módulo tiene sus propias variables globales, así que los datos tienen que viajar entre módulos por **parámetros** y por **`return`**.

## Contenido

| Archivo | Ejercicio | Tema |
|---|---|---|
| `ejercicio_1301.txt` | Predicción de Código 1 | Variables globales que no se ven desde otro módulo (`NameError`) |
| `ejercicio_1302.txt` | Predicción de Código 2: Scope y Retornos | Parámetros como copias locales y reasignación con `return` |
| `ejercicio_1303.txt` | Predicción de Código 3: Validación y Ciclos | Función de validación de DNI, ciclo `while` y búsqueda del mayor |
| `ejercicio_1304.txt` | Predicción de Código 4: Parámetros vs Variables Globales | Qué opciones funcionan y por qué las otras fallan |

Cada archivo incluye el enunciado, el código, el resultado esperado y la explicación paso a paso.

## Ideas principales

- Una función definida en `funciones.py` no puede ver las variables de `programa.py`, aunque se haga `from funciones import *`.
- Los parámetros de una función son copias locales: modificarlos adentro no cambia las variables originales.
- Para conservar los cambios hay que devolver los valores con `return` y reasignarlos al llamar a la función.

## Autor

Martín Navarro
