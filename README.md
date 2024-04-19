### Una tienda online de moda, con presencia en todo Brasil, necesita impulsar su rendimiento utilizando sus datos de manera estratégica. Como científico de datos, has sido convocado para analizar estos datos y ofrecer insights que guíen sus decisiones y respondan a las siguientes preguntas clave:

## **Preguntas**
 🚀 1. ¿Cual es el Top 5 productos más vendidos históricamente?
 
 🚀 2. ¿Cual es la evolución histórica de las ingresos netos?
 
 🚀 3. ¿Cuáles son los ingresos netos por vendedor por año?
 
 🚀 4. ¿Cuáles son las ciudades que proporcionan mayores ingresos netos?
 
 🚀 5. ¿Existe otro insight que puedas proporcionar?

### Importar e instalar librerias

#### Importa la librería de cálculos
  import numpy as np
#### Importa la librería para manipular la base de datos
  import pandas as pd
#### Instalar una librería en un entorno de Jupyter
  !pip install matplotlib
#### Importa la librería de visualización de datos
  import matplotlib.pyplot as plt
#### Importa la librería de visualización más detallada
  import seaborn as sns

#### Importar archivos desdes GitHub
url = "https://raw.githubusercontent.com/Karen-Aguilar/5_Project_Data_science/main/itens_pedidos.csv"

df = pd.read_csv(url)

####Visualizacion rapida de datos.

df.head()

![image](https://github.com/Karen-Aguilar/5_Project_Data_science/assets/151496907/22686f66-e185-4614-a888-78cf39cbfa88)


url = "https://raw.githubusercontent.com/Karen-Aguilar/5_Project_Data_science/main/pedidos.csv"

df = pd.read_csv(url)

####Visualizacion rapida de datos.

df.head()

![image](https://github.com/Karen-Aguilar/5_Project_Data_science/assets/151496907/36b603b2-176f-4e02-b5ed-ac07708ba749)


url = "https://raw.githubusercontent.com/Karen-Aguilar/5_Project_Data_science/main/productos.csv"

df = pd.read_csv(url)

####Visualizacion rapida de datos.

df.head()

![image](https://github.com/Karen-Aguilar/5_Project_Data_science/assets/151496907/cbb3dc1d-2c8a-47c8-85af-f8a1b9986a8c)
