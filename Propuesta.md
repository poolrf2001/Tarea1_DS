# La propuesta de  caso aplicado a Finanzas

# Suposiciones consideradas

| Concepto | Valor |
|-----------|-----------|
| Tasa nominal promedio | 16%   |
| Valor promedio del crédito | 20000   |
| Interés pagado por cliente | 3200    |
| Base de usuarios activos | 200    |
| Tasa de migración a otras entidades | 6%   |
| Nuevo modelo de ML reduce la tasa de migración en | 2.8%   |

**Falsos Positivos:**	
- Palancas costosas aplicadas a usuarios que no iban a migrar a otra entidad financiera.
  Ejemplo: 200 usuarios reciben 1% de descuento (tasa nominal), solo 160 iban a migrar.

- Costo: 40 × (1%) x 20000= $8 000 en falsos positivos.

**Falsos Negativos:**
- Costo de oportunidad por predicciones erróneas. 
  Ejemplo: Usuarios que migraron a la competencia y no fueron detectados: 4.	

- Costo: 4 × 3200 = $12800 en falsos negativos.	
