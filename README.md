## COVID-19 Detection from Chest X-Ray Images                                      

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detecção de COVID-19  a partir de imagens de raios X de tórax utlizando uma Deep Convolutional Neural Network otimizada.
</pre>

#### Code
<pre>
GitHub Link          : <a href=https://github.com/toniesteves/covid19-chest-x-ray-detection>COVID-19 Detection from Chest X-Ray Images </a>
Linkedin             : <a href=https://www.linkedin.com/in/toniesteves/>Antonio Esteves</a>
</pre>

#### Datasets
<pre>
Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
                 : <a href=https://data.mendeley.com/datasets/rscbjbr9sj/2>Chest X-Ray Images (Pneumonia) Dataset (Original Dataset - No Labeled)</a>
Dataset Name     : COVID-19 image data collection
Dataset Link     : <a href=https://github.com/ieee8023/covid-chestxray-dataset>COVID-19 image data collection (Original Dataset)</a>

</pre>

<pre>
<b>Detalhes do Dataset</b>
Nome do Dataset              : Imagens de raio X de toráx (COVID-19)
Número de Classes            : 2
Número/Tamanho das imagens   : Total      : 178 (98.8 Megabyte (MB))
                               Treino     : 76  (51.7 Megabyte (MB))
                               Validação  : 30  (9.1  Megabyte (MB))
                               Teste      : 72  (38.4 Megabyte (MB))

<b>Parâmetros do Modelo</b>
Machine Learning Library     : Keras
Base Model                   : Custom Deep Convolutional Neural Network
Otimizadores                 : Adam
Função de Perda              : categorical_crossentropy

<b>Deep Convolutional Neural Network Otimizada: </b>
<b>Parâmetros de Treino</b>
Batch Size                   : 64
Número of Épocas             : 100
Tempo de Treino              : 40 Minutes

<b>Saída (Prediction/ Recognition / Classification Metrics)</b>
<b>Teste</b>
F1-Score                     : 84.79%
Accuracy                     : 83.33%
Loss                         : 0.07
Precision                    : 82%
Recall (COVID-19)            : 86.11% (Para as classes positivas)
Specificity                  : 80.56%
</pre>

##### Sample Output:
<kbd>
<img src=https://github.com/toniesteves/covid19-chest-x-ray-detection/blob/master/data/output/figures/sample.png>
</kbd>

<kbd>
<a href=https://github.com/toniesteves/covid19-chest-x-ray-detection/blob/master/data/output/figures/result.png>See More Images</a>
</kbd>

##### Confusion Matrix:
<kbd>
<img src=https://github.com/toniesteves/covid19-chest-x-ray-detection/blob/master/data/output/figures/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>

##### ROC Curve:
<kbd>
<img src=https://github.com/toniesteves/covid19-chest-x-ray-detection/blob/master/data/output/figures/ROC.png alt="ROC Curve" width=800px height=600px>
</kbd>


#### Tools / Libraries
<pre>
Languages               : Python
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Duration                : March 2020 - Current
Current Version         : v1.0.0.0
Last Update             : 23.03.2020
</pre>
