# Análisis de sentimiento de Tweets sobre el COVID-19</br> 
### Problema de clasificación multiclase utilizando Redes Neuronales Recurrentes (RNN)
<p align="left">
<img src="https://i.ibb.co/BrxvVqv/NLP-2.jpg">
</p>
El objeto del presente proyecto es el de desarrollar una Red Neuronal Recurrente (RNN) que sea capaz de clasificar con éxito tweets relacionados con el COVID-19. Para este fin, se va a llevar a cabo un análisis de sentimiento de los textos extraídos directamente de Twitter aplicando técnicas de Procesamiento de Lenguaje Natural (NLP).</br>

</br>
Los datasets de partida con que contamos (entrenamiento y prueba):</br>
</br>

- *Corona_NLP_train.csv*
- *Corona_NLP_test.csv*

En un primer lugar se realiza un análisis exploratorio de los datos para posteriormente llevar a cabo la limpieza y preprocesado de los mismos. Una vez finalizado, se definen las capas de que se compone la Red Neuronal Recurrente, definiéndose como Callback un Early Stopping a fin de garantizar que no se produce Overfitting durante el aprendizaje.

Los resultados para cada una de las clases quedan reflejados en un informe de clasificación final.
