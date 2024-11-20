<h1 align="center"> EDA SOBRE COMPORTAMIENTO DEL INTERNET EN ARGENTINA DE 2014 A 2024 </h1>

<img width="1000" aling="center" alt="Captura de pantalla 2024-11-19 a la(s) 8 42 07 p  m" src="https://github.com/user-attachments/assets/65f75c84-1a49-4e06-b138-ecaa2abf7dba">


### Descripción :memo:
El proyecto a continuación es un EDA que evalua el comportamiento del internet en Argentina desde 2014 a 2024. Este proyecto se realiza con el fin de analizar cuales fueron los comportamientos del internet durante 2014 a 2024 y poder entender que factores pudieron influir en estos eventos, ademas de presentar de forma clara en que provincias hubo mas accesos.

<img width="1000" aling="center" alt="Captura de pantalla 2024-11-19 a la(s) 8 38 58 p  m" src="https://github.com/user-attachments/assets/48900855-6fd4-45d9-a69b-4fc17681fcc3">

Cuales fueron las tecnologías que mas se usaron, entre otros factores para poder llegar a conclusiones que nos permitan tomar decisiones a futuro para aumentar la presencia de la empresa en el mercado del internet. 

### Tecnologías usadas :computer:
- Python 3.11.9
- Matplotlib 3.9.2
- Numpy 2.1.2
- Pandas 2.2.3
- Plotly 5.24.1
- Seaborn 0.13.2


### Instalación :wrench:
**Pasos de instalación:**
1. Clonar el repositorio: `git clone https://github.com/MyriamRengifo/Proyecto02.git`

2. Crear un entorno virtual: `python -m venv venv`
3. Activar el entorno virtual:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Instalar las dependencias: `pip install -r requirements.txt`

### ¿Qué archivos encontraras dentro del repositorio? :page_facing_up:
- EDA FINAL.ipynb: En este archivo podrás encontrar todos los análisis hechos, junto con algunas conclusiones y recomendaciones.

- Requirements.txt: Contiene todas las librerias que necesitas para no tenga problemas al ejecutar el análisis.

- Internet.xlsx: Es donde se encuentra toda la data original.

### Metodología :chart_with_upwards_trend:

Se comienza cargando los datos al notebook y haciéndoles un pequeño ETL a cada uno de los dataframes con el fin de que puedan agruparse entre ellos por medio de sus columnas en común. 
Una vez la data ya se considera de calidad y se ha hecho la agrupación en un solo dataframe se comienza la búsqueda de valores atípicos y su significado a través de boxplots. Se calcula su media, mediana, desviación estándar y cuartiles. Se hace un gráfico de dispersión para observar mejor estos valores atípicos y poder obtener sus índices. Una vez determinamos nuestros datos a usar, se hacen distintos gráficos, entre esos:
-	`Gráficos de líneas:` Se usan para determinar el comportamiento de los accesos de las distintas provincias a lo largo de los años, el crecimiento de accesos durante el COVID 19, entre otros. 
-	`Gráficos de dispersión:` Se usan para ver valores atípicos, el comportamiento de los accesos por cada 100 hogares argentinos por año, entre otros. 
-	`Gráficos de barras:` Se usan para ver que tecnologías son más usadas por provincia y otros.

Todo con el fin de realizar análisis del comportamiento mostrado en cada gráfico y poder generar conclusiones. 

### Conclusiones 🗒️

Entre las conclusiones se encuentran las siguientes: 

  - El número de habitantes influye en el aumento de accesos, sin embargo, Capital Federal la cual es la segunda provincia mas poblada, no presenta un aumento significativo en los últimos años.
  - La provincias con mejor internet no necesariamente son las mas pobladas ni tampoco son las que tienen mas accesos.
  - Actualmente ADSL y Cable Modem son las tecnologías mas utilizadas, sin embargo, hay una oportunidad de negocio frente a la implementación de la fibra óptica.


### Autor ✏️
Myriam Rengifo
