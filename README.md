# GreenGuard
GreenGuard is a user-friendly and interactive web application designed to help farmers, researchers, and agricultural enthusiasts quickly and accurately identify plant diseases. Built with 
Streamlit, this app leverages the power of Convolutional Neural Networks (CNNs) to perform multi-class classification on plant images, predicting diseases with high accuracy.

**Features:** 
- Disease Prediction: Identify diseases in plant leaves using advanced CNN models trained on the PlantVillage Dataset, a benchmark dataset for plant disease detection.
- Multi-class Classification: The model classifies images into multiple disease categories, offering precise insights into plant health.

**Source of dataset:** [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

The PlantVillage dataset consists of 54303 healthy and unhealthy leaf images divided into 38 categories by species and disease.

### Web application Demo:
![Screenshot 2024-12-07 122004](https://github.com/user-attachments/assets/c6f8d537-2a2e-4a24-bf44-81503d900c83)

### Model Details:
- Architecture: The 2-layer CNN model architecture is designed to handle multi-class classification tasks efficiently, incorporating layers that extract complex patterns from plant leaf images.
- Training: The model was trained on a diverse set of plant leaf images, ensuring it generalizes well across different types of diseases.
- Performance: Achieved 91% accuracy and low validation loss on the test dataset, demonstrating its effectiveness in real-world applications.
  
