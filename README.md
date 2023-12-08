PERSON DETECTION USING YOLOv8

Data Preparation
1. Dataset Download:
* The dataset was obtained from People Image Dataset (kaggle.com).
2. Selection of Training Images:
* A subset of 50 images was chosen from the entire dataset for model training.
* The dataset comprises images featuring individuals across various age groups, encompassing children, men, women, and older individuals.
3. Annotation with labelImg:
* The labelImg tool was employed for annotating persons within the selected images.
4. Annotation Output:
* The annotated images were saved in a specified format YOLO.
Data Processing
* The prepared dataset, consisting of annotated images and corresponding YOLO-formatted labels, was used to train the YOLOv8 model.
* Training involved multiple iterations (epochs), allowing the model to learn and refine its ability to detect persons in various contexts.

Evaluation
* The trained YOLOv8 model was evaluated on a separate validation set to assess its performance in detecting persons.


The YOLOv8 model has been successfully trained to detect persons in images based on the carefully prepared dataset. The model's performance can be further improved through fine-tuning or additional iterations, as needed.
