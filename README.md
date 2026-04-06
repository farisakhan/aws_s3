# creating s3 bucket and put objects in bucket through local pc using aws cli

## 📌 Objective
This project demonstrates how to create an S3 bucket and upload a file using AWS CLI.

## 🛠️ Tools Used
- AWS CLI
- Amazon S3
- IAM User (for authentication)

## 🚀 Steps Performed

### 1. Configure AWS CLI
aws configure
Enter:
- AWS Access Key
- AWS Secret Key
- Region: us-west-2
- Output: json

---

### 2. Create S3 Bucket
aws s3 mb s3://farisa-s3-demo-2026-12345 --region us-west-2

---

### 3. Verify Bucket Creation
aws s3 ls

---

### 4. Upload File from Local System
aws s3 cp "C:\Users\faris\OneDrive\Desktop\hello.txt" s3://farisa-s3-demo-2026-12345/

---

### 5. Verify File Upload
aws s3 ls s3://farisa-s3-demo-2026-12345/

---

## 🌍 Region
us-west-2 

## 📄 Description
This project demonstrates how to create an S3 bucket and upload a file using AWS CLI from a local system.  
All operations are performed using command-line without using the AWS Management Console.
The file (hello.txt) is uploaded from the local system to the S3 bucket.

## ✅ Output
- S3 bucket created successfully
- File uploaded successfully to the bucket

## 💡 Key Points
- S3 bucket names must be globally unique  
- AWS CLI is used for automation and cloud management  
- Files can be uploaded using their local system path  
