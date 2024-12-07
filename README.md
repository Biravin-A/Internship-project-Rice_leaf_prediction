PRCP- 1001- RiceLeaf disease detection

Problem Statement

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a model which can classify the three major attacking diseases of rice plants like leaf blast, bacterial blight and brown spot.

Task3:- Analyze various techniques like Data Augmentation, etc and create a report on that.


Dataset Link:
This dataset contains 120 jpg images of disease-infected rice leaves. The images are grouped into 3 classes based on the type of disease. There are 40 images in each class.
Classes
●	Leaf smut
●	Brown spot
●	Bacterial leaf blight
Domain: 

Link : https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1001-RiceLeaf.zip










Model Comparison Report

Create a report stating the performance of multiple models on this data and suggest the best model for production.

Report on Challenges faced

Create a report which should include challenges you faced on data and what technique used with proper reason.


Note:-All above tasks have to be done on a single jupyter notebook and share the same for final submission of the project.



Objective:
To classify rice plant diseases using machine learning models, specifically a Convolutional Neural Network (CNN), to detect diseases like Leaf Blast, Bacterial Blight, and Brown Spot.

Model Training Progress:
The training process spanned 30 epochs, showing significant improvements in accuracy and loss reduction. Key milestones include:

Epoch 1: Accuracy = 40.8%, Loss = 1.108
Epoch 4: Accuracy = 35.4%, Val Accuracy = 63.64% (First sign of model improvement)
Epoch 11: Accuracy = 46.56%, Val Accuracy = 72.73%
Epoch 18: Accuracy = 57.02%, Val Accuracy = 81.82%
Epoch 19: Accuracy = 53.06%, Val Accuracy = 90.91% (A major milestone)
Key Insights:
The training accuracy reached as high as 67.1%, while the validation accuracy peaked at 90.91%, which indicates that the model generalized well to new data.
The model initially struggled, but with more training (Epoch 19), it achieved significant improvement, reflecting the power of CNNs in image classification tasks.
Conclusion:
The CNN-based model can accurately identify the three key diseases in rice plants. This can help farmers, agricultural experts, and policymakers detect crop diseases early, leading to better pest control and increased crop yields.
