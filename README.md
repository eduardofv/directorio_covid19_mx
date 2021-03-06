# Directorio de fuentes de datos, repositorios y visualizaciones sobre COVID-19 en México

## Repositorios de datos adaptados de fuentes oficiales

- El equipo de @guzmart captura los datos oficiales del reporte diario en [este repositorio](https://github.com/guzmart/covid19_mex)
- [Datos procesados de la fuente original](https://github.com/carranco-sga/Mexico-COVID-19) por @carranco-sga
- [Datos extraídos del mapa en formato de series de tiempo (csv)](https://github.com/eduardofv/covid) por @eduardofv (mantengo este directorio)
- [Herramienta para obtener datos recientes sobre la situación de COVID19 en México.](https://wallyqs.github.io/covid19mx/) y su [repositorio](https://github.com/wallyqs/covid19mx) por @wallysqs
- Series de tiempo en el [repositorio](https://github.com/mariorz/covid19-mx-time-series) de @mariorz
- [Proyecto en git para extraer los datos de los archivos pdf oficiales, hacerlos manejables y guardar un historico de manera automática](https://github.com/covidctdmx/covid_ctd_mx) de [@covidctdmx](https://twitter.com/covidctdmx)
- [Serendipia](https://serendipia.digital/2020/03/datos-abiertos-sobre-casos-de-coronavirus-covid-19-en-mexico/) almacena datos fuente y procesados
- [Covidmex.live/explore](https://covidmex.live/explore) procesan y almacenan los datos oficiles y permiten descargarlos en CSV, JSON y MySQL 
- [nataquinones/covid19_mexico](https://github.com/nataquinones/covid19_mexico) tiene almacenados los PDFs oficiales así como datos procesados y series de tiempo en TSV. También tiene un [resumen y visualizaciones](https://nataquinones.github.io/covid19_mexico/)
- [Eduardo Rojas](https://www.kaggle.com/lalish99/covid19-mx) tiene este análsis en Kaggle y comparte un [dataset](https://www.kaggle.com/lalish99/covid19-mx?rvi=1) con datos oficiales 
- [COVID-19 en México](https://www.covid19in.mx/) de [@mayrop](https://twitter.com/mayrop) cotiene visualizaciones y datos muy valiosos.

_Para agregar nuevos registros o hacer correcciones favor de abrir un [pull request](https://github.com/eduardofv/directorio_covid19_mx/pulls) o un [issue](https://github.com/eduardofv/directorio_covid19_mx/issues). [Repositorio](https://github.com/eduardofv/directorio_covid19_mx)_

## Visualizaciones y análisis

- [Twitter de @rafaelprietoc](https://twitter.com/rafaelprietoc) cin excelentes análisis
- [Covidatos de Eli Parra](https://covidatos.mx/), muy buena [hoja de cálculo](https://docs.google.com/spreadsheets/d/1ihdwd-YY5h_wCkaaKVK0P70gjhxxRlLuNLYPQeJwrq8/edit?usp=sharing)
- [covid19mexico.github.io](https://covid19mexico.github.io/) Herramientas númericas y visuales para seguir el desarrollo de la pandemia en México
- [mapacoronavirusmexico.com](https://mapacoronavirusmexico.com/) Mapa y dashboard de casos en México
- [https://covid19enmexico.com/](https://covid19enmexico.com/) Dashboard donde agregan datos publicados por órganos oficiales de los estados a lo largo del día, por lo que puede haber diferencias con los datos de Secretaría de Salud.
- [Covidmex.live](https://covidmex.live/) agregan los datos oficiales y en [Explore](https://covidmex.live/explore) permite filtrar los datos del comunicado diario
- [guzmanlev](https://sites.google.com/site/guzmanlev/covid19) Visualizaciones y mapas incluyendo Latinoamérica
- [mexicovid19.mx](http://mexicovid19.mx/index.html) de la Escuela de Gobierno y Transformación Pública del ITESM
- [Coronamex](https://coronamex.github.io/) tiene análisis distintos muy interesantes.
- [Proyecto.li](https://proyecto.li/) tiene análisis y visualizaciones basados en los datos publicados por los gobiernos estatales.

## Fuentes oficiales
 
- [Datos Abiertos - Dirección General de Epidemiología](https://www.gob.mx/salud/documentos/datos-abiertos-152127) Empezó a publicar lso datos desagregados de casos estudiados en formato abierto con diccionario de datos.
- [Comunicado Técnico Diario](https://www.gob.mx/salud/documentos/coronavirus-covid-19-comunicado-tecnico-diario-238449)
- [MODELO EPIDEMIOLÓGICO COVID-19 DEL GOBIERNO DE LA CIUDAD DE MÉXICO](https://modelo.covid19.cdmx.gob.mx/modelo-epidemico)
- [Sistema Nacional de Vigilancia Epidemiológica (sinave)](https://covid19.sinave.gob.mx/)
- [Mapa de Covid-19 en México](https://covid19.sinave.gob.mx/mapa.aspx)

## Otros recursos interesantes

- [Excelentes gráficas del Financial Times](https://www.ft.com/coronavirus-latest)
- [Covidtrend con la gráfica de trayectorias de Henry Reich y Aatish Bhatia](https://aatishb.com/covidtrends/)
- [BNO News](https://bnonews.com/index.php/2020/04/the-latest-coronavirus-cases/)
- [pypi.org/project/covidmx/](https://pypi.org/project/covidmx/) una librería de Python para acceder a los datos oficiales de @FedericoGarza
- [Centro de información geográfica de la UNAM sobre COVID-19 en México](https://covid19.ciga.unam.mx/)
- [Repositorio documental CONACYT sobre el Novel Coronavirus COVID-19](https://covid-19.conacyt.mx/jspui/) contiene artículos científicos, informes técnicos especializados y materiales de consulta. Ver el [comunicado del CONACYT](https://www.conacyt.gob.mx/index.php/comunicados/1261-com-154-2020)

## Otras fuentes reconocidas

- [Datos de Johns Hopkins](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)
- [CORD-19 COVID-19 Open Research Dataset](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)

# ¿Por qué es importante todo este trabajo?

Aunque parece que hay redundancia, ya que mucha gente está dedicando su tiempo a procesar las mismas fuentes oficiales, hemos visto que las inconsistencias que contienen, la dificultad de utilizarlas en los formatos publicados y el hecho de que cambien cada día hacen necesario corregirlas, transformarlas y crear archivos históricos para que puedan ser utilizadas por quien las requiera. Cada quien está resolviendo los mismos problemas pero de forma distinta, lo cual ayuda a tener una variedad de soluciones y un respaldo de información. Además, siendo un esfuerzo totalmente voluntario, no está de más disponer de varias fuentes en caso de que alguien no pueda continuar con su trabajo. Es por ello que agradecemos el esfuerzo y dedicación que tantas personas están poniendo en proyectos que buscan beneficiar a la comunidad.

