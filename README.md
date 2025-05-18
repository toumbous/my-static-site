# Static Website CI/CD Pipeline with AWS S3 & CodePipeline

This project demonstrates a complete DevOps workflow for deploying a static website using AWS services.
It includes automatic deployment from GitHub to Amazon S3 using AWS CodePipeline.

## 🔧 Technologies Used
- **AWS S3**: Hosts the static website
- **AWS CodePipeline**: Automates deployment from GitHub
- **GitHub**: Source code repository
- **HTML/CSS**: Front-end of the website

## 🚀 What It Does
Every time you push changes to the `master` branch of your GitHub repository, the AWS pipeline:
1. Pulls the code from GitHub
2. Packages the code into a ZIP
3. Deploys the contents to the configured S3 bucket
4. Automatically updates the live website

## 🌍 Live Demo
[Visit the deployed website](http://your-s3-static-site-url-here)

## 📝 Setup Summary
- Created an S3 bucket with static website hosting enabled
- Set public access and added correct bucket policy
- Connected GitHub via AWS CodePipeline (GitHub App)
- Configured source, skipped build, deployed to S3

## ✅ Benefits
- No manual upload/deploy needed
- Everything updates automatically with a single `git push`
- Great entry-level DevOps portfolio piece

## 📁 Repository Structure
```
/index.html
/css/
/js/
/images/
```

## 🧠 About
This project was built as a hands-on DevOps learning exercise, focusing on automation, CI/CD, and cloud infrastructure.

---
🗓️ Generated on May 18, 2025 by toumbous
