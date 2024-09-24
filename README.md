# AWS-Rekognition-Image-Label-Detection
This project demonstrates how to use **AWS Rekognition** to detect objects, scenes, and concepts in images stored in **Amazon S3**. It also visualizes the detected labels by drawing bounding boxes on the image using **Matplotlib** and **Pillow**.

## Features

- Detect labels (objects, scenes, and concepts) in an image using AWS Rekognition.
- Display detected labels and their confidence scores.
- Visualize the detected objects with bounding boxes over the image.
- Download and display images directly from an Amazon S3 bucket.

## Technologies Used

- **AWS Rekognition** for image label detection.
- **Amazon S3** for storing images.
- **Boto3** (AWS SDK for Python) for interacting with AWS services.
- **Matplotlib** for plotting bounding boxes and labels.
- **Pillow (PIL)** for handling and manipulating images in Python.

## Prerequisites

Before running this project, make sure you have the following setup:

- **AWS Account**: You will need an AWS account with **Rekognition** and **S3** services enabled.
- **AWS Credentials**: Ensure you have properly configured AWS credentials on your machine.

## Steps

The following steps will be implemented 

1. Creating an S3 bucket
2. Uploading the image to the S3 bucket
3. Configuring AWS CLI
4. Importing libraries 
5. Adding detect_labels function
6. Adding main function
7. Running Python File
## Output

```python
Detected labels for busy roads.jpg

Label: Person
Confidence: 99.49266815185547

Label: Bicycle
Confidence: 98.99691009521484

Label: Vehicle
Confidence: 98.99691009521484

Label: Truck
Confidence: 98.08560180664062

Label: Traffic Light
Confidence: 97.31024169921875

Label: Bus
Confidence: 97.00897979736328

Label: Moving Van
Confidence: 95.9243392944336

Label: Shoe
Confidence: 93.17137908935547

Label: Boarding
Confidence: 86.51419830322266

Label: Handbag
Confidence: 86.10273742675781

Labels detected: 10

```

![download.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b6a54f-ddca-42d6-a329-404029144b9f/636aa3d1-392d-4bac-a6d0-0e421ee3b3f8/download.png)
