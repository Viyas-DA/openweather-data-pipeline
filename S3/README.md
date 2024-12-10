# Steps followed to create S3

1. Create a S3 bucket

2. Get back to EC2 --> Instance --> Modify IAM role to create a new IAM role and in under AWS services select EC2 full access and Amazon s3 full access and create a role

   (This helps EC2 able to connect with S3, that is when we run the code on EC2 and it generate the CSV file then it load it into S3 bucket.)

   ![image](https://github.com/user-attachments/assets/59d33e1c-4c9b-42ba-a751-430f9026d3cb)
