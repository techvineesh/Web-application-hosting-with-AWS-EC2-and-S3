# Web-application-hosting-with-AWS-EC2-and-S3

## Node.js web Application Hosting on AWS EC2 and S3

## Overview
This project demonstrates hosting a Node.js application on an AWS EC2 instance, featuring an image gallery integrated with Amazon S3. The application showcases a personalized congratulatory message and ensures secure and efficient hosting using AWS resources.

## Prerequisites
- Ensure you can connect to the EC2 instance using AWS Systems Manager.
- Create an IAM role with necessary policies for secure access.
- Set up a Virtual Private Cloud (VPC) for a dedicated network environment.

## Required Resources

### Amazon EC2 Instance
- Launch an instance using an Ubuntu AMI.
- Access the instance and deploy the Node.js application provided in the zip file.
- Install Node.js and npm to run the application.
- Include the Express framework as part of the Node.js setup.

### Amazon S3 Bucket
- Upload at least three images to your S3 bucket.
- Set each image to public access for integration within the application.

## EC2 Instance Setup
1. Install Node.js and npm carefully as these are critical for running the application.
2. Confirm installation versions using the following commands:
   ```
   $ node -v
   $ npm -v
   ```
3. Take a screenshot after running these commands to confirm installation.

## Preparing the Application Files
- Adjust the application files as specified before uploading them to EC2.

## Instructions

### Completion Page Modifications
1. Extract the provided zip file and open the `completion.html` file.
2. Replace `[Your Name]` with your actual name.
3. Add S3 image links in place of `S3IMAGESURL` using the public URLs from your S3 bucket.

### Running the Application
1. Deploy and test the application on your EC2 instance by running:
   ```
   $ node app.js
   ```
2. Verify that images from S3 are displayed correctly in the application gallery.

---

By following these steps, you will successfully deploy and host a Node.js application on AWS infrastructure.
