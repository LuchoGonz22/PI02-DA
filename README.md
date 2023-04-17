<h1 align='center'>
  <img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
</h1>
  
  <h1 align='center'>
 <b>Análisis de datos del mercado bursátil (S&P 500)</b><br>
    LUCIANO GONZALEZ
</h1>

<h1 align='center'>
<img src='https://github.com/LuchoGonz22/PI02-DA/blob/main/assets/logo_da.jpg' height = 200>
</h1>

## Índices
- [Contexto](#contexto)
- [Fases](#fases)
- [Material](#material)
- [KPI's](#kpis)
  
## Contexto
Este proyecto tiene como objetivo analizar el mercado bursátil S&P 500 y aplicar diversas técnicas de análisis de datos para entender su funcionamiento y obtener información valiosa para una empresa sin conocimientos financieros. Se utilizaron datos obtenidos a través de la API de yFinance, Webscraping y se realizaron análisis exploratorios de los datos, así como la creación de KPIs y visualizaciones en Power BI para una mejor comprensión y toma de decisiones.
  
## Fases
  * Ingesta y limpieza de datos: Se buscó y se descargó datos históricos del S&P 500 a través de la API de Yahoo Finance. Se limpiaron y procesaron los datos para          poder analizarlos posteriormente.<br>

  * Análisis exploratorio de datos (EDA): Se realizaron visualizaciones y se exploraron los datos para encontrar patrones y tendencias. Se examinaron los precios de        cierre, los volúmenes de negociación y otros datos relevantes para el análisis.<br>

  * Cálculo de KPIs: Se calcularon varios KPIs para evaluar el rendimiento del mercado bursátil. Estos KPIs incluyen la capitalización de mercado, el retorno sobre el      patrimonio (ROE), las ganancias por acción (EPS) y la relación de Sharpe.<br>

  * Creación de un dashboard en PowerBI: Finalmente, se creó un dashboard interactivo en PowerBI para presentar los resultados de manera clara y fácil de entender          para el cliente.<br>
  
## Material
* datasets_companies: Carpeta donde se guardaron los archivo de las empresas en general. [Acceder aquí](https://github.com/LuchoGonz22/PI02-DA/tree/main/datasets_companies)<br>
* tech_kpis: Carpeta donde se guardaron los KPI's con las empresas "Tech". [Acceder aquí](https://github.com/LuchoGonz22/PI02-DA/tree/main/tech_kpis)<br>
* eda_process_comp: Archivo Jupyter Notebook donde se realizó el proceso de EDA para el análisis de los datos. [Acceder aquí](https://github.com/LuchoGonz22/PI02-DA/blob/main/eda_process_comp.ipynb)<br>
* dashboards: Carpeta donde contiene los dashboards realizados en PowerBI y en formato PDF. [Acceder aquí](https://github.com/LuchoGonz22/PI02-DA/tree/main/dashboards) <br>

  
## Tecnologías utilizadas
* Python: para la limpieza, procesamiento y análisis de datos.<br>
* PowerBI: para la visualización y presentación de los datos.<br>
* GitHub: para el control de versiones del código y la documentación del proyecto.<br>

## KPI's
- Market Capitalization: Es el valor total de mercado de una empresa, es decir, el valor que los inversionistas están dispuestos a pagar por todas las acciones en circulación de la empresa. Se calcula multiplicando el precio de una acción por el número total de acciones en circulación. <br>

- Return on Equity (ROE): Es una medida de la rentabilidad de una empresa en relación con el capital que los accionistas han invertido en ella. Se calcula dividiendo la utilidad neta de una empresa entre el total de su patrimonio. Cuanto mayor sea el ROE, mejor será la rentabilidad de la empresa en relación con la inversión de los accionistas. <br>

- Earnings per Share (EPS): Es una medida de la ganancia por acción de una empresa, es decir, la cantidad de ganancias que una empresa ha obtenido por cada acción en circulación. Se calcula dividiendo las ganancias netas de una empresa entre el número total de acciones en circulación. Cuanto mayor sea el EPS, mejor será la rentabilidad de la empresa por acción.
  
 - Sharpe Ratio: Mide numéricamente la relación Rentabilidad / Volatilidad Histórica (desviación standard) de un Fondo de Inversión. Se calcula dividiendo la rentabilidad de un fondo menos la tasa de interés sin riesgo entre la volatilidad o desviación standard de esa rentabilidad en el mismo periodo.

## Resultado y conclusiones
A través del análisis de los datos y la visualización de los mismos, se encontraron diversos patrones interesantes en el comportamiento del mercado bursátil. También se calcularon los KPIs antes mencionados para las empresas tecnológicas Amazon, Apple y Microsoft, y se crearon gráficos para visualizar su evolución a lo largo del tiempo.
<br>
<br>
En general, se encontró que las empresas tecnológicas tuvieron un mejor rendimiento en términos de Market Capitalization, ROE y EPS. Sin embargo, el Sharpe Ratio, que mide la rentabilidad ajustada al riesgo, mostró resultados más variados entre las empresas.
<br>
<br>
El dashboard creado en Power BI permitió una visualización interactiva de los datos y facilitó la comprensión de su comportamiento. Se recomienda seguir explorando el uso de herramientas de visualización de datos para mejorar la comunicación de resultados a stakeholders no técnicos.
