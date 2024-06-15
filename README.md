# 🌐 **Expansión de Laboratorios y Centros de Vacunación - Farmaceutica Biogenesys** 

## 🎯Objetivo: 
Identificar ubicaciones estratégicas óptimas para la expansión de laboratorios y centros de vacunación a la Farmacéutica Biogenesys en Argentina, Chile, Colombia, México, Perú y Brasil. Basado en la incidencia de COVID-19.

## 💻**Descarga e Instalación de Programas para abrir los archivos del proyecto**  

1. Visual Studio Code:
2. Python
3. Librerias: NumPy, Pandas, Matplotlib, Seaborn, Geopandas
4. Power Bi Desktop

- Debe descargarse los siguientes arhivos para poder ejecutar los scripts en pyhton:
_Dataset original_: [data_latinoamerica](https://drive.google.com/file/d/18FGvT2x1nqA5TQ22P5FyJ5eLXlHprqzj/view)
_Dataset normalizado_: [DatosFinalesFiltradoNuevo](https://github.com/MFlorenciaLoCascio/BD_Incidencias_Covid19_ProyectoHenry/blob/main/DatosFinalesFiltradoNuevo.csv)

## 🗂️ Desarrollo del Proyecto

### Carga y transformación de datos

+ Extracción de base de datos _Dataset original_
  
+ Importar librerias dentro Jupyter Notebook
  + Numpy y Pandas
 
+ Carga del dataset original

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

+ Guardadodearchivo: .CSV filtrado

### Análisis Exploratorio y Visualización

+ Importarlibrerías:
  + numpy,pandas,matplotlib y seaborn
  + Cargadeldataset: en formato .CSV
  + Visualizaciones de datos con matplotlib y seaborn

### EDA con Numpy y Pandas

+ Importarlibrerías:
  + numpy, pandas, matplotlib, seaborn, geopandas

+ Carga del dataset: en formato .CSV
  
+ Análisis exploratorio detallado utilizando técnicas avanzadas con Numpy y Pandas


## 📊 EDA e Insights:

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

