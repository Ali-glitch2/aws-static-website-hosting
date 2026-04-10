# AWS-STATIC-WEBSITE-HOSTING-PROJECT
<img width="1131" height="386" alt="image" src="https://github.com/user-attachments/assets/c2281b12-ec60-4dce-8c09-340281c6f1e8" />


## Features
- **Static Website Hosting**: Accessible via a public URL provided by S3.
- **Custom Error Pages**: Configured custom error pages for a better user experience.
- **Access Management**: Implemented AWS S3 Bucket Policies and ACLs to control public access.

## Setup and Deployment

### Step 1: Create an S3 Bucket
1. Search for S3 bucket service 
<img width="2451" height="1216" alt="Screenshot 2026-04-10 155953" src="https://github.com/user-attachments/assets/ef1cbc42-b9a1-476b-a912-df54028b7d50" />
2. Create a bucket
<img width="1111" height="227" alt="Screenshot 2026-04-10 164357" src="https://github.com/user-attachments/assets/045f1914-cd5a-4002-9943-a7ded0a84f32" />
3.Enable ACLs:
   * During bucket creation, under "Object Ownership," select ACLs enabled.
   * This allows fine-grained control over the permissions of individual objects in the bucket

 ### Step 2: Upload Files

