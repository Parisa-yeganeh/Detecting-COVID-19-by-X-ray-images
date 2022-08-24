# Detecting-COVID-19-by-X-ray-images

<h3>Disclaimer</h3>
</strong></p>This repo is just for training and educational purposes. It is not meant to be a reliable, highly accurate COVID-19 diagnosis system, nor has it been professionally or academically vetted. The dataset has been gathered by Adrian Rosebrock on March 16, 2020 pyimagesearch.com and it is available at pyimagesearch.com</strong></p>

<h3>COVID-19 patient X-ray image dataset</h3>

</strong></p>In this repo we are going to detect COVID19 from X-ray images. The dataset is publicly available at <a href="https://pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/" target="_blank" rel="noopener noreferrer">pyimagesearch.com.</a> The COVID-19 X-ray image dataset we’ll be using for this code was created by Dr. Joseph Cohen. He collected X-ray images of COVID-19 cases and published them in the <a href="https://github.com/ieee8023/covid-chestxray-dataset/" target="_blank" rel="noopener noreferrer">following GitHub repo.</a> We'll be using 25 infected lung X-ray from that source that Adrian Rosebrock has done some sort of steps in order to create the COVID-19 X-ray image dataset. As the healthy lung X-ray samples, Adrian Rosebrock has sampled 25 X-ray images from healthy patients from <a href="https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/" target="_blank" rel="noopener noreferrer">Kaggle’s Chest X-Ray Images (Pneumonia) dataset.</a></p>

<h4>Description of the project</h4>

</strong></p> 

<figure id="attachment_14049" aria-describedby="caption-attachment-14049" style="width: 700px" class="wp-caption aligncenter"><a href="https://pyimagesearch.com/wp-content/uploads/2020/03/covid19_keras_dataset.png"><img class="size-full wp-image-14049" src="https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?lossy=1&strip=1&webp=1" alt="" width="700" height="381" srcset="https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?size=126x69&amp;lossy=1&amp;strip=1&amp;webp=1 126w, https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset-300x163.png?lossy=1&amp;strip=1&amp;webp=1 300w, https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?size=378x206&amp;lossy=1&amp;strip=1&amp;webp=1 378w, https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?size=504x274&amp;lossy=1&amp;strip=1&amp;webp=1 504w, https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?size=630x343&amp;lossy=1&amp;strip=1&amp;webp=1 630w, https://929687.smushcdn.com/2633864/wp-content/uploads/2020/03/covid19_keras_dataset.png?lossy=1&amp;strip=1&amp;webp=1 700w" sizes="(max-width: 630px) 100vw, 630px" /></noscript></a><figcaption id="caption-attachment-14049" class="wp-caption-text"><strong></p>Figure 1:</strong> CoronaVirus (COVID-19) chest X-ray image data. On the left we have positive X-ray images, whereas on the right we have negative samples. These images are used to extraxt features and train a machine learning model with TensorFlow and Keras to automatically predict whether a patient has COVID-19.</figcaption></figure>


  
  
  
  






