# AeroInspect.AI

# **Introduction**

AeroInspect.AI is a deep learning-powered Quality Assurance (QA) solution designed for real-time defect detection in aerospace manufacturing. This system minimizes costly failures by leveraging advanced computer vision techniques using the YOLOv10 model.


# **Problem statement we are trying to address**

The aviation industry is under constant pressure to maintain timely deliveries. However, quality assurance failures often lead to delays and high costs due to rework and component failures. Traditional inspection systems struggle to meet the high precision demands required in aerospace manufacturing.


# **Solution**
AeroInspect.AI integrates deep learning and computer vision to deliver accurate, real-time defect detection. By identifying defects early, it ensures timely interventions, preventing delays and reducing overall quality control costs.

<img width="1438" alt="Screenshot 2024-09-17 at 6 31 57 PM" src="https://github.com/user-attachments/assets/06cd9850-753a-4be6-abf7-e77b98b83e77">


# **Key Features**

1. Real-time defect detection with YOLOv10
2. Capable of identifying up to 17 distinct defect types
3. Self-learning capabilities for continuous improvement
4. Integration with existing production workflows
5. Cloud-based analytics and defect reporting

# **High level Architecture Diagram** 

<img width="1438" alt="Screenshot 2024-09-17 at 6 38 04 PM" src="https://github.com/user-attachments/assets/17e968c0-7902-44b2-addd-18903c1e052c">



# **Technologies Used** 



1. Camera: Bosch DINION IP Ultra 8000 MP – High-res cameras to capture clear, real-time video of engineers' work.
2. GPU: NVIDIA – To speed up the AI model’s training and detection processes.
3. Video Processing: OpenCV – For real-time video stabilization and compression.
4. Object Detection: YOLOv8 with PyTorch – Detects errors in design and manufacturing in real-time.
5. Dataset Management: Roboflow – Helps create and manage custom datasets for training the detection models.
6. Containerization and Deployment:- We are using DOCKER For packaging and deploying the entire system, ensuring consistency across different environments and simplifying scaling.
7. Deep Learning & Model Training: TensorFlow is utilized for building and training deep learning models to detect errors and deviations in real-time, ensuring precise and        efficient processing of complex data during manufacturing.


<img width="662" alt="Screenshot 2024-09-17 at 6 42 13 PM" src="https://github.com/user-attachments/assets/91737b19-3580-4d9f-bcf1-a0a7dc92736d">

 # **Product Performance Feasibility**

For the performance feasibility of AeroInspect.AI, we can consider several key metrics: detection accuracy and real-time processing speed

![detection_accuracy_over_time](https://github.com/user-attachments/assets/b07a0ebf-f0c0-470b-b5b5-a36670692a11)

Here is the graph representing Detection Accuracy Over Time for AeroInspect.AI, showing how the model improves in accuracy as it learns from identified defects.

<img width="1253" alt="Screenshot 2024-09-17 at 6 47 13 PM" src="https://github.com/user-attachments/assets/05be93fb-57db-450b-a71f-71b1d498f29b">

This graph representing The real-time processing speed of AeroInspect.AI for different types of defects.














