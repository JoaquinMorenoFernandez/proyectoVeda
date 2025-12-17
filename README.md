# Proyecto V, Analisis Exploratorio de Datos
Ejercicio 5, analisis exploratorio de datos, dataset

GOOGLE COLAB LINK ----> https://colab.research.google.com/drive/1yHTxTxoxNyoG_vwsp8Ulev1900YDNQCe

**¿Qué es el EDA y cuál es su propósito en el análisis de datos?**
El EDA es un análisis de datos exploratorio, en el cual se analizan y trabajan los siguientes datos: Análisis descriptivo, ajuste de tipos de variable, deteccion y tratamiento de variables faltantes, identificacion de datos atipicos, correlacion de variables.

**Añade un ejemplo práctico de un caso en el que el EDA sea fundamental antes de aplicar modelos de Machine Learning**
Por ejemplo, cualquier modelo de machine learning que usen usuarios o trabajadores de una empresa, necesita estar entrenado en los tipos de datos y tipo de uso que se le va a dar a dicho machine learning.

**¿Qué tipos de datos existen (categóricos, numéricos, ordinales, etc.) y cómo se tratan en un EDA?**
- Cualitativos -> Categoricos -> Ordinal y Nominal.
- Cuantitativos -> Numericos -> Discreto y Continuo.

**¿Qué técnicas básicas se usan en un EDA?**
Análisis descriptivo, ajuste de tipos de variable, deteccion y tratamiento de variables faltantes, identificacion de datos atipicos, correlacion de variables.

**¿Cuál es la diferencia entre análisis univariado, bivariado y multivariado?**
- Univariado: analiza una sola variable para describirla.
- Bivariado: analiza dos variables para ver si están relacionadas.
- Multivariado: analiza tres o más variables para estudiar relaciones complejas o predecir resultados.

**¿Qué es la limpieza de datos y qué tareas suelen incluirse en este paso?**
Consiste en eliminar los datos en blanco, erroneos o inconsecuentes y trata de aunar la mayoria de datos bajo el mismo tipo de variable para poder trabajar las tablas que haya mas comodamente

**¿Qué papel juegan las librerías pandas, matplotlib y seaborn en un EDA?**
- seaborn/matplotlib: Visualización de datos, gráficos.
- pandas: Gestión de conjuntos de datos (dataframes), lectura de archivos de datos (csv, excel), transformaciones...

**Explica brevemente el flujo típico de un EDA desde la carga del dataset hasta las conclusiones**
El flujo de trabajo de un EDA es:
1º Preguntas: Que quieres encontrar, que quieres saber sobre los datos, razón por la que analizamos los datos
2º Determinar tamaño de los datos: Cuantas obervaciones existen, cuantas variables hay, ¿necesitas todas las observaciones?, ¿necesitas todas las variables?
3º Categorizar variables: Variables categoricas, variables continuas, como tratar datos faltantes, como explorar cada variable dependiendo de su categoria
4º Limpieza y validacion de datos: ¿Valores faltantes?, ¿en que proporcion?, ¿como los trato?, ¿distribucion?, ¿valores atipicos?
5º Establecer relaciones: ¿que relaciones existen entre las variables?, ¿consideramos todas lsa variables?, ¿se agrupan las observaciones, que significa?, ¿Se observa algun patron, y significa algo?

**¿Qué es una matriz de correlación y para qué sirve en el EDA?**
Una matriz de correlación muestra la relación (fuerza y dirección) entre pares de variables numéricas.
En el EDA sirve para detectar variables relacionadas o redundantes.

**¿Qué son los outliers y qué métodos existen para detectarlos y tratarlos en un análisis exploratorio?¿Qué es hipótesis testing y para qué sirve en el EDA?**
Los outliers son valores atípicos; se detectan con IQR, z-score o boxplots y se tratan eliminándolos, transformándolos o analizándolos aparte.
El hypothesis testing evalúa si un patrón observado es estadísticamente significativo en el EDA y ayuda a validar relaciones o diferencias iniciales.
