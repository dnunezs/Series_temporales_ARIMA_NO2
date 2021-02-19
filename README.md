# Análisis de series temporales de la calidad del aire (NO2) y predicción con modelo ARIMA
Utilizaremos los datos de la [calidad del aire](http://mediambient.gencat.cat/es/05_ambits_dactuacio/atmosfera/qualitat_de_laire/principals_contaminants/index.html) del Eixample de Barcelona desde 2011, concretamente del contaminante dióxido de nitrógeno (NO2). Los datos son medidos por la Red de Vigilancia y Previsión de la Contaminación Atmosférica y se pueden obtener para otras estaciones, contaminantes y períodos [aquí](http://mediambient.gencat.cat/es/05_ambits_dactuacio/atmosfera/qualitat_de_laire/vols-saber-que-respires/descarrega-de-dades/index.html).

- Analizamos la serie temporal viendo que tiene heterocedasticidad, tendencia y estacionalidad, eliminando esto compnenetes.
- Aplicamos un modelo SARIMA.
- Usamos el modelo SARIMA que hemos fitado antes para predecir los dos próximos años.
- Añadimos la heterocedasticidad, tendencia y estacionalidad para comparar el resultado de la predicción.

![alt text](https://github.com/dnunezs/Series_temporales_ARIMA_NO2/blob/main/Predicci%C3%B3n%20ARIMA%20NO2.png)
