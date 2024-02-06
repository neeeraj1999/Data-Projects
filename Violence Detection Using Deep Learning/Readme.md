## Project Overview
Deep learning-based system designed for real-time violence detection in video streams, employing a Convolutional Neural Network (CNN) with MobileNetV2 architecture
for efficient feature extraction leveraging a balanced dataset comprising 2000 videos for training and validation, ensuring robustness and accuracy.

## Key Features and Technical Aspects  
<!DOCTYPE html>
<html>
<body>

  <h3>Real-time Violence Detection</h3>
  <p>The system uses a CNN model to continuously analyze video streams from surveillance cameras.It is capable of processing video data in real-time, identifying potential violent activities as they occur.</p>

  <h3>MobileNetV2 for Feature Extraction</h3>
  <p>MobileNetV2 is a lightweight yet efficient CNN architecture chosen for its balance between performance and computational cost. It excels in extracting relevant features from video frames, crucial for accurate violence detection.</p>

  <h3>Frame-level Analysis</h3>
  <p>This approach involves dissecting video streams into individual frames and analyzing each frame independently. This granular analysis allows for the precise identification of violent elements within a video.</p>

  <h3>Dataset Utilization</h3>
  <p>The model is trained and validated on a comprehensive dataset containing a mix of violent and non-violent scenes. This diverse dataset ensures that the model learns to differentiate various aspects of violence from normal activities effectively.</p>

  <h3>Binary Classification</h3>
  <p>The system employs binary classification to categorize video frames. Each frame is classified as either 'violent' or 'non-violent'. This classification is based on the learned features and patterns that the model has been trained on.</p>
</body>
</html>

## Model Training and Evaluation
Employed TensorFlow and Keras for model development and training.
Performance evaluation based on accuracy, precision, and recall metrics.

## Conclusion
The project's implementation successfully managed the task of violence detection, even with limited GPU resources. The key to this success was the data augmentation process, which compensated for the small volume of labeled data. By increasing the sample size, it allowed the model to discern meaningful patterns within the frames. Additionally, retraining the CNN networks significantly enhanced performance. This approach underlines the effectiveness of data augmentation and model retraining in overcoming hardware limitations and data scarcity, ultimately leading to a robust and efficient violence detection system.
