### This section of repository contains classification of dog breed using deep learning and transfer learning.

Tools used in this porject are as follows:-

  - Google colab (For GPU use)
  - TensorFlow 2.3.0
  - TensorFLow Keras (Modelling)
  - TensorFlowHub 0.9.0 (For transfer learning)
  - Matplotlib (For visualization)
  - Numpy
  - Scikit-learn (For data split)
  - Pandas
  
  
Information about data: This data has been obtained from kaggle competition. We have over 10,000 images of dogs with label(Train-set) and 10,000 images of dogs without labels(Test-set).We have 120 unique breeds of dogs in this dataset. A single breed has average 82 images.
  
Images are converted into Tensors and then into batches to be able to feed into our deep learning model.

Deep learning model used here is MobileNetV2 from TensorFLowHub.


