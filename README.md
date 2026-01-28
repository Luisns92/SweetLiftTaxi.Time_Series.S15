# Sweet Taxi, Series temporales

📖 Resúmen:  
  Analizar y preparas los datos para lograr predecir el comportamiento de las siguientes horas de servicio, con RMSE máximo de 48.
  .  
  .  
  .  

🎯 Objetivo:  
  Construir modelo que prediga las horas más concurridas para atraer mayores conductores en esas horas y abastecer la demanda.

❌ Problema:  
  Información primaria insuficiente.

✅ Solución:  
  Creación columnas de comportamiento temporal (año, mes, día, día de la semana y hora) así como desfases (lag) y promedio móvil.

🔢 Metodologia:  
  1. Limpiamos y le damos formato a los datos.
  2. Enriquecimiento del conjunto de datos con nuevas columnas.
  3. Creación de modelos y pruebas. 
  4. Elección del mejor modelo mediante la metrica RMSE.

📊 Conclusiones:  
  Se logró crear un modelo capaz de predecir las siguientes ordenes por horas, el modelo satisface las necesidades mínimas del cliente.
