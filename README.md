Proyecto Data Science

Primera Entrega: Avance del Proyecto Final

Abstract del Proyecto

El presente proyecto tiene como objetivo realizar un análisis exploratorio de datos financieros a partir de un dataset que contiene información sobre operaciones de compra y venta de activos, incluyendo variables como las fechas de compra y venta, los precios asociados a cada transacción, el retorno nominal y el retorno esperado anualizado, junto con la clasificación de cada operación dentro de un sector específico.

La elección de este dataset se fundamenta en la relevancia que tienen los análisis cuantitativos en el ámbito de las finanzas y las inversiones. Comprender la evolución de retornos, la dispersión de resultados entre sectores y la estabilidad de cada componente permite identificar patrones de riesgo y oportunidad que resultan fundamentales para la toma de decisiones estratégicas en la gestión de carteras. Además, este conjunto de datos ofrece la posibilidad de aplicar técnicas de limpieza, transformación y visualización de datos, lo que refuerza el valor pedagógico del proyecto como ejercicio práctico en ciencia de datos.

El análisis propuesto tiene como objetivos centrales:

Procesar y limpiar el dataset, transformando columnas de tipo texto en formatos adecuados para el análisis (fechas y variables numéricas).

Explorar la distribución de los retornos mediante estadísticas descriptivas y visualizaciones como boxplots, que permiten comparar la estabilidad y el comportamiento de los distintos sectores.

Identificar correlaciones entre variables financieras, evaluando si existen sectores con un comportamiento más homogéneo o más riesgoso en relación a su retorno esperado.

A partir del boxplot presentado, en el análisis de la Distribución de Expected Return (Yearly) por Sector,es posible realizar las siguientes observaciones respecto a la estabilidad, retornos medianos, dispersión y presencia de valores extremos en los distintos sectores:

Sector más estable:
El sector FMCG muestra la menor dispersión en sus retornos anuales. La caja (IQR) es relativamente compacta y presenta pocos valores atípicos, lo que indica una mayor estabilidad y menor variabilidad en comparación con los demás sectores.

Sector con mayores retornos medianos:
El sector TECH se destaca por tener la mediana más alta entre todos los sectores analizados. Esto sugiere que, en promedio, ofrece mayores retornos esperados anuales en comparación con los demás.

Sector con mayor riesgo (alta dispersión):
Nuevamente, el sector TECH evidencia la mayor dispersión, ya que presenta una caja más amplia y bigotes más extendidos. Esto implica una alta volatilidad: si bien puede generar retornos elevados, también existe un mayor riesgo asociado debido a la variabilidad de los resultados.

Sectores con valores extremos relevantes:

AUTO: es el sector con mayor cantidad de outliers, tanto en valores muy altos (superiores al 0.8) como en retornos intermedios. Estos casos conviene investigarlos en detalle, ya que pueden corresponder a eventos excepcionales o empresas con comportamientos atípicos.

BANK: presenta outliers hacia ambos extremos, lo cual refleja situaciones particulares de riesgo o retornos extraordinarios que se apartan de la tendencia general.

RETAIL: también evidencia algunos valores extremos positivos, los cuales podrían señalar oportunidades de inversión fuera de lo habitual.

Detectar valores atípicos (outliers) que puedan tener un impacto desproporcionado en las conclusiones y que ameriten un análisis detallado.

De esta manera, el estudio busca no solo describir el comportamiento de los datos disponibles, sino también generar insights útiles para la toma de decisiones financieras. El valor agregado de este trabajo radica en combinar herramientas de análisis numérico con técnicas de visualización multivariada, para obtener una visión más clara sobre la relación entre los retornos y los sectores en los que operan los activos.

En resumen, el análisis del boxplot permite concluir que FMCG es el sector más estable, mientras que TECH ofrece los mayores retornos medianos, aunque con un nivel de riesgo considerablemente más alto debido a su dispersión. Por otro lado, los sectores AUTO y BANK presentan una alta frecuencia de valores extremos, lo que amerita un análisis más detallado de los casos puntuales.

En conclusión, este proyecto pretende establecer un puente entre la teoría financiera y el análisis práctico de datos, brindando una base sólida para la formulación de hipótesis, la evaluación de riesgos y la identificación de oportunidades de inversión.

Preguntas e Hipótesis

Preguntas de investigación:

¿Qué sectores presentan mayor estabilidad en términos de retornos anuales esperados?

¿Existe algún sector que muestre consistentemente retornos medianos más elevados que los demás?

¿Cuáles son los sectores con mayor dispersión en sus retornos, lo que podría interpretarse como mayor riesgo?

¿Se identifican sectores con valores extremos (outliers) que convenga investigar en profundidad?

¿Hay correlaciones significativas entre el precio de compra/venta y los retornos anuales esperados?

Hipótesis iniciales:

H1: Sectores con mayor estabilidad muestran una menor dispersión en los boxplots de retornos.

H2: Sectores de alta rentabilidad medianamente esperada también presentan mayor riesgo (volatilidad).

H3: Los valores extremos pueden estar asociados a errores de registro o a operaciones financieras extraordinarias.

H4: Existe una correlación positiva entre los precios de los activos y el retorno esperado anualizado.
