# ERT e IP en un sitio de residuos industriales y municipales (Taman Kepong Indah, Kuala Lumpur)

Reprocesamiento e interpretación de seis líneas de tomografía de resistividad eléctrica (ERT) con polarización inducida (IP), arreglo Wenner-Schlumberger. Los datos de campo son de Arifin et al. (2020) y **no se incluyen**.

**Autor:** Ian A. Sandoval-Valderrábano, Facultad de Ingeniería, Benemérita Universidad Autónoma de Puebla (BUAP).

## Contenido
- [`paper/ERT_IP_Kuala_Lumpur_IEEE.pdf`](paper/ERT_IP_Kuala_Lumpur_IEEE.pdf): artículo en formato IEEE.
- [`paper/overleaf/`](paper/overleaf): fuente LaTeX y figuras.
- [`codigo/`](codigo): inversión propia en Python (modelado directo 2.5D por elementos finitos con topografía, mínimos cuadrados con suavidad, Gauss-Newton), modelo 3D y figuras. Ver [`codigo/README.md`](codigo/README.md).

## Resultados
- Depuración con criterios explícitos (149 de 1,862 datos) y modelos con RMS de 5.4 a 7.4 %.
- Capa de residuos (< 100 Ω·m) con base a 8–19 m y techo del basamento (> 400 Ω·m) a 14–31 m.
- Volumen afectado estimado de ~3.7 × 10⁵ m³ en el modelo 3D (exportable a ParaView).
- La baja resistividad se explica por iones mayoritarios y no por metales traza.

## Advertencias
El código es una implementación propia: sus resultados no son numéricamente idénticos a los de programas comerciales como Res2DInv. Las clases de resistividad no están calibradas con sondeos.

## Licencia
MIT.
