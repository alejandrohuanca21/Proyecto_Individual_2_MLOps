# ANALISIS DE SINIESTROS VIALES EN CABA

![siniestros](https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/blob/main/IMAGEN/consejos-de-seguridad-vial.jpg)

## INTRODUCCION
Este proyecto tiene como finalidad la elaboración de un análisis de datos solicitado por el Observatorio de Movilidad y Seguridad Vial (OMSV), bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA). Para el analisis de datos se utiliza un dataset con información sobre homicidios de siniestros viales en la Ciudad de Buenos Aires, durante los años 2016-2021, que es de publico acceso en la página oficial del Gobierdo de la ciudad.

## FUENTE 

Para esto se va trabajar con dos Datasets bajados de la web data.buenosaires.gob.ar/dataset/victimas-siniestros-viales, que contiene un archivo en formato Excel con informacion de Víctimas Fatales y lesiones en Siniestros Viales en la ciudad de Buenos Aires (Homicidios.xlsx y lesiones.xlsx).

## PASOS

Como primer paso se hizo un proceso de ETL (Extracción, limpieza y carga de datos) y un Proceso de EDA (Análisis Exploratorio de los datos) en Visual Studio, con el lenguaje de programacion Python y las librerias Pandas, Os, Matplotlib, Seaborn, Folliun y Sqlalchemy y las librerias necesarias para su correcta funcionalidad para luego la confeccion de un dashboard o un reporte usando en este caso la herramienta de PowerBI para luego presentarlo.

## OBJETIVO

El objetivo es elaborar un proyecto de analisis de datos, con el fin de generar informacion que le permita a las autoridades locales tomar medidas para disminuir la cantidad de victimas fatales de los siniestros viales.

## ANALISIS 

Se contabilizaron un Total de 715 Homicidios por accidentes de transito en el rango de los años 2016 al 2021.

De esas 715 muertes el 77% son de sexo Masculino.

El año con mayor cantidad de Homicidos por Accidentes fue el 2018 con 148 muertes.

Las comunas que mas Homicidios por accidentes tienen son la Comuna 1 ( barrios de Retiro, San Nicolás, Puerto Madero, San Telmo, Montserrat y Constitución), 4 (barrios de La Boca, Barracas, Parque Patricios y Nueva Pompeya) y 9 ( barrios de Liniers, Mataderos y Parque Avellaneda.).

Los meses con mas Homicidios por accidentes son Noviembre y Diciembre.

42% de los accidentes con victimas fatales son en Motos.

35% de los accidentes con victimas fatales son Peatones.

60% de los accidentes suceden en avenidas, con un 85% de ellos en una esquina o cruce.

Los horarios con mas accidentes son entre las 6 y 8 de la mañana.

## SOLUCIONES PROPUESTAS

Continuar monitoreando los 3 Kpis propuestos.

Reforzar los controles en los horarios pico del día a día

Generar una campaña de concientización para prevenir los accidentes en las avenidas y cruces.

Realizar prevencion sobre las personas de Sexo Masculino, en especial a los jovenes de 18 a 39 años.

Generar un proyecto con legisladores de la provincia en conjunto con el observatorio y presentarlo en la legislatura bonaerense para crear un programa de educación integral obligatorio sobre adicciones y seguridad vial enfocado en los primeros años que los jovenes sacan el registro de conducir.

Generar una campaña de Prevencion de accidentes en motociclistas y peatones que son los que tienen mayor riesgo.

Hacer enfasis en el control de las comunas 1 , 4 y 9 que son las comunas con mayor indice de accidentes de transito mortales.

## RUTA DE TRABAJO 

### ETL
Se realizo un trabajo de extraccion y tratamiento de los datos donde se tuvo en cuenta datos nulos, duplicados y conversion de formatos de los datos para posteriormente ser analizados.
#### Link : https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/blob/main/ETL_y_EDA.ipynb

### EDA
Se realizo un analisis exploratorio de datos previo donde pudimos observar como se comportaban las variables a travez de graficos estadisticos. 
#### Link : https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/blob/main/ETL_y_EDA.ipynb

### Dashboard

Se realizo un Dashboard interactivo en la herramienta PowerBI, done podremos observar las graficas y el comportamiento de los datos de manera interactiva y amigable para el visualizador.
#### Link : https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/blob/main/Accidentes%20de%20transito%20CABA.pbix

## KPIS
Se elaborará tres KPIs propuestos con sus correpondientes graficas:

    Reducción del 10% en la tasa de homicidios en siniestros viales en los últimos seis meses, en comparación con el semestre 
    anterior.

    Reducción del 7% en la cantidad de accidentes mortales de motociclistas en el último año, respecto al año anterior.

    Reducción del 15% en la cantidad de accidentes mortales en avenidas en el último año, respecto al año anterior.

#### Link KPIS : https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/blob/main/KPIS.ipynb

## Documentation

[Dataset1](https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/tree/main/Datasets)
[Dataset2](https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/tree/main/Datasets%202)
[Dataset3](https://github.com/alejandrohuanca21/Proyecto_Individual_2_MLOps/tree/main/Datasets3)
Aqui podemos encontrar el link a los datasets originales
