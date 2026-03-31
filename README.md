<h1>#challengeonetelecomx9</h1>
<br>
<p align="center"> <img width="500" height="500" alt="Insignia" src="https://github.com/user-attachments/assets/d0286f62-3ca5-49d9-9803-1d042dec89a2" /> </p>
<br>
<h2>🚀 Instrucciones para ejecutar el Notebook</h2>
<p>Para ejecutar este notebook en Google Colab, sigue los siguientes pasos:</p>
<p>1. Abre Google Colab en tu navegador web. </p>
<p>2. Haz click en "Subir" > luego en "explorar" > y selecciona el archivo.ipynb de este proyecto desde tu computadora. </p>
<p>3. Una vez que el Notebook esté abierto en Colab, ejecuta las celdas del Notebook secuencialmente. Si quieres ejecutar todo de una vez, puedes hacerlo en la opción "Ejecutar todas".</p>
<br>
<h2>🚨 Aviso</h2>
<p>La solución de este Notebook la encuentras en el archivo: TelecomX_LATAM.ipynb</p>
<br>
<h2>📖 Misión</h2>
<h4>Churn de Clientes</h4>
<p>La misión es desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios, la empresa quiere anticiparse al problema de cancelación.</p>
<br>
<p>¿Qué se practicará?</p>
<p>Preprocesamiento de datos para Machine Learning.</p>
<p>Construcción y evaluación de modelos predictivos.</p>
<p>Interpretación de resultados y entrega de insights.</p>
<p>Comunicación técnica con enfoque estratégico.</p>
<br>
<h2>🎯 Objetivos del challenge</h2>
<p>Preparar los datos para el modelado (tratamiento, codificación, normalización).</p>
<p>Realizar análisis de correlación y selección de variables.</p>
<p>Entrenar dos o más modelos de clasificación.</p>
<p>Evaluar el rendimiento de los modelos con métricas.</p>
<p>Interpretar los resultados, incluyendo la importancia de las variables.</p>
<p>Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.</p>
<br>
<h3>📌 Extracción (E - Extract)</h3>
<h4>Extracción del archivo tratado</h4>
<p>Carga el archivo datos_limpios.csv que contiene los datos tratados anteriormente. Utiliza el mismo archivo que se limpió y organizó en el Challenge-Telecom-X-1. El archivo contiene los datos corregidos y estandarizados.</p>
<h3>🔧 Transformación  (T - Transform)</h3>
<h4>Eliminación de columnas irrelevantes</h4>
<p>Elimina columnas que no aportan valor al análisis o a los modelos predictivos, como identificadores únicos (por ejemplo, el id del cliente). Estas columnas no ayudan en la predicción de la cancelación y pueden incluso perjudicar el desempeño de los modelos.</p>
<h4>Análisis dirigido</h4>
<p>Investiga cómo variables específicas se relacionan con la cancelación, tales como:</p>
<p>-Tiempo contrato × Cancelación.</p>
<p>-Total cobrado × Cancelación.</p>
<p>Utiliza gráficos como boxplots para visualizar patrones y posibles tendencias.</p>
<h4>Análisis de correlación</h4>
<p>Visualiza la matriz de correlación para identificar relaciones entre las variables numéricas. Presta especial atención a las variables que muestran una mayor correlación con la cancelación, ya que estas pueden ser fuertes candidatas para el modelo predictivo.</p>
<h4>Verificación de la proporción de cancelación (Churn)</h4>
<p>Calcula la proporción de clientes que cancelaron en relación con los que permanecieron activos. Evalúa si existe un desbalance entre las clases, ya que esto puede impactar en los modelos predictivos y en el análisis de los resultados. Puedes usar value_counts() de pandas para obtener esta proporción.</p>
<h4>Encoding</h4>
<p>Transforma las variables categóricas a formato numérico para hacerlas compatibles con los algoritmos de machine learning. Utiliza un método de codificación adecuado, como one-hotencoding.</p>
<h4>Separación de datos</h4>
<p>Divide el conjunto de datos en entrenamiento y prueba para evaluar el rendimiento del modelo. Una división común es 70% para entrenamiento y 30% para prueba, o 75/25, 80/20, dependiendo del tamaño de la base de datos.</p>
<h4>Creación de modelos</h4>
<p>Crea al menos dos modelos diferentes para predecir la cancelación de clientes.</p>
<h4>Evaluación de los modelos</h4>
<p>Evalúa cada modelo utilizando las siguientes métricas:</p>
<p>-Exactitud (Acurácia)</p>
<p>-Precisión</p>
<p>-Recall</p>
<p>-F1-score</p>
<p>-Matriz de confusión</p>
<br>
<h2>⚙️ Entorno de desarrollo</h2>
<p>Google Colab.</p>
<br>
<h2>🧠 Tecnologías utilizadas</h2>
<p>-Python.</p>
<br>
<h2>📘 Librerías utilizadas</h2>
<p>-pandas.</p>
<p>-plotly.</p>
<p>-matplotlib.</p>
<p>-seaborn.</p>
<p>-scikit-learn.</p>
<p>-imbalanced-Learn.</p>
<p>-numpy.</p>
<p>-pickle.</p>
