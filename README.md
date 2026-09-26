# Project Name: License Plate Detection
**Course Name: ITAI 1378**

**Team Members: Funsho Orogun, (only me)**

**Project Tier: Tier 1**

**Reasoning:**
This project was in the Free project tier. I also feel like I could build this project idea into something that I could use in real life


**Problem Statement:**
License plates need to be located accurately in images for systems such as automated parking and traffic monitoring. Manually finding license plates in images can be time-consuming, especially when there are many vehicles. This project will use computer vision to automatically detect and locate license plates.


**Solution Overview:**
The system will take an image as input and output a bounding box around each detected license plate. The goal is to create a working proof of concept that can automatically locate license plates.

**Technical Approach:**
The project will use the YOLOv8 object detection model to detect license plates in images. 

**Data plan:**
***Source:*** Public license plate detection dataset or a dataset collected from parking lots.

    **Size:** Approximately 500–1,000 labeled images.

    **Labels:** Each license plate will be labeled with a bounding box using the `license_plate` class.

    **Link:** A public dataset link will be added if a public dataset is selected.
