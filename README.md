# YOLOv8 Fine-Tuning for Pose Estimation with Horses

This project involves fine-tuning the YOLOv8 model for pose estimation, specifically focusing on horses. The goal was to develop a model capable of processing video input and providing accurate bounding box predictions for horses.

## Dataset

The dataset used for this project is the [Horse-10 dataset](https://paperswithcode.com/dataset/horse-10). This dataset contains a variety of horse images which are essential for training the pose estimation model.

## Steps Involved

1. **Data Preparation:**
   - Downloaded the Horse-10 dataset.
   - Performed merging and splitting operations on the dataset to prepare it for training and testing.

2. **Model Training:**
   - Utilized the YOLOv8 model for fine-tuning.
   - Applied the training on the preprocessed dataset to obtain a model that can predict bounding boxes around horses in video inputs.

3. **Evaluation Metrics:**
   - Achieved significant results with a precision close to 1.
   - Displayed essential metrics for model evaluation:
     - **Precision:** Measures the accuracy of the positive predictions.
     - **Recall:** Measures the ability of the model to find all relevant instances.
     - **F1-Score:** The harmonic mean of precision and recall, providing a single metric for model performance.
     - **Confusion Matrix:** Visualizes the performance of the model by showing the true positives, false positives, true negatives, and false negatives.

4. **Comparative Analysis:**
   - Conducted a detailed comparative analysis of real and predicted labels to understand the model's performance better and identify any areas for improvement.
     **Real Labels**
    ![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/4f98f487-743e-4081-9ab5-eb7f147d2b61)
    **Predicted Labels**
    ![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/4410631f-02f6-414d-8bcd-f3568ff7b18a)



## Results

- **Precision:** Close to 1
- **Recall:** High recall value indicating the model's effectiveness in identifying horses.
- **F1-Score:** Indicates a strong balance between precision and recall.
- **Confusion Matrix:** Provided insights into the distribution of predictions across different classes.
- 
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/1f91c316-62de-4b5b-92fd-f985f3bbc9cf)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/8dac77d6-80ed-4bf2-a91a-c4a5cf90872c)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/fc094477-f5f5-4b91-8b05-2bf33d744ff2)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/90790bf2-8c7a-4bf2-a7ca-6298f7c2f57c)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/8c12a71c-4424-4f17-a3b4-a860c63f807d)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/8855e1d1-4848-4e94-b840-8214fd7aeea1)
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/ba5cdf80-b331-472a-b524-9bdab534b876)


## Ouput :
![image](https://github.com/HaykelBargouguy/YOLOv8-Fine-Tunning-For-Horse-Pose-Estimation/assets/98351985/31ff836e-5214-4563-b74a-272e6b56da7a)

## Conclusion

The YOLOv8 model fine-tuned on the Horse-10 dataset demonstrates excellent performance in pose estimation for horses. The high precision, recall, and F1-score reflect the model's reliability and accuracy in detecting horses in video inputs. The comparative analysis further validates the model's predictions, ensuring robustness and effectiveness.





