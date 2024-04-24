<h1 align="center">Hello, I'm <a href="#" target="_blank">Nikita!</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Graduate of the Faculty of Computer Science, Java developer from Kazakhstan</h3>

<h2>Launch Instructions</h2>

# AWS-Facial-Recognition-API-Application
app that demonstarates how to use Amazon Rekognition api features for facial recognition with node.js

## AWS Configurations
1. You need to log in to AWS service.
2. Configure user and storage and get permission to run Amazon Rekognition API:
-User:
    - Type "IAM" into the search bar, click the "users" in the left menu and then "add user".
    - <img src="https://github.com/Nikita333111/AWS-Facial-Recognition-API-Application/blob/main/amazon-rekognition/instructions%20imgs/user%20creation.png" height="350" alt="конфигурация бд">
    - Choose "programming use option" and add polices "amazonS3fullaccess" and "amazonrekognitionfullaccess".
    - <img src="https://github.com/Nikita333111/AWS-Facial-Recognition-API-Application/blob/main/amazon-rekognition/instructions%20imgs/set%20permissions.png" height="350" alt="конфигурация бд">
    - Generate access key id and secret access key.
-Bucket:
    - Type "S3" into the search bar, click the "buckets" in the left menu and then "create bucket".
    - Type uniqe bucket name and same aws region as we will use in the project later.
    - !<img src="https://github.com/Nikita333111/AWS-Facial-Recognition-API-Application/blob/main/amazon-rekognition/instructions%20imgs/create%20bucket.png" height="350" alt="конфигурация бд">
    - Click create bucket
    - Upload images that you want to analyze into your bucket.
    - <img src="https://github.com/Nikita333111/AWS-Facial-Recognition-API-Application/blob/main/amazon-rekognition/instructions%20imgs/upload%20img.png" height="350" alt="конфигурация бд">
## Project Configuration
1. Clone this project "git clone https://github.com/coursera-guided/amazon-rekognition.git" and install dependensies:
    - type into project terminal "npm install" and "npm install aws-sdk".
    - paste your public and private keys into env file.
2. Run project.
    - Type node server.js into your terminal in ptoject directory to run application.
    - Go to localhost:8089 in yuor browser to test application.

## Clean up
1. Clean up your enviroment:
    - Delete bucket and user to avoid aws payment, aws is pay to use platform, so you need to clean all stuff after usage. 
