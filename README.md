### *Identificación de patrones de evasión tributaria en Colombia Mediante técnicas de aprendizaje no supervisado*

### *Integrantes*

-   Edgardo Sánchez
-   Juan Medina
-   Manuel Alarcón

### *Objetivo*

Analizar datos abiertos para identificar clústeres y patrones de riesgo
de evasión tributaria en Colombia, utilizando variables proxy que
representen las principales causas estructurales, económicas e
institucionales de la evasión.

### *Descripción*

Este proyecto busca explorar, a través de técnicas no supervisadas de
aprendizaje automático, cómo factores: * socioeconómicos * de capacidad
contributiva se relacionan con los patrones de evasión tributaria en
Colombia. Se utilizan técnicas de: * K-means * PCA (Análisis de
Componentes Principales)

### *Alcance del proyecto*

Este análisis se desarrolla a nivel regional/departamental, utilizando
datos agregados provenientes de fuentes oficiales. Dada la ausencia de
microdatos tributarios públicos, el enfoque se basa en variables proxy
que aproximan el riesgo de evasión y la cultura de cumplimiento.

### *Desafíos*

-   Acceso y limpieza de bases de datos dispersas (DIAN, DANE,
    Transparencia, etc.).
-   Construcción de proxies representativos para variables intangibles
    como “confianza en el gobierno” o “cultura tributaria”.
-   Posible falta de microdatos detallados sobre sanciones o evasión
    directa.
-   Integración de diferentes fuentes de información (fiscal,
    socioeconómica y percepción ciudadana).
-   Diferentes escalas temporales y geográficas entre bases de datos.

### *Entrega de valor*

-   Identificar perfiles de riesgo de evasión tributaria con base en
    datos públicos.
-   Proveer evidencia útil para diseñar políticas públicas más
    focalizadas en aumentar el cumplimiento tributario.
-   Generar un marco replicable para futuros estudios sobre evasión y
    cumplimiento fiscal en Colombia y América Latina.
-   Integrar herramientas de inteligencia artificial con economía
    pública aplicada.

### *Stakeholders*

-   DIAN
-   DANE
-   Ministerio de Hacienda
-   Ciudadanos y empresas
-   Academia

### *Técnicas Utilizadas*

-   K-means clustering
-   PCA (Análisis de Componentes Principales)
-   Estandarización de variables (StandardScaler)
-   Métrica del codo
-   Análisis de carga factorial

### *Fuentes de datos*

-   DIAN
-   DANE
-   Transparencia Internacional
-   LAPOP – AmericasBarometer
-   Banco Mundial – CPIA

### *Variables (Proxies)*

-   Carga tributaria relativa
-   Capacidad económica
-   Confianza en el gobierno
-   Percepción de corrupción
-   Informalidad laboral
-   Historial de tradición tributaria
-   Sanciones efectivas
-   Complejidad normativa

### *Resultados generales*

-   Identificación de clústeres
-   Asociación entre informalidad, corrupción y menor cumplimiento
-   Factores institucionales relevantes

### *Limitaciones*

-   No existen datos directos de evasión
-   Relaciones correlacionales, no causales
-   Proxies imperfectas
