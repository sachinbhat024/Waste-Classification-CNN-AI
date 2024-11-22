# Waste Classification Using CNN 🗑️📷
This project focuses on developing an automated waste classification system using advanced Convolutional Neural Network (CNN) techniques to classify waste into six categories: cardboard, glass, metal, paper, plastic, and vegetation.

The dataset for this project consisted of 2,864 images, equally distributed among the six waste types. Each image was pre-processed to ensure consistent size (100x100 pixels) and normalized to optimize the model's learning efficiency. The dataset was split into training and test sets with a 70/30 ratio.

We used a CNN model as it is ideal for image classification due to its ability to learn spatial patterns. We experimented with various architectures by adjusting the number of convolutional layers, hidden layers, hidden nodes, pooling layers, dropout rates, and the size of the kernels. The aim was to identify the model that offered the best performance.

The best model (CNN 6), featuring 4 convolutional layers followed by 3 max-pooling and 2 hidden layers, achieved a test accuracy of 77.79% and a Kappa score of 0.733, reflecting a strong alignment between the model’s predictions and the actual labels. The Vegetation class had the highest accuracy, with 121 out of 122 samples correctly classified. In contrast, the Plastic class was the most challenging, with only 99 out of 155 samples correctly identified, likely due to visual similarities with materials like Cardboard and Paper.

While the model presents a solid solution for automating the waste sorting process, there is room for improvement. Techniques such as data augmentation and using pre-trained models are recommended to enhance real-world performance and address misclassifications, particularly in classes like Plastic.
