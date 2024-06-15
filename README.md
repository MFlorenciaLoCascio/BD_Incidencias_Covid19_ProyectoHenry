<center>
<h1> 🌐Estudio de Investigación para la Expansión de Laboratorios y Centros de Vacunación - Farmaceutica Biogenesys 🔬 </h1>
</center>

## 🎯Objetivo: 

<p> Identificar ubicaciones estratégicas óptimas para la expansión de laboratorios y centros de vacunación a la Farmacéutica Biogenesys en Argentina, Chile, Colombia, México, Perú y Brasil. Basado en la incidencia de COVID-19. </p>

## 💻**Descarga e Instalación de Programas para abrir los archivos del proyecto**  

1. Visual Studio Code:
2. Python
3. Librerias: NumPy, Pandas, Matplotlib, Seaborn, Geopandas
4. Power Bi Desktop

__Debe descargarse los siguientes arhivos para poder ejecutar los scripts en pyhton:__
  
_Dataset original_: [data_latinoamerica](https://drive.google.com/file/d/18FGvT2x1nqA5TQ22P5FyJ5eLXlHprqzj/view)
_Dataset normalizado_: [DatosFinalesFiltradoNuevo](https://github.com/MFlorenciaLoCascio/BD_Incidencias_Covid19_ProyectoHenry/blob/main/DatosFinalesFiltradoNuevo.csv)

## 🗂️ Desarrollo del Proyecto

### 👉 Python / Jupyter Notebook

[**Archivo Scripts de Python/JN**](https://github.com/MFlorenciaLoCascio/BD_Incidencias_Covid19_ProyectoHenry/blob/main/Python_Biogenesys_Lo_Cascio_Maria_Florencia.ipynb)

### 1. Carga y transformación de datos 

+ Extracción de base de datos `data_latinoamerica`
  
+ Importar librerias dentro Jupyter Notebook

```
import numpy as np
import pandas as pd
```
  
+ Carga del dataset original *data_latinoamerica*
`data = pd.read_csv('data_latinoamerica.csv')`

+ Exploración de datos: para obtener información inicial
  + visualizar la cantidad de registros y columnas
  + visualizar la calidad de los datos
  + verificar el tipo de datos en el conjunto de datos
  + verificar cuantos registros nulos hay

+ Limpieza y Nueva Exploración de datos
  + filtrar por países seleccionados de LATAM
  + modificar el tipo de dato de fecha
  + filtrar por ‘location key’ con los valores que tengan datos (ya que no pueden haber registros nulos asociados, ya que esta es mi PK.
  + filtre por fechas mayores a 01/01/2021
  + verifiqué columnas con datos nulos
  + quité columnas no relevantes para mi análisis
  + los valores negativos los lleve a 0
  + columnasconvalores nulos los lleve a 0
  + cambié un valor atípico con el valor más cercano a esa fecha

+ Guardadodearchivo: `DatosFinalesFiltradoNuevo`

### 2. Análisis Exploratorio y Visualización

+ Importarlibrerías:

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

+ Cargadeldataset: `DatosFinalesFiltradoNuevo.csv`
  
+ Visualizaciones de datos con matplotlib y seaborn

### 3. EDA con Numpy y Pandas

+ Importarlibrerías:

```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import geopandas as gpd
```

+ Carga del dataset:  `DatosFinalesFiltradoNuevo.csv`
  
+ Análisis exploratorio detallado utilizando técnicas avanzadas con Numpy y Pandas

### 👉 *Power Bi*

Aquí puede ingresar a ver el [Dashboard_Biogenesys](https://github.com/MFlorenciaLoCascio/BD_Incidencias_Covid19_ProyectoHenry/blob/main/Dashboard_Biogenesys_Lo_Cascio_Maria_Florencia.pbix)

1. Importar archivo `DatosFinalesFiltradoNuevo`
2. Crear tabla calendario
3. Desarrollar medidas DAX
4. Diseñar un dashboard interactivo aplicando storytelling
5. Obtener insights significativos para determinar la ubicación óptima de expansión de laboratorios y centros de vacunación para la farmaceutica

## 📊 EDA e Insights Generales:

### 1- Chile:

- __Políticas de Vacunación:__ Alta cobertura de vacunación (3.54 dosis por persona).
- __Inversión en Salud:__ Alta proporción de médicos y enfermeras por habitante.
- __Densidad y Habitantes:__ Población urbana bien atendida.
- __Problemas Sociales y Económicos:__ Menor prevalencia de diabetes y fumadores, alta estabilidad económica.

### 2- México:

- __Políticas de Vacunación:__ Moderada cobertura de vacunación (1.89 dosis por persona), con potencial de mejora.
- __Inversión en Salud:__ Necesita mejorar la proporción de médicos; buena cantidad de enfermeras.
- __Densidad y Habitantes:__ Gran población urbana facilita la logística.
- __Problemas Sociales y Económicos:__ Alta prevalencia de diabetes y fumadores; economía robusta (PBI per cápita de 9.9 mil USD).

### 3- Brasil:

- __Políticas de Vacunación:__ Baja cobertura de vacunación (1.64 dosis por persona).
- __Inversión en Salud:__ Buena cantidad de médicos, pero insuficiente número de enfermeras.
- __Densidad y habitantes:__ Gran población urbana.
- __Problemas Sociales y Económicos:__ Problemas sociales significativos.

### 4- Argentina:

- __Políticas de Vacunación:__ Moderada cobertura de vacunación (2.43 dosis por persona).
- __Inversión en Salud:__ Buena proporción de médicos y enfermeras.
- __Densidad y Habitantes:__ Población urbana considerable.
- __Problemas Sociales y Económicos:__ Buena economía, pero con buen potencial de crecimiento en salud.

### 5-Perú:

- __Políticas de Vacunación:__ Moderada cobertura de vacunación (2.85 dosis por persona).
- __Inversión en Salud:__ Necesita más inversión en personal sanitario.
- __Densidad y habitantes:__ Población mixta urbana y rural.
- __Problemas Sociales y Económicos:__ Desafíos económicos y sociales significativos.

### 6- Colombia:

- __Políticas de Vacunación:__ Baja cobertura de vacunación (1.72 dosis por persona).
- __Inversión en Salud:__ Baja proporción de médicos y enfermeras.
- __Densidad y habitantes:__ Población urbana creciente.
- __Problemas Sociales y Económicos:__ Desafíos económicos y sociales

## 📈 Conclusiones sobre el Objetivo:

<p>Considerando aspectos críticos como la demanda de vacunas, infraestructura sanitaria, factores socioeconómicos y factores de riesgo, México es el país adecuado para que Biogenesys pueda establecer una resencia sólida para la expansión de laboratorios y centros de vacunación, especialmente en áreas urbanas densamente pobladas.</p>
 
<p>Requiere inversiones en campañas de vacunación y mejoras en infraestructura médica para combatir el COVID-19 o futuras enfermedades que aseguran una demanda constante de servicios de salud.</p>

## 💉 Insights sobre la oportunidad de *Expansión en México*:

<p>1. __Factores Socioeconómicos:__ Con un GDP per cápita de 9.900 USD, México tiene una economía suficientemente fuerte para soportar inversiones en infraestructura sanitaria. Permitiendo que una mayor proporción de la población tenga acceso a servicios de salud privados.</p>
   
</p>3. __Infraestructura Sanitaria:__ Tiene una proporción intermedia de médicos y enfermeras por cada 1,000 habitantes. Esto indica que hay infraestructura sanitaria disponible, pero también la __necesidad de reforzar estos recursos para mejorar la capacidad de respuesta ante emergencias. </p>
   
</p>5. __Demanda de Vacunas:__ Promedio de 1.89 dosis administradas por persona, lo cual sugiere una demanda moderada a alta de vacunas. </p>
   
</p>7. __Mortalidad:__ Tiene un alto ratio de mortalidad y puede requerir intervenciones adicionales teniendo un impacto significativo. </p>
   
</p>9. __Factores De Riesgo:__ México tiene una prevalencia significativa de diabetes y fumadores. Estos factores de riesgo aumentan la demanda de servicios de salud especializados, incluidos los laboratorios y centros de vacunación.</p>

</p>11. __Densidad y Habitantes:__ Gran población urbana facilita la logística de distribución eficiente de suministros médicos y vacunas.</p>

## 🌍 Recomendaciones para la *Expansión en México*

1. **Incrementar Cobertura de Vacunación:**
- Implementar campañas de concientización para aumentar la aceptación de vacunas.
- Establecer más centros de vacunación en áreas urbanas densamente pobladas.

3. **Mejorar Infraestructura Sanitaria:**
- Aumentar la cantidad de médicos mediante programas de formación y contratación.
- Mejorar la infraestructura de los centros de salud existentes.

5. **Enfocar en Problemas de Salud Crónica:**
- Desarrollar programas específicos para tratar y prevenir diabetes y reducir el tabaquismo.
- Colaborar con organizaciones locales para implementar programas de salud comunitaria.

6. **Optimizar la Logística de Distribución:**
- Utilizar la alta densidad urbana facilitando la distribución eficiente de suministros
 médicos y vacunas.

## 📝 Informe: 
Aquí puede encontrar información más a detalle sobre el proyecto:

[Informe Expansión Biogenesys](https://github.com/MFlorenciaLoCascio/BD_Incidencias_Covid19_ProyectoHenry/blob/main/Informe_Biogenesys_Lo_Cascio_Maria_Florencia.pdf)

## ⚙️ Herramientas utilizadas:

+ Visual Studio Code
+ Python
+ Jupyter Notebook
+ NumPy
+ Pandas
+ Matplotlib
+ Seaborn
+ Power Bi
+ Power Query
+ DAX
+ Figma
+ Canva
+ Power Point
+ G. Docs




