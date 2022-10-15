# Microclimatic-analysis-for-cultural-heritage-preservation
Microclimatic analysis for cultural heritage preservation purposes using data-logger record.

This is the R script used to generate the complete microclimatic analysis for cultural heritage preservation purposes using data-logger record shown in the manuscript:

Ureña, I. and Bolívar, H. (2022). Aplicación del lenguaje de programación R al análisis de datos microclimáticos para Conservación Preventiva. Ciencia y Arte VIII. Ministerio de Cultura y Deporte. pp: 91-103.

You can find the book (free) in this url: https://www.libreria.culturaydeporte.gob.es/search/?q=Ciencia+y+Arte+VIII

This repository consists of the script “analisis_microclimatico.Rmd” and a document generated as example in html and pdf format.

The script uses RMarkdown to generate a document in html format. When you click the “Knit” button a document will be generated with all the graphics and tables created with the results of the analyses. This document has the following parts:

- Head
- Information about the data collected
- Global analysis:
    -	Summary table
    -	Time series of relative humidity and temperature values
    -	Histogram for humidity and temperature
    -	Box-plot for humidity and temperature
    -	Information on maximum hourly and daily fluctuations for relative humidity and temperature
    -	Boxplot with maximum hourly and daily fluctuations for relative humidity and temperature
- Annual analysis: summary table
- Monthly analysis:
    - Summary table 
    - Monthly graphics with temporal evolution of relative humidity and temperature values
    - Table of maximum daily fluctuations for each month 
    - Table of maximum hourly fluctuations for each month
- Seasonal analysis

The report and the comments on the scripts are written in Spanish.

The data used as input for the analyses (datos_sensor.xls) are generated for the software Testo Comfort Software Basic 5,from the data collected for the data-logger Testo 174 H (Testo Industrial Services GmbH, Alemania), which is an instrument extensively used for the cultural institutions.

The example has been created with simulated data of a hypothetical recording of the relative humidity and temperature values each hour for a period of 426 days (approx. 14 months).

More information about the analyses on the publication.

This script is accessible under a Creative Commons 4.0 license under the following terms: acknowledging the creator's attribution, for non-commercial use, it must be shared with the same license and without the possibility of additional restrictions (CC BY-NC-SA 4.0). You can check the license details at the following location: http://creativecommons.org/licenses/by-nc-sa/4.0/
