# Brain-Tumor-Detection
Sequential Xception Classification Model with 4 classes: Pituitary, Meningioma, Glioma, No Tumor.

Performance Results and Visualizations
The model demonstrates exceptional accuracy across all datasets, showcasing its robustness and reliability in tumor classification.

Overall Accuracy Metrics:
Training Accuracy: 99.89% (Loss: 0.0021)

Validation Accuracy: 98.32% (Loss: 0.0873)

Test Accuracy: 97.87% (Loss: 0.1356)

These figures indicate that the model generalizes well, with minimal overfitting.

Class-wise Performance:
Class	Precision	Recall	F1-Score	Support
Pituitary	0.99	0.93	0.96	150
No Tumor	0.93	0.99	0.96	153
Meningioma	1.00	1.00	1.00	203
Glioma	0.99	0.98	0.99	150

Overall Accuracy: 0.98 (based on 656 test samples)

Key Highlights:
Perfect classification performance on Meningioma cases, with 100% precision, recall, and F1-score.

High performance across all tumor classes, with F1-scores ranging from 0.96 to 1.00.

Balanced model behavior, as evident from near-equal precision and recall values for each class.

Visual Summary:
Training, validation, and testing accuracies are consistently high and visually represented with clear bar graphs.

F1-scores for each class are also color-coded and labeled, emphasizing the model’s strong performance.

A special note highlights the model’s perfect detection of meningioma, showcasing its clinical reliability in that category.
