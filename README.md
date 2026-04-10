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
2. Create a Bucket
<img width="1111" height="227" alt="Screenshot 2026-04-10 164357" src="https://github.com/user-attachments/assets/045f1914-cd5a-4002-9943-a7ded0a84f32" />
3.Enable ACLs:
   * During bucket creation, under "Object Ownership," select ACLs enabled.
   * This allows fine-grained control over the permissions of individual objects in the bucket
     
 ### Step 2: Upload Files

 1. Upload your website files
 2. Upload index.html and the other folder to the S3 bucket.
    <img width="1527" height="434" alt="image" src="https://github.com/user-attachments/assets/774159c3-d4b8-42ac-b025-20cb2f68ee32" />

### Step 3: Configure the Bucket for Static Website Hosting
1. Premission review to confirm that Block all public access is turned off
<img width="2256" height="1119" alt="Screenshot 2026-04-10 160337" src="https://github.com/user-attachments/assets/705f7642-f59d-426b-8faf-dfd039a13e6f" />
 2. Go to the bucket properties in the S3 console.
 3. In the Static website hosting section, click Edit
 4. For Static website hosting, choose Enable.
 5.  For Hosting type, choose Host a static website.
 6.  Set index.html as the Index document.
     ptionally, set a custom error document like error.html.
 < img width="2336" height="310" alt="Screenshot 2026-04-10 160632" src="https://github.com/user-attachments/assets/7f5a82b0-ac2c-43d4-9abe-e836af13415f" />
 <img width="2166" height="1051" alt="Screenshot 2026-04-10 160732" src="https://github.com/user-attachments/assets/91811a1c-4e4c-42c2-b7cf-b52027c1ca56" />
### Step 4: Confirm the Static Website is Created
 <img width="2006" height="382" alt="Screenshot 2026-04-10 160806" src="https://github.com/user-attachments/assets/bf8bf624-b38c-461d-96bc-433b754bcf4f" />

##Preview:
<img width="2499" height="834" alt="Screenshot 2026-04-10 160925" src="https://github.com/user-attachments/assets/34933b7c-5fc5-48dc-aac4-4069b4e086c5" />








