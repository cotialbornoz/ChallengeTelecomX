# **Challenge Telecom X**

Trabajo final del Challenge Alura Store del curso de Aprendiendo a hacer ETL para Data Science de ALURA Latam | ONE Oracle Next Project. Se basa en el concepto Challenge Based Learning, es decir, un aprendizaje centrado en desafíos que Apple ayudó a crear y que se basa en 3 pilares: Compromiso - Investigación - Actuación.

Con esto, se buscó poner en práctica habilidades esenciales de análisis de datos en un escenario de negocios real, aplicando los conceptos de ETL (Extracción - Transformación - Carga) en la preparación de datos, crear visualizaciones estratégicas para identificar patrones y tendencias y realizar un Análisis Exploratorio de Datos (EDA) para generar un informe con insights relevantes.

Proyecto **finalizado**.

## **Objetivo del análisis realizado**

Se buscó brindale a la empresa Telecom X, a través del proyecto "Churn de Clientes", un análisis detallado de los factores que llevan a la pérdida de clientes, con el objetivo de bajar la alta tasa de cancelaciones.

## **Proyecto**

### Estructura

El proyecto se compone de 4 partes:

1. Extracción (E - Extract): se importaron los datos de la API de Telecom X, a partir de un archivo JSON.
2. Transformación (T - Transform): tras comprender la estructura del dataset, se realizó una comprobación y manejo de incoherencias e inconsistencias en los datos. También, se realizó la estandarización y la transformación de los mismos. 
3. Carga y análisis (L - Load & Analysis): se buscó entender la distribución de evasión, para posteriormente explorar como se distribuye la misma con respecto a las variables categóricas y numéricas.
4. Informe final: resumen de los principales hallazgos y recomendaciones para ayudar a reducir la evasión, junto con gráficos y visualizaciones para identificar patrones.

### Gráficos e insights

Puntualmente, en este proyecto encontrarás el análisis de la fuga de los clientes según:

* Su género y edad.
* Si posee pareja y/o dependientes u adicionales.
* Antigüedad en el servicio
* Tipo de contrato
* Servicios adquiridos
* Monto de cargos mensuales vs cargos totales
* Método de pago

![Preview Gráficos](https://i.imgur.com/nlJ7jbo.png "Preview Gráficos")

### Instrucciones

Para ejecutar un archivo .ipynb, las formas más comunes son usar Jupyter Notebook/Lab localmente, VS Code, o Google Colab en la nube.

* Google Colab: sube el archivo a Google Colab (o Google Drive), abre el archivo y haz clic en el botón de reproducción en las celdas.

* Jupyter Notebook/Lab: inicia el servidor de Jupyter desde su terminal (jupyter notebook), navegue hasta el archivo en el navegador web y haga clic para abrirlo. Una vez abierto, use "Cell" > "Run All" o presione Shift + Enter para ejecutar celdas individualmente. 

* Visual Studio Code (VS Code): abre el archivo en VS Code (requiere la extensión de Python/Jupyter) y haz clic en "Run All" o ejecuta celda por celda. 

