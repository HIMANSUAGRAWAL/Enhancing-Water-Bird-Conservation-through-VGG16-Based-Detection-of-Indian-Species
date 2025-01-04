
# Indian Waterbird Identification using Deep Learning (VGG-16)

This project focuses on the identification of Indian waterbird species using deep learning techniques, specifically leveraging VGG-16, a popular Convolutional Neural Network (CNN) architecture. The goal of this work is to enhance waterbird conservation efforts by providing an accurate and efficient solution for species identification.

## Dataset

The dataset used for training and testing contains images of 25 different Indian bird species, sourced from Kaggle. The collection includes a total of 22,600 images, with each species represented by 500 images. These images cover various angles of the birds, ensuring a diverse range of perspectives. For training purposes, 70% of the images were used, while the remaining 30% were set aside for validation.

### Bird Species Included:

- Common Kingfisher
- Sarus Crane
- White-Breasted Kingfisher
- And more...

## Model

The model was built using the VGG-16 architecture, which is known for its deep layers and robust performance in image classification tasks. The model was trained on the collected dataset and evaluated based on accuracy, precision, recall, and F1-score.

### Performance Metrics:

- **Accuracy**: 92.69%
- **Loss**: 0.2537
- **Precision, Recall, F1-scores**: The model's performance was analyzed for different species like the Common Kingfisher and Sarus Crane. 
    - **White-Breasted Kingfisher**: Achieved maximum precision and an F1-score of 0.97.

## Results

The model achieved outstanding results, particularly in identifying the White-Breasted Kingfisher. The classification report showcases the model's precision, recall, and F1-scores for various species, highlighting the effectiveness of the deep learning model for accurate species identification.

## Contributions

- **Accuracy**: The model demonstrated an impressive accuracy of 92.69%, making it a highly reliable tool for bird species detection.
- **Wildlife Conservation**: The successful detection of various waterbird species can assist in ecological research and conservation activities aimed at protecting these species in their natural habitat.
  

### Requirements:
- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib
- OpenCV

## Conclusion

This project demonstrates the potential of deep learning in wildlife conservation and biodiversity monitoring. The model can play a crucial role in safeguarding waterbird species, assisting researchers, and aiding in ecological conservation efforts.
