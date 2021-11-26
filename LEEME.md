# Analisis microclimático para la conservación del patrimonio cultural

Este es el texto en lenguaje R desarrollado para realizar el análisis estadístico completo de las condiciones microclimáticas para conservación preventiva a partir del registro tomado por data-loggers presentado en el manuscrito:

Ureña, I. y Bolívar, H. (2022). Aplicación del lenguaje de programación R al análisis de datos microclimáticos para Conservación Preventiva. Ciencia y Arte VIII. Ministerio de Cultura y Deporte.

El repositorio contiene el script: “analisis_microlimatico.Rmd”, el informe generado en formato html y en pdf.

El script usa RMarkdown para general un documento en formato html. Cuando se pulsa el botón “Knit” se genera el informe con los resultados del análisis mostrados en forma de texto, tablas y gráficos. Dicho documento consta de las siguientes partes

- Cabecera
- Datos del sensor
- Análisis global, con:
  -	tabla resumen de los parámetros medidos.
  -	gráfica de evolución temporal de los parámetros humedad relativa y temperatura.
  -	histograma de frecuencias de las variables humedad relativa y temperatura
  -	diagramas de cajas de los valores de humedad relativa y temperatura.
  -	texto en el que se detalla la oscilación máxima diaria y horaria
  -	diagramas de cajas de las oscilaciones diarias y horarias tanto para la humedad relativa como para la temperatura.
- Análisis anual de las variables, en el que se presenta en una tabla resumen.
- Análisis mensual, con:
  - tabla resumen 
  - gráficos mensuales con la evolución temporal
  - tabla con las oscilaciones máximas diarias para cada mes 
  - tabla con las oscilaciones máximas horarias para cada mes
- Análisis estacional

El informe generado así como los comentarios dentro del script están en castellano.

Los datos empleados como entrada para el análisis (datos_sensor.xls) tienen el formato de tabla xls que genera el software Testo Comfort Software Basic 5, a partir de los datos recogidos por el data-logger de la marca y modelo Testo 174 H (Testo Industrial Services GmbH, Alemania), ya que se trata de un instrumento ampliamente utilizado en diversas instituciones culturales.
Para el informe ejemplo presentado se ha empleado un conjunto de datos correspondiente a un caso simulado en el que se toman los valores de humedad relativa y temperatura cada hora durante un periodo aproximado de 14 meses (426 días).

Más información sobre el análisis disponible en la publicación.

Este script se encuentra accesible bajo una licencia Creative Commons 4.0 bajo los siguientes términos: reconociendo la atribución del creador, para su uso sin fines comerciales, se ha de compartir con igual licencia y sin la posibilidad de realizar restricciones adicionales (CC BY-NC-SA 4.0). Puede consultar los detalles de la licencia en la siguiente ubicación: http://creativecommons.org/licenses/by-nc-sa/4.0/
