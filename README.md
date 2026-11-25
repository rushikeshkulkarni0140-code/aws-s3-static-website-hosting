# ☁️ AWS S3 Static Website Hosting – Cloud Portfolio

## 📌 Project Overview

This project demonstrates how to host a static portfolio website using **Amazon Simple Storage Service (Amazon S3)**.

I created an S3 bucket, uploaded website files, enabled static website hosting, configured public access, and troubleshooted a 403 Forbidden error to make the website publicly accessible.

## 🚀 Live Website

🔗 [Visit My AWS S3 Portfolio](http://rushikesh-cloud-portfolio-2026.s3-website-ap-southeast-2.amazonaws.com)

## 🎥 Project Demo

▶️ [Watch My AWS S3 Portfolio Demo](https://github.com/rushikeshkulkarni0140-code/aws-s3-static-website-hosting/blob/main/S3%20Portfolio%20Demo.mp4)

## 🛠️ AWS Services & Technologies Used

- Amazon S3
- S3 Static Website Hosting
- Bucket Policies
- Access Control Lists (ACLs)
- HTML
- AWS Management Console

## ⚙️ Project Implementation

1. Created an S3 bucket named `rushikesh-cloud-portfolio-2026`.
2. Selected AWS Region `ap-southeast-2` (Asia Pacific – Sydney).
3. Uploaded website files, including `index.html` and supporting assets.
4. Enabled static website hosting and configured `index.html` as the index document.
5. Configured public access and object-level ACLs to allow public read access.
6. Created and tested an S3 bucket policy with an explicit Deny rule to prevent deletion of `index.html`.
7. Accessed the website using the S3 static website endpoint.

## 📸 Project Screenshots

| No. | Screenshot | View |
|---|---|---|
| 01 | S3 Bucket Creation | [View Screenshot](03-s3-bucket-creation.png.png) |
| 02 | Website Files Upload | [View Screenshot](04-s3-website-files-upload.png.png) |
| 03 | Static Website Hosting Configuration | [View Screenshot](05-s3-static-website-hosting.png.png) |
| 04 | 403 Forbidden Error | [View Screenshot](06-s3-403-forbidden-error.png.png) |
| 05 | Successful Website Deployment | [View Screenshot](screenshots/05-s3-website-deployment-success.png) |

## 🐛 Challenge & Troubleshooting

**Issue:** The website initially displayed a `403 Forbidden – Access Denied` error.

**Root Cause:** The uploaded S3 objects were private by default and did not allow public read access.

**Solution:** Configured the required public access settings and object-level ACL permissions.

**Result:** Successfully resolved the error and made the static website accessible through the S3 website endpoint.

## 📚 Key Learnings

- Creating and configuring Amazon S3 buckets.
- Hosting static websites using Amazon S3.
- Understanding S3 permissions and public access.
- Working with ACLs and bucket policies.
- Troubleshooting 403 Forbidden errors.
- Understanding explicit Deny rules in resource policies.

## 👨‍💻 About Me

**Rushikesh Kulkarni**

Aspiring Cloud Engineer | AWS | Linux | Networking | Cloud Computing

I'm building practical cloud projects to strengthen my AWS skills and develop real-world cloud engineering experience.

---

⭐ If you find this project useful, feel free to explore the repository!
