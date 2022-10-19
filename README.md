# Capstone-Project-Analisis-de-Datos

Integrantes: <br />
Felipe Bello <br />
Olga Cid <br />
Roberto Monsalves <br />
<br />
<br />
El uso de bicicletas se ha masificado en los últimos años como medio de transporte y acercamiento a los lugares de trabajo, estudios u otro destino, siendo una alternativa al transporte público, lo que ayuda a aliviar la congestión en las calles y el tránsito, además de promover la actividad física y mejorar la calidad de vida. Esto demanda y requiere de la mantención de una infraestructura , mecanismos y políticas públicas que sustenten y fortalezcan este servicio.

Los sistemas de bicicletas compartidas, también conocidos como sistemas de bicicletas públicas, facilitan la disponibilidad automática de bicicletas para que sean utilizadas temporalmente como medio de transporte. La mayoría de estos sistemas permiten recoger una bicicleta y devolverla en un punto diferente (estaciones o dockers), para que el usuario solo necesite tener la bicicleta en su posesión durante el desplazamiento. Uno de los principales retos en la gestión de estos sistemas es la necesidad de redistribuir las bicicletas para intentar que, en todas las estaciones, haya bicicletas disponibles a la vez que espacios libres para devoluciones.

Este proyecto contempla realizar un análisis del tiempo de viaje de los pasajeros en bicicletas en la ciudad de Toronto para el año 2021(link del dataset original: https://ckan0.cf.opendata.inter.prod-toronto.ca/tr/dataset/bike-share-toronto-ridership-data/resource/ddc039f6-07fa-47a3-a707-0121ade3b307) y predecir mediante técnicas de series de tiempo el tiempo promedio de viajes de los pasajeros para el año 2022 con la finalidad de cuantificarlos y prever potenciales medidas a considerar para sostener y expandir este servicio. Para ello se hace uso de un set de datos públicos que considera los tiempos de viaje entre estaciones de Toronto y se plantean las siguientes interrogantes: ¿ Cuál es el tiempo de viaje en bicicletas de los pasajeros en Toronto? ¿ Cuál(es) son las horas peak del día donde se solicita el servicio de bicicletas y qué días es dónde se concentra el mayor número de viajes en bicicletas en Toronto? ¿ Cuáles son las 10 estaciones de origen con mayor número de viajes? ¿Cuáles son las 10 estaciones destino con mayor número viajes finalizados? ¿Qué variables inciden en los resultados? ¿Cómo se proyectan los tiempos de viaje para el año 2022 en las estaciones más concurridas?
<br />
<br />
Los archivos con los dataset se encuentran comprimidos en formato rar debido a su gran tamaño.<br />
En este repositorio hay 4 carpetas: <br />
- La carpeta 'raw' contiene los dataset originales en formato rar, el nombre de cada archivo corresponde al mes de ese numero(01 para Enero, 02 para Febrero etc.)<br />
- La carpeta 'processed' contiene el dataset ya limpio y con el que se trabajará en formato rar separado en 2 archivos debido a su tamaño. Para poder abrirlo se deben descargar los 2 archivos en una misma carpeta y descomprimir "bicis.part01" primero.<br />
- La carpeta 'notebooks' incluye 3 notebooks de Jupyter. "1_limpieza.ipynb" contiene el código usado para la limpieza de datos, "2_analisis.ipynb" contiene el código con el analisis y la aplicación de los modelos y "3_reporte.ipynb" trae el informe final del trabajo. <br />
- La carpeta 'output' contiene el informe final del trabajo en formato html.
<br />
<br />
Para ejecutar el código del notebook "1_limpieza.ipynb" se deben descomprimir los dataset encontrados en la carpeta "raw" en la misma carpeta que el notebook y ejecutarlo utilizando JupyterNotebook o JupyterLab. Los notebooks "2_analisis.ipynb" y "3_reporte.ipynb" trabajan utilizando el dataset almacenado en la carpeta "processed", se debe descomprimir y almacenerlo en la misma carpeta que los notebooks, luego ejecutarlos utilizando JupyterNotebook o JupyterLab.
