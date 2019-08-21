e---
# Proyectos 2019-1. Inteligencia Artificial. 

## Prof: Fabio Martínez, Ph.D

---

# Lista de Proyectos
1. [CheckYourZone: Un módelo predictivo de zonas con mayores delitos en Bucaramanga](#proy1)
2. [Detección de *Hate speech* en *Twitter*](#proy2)
3. [Conozca su estabilidad financiera](#proy3)
4. [Análisis de suicidios a nivel mundial y nacional](#proy4)
5. [VoiceHelp](#proy5)
6. [ArtSource](#proy6)
7. [Inteligencia artificial para el uso agricola](#proy7)
8. [Extreme climate even detection](#proy8)
9. [la línea 123 en Bogotá:Predicción de prioridades y prevención de falsas alarmas](#proy9)
---

## CheckYourZone: Un módelo predictivo de zonas con mayores delitos en Bucaramanga <a name="proy1"></a>

**Autores: Oscar Esneyder Sinuco, Juan José Arango, Jorge Perea**



<img src="/sources/check_banner.jpg" style="width:700px;">

**Objetivo: Construir un modelo predictivo para los delitos del municipio de Bucaramanga.**  

- Dataset: Cerca de 100k registros de denuncias desde el año 2009 hasta 2019 (Marzo) y 21 caracteristicas, entre las cuales están dia, mes, lalitud, longitud.
- Modelo: egresores basados en redes neuronales y Arboles de decisión


[(code)](https://gitlab.com/oscarsinuco/inteligencia); [(video)](https://drive.google.com/file/d/1mhFKXVev4RSSd4xfnBrXA47BfIj7DyzW/view); [(+info)](/sources/CHECK_YOUR_ZONE.pptx)

---

## Detección de *Hate speech* en *Twitter* <a name="proy2"></a>

**Autores: Valentina Goyeneche, Liceth Rozo**

<img src="https://github.com/vgoyenechec/Hatespeech-en-twitter/blob/master/imgs/banner.png" style="width:700px;">

**Objetivo:Clasificar tweets en ofensivo, hatespeech o ninguno, para filtrar el contenido que promueva el odio.**  

- Dataset: Un dataset internacional con 24783 tweets, 148.609 "características" y un dataset colombiano con 16044, 143023 características
- Modelo: RandomForest,, SVC, MultinomialNB, OneVsRest, CrossValidation, Kmeans, Red Neuronal.

[(code)](https://github.com/vgoyenechec/Hatespeech-en-twitter/); [(video)](https://www.youtube.com/watch?v=lDmo4KoRURw&feature=youtu.be); [(+info)](https://github.com/vgoyenechec/Hatespeech-en-twitter/blob/master/presentation/TwitterHSBalanceado.html)

---

## Conozca su estabilidad financiera <a name="proy3"></a>

**Autores: Jose Saul Vega, Diego Armando Villamizar**

<img src="https://github.com/JoseSaul23/ProyectoIA/blob/master/BANNER.png" style="width:700px;">

**Objetivo:**   Predicción de ingresos en adultos, para saber si se encuentran por encima o por debajo de la linea de estabilidad económica

- Dataset: mas de 30000 personas de todo el mundo
- Modelo:  RandomForestClassifier con 34 arboles y 16 de profundidad.
- Librerias: Seaborn (gráfica de relación entre características), Folium (Mapas), LabelEncoder (mapeo de datos) y StandardScaler (normalización de X) de Sklearn


[(code)](https://github.com/JoseSaul23/ProyectoIA); [(video)](https://www.youtube.com/watch?v=xGPHqA5KNMI&feature=youtu.be); [(+info)](https://github.com/JoseSaul23/ProyectoIA/blob/master/PRESENTACION.pptx)

---

## Análisis de suicidios a nivel mundial y nacional <a name="proy4"></a>

**Autores: Daniela Quintero, Martha Eliana Arenas, Carlos Daniel Barrera**


<img src="https://github.com/carlos-1299/Analisis-de-suicidios-a-nivel-mundial/blob/master/banner_mundial.jpeg" style="width:700px;">

**Objetivo:**  Analizar la crisis del suicidio que se vive a nivel mundial, estudiando las principales causas que lleva a que las personas se suiciden. 


- [Dataset](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016 ):  
- Modelo:  Clasificador RandomForest, ExtraTree; Algoritmo no supervisado: Kmeans

[(code)](https://github.com/carlos-1299/Analisis-de-suicidios-a-nivel-mundial); [(video)](https://www.youtube.com/watch?v=BZ65P8OL3Dg&feature=youtu.be); [(+info)]()


---

## Proyecto <VoiceHelp="proy5"></a>

**Autores: Diana Torres, Luis Jimenez, Maria Aparicio**

<img src="https://github.com/sofiat99/VoiceHelp/blob/master/banner1.png" style="width:900px;">

**Objetivo:  Ayudar a las personas con problemas auditivos y personas interesadas en aprender español.**  

- Dataset: 40 clases,48556 datos, cada uno con 100 características (mfcc)
- Modelo: GaussianNB, DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier, VotingClassifier,SGDClassifier, Birch,DBScan,KMeans

[(code)](https://github.com/sofiat99/VoiceHelp); [(video)](https://www.youtube.com/watch?v=ogIixp8eV8U&rel=0); [(+info)](https://github.com/sofiat99/VoiceHelp/blob/master/Voichelp.pdf)


---

## ArtSource <a name="proy6"></a>

**Autores: Juan David Niño, Maria Fernanda Navas, Juan Pablo Moreno **

<img src="https://github.com/fhum/ArtSource/blob/master/logo.png" style="width:700px;">

**Objetivo:**  

- Dataset: 79000 imagenes de arte, 27 estilos artísticos 
- Modelo: BoW, CNN, transferLearning

[(code)](https://github.com/fhum/ArtSource); [(video)]( https://youtu.be/1LOi7YGIMLA); [(+info)](https://github.com/fhum/ArtSource/blob/master/presentation.pdf)

---

## Inteligencia artificial para el uso agricola <a name="proy7"></a>

**Autores: Cristian Andrés Picón, Andrea Juliana Villalba**

<img src="https://github.com/capr99/AI_Agricultura/blob/master/images/BannerAI.png" style="width:700px;">

**Objetivo:Obtener una estimación de la producción de un cultivo en determinada zona para ayudar a los agricultores Colombianos.**  

- Dataset: Fueron utilizados 6 datasets con datos superiores a los 3000 en varios casos: ['Cafe', 'Maiz', 'Tomate', 'Soya', 'Cacao', 'Aguacate']
- Modelo: Decision Tree Regressor y Random Forest Regressor para la estimación de la producción, Kmeans y DBScan para el analisis de los datos

[(code)](https://github.com/capr99/AI_Agricultura); [(video)](https://www.youtube.com/embed/rraRTj8XcPE); [(+info)](https://github.com/capr99/AI_Agricultura/blob/master/Pv2Slides.ipynb)

---

## Extreme climate even detection <a name="proy8"></a>

**Autores: Maximiliano Garavito, Maria Daniela Lizarazo**

<img src="https://github.com/mdlizarazo/IA-Project/blob/master/banner.png" style="width:700px;">

**Objetivo:Detectar eventos climaticos extremos.**  

- Dataset:  para cada variable existen 3 dimensiones: lat: 336, lon: 276, time: 690). Se utilizaron 2 variables, y al final se extrajeron 4 features.

- Modelo: Algoritmo KDE, Logistic Regressor, Estandarizacion, cross validation.

[(code)](https://github.com/mdlizarazo/IA-Project); [(video)](/sources/2162094/VideoProyectoIA.wmv); [(+info)](/sources/2162094/DetecciondeEventosSlide.ppt)

---

## La línea 123 en Bogotá:Predicción de prioridades y prevención de falsas alarmas <a name="proy9"></a>

**Autores: **

<img src="https://github.com/omarsan1/ProyectoInteligencia/blob/master/BannerProyect.jpeg" style="width:700px;">

**Objetivo: Predecir falsas alarmas y prioridades en las llamadas según los datos proporcionados en las llamadas a la línea 123.**  

- Dataset: Más de 113000 registros de llamadas con 8 características como localidad, edad, género, tipo de incidente, entre otras. Tomado de Datos Abiertos Colombia (datos.gov.co)[link](https://www.datos.gov.co/dataset/Llamadas-de-Urgencias-y-Emergencias-que-ingresan-a/r6vd-czd2)
- Modelo: Clasificadores Gaussian, Decision Tree, Random Forest, KNN, Deep neuronal network.



[(code)](https://github.com/omarsan1/ProyectoInteligencia/); [(video)](https://drive.google.com/file/d/1LFs7JoNDDfAilfKqjJNQq8L1DZ3ikENI/view); [(+info)](https://github.com/omarsan1/ProyectoInteligencia/blob/master/An%C3%A1lisis%20de%20llamadas%20a%20la%20l%C3%ADnea%20123.pptx)



---

## Proyecto <a name="proy7"></a>

**Autores: a**

<img src="https://i.imgur.com/ueLN6rk.jpg" style="width:700px;">

**Objetivo:**  

- Dataset: 
- Modelo: 

[(code)](); [(video)](); [(+info)]()

---
