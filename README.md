# Ejercicio 1: Cálculo de Salario Quincenal con Deducciones Variables

Aplicación web en PHP que calcula el sueldo quincenal de un trabajador.

## Archivos
- `index.html`: formulario con nombre, cédula y horas trabajadas (diurna, vespertina y nocturna).
- `calcular.php`: calcula el sueldo bruto, aplica las deducciones y muestra el resultado.

## Funcionamiento
1. Tarifas por hora: Diurna = 675 Bs., Vespertina = 700 Bs., Nocturna = 956.23 Bs.
2. El sueldo bruto es la suma de las horas de cada turno por su tarifa.
3. Según el sueldo bruto se aplican los porcentajes:
   - Menor a 85.000 Bs.: Ahorro Habitacional 0.1% y Seguro Social 0.15%.
   - Entre 85.000 y 150.000 Bs. (inclusive): 0.15% y 0.2%.
   - Mayor a 150.000 Bs.: 0.3% y 0.25%.
4. Se muestran los datos del empleado, el sueldo bruto, los descuentos y el sueldo neto.
