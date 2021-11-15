# Reglas de las expresiones aritméticas

- Los vértices terminales son **operandos** (**números**), con los que haremos operaciones.
- Los vértices internos o raíces van a ser los **operadores**.
- El nodo raíz **siempre debe ser un operador** y va a ser el operador con mas relevancia dentro de nuestra expresión aritmetica
- El orden de resolución de las operaciones aritmética siempre es:**paréntesis, raíces, potencias, multiplicación, división, suma y resta.**

## Maneras de recorrer una expresión aritmética
Al igual que los arboles tenemos tres maneras de recorrer una expresión aritmética:

- **Pre fijo:** raíz, izq, der
- **In fijo:** izq, raíz, der
- **Pos fijo:** izq, der, raíz
