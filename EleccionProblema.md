## I. Elección del Problema
La industria elegida es la de Finanzas
Aplicación: Modelo de detección de compra de deuda a nuestros clientes

# Ejemplo Completo de Tablas e Imágenes Personalizadas en Markdown

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
  }
  th {
    background-color: #f2f2f2;
  }
</style>

## Tabla Personalizada

<table>
  <tr>
    <th>Categoría</th>
    <th>Caso de uso</th>
    <th>Decisión</th>
    <th>Incertidumbre</th>
    <th>Resultado</th>
  </tr>
  <tr>
    <td>Detección de Migración de clientes</td>
    <td>Sistema de detección</td>
    <td>Ofertas más atractivas: Ampliación de créditos y/o Reducción de tasa de interés</td>
    <td>Se irá con la competencia o no</td>
    <td>Mayor fidelización de clientes, menor reducción de clientes.</td>
  </tr>
  <tr>
    <td rowspan="4">Predecir el comportamiento futuro de los clientes (la migración)</td>
    <td>Detectar/Identificar clientes buenos propensos a cambiar sus productos/servicios financieros a otra entidad.</td>
    <td></td>
    <td>Precisión del modelo: Que tan exacto es el modelo para identificar a los clientes que migrarán</td>
    <td>Tasa de cuantos clientes migran</td>
  </tr>
  <tr>
    <td>Buenos: 12 meses con pago puntual</td>
    <td></td>
    <td>Que tan convencido se encuentra el cliente con las ofertas otorgadas</td>
    <td></td>
  </tr>
  <tr>
    <td>No créditos castigados</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Clientes exclusivos (1 entidad financiera: nosotros)</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

## Imagen Personalizada

<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo de GitHub" width="200" height="200">
</p>

# Ejemplo de Imagen Personalizada en Markdown

<!-- Imagen con tamaño ajustado y alineada al centro -->
<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo de GitHub" width="200" height="200">
</p>

<!-- Imagen con un tamaño específico y borde -->
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo de GitHub" style="width: 150px; height: 150px; border: 2px solid black;">
