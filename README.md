# S3_static_website
My first basic S3 static website project
# Static Website Hosting with Amazon S3

This project demonstrates how to host a static website using **Amazon S3** as part of a DevOps learning task.

## 🚀 Project Goals

- Understand how S3 buckets work
- Upload and manage static files (`index.html`, `error.html`)
- Set permissions and bucket policies for public access
- Enable static website hosting
- Access the site through a public S3 endpoint

## 📂 Files

- `index.html`: Main page of the website
- `error.html`: Custom error page shown for 404 errors (optional)

## 🌐 Live Website

> Once deployed, the site is accessible at the S3 static website endpoint URL.

Example:
http://my-static-site-1310.s3-website.ap-south-1.amazonaws.com/


## 🛠️ Steps to Deploy

1. Create an S3 bucket and disable "Block all public access"
2. Upload `index.html` (and `error.html`)
3. Add a bucket policy to make files public
4. Enable static website hosting under bucket properties
5. Access the website via the given S3 endpoint

## 📘 Technologies Used

- AWS S3
- HTML/CSS
- GitHub for version control

## 📌 Notes

- This project is for learning purposes only.
- Do not store sensitive information in public buckets or repos.

## 🙌 Author

G S G SUDARSHAN – DevOps Learner
