# Proyecto-TelecomArg

---Rol a desarrollar
En este contexto, una empresa prestadora de servicios de telecomunicaciones le encarga a usted la realización de un análisis completo que permita reconocer el
comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet, pero también es importante 
considerar el comportamiento asociado al resto de los servicios de comunicación, con el fin de orientar a la empresa en brindar una buena calidad de sus servicios,
identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.

Con el fin de monitorear la eficacia de los objetivos de la empresa, se le pide visualizar en un dashboard el siguiente KPI y establecer 3 KPIs adicionales 
producto de su análisis:

**Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia. (Datos)

Nota: En la sección de material de apoyo se puede encontrar más información sobre los KPIs.

Propuesta de trabajo -requerimientos de aprobación-


--Análisis Exploratorio de los datos (Exploratory Data Analysis = EDA)

El reporte debe incluir un resumen de estadísticas descriptivas de los datasets, análisis univariados (por ejemplo, distribución de variables numéricas), 
análisis bivariados (correlación entre variables numéricas y/o categóricas) y cualquier análisis que le ayude al mejor entendimiento de los datos (encontrar 
patrones, outliers y/o anomalías, entre otros). El reporte debe presentarse en un notebook (.ipynb) con adecuado uso de markdowns y comentarios.

--Dashboard

Debe ser funcional y coherente con el análisis y la historia que vayan a relatar. El archivo debe estar en su repositorio (.pbix, .py o el que aplique).

--KPIs

Se deben sugerir 3 KPIs y deben aparecer en el dashboard. Tenga en cuenta que deben tener relación con la historia que está contando. Asimismo, se espera 
que en la presentación explique el análisis y la funcionalidad de los KPIs sugeridos.

⚠️ Análisis ⚠️

No se calificará solamente la producción de gráficos con datos (dashboard), sino también los análisis y conclusiones que encuentren en ellos.

Repositorio de GitHub

El repositorio debe contener un README principal donde se presente de forma general su proyecto. Presentar como propio el readme proporcionado por Henry será 
considerado como insuficiente para cumplir con este requerimiento.

PLUS
Nota: la realización de los siguientes ítems no es intercambiable con los requerimientos mínimos establecidos en la sección anterior "Propuesta de trabajo". 
Empiece con esta sección una vez haya cumplido con los requerimientos mínimos, a modo de desafiarse a usted mismo.

Redactar un reporte de análisis con base en sus dashboards e incluirlo en el readme de sus repositorios. También debe incluir el análisis y la funcionalidad de 
los KPIs sugeridos.

Ejecutar scripts de python en la herramienta de visualización de datos escogida.

Extraer los datos desde la API del sitio (no descarga de csv).

Cruce de datos con datasets complementarios.
*************************************************************************
dataset principal: https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/

Tablas a consultar:
( x ) "Penetración de internet fijo (accesos por cada 100 hogares)", podemos identificar rápidamente qué provincias tienen las mayores tasas de penetración de internet
fijo y cuáles necesitan mejorar. De esta forma, podemos establecer prioridades para enfocar los esfuerzos de la empresa.

( x ) "Acceso a internet fijo por rangos de velocidad de bajada y provincia" permitirá a la empresa realizar un análisis más detallado de la calidad del servicio de 
internet que ofrecen en cada provincia. Utilizando esta información, se pueden identificar áreas en las que se necesitan mejoras significativas.

( x ) "Ingresos trimestrales por la prestación del servicio de internet fijo" permitirá evaluar la rentabilidad de la empresa y cómo esta varía a lo largo del tiempo.
Esto ayudará a establecer objetivos realistas y planificar la estrategia de la empresa en consecuencia.

( x ) "Velocidad media de bajada de internet fijo por provincia" permitirá a la empresa comparar su servicio de internet con el promedio del país y otras provincias.
Esto les dará una idea de qué áreas necesitan mejorar en términos de velocidad de internet.

( x ) "Total nacional de accesos a internet fijo por banda ancha y banda angosta" permitirá a la empresa identificar la tendencia en cuanto a la utilización de servicios
de banda ancha y banda angosta, lo que les permitirá diseñar su estrategia de servicios en consecuencia.

*************************************************************************
