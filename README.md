

#*Identificación de patrones de evasión tributaria en Colombia mediante técnicas de aprendizaje no supervisado*

### *Integrantes*

* Edgardo Sánchez
* Juan Medina
* Manuel Alarcón

### *Objetivo*

Analizar datos abiertos de fuentes oficiales y académicas para identificar clústeres y patrones de riesgo de evasión tributaria en Colombia, utilizando variables proxy que representen las principales causas de evasión.

### *Descripción*

Este proyecto busca explorar, a través de técnicas no supervisadas de aprendizaje automático, cómo factores socioeconómicos, de confianza institucional y de capacidad contributiva se relacionan con la evasión tributaria en Colombia.
Se utilizarán *K-means, **PCA* y *Apriori* para detectar clústeres de contribuyentes, reducir dimensionalidad y encontrar reglas de asociación que revelen combinaciones de factores vinculados al incumplimiento fiscal.


### *Desafíos*

* Acceso y limpieza de bases de datos dispersas (DIAN, DANE, Transparencia, etc.).
* Construcción de proxies representativos para variables intangibles como “confianza en el gobierno” o “cultura tributaria”.
* Posible falta de microdatos detallados sobre sanciones o evasión directa.
* Integración de diferentes fuentes de información (fiscal, socioeconómica y percepción ciudadana).

### *Entrega de valor*

* Identificar perfiles de riesgo de evasión tributaria con base en datos públicos.
* Proveer evidencia útil para diseñar políticas públicas más focalizadas en aumentar el cumplimiento tributario.
* Generar un marco replicable para futuros estudios sobre evasión y cumplimiento fiscal.


### *Stakeholders*

* *DIAN*: interesada en mejorar el control y las estrategias de fiscalización.
* *DANE*: aporta datos socioeconómicos y de percepción social.
* *Ministerio de Hacienda*: beneficiario indirecto por mayor eficiencia recaudatoria.
* *Ciudadanos y empresas*: actores evaluados en términos de su cumplimiento fiscal.
* *Academia*: análisis que enriquece el campo de la economía pública y la ciencia de datos aplicada.

### *Técnicas que se utilizarán*

* *K-means clustering*: para agrupar contribuyentes o regiones según perfiles de riesgo de evasión.
* *PCA (Análisis de Componentes Principales)*: para reducir la dimensionalidad de las variables proxy y obtener factores latentes.
* *Apriori (reglas de asociación)*: para identificar combinaciones frecuentes de factores que explican patrones de incumplimiento.


### *Fuentes de datos*

* *DIAN*: estadísticas de recaudo, sanciones y comercio exterior ([Datos Abiertos DIAN](https://www.dian.gov.co/atencionciudadano/Paginas/Datos-Abiertos.aspx)).
* *DANE*: Encuesta Pulso Social, GEIH (informalidad laboral), ingresos y gastos de los hogares ([DANE](https://www.dane.gov.co/index.php/estadisticas-por-tema)).
* *Transparencia Internacional / Transparencia por Colombia*: Índice de percepción de corrupción ([transparency.org](https://www.transparency.org/en/cpi/2024)).
* *LAPOP – AmericasBarometer*: datos de confianza institucional y cultura tributaria ([LAPOP](https://www.vanderbilt.edu/lapop/)).
* *Banco Mundial – CPIA*: indicadores de rendición de cuentas y corrupción ([World Bank Data](https://data.worldbank.org/indicator/IQ.CPA.TRAN.XQ)).

### *Variables (Proxies)*

1. *Carga tributaria relativa* = impuestos recaudados / PIB regional (DIAN + DANE).
2. *Capacidad económica* = ingreso promedio per cápita por región (DANE).
3. *Confianza en el gobierno* = porcentaje de encuestados con confianza alta en instituciones (Pulso Social – DANE, LAPOP).
4. *Percepción de corrupción* = puntaje del Índice de Percepción de Corrupción (TI/Transparencia por Colombia).
5. *Informalidad laboral* = % de ocupados sin seguridad social (GEIH – DANE).
6. *Historial de tradición tributaria* = evolución de contribuyentes registrados en RUT (DIAN).
7. *Sanciones efectivas* = número de sanciones tributarias aplicadas por año (DIAN).
8. *Complejidad normativa* = número de reformas tributarias aprobadas por año (repositorios académicos + EMI).
