# Time-Series-Forecasting-RNN-LSTM-GRU
Este proyecto implementa y compara modelos de aprendizaje profundo para la predicción de series temporales. Se enfoca en el uso de Redes Neuronales Recurrentes (RNN) para capturar dependencias a largo plazo y patrones secuenciales en datos históricos.


# Time Series Forecasting: Comparative Analysis with LSTM & GRU

## Descripción
Este proyecto implementa y compara modelos de aprendizaje profundo para la predicción de series temporales. Se enfoca en el uso de Redes Neuronales Recurrentes (RNN) para capturar dependencias a largo plazo y patrones secuenciales en datos históricos.

## Stack Tecnológico
* **Framework:** TensorFlow / Keras.
* **Arquitecturas:** LSTM (Long Short-Term Memory) y GRU (Gated Recurrent Unit).
* **Procesamiento:** Scikit-learn (MinMaxScaler), Pandas, NumPy.
* **Visualización:** Matplotlib (Análisis de tendencias y estacionalidad).

## Innovaciones y Análisis Técnico
* **Benchmarking de Arquitecturas:** Implementación comparativa entre modelos **LSTM** y **GRU**, analizando la eficiencia computacional vs. precisión de predicción.
* **Arquitectura Robusta:** Integración de capas de **Dropout** para mitigar el sobreajuste (overfitting) y garantizar la estabilidad del modelo.
* **Manejo de Gradientes:** Análisis de la eficacia de las unidades GRU para evitar el desvanecimiento del gradiente en contextos de recursos computacionales limitados, manteniendo un rendimiento competitivo.
* **Resultados Visuales:** Los modelos alcanzaron una alta fidelidad en las predicciones, con curvas de tendencia que se alinean casi perfectamente con los datos reales.

## Conclusiones del Proyecto
* Se demostró que tanto LSTM como GRU ofrecen resultados consistentes para este conjunto de datos, con una convergencia estable.
* La unidad **GRU** se destaca como una alternativa eficiente en costo de procesamiento sin sacrificar significativamente el rendimiento.

<img width="843" height="564" alt="image" src="https://github.com/user-attachments/assets/f63ee168-9116-4b0c-a0c3-add46b9559fe" />
<img width="873" height="552" alt="image" src="https://github.com/user-attachments/assets/843144be-b9f9-4a4b-b1c1-55a8da4402a7" />
<img width="1190" height="571" alt="image" src="https://github.com/user-attachments/assets/f671da0b-0485-479a-b68d-9495e6f9ee61" />
<img width="1134" height="515" alt="image" src="https://github.com/user-attachments/assets/79483a46-316d-4e48-a5cf-7f0f0f0272b8" />
<img width="1146" height="528" alt="image" src="https://github.com/user-attachments/assets/7e278039-2579-40c8-9042-67ea8fbf35dc" />





## Cómo empezar
1.  Instalar dependencias: `pip install tensorflow pandas matplotlib scikit-learn`
2.  Clonar el repositorio.
3.  Ejecutar el notebook `Trabajo final Series temporales_01.ipynb`.
