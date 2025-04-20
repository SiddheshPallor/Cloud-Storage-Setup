📦 Amazon S3 Bucket Project: Upload & Permissions Management

📁 Project Overview
This project demonstrates how to create and configure an Amazon S3 bucket, upload a dataset (netflix_titles.csv), and manage permissions. It also highlights a common permissions issue related to ACLs and how AWS handles public access control.

✅ Features
Create an S3 bucket (my-cloud-project-bucket1)

Upload CSV file to the bucket

Review and manage permissions

Identify and understand blocked ACL usage

Learn AWS best practices for object-level security

🛠️ Technologies Used
AWS S3 – Object storage

AWS Console – GUI for resource creation and config

netflix_titles.csv – Sample dataset for testing

⚠️ Common Issue Faced
While trying to make the uploaded object public via ACL, the option was disabled due to AWS security defaults. This was resolved by understanding that:

✅ ACLs are disabled by default in AWS S3 for enhanced security.
🔐 Public access should instead be controlled via Bucket Policies or IAM roles.

📚 What I Learned
How to create and use Amazon S3 buckets

Uploading objects through AWS Console

AWS permission models (ACL vs Bucket Policies)

Debugging public access issues with S3 objects

🙌 Author
Made with ☁️ by Siddhesh Pallor
Beginner Cloud Enthusiast | Learning AWS
🔗 https://www.linkedin.com/in/siddhesh-pallor-821516311/


