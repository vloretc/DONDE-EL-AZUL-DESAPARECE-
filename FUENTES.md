# Referencias y alcance de los datos

Esta interfaz es una simulación visual. La versión actual aumenta de forma continua hasta septiembre de 2026, cuando alcanza 6.3 millones de toneladas y 350,000 km². El descenso anterior fue eliminado por petición del usuario. Estos valores son objetivos del prototipo, no observaciones verificadas. Los valores intermedios se reescalaron de forma ilustrativa para representar un crecimiento continuo hasta septiembre. Ningún valor de los ocho keyframes se extrajo de las fuentes. Las fechas son posiciones de la línea del tiempo ilustrativa, no observaciones históricas. No existe conexión en vivo con NASA, UNAM o USF.

- **Biomasa:** millones de toneladas, valores ilustrativos.
- **Extensión:** kilómetros cuadrados, valores ilustrativos.
- **Densidad:** porcentaje de superficie cubierta de la escena simulada, valores ilustrativos. No se calcula a partir de biomasa/extensión ni se ha medido sobre las imágenes. No equivale a densidad volumétrica (kg/m³).

## Fuentes consultadas

- [NASA Ciencia — Crece el cinturón de sargazo del Atlántico](https://ciencia.nasa.gov/ciencias-terrestres/crece-el-cinturon-de-sargazo-del-atlantico/). Describe mapas de densidad basados en la fracción de superficie oceánica cubierta, promediada por píxel. Se usa como referencia conceptual, sin copiar sus cifras regionales a la simulación.
- [LANOT, UNAM — Monitoreo de sargazo](https://www.lanot.unam.mx/home/sargazo/). Plataforma de detección satelital y consulta de superficies y series temporales; sus resultados dependen de la región observada y la cobertura de nubes.
- [USF — Sargassum Watch System](https://optics.marine.usf.edu/projects/saws.html). Publica productos de densidad y boletines regionales; emplea densidad de cobertura expresada en porcentaje.

Para usar datos observados, deben coincidir la región, la fecha y la definición de superficie en los tres indicadores. No deben combinarse cifras del cinturón atlántico completo con superficies locales de LANOT como si correspondieran a una misma medición.

## Niveles visuales de la simulación

El recuadro de densidad muestra un porcentaje y un nivel. Se usan rangos ilustrativos para el prototipo:

- Baja: 0 ≤ cobertura < 20 %.
- Moderada: 20 ≤ cobertura < 40 %.
- Alta: 40 ≤ cobertura < 60 %.
- Severa: 60 ≤ cobertura < 80 %.
- Extrema: 80 ≤ cobertura ≤ 100 %.

Estos límites son una elección de interfaz, no umbrales científicos oficiales ni derivados de NASA, LANOT o USF. Los porcentajes de la captura del usuario representan frecuencias de meses, por lo que no se usan como límites de cobertura. Para aplicar una clasificación científica se necesitan sus puntos de corte.

La explicación de densidad junto al recuadro describe cobertura en porcentaje. La fórmula de la captura (biomasa mensual / superficie regional) produce densidad de masa en t/km² y no se presenta como equivalente al porcentaje.
