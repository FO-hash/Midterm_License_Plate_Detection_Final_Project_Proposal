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

      Source: Public license plate detection dataset or a dataset collected from parking lots.

      Size: Approximately 500–1,000 labeled images.

      Labels: Each license plate will be labeled with a bounding box using the `license_plate` class.

      Link: A public dataset link will be added if a public dataset is selected.

**Success Metrics**

      Primary metric: mAP (mean Average Precision) for license plate detection.

      Primary target: Achieve at least 80% mAP on unseen test images.

      Secondary metric: The model should successfully detect license plates in a variety of images with different vehicle positions and backgrounds.

      Secondary target: Detect most clearly visible license plates without producing excessive false detections.

## Milestone Plan

| Phase                   | Goal                                                        | Milestone                                 | 16-Week Term | 10-Week Term |
| ----------------------- | ----------------------------------------------------------- | ----------------------------------------- | ------------ | ------------ |
| **Blueprint**           | Plan the license plate detector                             | Midterm submitted                         | Week 10      | Week 5       |
| **First Working Demo**  | Get YOLOv8 running on sample images                         | Something works, even if rough            | Week 11      | Week 6       |
| **Make It Yours**       | Add the license plate dataset and train/customize the model | System works on the license plate problem | Weeks 12–13  | Weeks 7–8    |
| **Improve and Measure** | Test the model and measure its performance                  | Metrics recorded                          | Week 14      | Week 9       |
| **Package and Present** | Finish README, slides, AI usage log, and demo               | Final submitted                           | Week 15      | Week 10      |

**Top Risks + Plan B:**

      Risk 1: The public dataset may not have enough good-quality license plate images.
      
      Plan B: Use another public dataset or collect additional images from parking lots.
      
      Risk 2: Training the YOLOv8 model may not produce good detections.
      
      Plan B: Start with a pretrained YOLOv8 model, reduce the project scope, and use the pretrained model for the working proof of concept.

Ai usage Log is added to the GitHub repository
