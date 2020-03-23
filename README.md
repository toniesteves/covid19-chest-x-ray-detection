## COVID-19 Detection from Chest X-Ray Images                                      

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, ImageNet, Inception
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Description
<pre>
1. Detecção de Pneumonia pediátrica a partir de imagens de raios X de tórax utlizando uma Deep Convolutional Neural Network otimizada e retreinando um modelo pré-treinado  “InceptionV3” com 5856 imagens de raios X (1.15GB).
2. For retraining removed output layers, freezed first few layers and fine-tuned model for two new label classes (Pneumonia and Normal).
3. With Custom Deep Convolutional Neural Network attained testing accuracy 89.14% and loss 0.31.
</pre>

#### Code
<pre>
GitHub Link          : <a href=https://github.com/toniesteves/Detection-of-Pneumonia-from-Chest-X-Ray-Images>Detection of Pneumonia from Chest X-Ray Images(GitHub)</a>
Statistical Analysis : <a href=https://github.com/toniesteves/chest-x-ray-pneumonia-inference>Pneumonia from Chest X-Ray Images Analysis inference(GitHub)</a>
Linkedin             : <a href=https://www.linkedin.com/in/toniesteves/>Antonio Esteves</a>
</pre>

#### Dataset
<pre>
Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
                 : <a href=https://data.mendeley.com/datasets/rscbjbr9sj/2>Chest X-Ray Images (Pneumonia) Dataset (Original Dataset - No Labeled)</a>
Original Paper   : <a href=https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5>Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning</a>
                   (Daniel S. Kermany, Michael Goldbaum, Wenjia Cai, M. Anthony Lewis, Huimin Xia, Kang Zhang)
                   https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
</pre>

<pre>
<b>Detalhes do Dataset</b>
Nome do Dataset              : Imagens de raio X de toráx (Pneumonia)
Número de Classes            : 2
Número/Tamanho das imagens   : Total      : 5856 (1.15 Gigabyte (GB))
                               Treino     : 5216 (1.07 Gigabyte (GB))
                               Validação  : 320  (42.8 Megabyte (MB))
                               Teste      : 320  (35.4 Megabyte (MB))

<b>Parâmetros do Modelo</b>
Machine Learning Library     : Keras
Base Model                   : InceptionV3 && Custom Deep Convolutional Neural Network
Otimizadores                 : Adam
Função de Perda              : categorical_crossentropy

<b>Deep Convolutional Neural Network Otimizada: </b>
<b>Parâmetros de Treino</b>
Batch Size                   : 64
Número of Épocas             : 100
Tempo de Treino              : 1 Hours

<b>Saída (Prediction/ Recognition / Classification Metrics)</b>
<b>Teste</b>
F1-Score                     : 92.79%
Accuracy                     : 90.71%
Loss                         : 0.25
Precision                    : 90.10%
Recall (Pneumonia)           : 95.64% (Para as classes positivas)
<!--Specificity             : -->
</pre>

##### Sample Output:
<kbd>
<img src=https://github.com/toniesteves/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning/blob/master/demo/sample/sample.png>
</kbd>

<kbd>
<a href=https://github.com/toniesteves/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning/blob/master/demo/images/result.png>See More Images</a>
</kbd>

##### Confusion Matrix:
<kbd>
<img src=https://github.com/toniesteves/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning/blob/master/demo/report/CM.png alt="Confusion Matrix" width=800px height=600px>
</kbd>

##### ROC Curve:
<kbd>
<img src=https://github.com/toniesteves/Pneumonia-Detection-from-Chest-X-Ray-Images-with-Deep-Learning/blob/master/demo/report/ROC.png alt="ROC Curve" width=800px height=600px>
</kbd>


#### Tools / Libraries
<pre>
Languages               : Python
Libraries               : Keras, TensorFlow, Inception, ImageNet
</pre>

#### Dates
<pre>
Duration                : October 2019 - Current
Current Version         : v1.0.0.5
Last Update             : 29.06.2019
</pre>
