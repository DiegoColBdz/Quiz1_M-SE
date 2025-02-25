# Quiz 1: Modelos y Simulación Empresarial

## Descripción
Este proyecto contiene el desarrollo del Quiz 1 de la asignatura Modelos y Simulación Empresarial, en el cual desarrollamos un modelo de simulación para resolver un problema de optimización de configuración de asientos en aeronaves para Alpha Airlines.

## Autores
- **Samuel Corrales Salazar**
- **Diego Collazos Bermudez**

## Problema a Resolver
Alpha Airlines necesita determinar la configuración óptima de asientos (distribución entre primera clase y clase turista) para su nueva flota de DC-717 en la ruta Boston-Atlanta-Chicago-Boston, con el objetivo de maximizar los beneficios.

### Consideraciones
- Cada fila de primera clase (4 asientos) requiere eliminar dos filas de clase turista (6 asientos cada una)
- La capacidad máxima es de 40 filas completas de clase turista (240 asientos)
- La demanda sigue distribuciones probabilísticas específicas para cada tramo
- Los ingresos por asiento varían según la clase y el tramo
- El costo fijo de operación del circuito completo es de $100,000 por día

## Tecnologías Utilizadas
Este proyecto ha sido desarrollado utilizando Python con las siguientes librerías:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import math 
import scipy.stats as stats
from scipy.stats import rv_discrete, rv_histogram, binom, norm, kstest
```

## Metodología
1. Análisis de las distribuciones de demanda por tramo
2. Modelado de la distribución de demanda para el tramo Atlanta-Chicago basado en datos históricos
3. Simulación de escenarios con diferentes configuraciones de asientos
4. Cálculo de ingresos esperados y variabilidad para cada configuración
5. Determinación de la configuración óptima que maximiza beneficios

## Resultados
En este proyecto presentamos la configuración óptima de asientos que maximiza los beneficios esperados para Alpha Airlines, considerando la variabilidad de la demanda y los diferentes ingresos por tramo y clase.

## Instalación y Uso
```bash
# Clonar el repositorio
git clone [url-del-repositorio]

# Navegar al directorio del proyecto
cd [nombre-del-directorio]

# Crear un ambiente virtual e instalar todas las librerias necesarias
pip install numpy pandas matplotlib seaborn scipy

# Abrir el cuaderno de Python con un editor como VS Code o usar un cuaderno de jupyter
pip install jupyterlab
jupyter lab [quiz1.ipynb]
```

## Conclusiones
Nuestro modelo de simulación permite a Alpha Airlines tomar decisiones informadas sobre la configuración de sus aeronaves, balanceando la demanda esperada con la maximización de beneficios en la ruta Boston-Atlanta-Chicago-Boston.

## Universidad
EIA
---

© 2025 Samuel Corrales Salazar & Diego Collazos Bermudez
