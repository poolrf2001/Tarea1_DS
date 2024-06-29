# III. Propuesta del Caso de Negocio

# Suposiciones consideradas

| Concepto | Valor |
|-----------|-----------|
| Tasa nominal promedio | 16%   |
| Valor promedio del crédito | 20 000   |
| Interés pagado por cliente | 3 200    |
| Base de usuarios activos | 200    |
| Tasa de migración a otras entidades | 6%   |
| Nuevo modelo de ML reduce la tasa de migración en | 2.8%   |

**Falsos Positivos:**	
- Palancas costosas aplicadas a usuarios que no iban a migrar a otra entidad financiera.
  Ejemplo: 200 usuarios reciben 1% de descuento (tasa nominal), solo 160 iban a migrar.

- Costo: 40 × (1%) x 20 000= $8 000 en falsos positivos.

**Falsos Negativos:**
- Costo de oportunidad por predicciones erróneas. 
  Ejemplo: Usuarios que migraron a la competencia y no fueron detectados: 4.	

- Costo: 4 × 3 200 = $12 800 en falsos negativos.	

**Valor Monetario:**

| Concepto | Valor (En Soles)|
|-----------|-----------|
| Costo de la migración de clientes sin modelo | 38 400  |
| Costo de la migración de clientes con modelo | 20 480   |
| Ahorro del nuevo modelo | 17 920    |
| Costo de falsos positivos | 8 000    |
| Costo de falsos negativos | 12 800  |