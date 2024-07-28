Laboratorio | Limpieza de datos categóricos
Para este laboratorio, utilizaremos el conjunto de datos del caso de negocio de análisis de clientes. Este conjunto de datos se puede encontrar en files_for_labla carpeta . En este laboratorio, exploraremos los datos categóricos. También puede continuar trabajando en el mismo cuaderno Jupyter del laboratorio anterior. Sin embargo, eso no es necesario.

Instrucciones
Importe las bibliotecas necesarias si está iniciando un nuevo cuaderno.
Cargue el archivo csv. Utilice la variable customer_dfcomo customer_df = pd.read_csv().
¿Qué debemos hacer con la customer_idcolumna?
Cargue las variables continuas y discretas en las variables numericals_dfy categorical_df, por ejemplo:
numerical_df = customer_df.select_dtypes()
categorical_df = customer_df.select_dtypes()
Dibuje gráficamente cada variable categórica. ¿Qué puede ver en los gráficos? Tenga en cuenta que en el laboratorio anterior utilizó un gráfico de barras para representar gráficamente los datos categóricos, con cada categoría única en la columna del eje x y una medida apropiada en el eje y. Sin embargo, esta vez intentará un gráfico diferente. Esta vez, en cada gráfico de la variable categórica, tendrá cada categoría única en la columna del eje x y el objetivo (que es numérico) en el eje Y.
Para los datos categóricos, verifique si es necesario realizar alguna limpieza de datos. Sugerencia : puede utilizar la función value_counts()en cada una de las columnas categóricas y verificar la representación de las diferentes categorías en cada columna. Analice si esta información se podría utilizar de alguna manera para la limpieza de datos.
