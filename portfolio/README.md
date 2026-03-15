# AWS Static Website Deployment

## Project Overview
This is a static website deployed using AWS services, showcasing a real-world DevOps deployment workflow. The website is hosted on Amazon S3 and delivered globally via CloudFront CDN for high performance.

## Live Site
[View Live Website](https://d1an60uo5pzemb.cloudfront.net/)

## Architecture
- **Amazon S3**: Used for static website hosting
- **Amazon CloudFront**: Global content delivery network for fast load times
- **EC2 (Ubuntu)**: Used for initial setup and file management
- **GitHub**: Repository for source code and version control

## Technologies Used
- HTML, CSS
- AWS S3
- AWS CloudFront
- AWS EC2
- Git & GitHub

## Features
- Fully static website hosted on AWS S3
- Global delivery through CloudFront CDN
- Version control and source code management via GitHub
- Clean DevOps workflow with server-side file management

## Project Highlights
- Deployed website accessible via a secure URL
- Followed DevOps best practices: source control, cloud deployment, and CI/CD-ready workflow
- Hands-on experience with AWS services

## Getting Started
If you want to deploy a similar project:
1. Create an S3 bucket and enable static website hosting
2. Upload your website files to S3
3. Configure CloudFront distribution pointing to the S3 bucket
4. Update DNS if using a custom domain
5. Keep sensitive data like API keys out of the repository

## Notes
- Large files in the repo may require Git LFS
- Secrets and API keys are **never committed** to the repository
