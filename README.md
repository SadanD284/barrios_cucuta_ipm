# Barrios San José de Cúcuta

Este repositorio contiene la digitalización cartográfica de los barrios en la ciudad de San José de Cúcuta, Norte de Santander (Colombia). La construcción de los polígonos se hace a partir del Plan de Ordenamiento Territorial (POT) del Acuerdo No. 022 de 2019. El objetivo principal de la iniciativa es construir unidades de barrios editables y disponibles para la investigación, la academia y la sociedad civil, siendo particularmente útil en estudios urbanos con información cuantitativa. 

La capa de barrios es compatible con el marco de georreferenciación del Departamento Administrativo Nacional de Estadísticas (DANE), por lo tanto, es posible unir datos de encuestas como el Censo Nacional de Población y Vivienda (CNPV) 2018. Este insumo es reproducible para diferentes tipos de estudios en el contexto urbano de la ciudad de San José de Cúcuta. Es importante advertir que las capas almacenadas en este repositorio no constituyen una cartografía oficial del municipio, sino una reconstrucción digital para fines analíticos.

Hacemos uso de los datos del CNPV 2018 para calcular una aproximación de la población por barrios en Cúcuta, y agregamos un ponderado del Índice de Pobreza Multidimensional (IPM) publicado en el geoportal del DANE para la ciudad. Esto permite mostrar al usuario la compatibilidad de los polígonos construidos con las manzanas censales.

## Organización de carpetas

**datasets:** archivos con diferentes formatos de los calculos realizados por barrios a partir de las capas digitalizadas.

**shapefile:** arhivos de las capas digitalizadas de los barrios de San José de Cúcuta.  

### Variables incluidas en la tabla de atributos

La capa incluye cuatro (4) columnas, se incluyen dos (2) dos variables como muestra analítica: 

**id:** variable de identificación del barrio (no corresponde necesariamente a un orden preestablecido).

**barrio:** nombre del barrio identificado en el POT.

**poblacion_:** población total estimada para cada barrio con base en el CNPV 2018 (DANE).

**ipm_ponder:** índice de pobreza multidimensional (IPM) ponderado por la población de cada barrio. 

Para mayor información sobre el proceso metodologico realizado en la digitalización de las capas consultar el documento *Digitalización de Barrios de Cúcuta (metodología de construcción)*.
 
## Información de contacto

A la fecha continuamos trabajando en algunas limitaciones identificadas en está primera versión. Para mayor información y sugerencias no dude en enviarnos un correo a sadandelacruz@gmail.com

## Cita

De la Cruz (2026). Digitalización de barrios San José de Cúcuta (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.18765372



