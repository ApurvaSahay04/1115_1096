# Chest X-ray Classification using ResNet-18 and Grad-CAM

## 1. Project Overview
This project focuses on Chest X-ray image classification using Deep Learning. A ResNet-18 convolutional neural network is used to classify chest X-ray images, while Grad-CAM (Gradient-weighted Class Activation Mapping) is implemented to visualize the important regions of the image influencing the model's predictions.

## 2. Objectives
- Develop a deep learning model for chest X-ray classification.
- Apply ResNet-18 for image classification.
- Use Grad-CAM to generate visual explanations of model predictions.
- Understand which regions of the X-ray images influence classification decisions.

## 3. Dataset
- Dataset: COVID-19 Radiography Database.
- Input: Chest X-ray images.
- Images are preprocessed before being passed to the deep learning model.

## 4. Technologies Used
- Python
- PyTorch
- ResNet-18
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Grad-CAM
- Jupyter Notebook

## 5. Methodology
1. Dataset loading and exploration.
2. Image preprocessing and preparation.
3. Implementation of the ResNet-18 architecture.
4. Model training and evaluation.
5. Grad-CAM visualization to interpret model predictions.
6. Analysis of model performance and activation maps.

## 6. Results
- Test accuracy: 98.75% (237 correct predictions out of 240 test samples).
- Grad-CAM visualizations were generated to interpret model predictions.
- Mean in-lung Grad-CAM activation: 33.7% (evaluated on 60 samples).

**Note:** The reported accuracy is based on the project's test set and should not be interpreted as clinical diagnostic performance.

## 7. Repository Structure
- `xray_grad_cam_main_v3 (1) (1).ipynb` – Main Jupyter Notebook containing implementation, training, evaluation and Grad-CAM visualizations.
- `README.md` – Project documentation.

## 8. How to Run
1. Clone or download this repository.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Install the required Python libraries.
4. Ensure the dataset is downloaded and its path is correctly configured.
5. Run the notebook cells sequentially.

## 9. Conclusion
This project demonstrates the application of deep learning for chest X-ray image classification using ResNet-18 and model interpretability using Grad-CAM. It provides insights into the image regions influencing the model's predictions.

## 10. Author
Apurva Sahay  
B.Tech – Computer Science and Engineering (Data Science)

K.Dhiraj
B.Tech – Computer Science and Engineering (Data Science)
