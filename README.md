# Easy-License-Plate-LPR-

Overview:
This repository contains the research paper and accompanying diagrams detailing a proof-of-concept license plate recognition system built using Amazon Web Services (AWS). 
The system leverages AWS Rekognition for image analysis, along with other AWS services like SageMaker, SNS, CloudWatch, Rekognition, Lambda, S3, and DynamoDB for scalability and efficiency.

Key Features:

AWS Rekognition Integration: Utilizes Rekognition's powerful image and video analysis capabilities for accurate license plate detection and recognition.
Scalable Architecture: Leverages AWS services like Lambda, S3, and DynamoDB to ensure scalability, reliability, and performance.
Database Storage: Stores recognized license plate information in a DynamoDB database.
Notification System: Sends notifications based on recognition outcomes (recognized or unrecognized plates).
Access Control: Implements IAM for secure access to AWS services.

System Architecture:
![Diagram Image](path/to/your/image.png)
Workflow:

Image/Video Capture: Cameras capture images or video streams.
Preprocessing: Images/videos undergo preprocessing steps (resizing, noise reduction).
License Plate Detection: AWS Rekognition detects license plates in the images/videos.
Character Segmentation: If necessary, characters within the license plate are segmented.
Character Recognition: AWS Rekognition recognizes the characters on the license plate.
Data Storage: Recognized license plate information is stored in DynamoDB.
Notification: SNS notifications are sent based on recognition outcomes.
Access Control: IAM manages access to AWS services.

Project Scope:

Proof-of-Concept: This project was primarily a conceptual exercise, focusing on demonstrating the feasibility of using AWS services for license plate recognition.
Future Phases: The paper outlines potential future phases, including the integration of real-time video processing and deployment in production environments.

Repository Contents:
Research Paper: A detailed document outlining the system architecture, methodology, and results.

Additional Notes:

Project Status: This is the first phase of the project and it may have limitations or incomplete features.
Future Work: In the future To test the functionality and performance of our system before deployment and implementation into the company's 
garage system we shall be working with a Chinese City Parking Dataset. 

