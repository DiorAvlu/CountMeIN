CountMeIn: Crowd Monitoring Using YOLOv9

Overview

CountMeIn is a sophisticated crowd monitoring system designed to detect, track, and count people in real-time using the YOLOv9 object detection model. This project leverages advanced deep learning techniques to provide accurate and efficient people detection in various environments, making it suitable for applications in public safety, event management, transportation, and urban planning.

Features

Real-time Detection: Utilizes YOLOv9 for fast and accurate people detection.
Scalability: Adaptable to different scenarios, from small indoor spaces to large outdoor events.
High Accuracy: Achieves high precision and recall, ensuring reliable performance.
Advanced Preprocessing: Includes data augmentation and preprocessing techniques to handle various real-world conditions.

Results

The YOLOv9 model was trained for 60 epochs using the People Detection Image Dataset from Roboflow. Key performance metrics include:

Best mAP@0.5: 0.84338 , 
Best Precision: 0.84741 , 
Best Recall: 0.77357
Best mAP@0.5:0.95: 0.5132


<img width="1258" alt="Screenshot 2024-05-22 at 11 26 01 PM" src="https://github.com/DiorAvlu/CountMeIN/assets/107558562/19b585e8-c641-4eaf-ab23-adb3abb952d6">

<img width="1260" alt="Screenshot 2024-05-22 at 11 25 02 PM" src="https://github.com/DiorAvlu/CountMeIN/assets/107558562/13028307-291c-4a13-9045-9e475c600865">





Limitations

Occlusions: Struggles with detecting people in highly occluded environments.
Lighting Conditions: Performance can degrade in low-light scenarios or extreme weather conditions.
Resource Limitations: Restricted access to high-performance GPUs can impact training efficiency.

Future Work

Data Augmentation: Incorporate more advanced techniques to simulate real-world conditions.
Transfer Learning: Utilize models trained on larger, more diverse datasets.
Fine-Tuning: Focus on specific challenging conditions like low-light environments.
GUI Development: Create a custom graphical user interface for easier deployment.
