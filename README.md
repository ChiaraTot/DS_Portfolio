# DS_Portfolio Chiara Totaro
## Análisis Exploratorio de Datos (EDA) - Dataset Big Startups

### Contexto
Realizar un análisis exploratorio de datos sobre el dataset "Big Startups",
para entender las características clave, tendencias y patrones en los datos relacionados con grandes startups creadas hasta 2015. 

[:se ha realizado slicing de las startup creadas antes del 1980] para una mejor comparacion con contextos historicos/economicos mas similares.

### Objetivo
 - Identificar patrones, tendencias y factores clave que puedan guiar a entender las claves del exito o fracaso de una startup.
 - Generar insights que permitan un entendimiento profundo del comportamiento de las startups.
 - Proporcionar una base para futuros estudios y aplicaciones, como predicciones de éxito, identificación de factores clave y toma de decisiones.

NOTA IMPORTANTE : 
- considerarè como Exitosas las startups que han conseguido salir a bolsa(IPO) o hayan sido adquiridas (adquired) - status EXIT
- se consideran como fracaso la startups que hayan cerrado (closed) - status FAIL
- las startup que siguen operativas tambien se consideran exitosas, aunque sobre estas se podrìa inferir con modelo de ML basados sobre resultados que pueda dar este mismo analisis.

#### Preguntas:
 - ¿Que % de startups fracasa?
 - ¿Cuál es la distribución de las startups por sector? y por pais?
 - ¿Existe una relación entre el sector donde opera la startup y el exito?
 - ¿Existe una relación entre el pais/region donde ha sido creada la startup y el exito?
 - ¿Existe una relación entre el total de financiamiento recibido y el exito
 - ¿Hay diferencias significativas entre startups de diferentes regiones?


### Enfoque

Etapas clave del proyecto:
- Obtencion y importacion de los datos desde la pagina de datos kaggle, obtenido desde la plataforma Crunchbase
- Comprensión del Dataset y de sus variables, inspeccionando la dimension, tipos de datos y realizando Análisis de Calidad de Datos:
  - Analisis missing y transformacion de datos para que sean mas manejables 

- Análisis Descriptivo y Visual de variables Categoricas y Numericas:
 - Univariante : tendencias centrales y desviaciones
  - Distribuciones de variables categóricas y numéricas.
 - Bivariante : descubrir relacciones entre variables
 - Multivariante : donde era necesario profundizar mas 


### Conclusiones:

Se identificaron patrones claves: 
El exito/fracaso de una startup està relacionado con:
 - Financiacion: Las startups que reciben mas financiacion tiene mas probabilidad de exito, es decir de salir a bolsa (IPO: Initial Public Offering - Oferta pública de acciones) o ser adquiridos por privados
 - Country:
  - En USA, se concentra la mayor cantidad de empresas tanto exitosas como fallidas, lo que refleja un ecosistema empresarial grande y competitivo.
  - EU y RDM muestran menor intensidad en ambos gráficos, sugiriendo menor participación en general o más cautela en sectores riesgosos.
 - Sector: 
   - Sectores tecnológicos (como Software, Curated Web, y Advertising) tienen alta actividad empresarial pero también riesgos asociados.
   - Sectores como Biotechnology parecen ser más seguros y orientados al éxito, especialmente en USA.

#### Documentación:

En el notebook Memoria hay un registro de todos los pasos y descubrimientos realizados durante el análisis.

#### Tecnologías Utilizadas

Lenguaje de programación: Python
Bibliotecas principales: Pandas, NumPy, Matplotlib, Seaborn
Entorno de desarrollo: Jupyter Notebook / Visual Studio Code

