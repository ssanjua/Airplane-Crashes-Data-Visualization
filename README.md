
<h1 align='center'>
 <b>PI02_DataAnalytics</b>
</h1>
 

<p align="center">
<img src="https://github.com/paupallares/PI_Analytics/blob/94e8c17365cf7ab8f4986d9489c64d5bbb275583/img/analytics.png"  height=300>
</p>

# <h1 align="center">**`Accidentes aéreos 🚀🚀 `**</h1>

## Contexto 🛫

La **seguridad aérea** es de suma importancia para prevenir accidentes y proteger a las personas y las aeronaves. Los accidentes aéreos pueden ser causados por una variedad de factores y pueden tener consecuencias devastadoras en términos de pérdidas humanas y económicas. Por esta razón, se lleva a cabo un **trabajo de investigación** en el análisis de accidentes aéreos para obtener conocimientos y mejorar la seguridad en la aviación.

El análisis de datos históricos de accidentes aéreos permite identificar patrones, tendencias y factores contribuyentes que pueden ayudar a prevenir futuros accidentes. Estos datos permiten a los investigadores obtener **insights valiosos** que pueden utilizarse para mejorar la capacitación de pilotos y personal de mantenimiento, así como para mejorar el diseño y la fabricación de aviones y equipos de aviación.

`En resumen, el análisis de datos de accidentes aéreos desempeña un papel fundamental en el trabajo de investigación para mejorar la seguridad aérea.`


## Propuesta 📝

El proyecto tiene como objetivo desarrollar un **`dashboard`** interactivo que permita a los usuarios explorar los datos y extraer información relevante sobre los accidentes de aviones. Además, se generará un informe completo para presentar los hallazgos obtenidos a partir del análisis de datos.

En el dashboard se muestran los siguientes indicadores clave de rendimiento **KPI**:

+ ▪️ Reducir en 5% la tasa de mortalidad a nivel anual.
+ ▫️ Reducir en un 8% la relación de muertes por accidentes a nivel anual.
+ ▪️ Mantener por encima del 50% los accidentes con sobrevivientes.
+ ▫️ Reducir anualmente en 10% el número de accidentes con fatalidades colaterales (en tierra).


# <h1 align="center">`🌩️ 🛫 🪂 🛩️ 🚁 🛰️ ✈️ 🛸 🛬 👩‍✈️`

## Contenido 📊
 
#### `ETL - EDA`

**Limpieza de datos** 👩🏻‍💻

En este proyecto, se realizó un ETL junto con un EDA utilizando diversas herramientas y bibliotecas como Matplotlib, NumPy, Pandas, Seaborn y Wordcloud.

Durante la etapa de extracción se llevó a cabo la limpieza de datos, donde se detectaron y manejaron los valores nulos y los valores atípicos.

Además, se realizaron diversas transformaciones en los datos, como renombrar columnas y la eliminación de campos innecesarios, con el objetivo de mejorar la calidad y la estructura de los datos.

Una vez que los datos estuvieron limpios y preparados, se procedió al Análisis Exploratorio. Durante esta etapa, se realizaron gráficos para explorar y visualizar los datos en busca de patrones, tendencias y relaciones.

Se realizaron análisis comparativos en función de los años y la cantidad de accidentes, lo que permitió obtener información valiosa sobre la evolución de los accidentes a lo largo del tiempo. Esto nos permitió comprender mejor el contenido del dataset y obtener información relevante sobre los accidentes aéreos.

#### `Dashboard interactivo 🎚️🎛️`

En este proyecto, utilizamos **`Tableau`** para crear un conjunto de dashboards interactivos que nos ayudaron a comprender mejor los accidentes aéreos y descubrir patrones y tendencias significativas en los datos. A través de estos dashboards, pudimos contar una historia convincente y obtener insights valiosos sobre los accidentes.

Se puede encontrar en este link: <a href="https://public.tableau.com/app/profile/paula.pallares/viz/PI_DA01/Dashboardmain?publish=yes">PI_DA02_paupallares</a>



#### `KPIs`

1. **`KPI 1:`** 

🔻 *Reducir en 5% tasa de mortalidad anual:* 

	Muertes a bordo / Personas a bordo

2. **`KPI 2:`** 

🔺 *Reducir en 8% tasa de muertes por accidente anual:*
	
	Personas a bordo / Cantidad de accidentes

3. **`KPI 3:`** 

🔻 *Mantener arriba del 50% los accidentes con sobrevivientes:*

	(Personas a bordo - Muertes a bordo) / Cantidad de accidentes 

4. **`KPI 4:`** 

🔺 *Mantener por debajo del 10% las fatalidades por accidentes colaterales:*
	
	Muertes colaterales / Total de muertes

  
#### `Hallazgos 🕵🏻‍♀️`

Durante el desarrollo de la aviación comercial, podemos observar un incremento en los accidentes y fatalidades a partir de aproximadamente 1914. Es comprensible que a medida que aumenta el número de vuelos, también se produzca un mayor número de accidentes. Entre 1918 y 1939, se conoce como la "Era de oro de la aviación", período en el cual se produjeron avances tecnológicos significativos y se despertó la fascinación mundial por la aviación. Esto resultó en un aumento en la cantidad de vuelos y, por ende, en los accidentes. Sin embargo, es interesante notar que durante este período, aunque los aviones se estrellaban, el costo en términos de vidas humanas no era tan significativo. Esto podría atribuirse a que muchos de estos vuelos eran realizados sin pasajeros, en su mayoría pruebas y desarrollos tecnológicos.

<p align='center'>
<img src ="https://github.com/paupallares/PI_Analytics/blob/94e8c17365cf7ab8f4986d9489c64d5bbb275583/img/accidentes%20vs%20fatalidades.png" height=250>
<p>

En la gráfica, podemos observar un drástico aumento en los accidentes después de 1940, coincidiendo con la Segunda Guerra Mundial y el subsiguiente incremento en la cantidad de vuelos debido a los avances en la aviación durante la guerra. Durante este tiempo, se construyeron numerosas aeronaves con fines militares, las cuales posteriormente se utilizaron para fines comerciales y de transporte. Con el fin de la guerra, la aviación comercial se separó de la militar y comenzó a expandirse. A partir de 1945, podemos notar una disminución en la cantidad de accidentes, pero un aumento en la cantidad de muertes por accidente. Esto tiene sentido considerando que los vuelos comerciales transportan significativamente más pasajeros que los vuelos militares.

Sin embargo, a partir de la década de 1990 hasta la actualidad, se observa un descenso tanto en la cantidad de accidentes como en el número de fatalidades. Esto se debe posiblemente a mejoras en seguridad, avances tecnológicos y una mayor capacitación en la industria de la aviación.

Podemos observar cómo una aeronave como la DOUGLAS DC-3 que es la que más número de accidentes tiene comenzó a operar después del estallido de la Segunda Guerra Mundial. Con el desarrollo de nuevas tecnologías y avances, parece haber quedado en desuso hacia 1980, justo cuando el de Havilland Canada DHC-6 Twin Otter 300 entra en acción. Si bien el de Havilland Canada DHC-6 Twin Otter 300 ha tenido un gran número de accidentes, está lejos de alcanzar los registros de la DOUGLAS DC-3. Aunque no disponemos de datos concretos sobre la cantidad de vuelos realizados por cada aeronave, podemos afirmar que la cantidad de accidentes de la DOUGLAS DC-3 es muy superior a cualquier otra, por lo tanto, no sería recomendable utilizar dicha aeronave en la actualidad.

<p align='center'>
<img src ="https://github.com/paupallares/PI_Analytics/blob/94e8c17365cf7ab8f4986d9489c64d5bbb275583/img/aeronaves.png" height=250>
<p>

En relación a los accidentes militares, estos son muy bajos en comparación con los accidentes de pasajeros, con una excepción que coincide con la Segunda Guerra Mundial, lo cual tiene mucho sentido histórico.

Observamos un pico extremadamente alto en el año 2001, el cual coincide con los acontecimientos del ataque a las Torres Gemelas en Estados Unidos, pero más allá de ese suceso en particular, las muertes en tierra o colaterales no son tan altas en comparación con las aereas.

En cuanto a la ubicación de los accidentes, se destaca que la ruta de Moscú, Rusia, ha tenido la mayor cantidad de accidentes, lo cual concuerda con los registros de los operadores. Entre ellos, la aerolínea rusa Aeroflot presenta el mayor número de accidentes y fatalidades. Esto respalda los registros históricos que indican que Aeroflot ha tenido cinco veces más accidentes que cualquier otra aerolínea. Es llamativo el contraste significativo entre Aeroflot y el resto de las aerolíneas, ya que sus fatalidades duplican incluso a las de las fuerzas armadas.

Basándonos en el análisis realizado, podemos sacar algunas **conclusiones** para este proyecto:

**`Reducción de accidentesy fatalidades:`**  El análisis revela una notable disminución en el número de accidentes de avión y fatalidades a lo largo del tiempo. A pesar del aumento en el número de vuelos y pasajeros la industria de la aviación ha logrado mejorar las medidas de seguridad y los protocolos, lo que ha resultado en una disminución en la frecuencia y gravedad de los incidentes.

**`Crecimiento exponencial de la industria:`** La cantidad de viajes desde 1908 se ha multiplicado a escalas gigantezcas lo que genera una industria que debe mantenerse en constante desarrollo y mejora. Los avances tecnológicos parecen haber sido un factor clave a la hora de reducir los accidentes y las fatalidades. 

<p align='center'>
<img src ="https://github.com/paupallares/PI_Analytics/blob/94e8c17365cf7ab8f4986d9489c64d5bbb275583/img/vuelos%20totales.png" height=250>
<p>


### Disclaimer
_Los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulan un entorno laboral, en el cual se trabajan diversas temáticas ajustadas a la realidad. No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.)._
  
<p align='center'>
<img src ="https://media.giphy.com/media/SA6qHijDp7Qn0KMAVP/giphy.gif" height=250>
<p>
