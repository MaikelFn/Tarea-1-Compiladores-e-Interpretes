# Tarea-1-Compiladores-e-Interpretes

## Decisiones tomadas

los no terminales se escriben entre '< >' usando la primera letra de cada palabra en mayúscula y guion_bajo para compuestos. 
Los operadores se prefijan con 'Op_' y los literales con 'Lit_', diferenciándolos de los tipos.
'Lit_Bool' usa "true"/"false".
Simbolo_Valido agrupa símbolos permitidos en 'Char'/'String'
el enunciado restringe los operadores pot y mod a operandos de tipo entero sin embargo esto no podemos abarcarlo por completo de forma sintactica por lo que decidimos abarcarlo luego.