# classification-of-plant-diseases


## Motivación y dataset

La motivación es crear un clasificador para enfermedades de plantas con herramientas de computer vision/ inteligencia artificial. Para entrenar el modelo se utilizará el dataset open source de PlantVillage (https://plantvillage.psu.edu/). PlantVillage es una plataforma, desarrollada en Penn State University que pone a disposición contenido libre sobre la salud de los cultivos. La idea de esta plataforma es democratizar el acceso a la información para la producción de alimentos en zonas carenciadas, principalmente en el continente Africano.

<p align="center">
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/PlantVillageLogo.png?raw=true" alt="grafico_1"/>
</p>

<p align="center">
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/plant_village_pic.jpg?raw=true" alt="grafico_2"/>
</p>

El dataset provisto por PlantVillage consta de 54303 imágenes de hojas sanas y no saludables divididas en 38 categorías por especie y enfermedad. El artículo original puede encontrarse en https://arxiv.org/pdf/1511.08060.pdf, realizado por David. P. Hughes, Marcel Salathe [[1]](#1). 


<p align="center">
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/plant_1.png?raw=true" alt="plant_1"/>
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/plant_2.png?raw=true" alt="plant_2"/>
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/plant_3.png?raw=true" alt="plant_3"/>

</p>

Distribución del dataset por clase,

<p align="center">
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/plants_distribution.png?raw=true" alt="grafico_2"/>
</p>


Distribución del dataset por tipo de planta, 

<p align="center">
  <img src="https://github.com/Adrok24/classification-of-plant-diseases/blob/main/images/piechart_type.png?raw=true" alt="grafico_3"/>
</p>

Un análisis estadístico del dataset puede ser consultado en la siguiente notebook: [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/Estadistica.ipynb)

## Modelos entrenados para la clasificación del dataset

### Modelos simple output
* CNN Custom [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/simple_output_custom.ipynb)

* ResNet50 [Notebook]

* ResNet101V2 [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/simple_output_resnet101.ipynb)

* VGG16 [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/simple_output_VGG16.ipynb)


### Modelos multi output

* Modelo multi output 1 [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/multi_output_model_1.ipynb)

* Modelo multi output 2 [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/multi_output_model_2.ipynb)

* Modelo multi output con ResNet [Notebook](https://github.com/Adrok24/classification-of-plant-diseases/blob/first_version/multi_output_resNet.ipynb)


* Otras pruebas pueden encontrarse en la [carpeta](https://github.com/Adrok24/classification-of-plant-diseases/tree/first_version/Otras%20pruebas/) 





<a id="1">[1]</a> An open access repository of images on plant health to enable the development of mobile disease diagnostics, David. P. Hughes and Marcel Salathe, 2016.


