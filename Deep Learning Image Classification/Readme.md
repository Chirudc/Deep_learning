# Deep Learning for Image Classification: CNNs and Transfer Learning
This project focuses on image classification using Convolutional Neural Networks (CNNs) and transfer learning. The first phase involves building a CNN model to classify images of cats and dogs using the Cats-and-Dogs 
dataset from Kaggle. The workflow includes dataset exploration, preprocessing, and model development with different CNN architectures, including configurations with 1, 2, and 3 convolutional blocks. The models are trained
and evaluated to compare performance based on accuracy and loss metrics. The goal is to understand how increasing model depth impacts classification results and to analyze the trade-offs between complexity and accuracy. 
The dataset can be downloaded from Kaggle or loaded directly using TensorFlow Datasets for seamless integration into deep learning pipelines.

The second phase introduces transfer learning and fine-tuning using a pretrained MobileNet V2 model. Initially, the lower layers of the model are frozen to leverage pretrained feature extraction, followed by fine-tuning 
the top layers to improve performance on the specific dataset. The results from both approaches—custom CNN and transfer learning—are analyzed to determine the most effective strategy for image classification. 
The project demonstrates the advantages of deep learning architectures and transfer learning in reducing training time while achieving high classification accuracy.
