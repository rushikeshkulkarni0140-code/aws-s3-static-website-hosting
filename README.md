# ☁️ Host a Static Website on Amazon S3.

**Project by:** Rushikesh Kulkarni.  
**Date:** November 2026.  
**AWS Service:** Amazon S3.  
**Project Type:** Cloud Computing | Static Website Hosting.

---

## 📌 1. Project Overview.

In this hands-on project, I hosted a static website using **Amazon Simple Storage Service (Amazon S3)**.

The main objective was to create an S3 bucket, upload website files, configure static website hosting, and make the website publicly accessible through an S3 website endpoint.

Throughout this project, I gained practical experience with AWS storage, website hosting, access permissions, and bucket security policies.

## 🛠️ 2. Tools and Technologies.

The following AWS services and concepts were used in this project.

• **Amazon S3:** Used to store website files and assets in cloud-based object storage.

• **Static Website Hosting:** Configured an S3 bucket to host a static website and generate a public website endpoint.

• **AWS Regions:** Used the Asia Pacific (Sydney) region (`ap-southeast-2`) for the S3 bucket.

• **Access Control Lists (ACLs):** Managed object-level permissions to make website files publicly accessible.

• **Block Public Access:** Configured public access settings to allow visitors to access the website.

• **S3 Bucket Policies:** Created a custom JSON bucket policy using an explicit Deny rule to protect important website files.

## ⏱️ 3. Project Duration and Achievements.

**Total time taken:** Approximately 30–45 minutes.

During this project, I successfully completed the following tasks.

• Created a globally unique Amazon S3 bucket.

• Uploaded HTML files and website assets.

• Enabled static website hosting.

• Configured object-level permissions using ACLs.

• Identified and resolved a 403 Forbidden error.

• Created a custom S3 bucket policy.

• Tested the bucket policy to verify file deletion protection.

## 🚀 4. Creating an Amazon S3 Bucket.

### What I Did.

• Opened the AWS Management Console.

• Navigated to the Amazon S3 service.

• Created a new S3 bucket to use as cloud storage for my static website files.

### Time Taken.

Creating the bucket took less than 10 seconds. AWS provisioned the storage space almost immediately after I submitted the configuration.

### AWS Region Selection.

• Selected the **Asia Pacific (Sydney)** region.

• Used the region code `ap-southeast-2`.

• Kept the default region selected for my account during bucket creation.

### Understanding Bucket Name Uniqueness.

• Learned that Amazon S3 bucket names must be globally unique across AWS accounts and Regions.

• Understood that each bucket requires a unique name.

• Learned that a bucket can be accessed through its corresponding S3 endpoints.

---

**Key Learning:** I learned how to create an S3 bucket, select an AWS Region, and understand the importance of globally unique bucket names.

![How I Set Up an S3 Bucket](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_ba6d42ad)

## Upload Website Files to S3.

### What I Did in This Step.

• Downloaded the `index.html` file and the website's image files to my local computer.

• Uploaded the website files into my Amazon S3 bucket.

• Stored all the website content files in cloud storage so they can be accessed by visitors.

### Files I Uploaded.

• **index.html:** Uploaded the main HTML file, which provides the structural blueprint of my webpage.

• **Assets Folder:** Uploaded the unzipped assets folder containing images and media files for my `rushikesh-cloud-portfolio-2026` portfolio website.

### How the Files Work Together.

• **index.html:** Provides the core structure and code of the webpage.

• **Assets Folder:** Contains the images and other files referenced by the HTML code.

• **Why Both Are Needed:** Both the HTML file and the assets folder are required because the webpage cannot display its portfolio images and other referenced content correctly if the required asset files are missing from the S3 bucket.

![Upload Website Files to S3](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_a265af88)

## Static Website Hosting on S3

### What I did in this step

In this step, I will enable static website hosting on my Amazon S3 bucket and set index.html as my index document. I am doing this to convert my S3 storage bucket into a web server that can generate a unique public endpoint URL for visitors to access my portfolio website.

### Understanding website hosting

Website hosting means storing your website's files—like HTML documents, CSS files, images, and other assets—on a secure web server connected to the internet. This allows anyone around the world to access and view your website by entering its web address into a browser.

### How I enabled website hosting

I enabled hosting by opening my Amazon S3 bucket in the AWS Console, navigating to the Properties tab, and scrolling down to the Static website hosting section. I clicked Edit, selected Enable, specified index.html as the index document, and saved my changes.

### Access Control Lists (ACLs)

An Access Control List (ACL) is a set of rules that defines who has permission to access and manage files inside an S3 bucket. In this step, I enabled ACLs so that I can control access permissions for my individual website files and make them publicly accessible to visitors.

![Static Website Hosting on S3](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_c22c54c0)

## Bucket Endpoints

### Understanding bucket endpoint URLs

When I first visited the bucket endpoint URL, I saw a 403 Forbidden error page. The reason for this error is that all files uploaded to Amazon S3 are private by default to keep the account secure. Since we have not made our HTML and image files public yet, S3 blocks us from viewing them.

### What I saw when I tested the endpoint

I saw a 403 Forbidden error page displaying an 'Access Denied' message. This happened because Amazon S3 keeps all uploaded files private by default to maintain cloud security, so public access to our website files is blocked until we explicitly configure permissions to make them public.

![Bucket Endpoints](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_22ce4daf)

## Success!

### What I did in this step

In this step, I will make the uploaded website files public using object-level Access Control Lists (ACLs). I am doing this to resolve the 403 Forbidden error and allow visitors to successfully load and view my portfolio website over the internet.

### How I resolved the 403 error

I resolved the 403 Forbidden error by going to the Objects tab inside my Amazon S3 bucket. I selected both the index.html file and the assets folder, clicked the Actions dropdown menu, selected Make public using ACL, and clicked Make public to confirm the changes.

### ✅ What were the key services and concepts you learnt in this project?

In this project, I learned how to use key cloud services and security configurations to host a web application. The core services and concepts include:

Amazon S3: Storing website assets in a cloud-based object storage service and understanding the requirement for globally unique bucket naming.

Static Website Hosting: Configuring S3 to act as a lightweight web server and generating a public bucket website endpoint URL.

AWS Regions: Learning how regional selection (such as Sydney ap-southeast-2) impacts latency, performance, and website load speeds for local users.

Access Control & ACLs: Resolving 403 Forbidden errors by disabling Block Public Access settings and using object-level Access Control Lists to safely expose files to the public.

S3 Bucket Policies: Writing JSON policies to implement granular security rules, utilizing explicit Deny effects, and leveraging the wildcard (\*) character to manage permissions globally or protect entire directories.

### ✅ How long did it take you to complete this project?

It took me approximately 30 to 45 minutes to complete this entire project. This time was spent creating and configuring the Amazon S3 bucket, downloading and uploading my portfolio files, enabling static website hosting, resolving the 403 Forbidden error, and writing a custom JSON bucket policy for the secret mission.


![Success!](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_5d4474f9)

## Bucket Policies

### What I did in this extension

In this secret mission, I am going to set up a custom S3 bucket policy that explicitly denies anyone—including myself—from deleting the index.html file. I am doing this to learn how to write JSON-based access policies, which provide much more granular security and control over bucket resources than standard ACLs.

### Understanding bucket policies

In this secret mission, I am going to set up a custom S3 bucket policy that explicitly denies anyone—including myself—from deleting the index.html file. I am doing this to learn how to write JSON-based access policies, which provide much more granular security and control over bucket resources than standard ACLs.

![Bucket Policies](https://nextwork.ai/rushikesh-kulkarni/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_sm2sm2sm)

### What my bucket policy does

My bucket policy uses an explicit Deny effect with a wildcard principal ("Principal": "\*") to ensure that the delete restriction applies to all users globally. While targeting ( index.html )protects that specific file, using a wildcard resource ending in ( /\* ) would block the deletion of every file in the bucket to protect all my portfolio assets at once. I successfully verified this policy in action by attempting to delete my file, which AWS immediately blocked with a 'Failed to delete' Access Denied error.
