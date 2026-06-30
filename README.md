# Proyecto QUBO-QAOA: matching bipartito 4x4

# Dataset

## Nombre del dataset:
 - #### Afluencia diaria de metrobus CDMX


## Fuente oficial o confiable:
 - ####  Organismo Público de Transporte

## Institución responsable:
 - Secretaria de Movilidad (SEMOVI)

## URL de la fuente:
 - https://datos.cdmx.gob.mx/dataset/afluencia-diaria-de-metrobus-cdmx

## URL raw del CSV usado en data/:
 - https://datos.cdmx.gob.mx/dataset/afluencia-diaria-de-metrobus-cdmx/resource/f7943c47-835d-4078-93ea-906f64b72f3b

## Licencia o condiciones de uso:
 - #### Licencia GPL
## Fecha de consulta:
 - #### 22 de junio 2026

## Dominio del problema:


# Modelado

## Conjunto A:

(Las 4 Estaciones de Origen/Interconexión más saturadas)
manejo en la zonas de pantitlan, Indios verdes,

## Criterio para elegir exactamente 4 elementos de A:



## Conjunto B:

## Criterio para elegir exactamente 4 elementos de B:

## Definición de x_ij = 1:

## Interpretación de x_ij = 0:

# Matriz de score

$$S = \begin{pmatrix} 10.0 & 56.56 & 37.55 & 150.68 \\ 20.0 & 27.15 & 25.03 & 75.34 \\ 30.0 & 33.94 & 62.58 & 50.23 \\ 15.0 & 45.25 & 50.07 & 125.57 \end{pmatrix}$$

## Columnas usadas:

## Fórmula exacta de S_ij:

## Normalización aplicada:

## Matriz S 4x4:

# Restricciones

## Restricción por filas:

## Restricción por columnas:

## Otras restricciones, si existen:

## Justificación de por qué el problema es matching bipartito:

## Justificación de por qué es razonable modelarlo como QUBO:

# Resultados

## Solución clásica exacta:

## Resultado QAOA local:

## Comparación clásico vs QAOA local:

## Si se usó hardware real o pipeline híbrido, comparación adicional:

# Ética y limitaciones

## Riesgos éticos:

## Medidas de mitigación:

## Limitaciones del modelo:

# Ejecución

## Instrucciones para abrir el archivo .ipynb en Google Colab:

## Instrucciones para ejecutar todas las celdas sin errores:
