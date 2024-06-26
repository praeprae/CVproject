# CVproject
CV2023 Final Project

◼︎ Project : 
Explainable AI for BI-RADS Classification in Breast Cancer Screening Using CNN and Grad-CAM

◼︎ Dataset : This project was conducted using a private dataset, so I cannot share it. However, I recommend using a public dataset such as VinDR-Mammo (link: https://www.kaggle.com/datasets/hadighahroudi/vindr-mammo-dataset?).

◼︎ Problem Description:

I aim to develop a BI-RADS classification system for breast cancer screening that achieves high performance while providing explainability.

◼︎ Input/Output:

The input to the system will be mammography images, and the output will be BI-RADS classification scores.

◼︎ Importance and Interest:

This project is important because accurate and explainable BI-RADS classification can significantly improve the early detection and treatment of breast cancer. By using explainable AI, radiologists and clinicians can better understand and trust the model's predictions, leading to more informed decision-making in clinical settings.

◼︎ Related Works:

Numerous efforts have been made to apply deep learning in breast cancer screening with a focus on explainability. These include approaches for BI-RADS scoring, abnormality detection, and segmentation. Researchers have developed various models to improve the accuracy and interpretability of mammography image analysis, contributing to better diagnostic tools in clinical practice.


◼︎ Method and Results:

Experiment 1: Utilizing a pretrained ResNet50 as the base model and employing cross-entropy loss as the criterion. This experiment achieved an accuracy of 0.4639.

Experiment 2: Utilizing a pretrained ResNet50 with additional fully connected hidden layers as the base model and employing cross-entropy loss as the criterion. This experiment achieved an accuracy of 0.4577.

Experiment 3: Utilizing a pretrained ResNet50 with additional fully connected hidden layers as the base model, and employing cross-entropy loss along with auxiliary loss between different views of images from the same breast as the criteria. This experiment achieved an accuracy of 0.6781.


◼︎ Discussion and Future Work

1. Utilize larger public datasets.
2. Implement image augmentation techniques such as adjusting brightness or contrast.
3. Experiment with larger and more complex models, such as EfficientNet or ViT.
4. Explore alternative evaluation criteria.
5. Apply more advanced eXplainable AI (XAI) techniques, such as Score-CAM or PYLON.
