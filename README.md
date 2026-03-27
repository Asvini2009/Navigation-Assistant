# Navigation-Assistant
Obstacle detection model with audio feedback for visually impaired individuals to navigate

**Abstract:**
Navigating daily life is a major challenge for visually impaired individuals, requiring new solutions that can effectively help them avoid obstacles. Current navigation aids, such as guide dogs and walking sticks, often provide limited real-time feedback 
and have difficulty predicting obstacles, while also being costly. To address these shortcomings, this study introduces a new solution using advanced machine learning technologies, specifically the YOLOv9 and YOLOv10 models. These models enhance the ability
to adapt to changing environments, allowing users to receive real-time alerts about obstacles in their path. 
The system uses a Raspberry Pi for the hardware component, offering a cost-effective way to provide real-time feedback through audio directions delivered via Bluetooth.
The proposed model shows significant improvements in object detection, achieving an accuracy of 0.847 in recognizing key obstacles like traffic cones, potholes, humans, and cars, with a reliable Frames Per Second (FPS) of 1.10 that ensures efficient performance. This level of accuracy supports effective navigation in complex environments, providing more independence and reducing reliance on traditional aids. Notably, this approach not only boosts users' morale and confidence but also has the potential to have a positive impact on communities on a larger scale.
The implications of this research suggest a significant move toward more independent navigation for visually impaired individuals. Future work will aim to expand the model's capabilities by using a broader dataset to cover more common obstacles and finding ways to make the model more compact for wider use. These improvements hold great promise for real-world applications, ultimately enhancing the quality of life for visually impaired individuals.

**Dataset Description:**
This project utilizes a dataset comprising 6276 high-resolution images. These images contain a wide array of outdoor, urban environments, including parking lots, sidewalks, roads, and recreational areas. The dataset focuses on 4 primary obstacle classes that pose significant risks to visually challenged individuals. These are people, cars, traffic cones, and potholes. 

