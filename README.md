# Easy-License-Plate-LPR-

Overview:
This repository contains the research paper and accompanying diagrams detailing a proof-of-concept license plate recognition system built using Amazon Web Services (AWS). 
The system leverages AWS Rekognition for image analysis, along with other AWS services like SageMaker, SNS, CloudWatch, Rekognition, Lambda, S3, and DynamoDB for scalability and efficiency.

Key Features:

AWS Rekognition Integration: Utilizes Rekognition's powerful image and video analysis capabilities for accurate license plate detection and recognition.<br>
Scalable Architecture: Leverages AWS services like Lambda, S3, and DynamoDB to ensure scalability, reliability, and performance.<br>
Database Storage: Stores recognized license plate information in a DynamoDB database.<br>
Notification System: Sends notifications based on recognition outcomes (recognized or unrecognized plates).<br>
Access Control: Implements IAM for secure access to AWS services.<br>

System Architecture:
<img width="926" alt="LPR_diagram" src="https://github.com/user-attachments/assets/20c010b9-ff11-42af-8df7-640c511c8d23"><br>

Workflow:

Image/Video Capture: Cameras capture images or video streams.<br>
Preprocessing: Images/videos undergo preprocessing steps (resizing, noise reduction).<br>
License Plate Detection: AWS Rekognition detects license plates in the images/videos.<br>
Character Segmentation: If necessary, characters within the license plate are segmented.<br>
Character Recognition: AWS Rekognition recognizes the characters on the license plate.<br>
Data Storage: Recognized license plate information is stored in DynamoDB.<br>
Notification: SNS notifications are sent based on recognition outcomes.<br>
Access Control: IAM manages access to AWS services.<br>

Project Scope:

Proof-of-Concept: This project was primarily a conceptual exercise, focusing on demonstrating the feasibility of using AWS services for license plate recognition.<br>
Future Phases: The paper outlines potential future phases, including the integration of real-time video processing and deployment in production environments.<br>

Repository Contents:
Research Paper: A detailed document outlining the system architecture, methodology, and results.<br>

Additional Notes:

Project Status: This is the first phase of the project and it may have limitations or incomplete features.
Future Work: In the future To test the functionality and performance of our system before deployment and implementation into the company's 
garage system we shall be working with a Chinese City Parking Dataset. 

