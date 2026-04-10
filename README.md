# AWS S3 Static Website Hosting

![Project Banner](https://github.com/user-attachments/assets/c2281b12-ec60-4dbe-8c09-340281c6f1e8)

## Overview
This project demonstrates how to host a static website using **Amazon S3** as part of the **AWS Cloud Quest - Cloud Practitioner** course. The website is publicly accessible via a URL provided by S3.

## Features
- **Static Website Hosting** — Accessible via a public URL provided by S3
- **Custom Error Pages** — Configured custom error pages for a better user experience
- **Access Management** — Implemented S3 Bucket Policies and ACLs to control public access

## AWS Services Used
- Amazon S3

---

## Setup and Deployment

### Step 1: Create an S3 Bucket
1. Search for **S3** in the AWS Console

![Search S3](https://github.com/user-attachments/assets/ef1cbc42-b9a1-476b-a912-df54028b7d50)

2. Click **Create Bucket**

![Create Bucket](https://github.com/user-attachments/assets/045f1914-cd5a-4002-9943-a7ded0a84f32)

3. Under **Object Ownership**, select **ACLs enabled**
   - This allows fine-grained control over permissions of individual objects in the bucket

---

### Step 2: Upload Website Files
1. Upload `index.html` and any other folders/files to the S3 bucket

![Upload Files](https://github.com/user-attachments/assets/774159c3-d4b8-42ac-b025-20cb2f68ee32)

---

### Step 3: Configure Static Website Hosting

1. Go to the **Permissions** tab and confirm **Block all public access** is turned **OFF**

![Public Access](https://github.com/user-attachments/assets/705f7642-f59d-426b-8faf-dfd039a13e6f)

2. Go to the **Properties** tab and scroll to **Static website hosting**
3. Click **Edit** and set the following:
   - Static website hosting: **Enable**
   - Hosting type: **Host a static website**
   - Index document: `index.html`
   - Error document: `error.html` (optional)

![Enable Hosting](https://github.com/user-attachments/assets/7f5a82b0-ac2c-43d4-9abe-e836af13415f)

![Hosting Config](https://github.com/user-attachments/assets/91811a1c-4e4c-42c2-b7cf-b52027c1ca56)

---

### Step 4: Confirm Website is Live

![Website Live](https://github.com/user-attachments/assets/bf8bf624-b38c-461d-96bc-433b754bcf4f)

---

## Preview

![Website Preview](https://github.com/user-attachments/assets/34933b7c-5fc5-48dc-aac4-4069b4e086c5)
