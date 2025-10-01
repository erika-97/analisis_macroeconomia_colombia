# Analisis Macroeconomico de Colombia
Análisis financiero de las 10K empresas de Colombia: Eficiencia, Solidez y Concentración Geográfica.
*Estudio de Caso de Análisis de Datos*

[Dashboard Screenshot 1](https://github.com/user-attachments/assets/c63c722f-62ea-46b7-b39a-02b7ae779cba)
[Dashboard Screenshot 2](https://github.com/user-attachments/assets/51ff2b87-a8ef-43f2-a7bd-92c00fd0bb0d)

## Resumen del Proyecto

Análisis de la información financiera de las **10.000 Empresas más Grandes de Colombia** (2021-2023). El proyecto se centró en evaluar la **relevancia económica** de los macrosectores, analizando tres pilares: **Rentabilidad Absoluta**, **Eficiencia Operativa (Margen)** y **Solidez Financiera (Endeudamiento)**. Se concluye que el sector **Servicios** lidera en volumen, pero el sector **Agropecuario** es el más sólido y eficiente.

---

## Pregunta Central de Negocio (El Problema Resuelto)

El objetivo fue responder: **¿Cuál es la relevancia de ciertos sectores en Colombia a través del análisis de su rentabilidad, estabilidad y concentración geográfica?**.

El análisis diagnóstico busca apoyar la toma de decisiones sobre dónde focalizar las políticas de inversión y desarrollo a nivel nacional.

##  Herramientas Utilizadas

**Python (VS Code):** Limpieza, manejo de *outliers* y transformación de variables financieras a formato numérico (Float64).
**Google Sheets:** Cálculos iniciales de indicadores clave (Ratio de Endeudamiento y Eficiencia Operativa).
**Tableau Public:** Diseño de dashboard interactivo para visualizar concentración de capital, eficiencia y riesgo geográfico.
**Fuente de Datos:** Datos Abiertos GOV.CO ("10.000 Empresas más Grandes del País")[cite: <https://www.datos.gov.co/Comercio-Industria-y-Turismo/10-000-Empresas-mas-Grandes-del-Pa-s/6cat-2gcs/about_data>].

##  Proceso de Análisis (Metodología)

1. **Limpieza y Preprocesamiento (Python):** Se procesaron los datos, se convirtieron los caracteres no numéricos de las columnas financieras a decimales y aplicando un filtro estadístico para eliminar **valores atípicos** (*outliers*) fuera del rango de ±2 desviaciones estándar de la media.
2.  **Cálculo de Indicadores Clave:**
      **Eficiencia Operativa:** `SUM(Ganancia) / SUM(Ingresos Operacionales)`.
      **Ratio de Endeudamiento:** `SUM(Pasivos) / SUM(Activos)`.
3.  **Visualización de *Insights*:** Construcción de 5 gráficos principales: Barras/Líneas (Ganancia vs. Ingresos por Macrosector), Barra (Eficiencia), Dispersión (Activos vs. Pasivos), Mapa (Concentración Geográfica), y Barras Apiladas (Composición Regional).

##  Hallazgos Clave

| Indicador | Sector Líder | Valor (2021-2023) | Conclusión |

| **Rentabilidad Total** | Servicios | $22.24 Billones COP | Es el motor económico en volumen absoluto. |
| **Eficiencia Operativa** | Minero | 8.39% Margen | **Servicios (4.99%)** es superado, indicando oportunidad para optimizar costos operativos. |
| **Solidez Financiera** | Agropecuario | 46.7% Ratio de Endeudamiento | Mayor estabilidad financiera y menor riesgo de deuda. |
| **Riesgo Geográfico** | Bogotá-Cundinamarca | 48.4% de la Ganancia Nacional | Fuerte centralización del valor económico, con alta dependencia del sector Servicios en la capital. |

##  Implicaciones y Recomendaciones Accionables

El análisis de rentabilidad y riesgo genera implicaciones claras para las políticas:

1.  **Optimización de Servicios:** Impulsar la **eficiencia operativa e impulsar proyectos innovadores** en el sector Servicios para sostener su liderazgo en volumen y aumentar su margen de ganancia (actualmente 3º en eficiencia).
2.  **Apalancamiento de la Estabilidad:** Incentivar la inversión y el desarrollo (como la tecnología) en el sector **Agropecuario**, aprovechando su **baja dependencia de deuda** y su alta eficiencia para promover un crecimiento de capital de bajo riesgo.
3.  **Descentralización Estratégica:** Explorar estrategias de descentralización que impulsen la rentabilidad en regiones secundarias, **mitigando el riesgo de concentración** asociado a la fuerte dependencia de Bogotá-Cundinamarca.


---
