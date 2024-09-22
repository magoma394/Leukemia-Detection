Leukemia Detection using Deep Learning and Computer Vision
This project utilizes deep learning and computer vision techniques to classify and detect acute lymphoblastic leukemia (ALL) from microscopic blood smear images. Leveraging advanced convolutional neural networks (CNNs) like EfficientNet B3, VGG16, and ResNet50, we aim to create a system that accurately classifies benign and malignant cells, specifically in detecting different subtypes of ALL.

Project Overview
Leukemia is a type of blood cancer affecting the bone marrow, where abnormal blood cells are produced. Accurate and early detection is crucial for effective treatment. This project focuses on detecting leukemia from peripheral blood smear (PBS) images using CNNs for feature extraction and classification.

Key Features:
Classification of leukemia cells into benign and malignant classes.
Advanced CNN architectures used include EfficientNet B3, VGG16, and ResNet50.
Custom CNN model for stage classification of leukemia.
Dataset
The dataset comprises 3242 high-resolution images from 89 patients. Images are categorized into benign and malignant classes, with malignant cases further classified into subtypes of leukemia (Early Pre-B, Pre-B, and Pro-B ALL).

Data Preprocessing:
Image resizing to 224x224 for CNN input.
Segmentation techniques to focus on relevant parts of the image.
Data augmentation (flipping, scaling) to improve model robustness.
Models and Techniques
EfficientNet B3
Accuracy: 93.75% with a 95.56% training accuracy.
Balanced approach between performance and computational efficiency.
VGG16 and VGG19
Known for simplicity and robustness.
Achieved moderate results but were less suitable compared to other models.
ResNet50
Tackles the vanishing gradient problem with residual learning.
Achieved 91.32% accuracy in its best configuration.
Custom CNN Model
Designed to classify the stages of leukemia.
Achieved 97.7% accuracy after extensive experimentation.
Results and Analysis
The project's models achieved significant accuracy in classifying leukemia stages. The best-performing model, a custom CNN, reached 97.7% accuracy, proving the viability of deep learning for this task.

Conclusion
This project demonstrates the potential of deep learning in medical diagnostics, specifically in classifying and detecting leukemia with high accuracy. The integration of deep learning into clinical practice could streamline diagnosis, improve treatment outcomes, and reduce misdiagnosis.
