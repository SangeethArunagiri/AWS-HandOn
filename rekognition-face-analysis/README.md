# 👁️ Face Detection & Comparison with Amazon Rekognition
This project demonstrates how to use **Amazon Rekognition** to detect, analyze, and compare faces using the AWS Console.

## 📸 Features
- Detect facial landmarks (eyes, nose, mouth, etc.)
- Identify emotions (happy, sad, angry, etc.)
- Compare faces across two images to check similarity
- All done using Rekognition — no code needed!

## 🛠️ Tools Used
- Amazon Rekognition
- AWS S3 (for image storage)
- AWS IAM (to control access)

## 🧪 How I Did It
1. Uploaded two face images to an S3 bucket
2. Used Rekognition's **"Compare Faces"** and **"Detect Faces"** features
3. Reviewed confidence scores and facial details
4. Visualized results in the AWS console

### 📥 Input Images
rekognition-face-analysis/images/input1.jpg
rekognition-face-analysis/images/input2.jpg

## 📚 Reference
Based on this AWS Hands-On Tutorial:  
🔗 [Detect, Analyze, and Compare Faces using Amazon Rekognition](https://aws.amazon.com/getting-started/hands-on/detect-analyze-compare-faces-rekognition/)

