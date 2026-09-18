# AWS Static Portfolio Website

A simple static portfolio website hosted on **Amazon S3** and delivered through **Amazon CloudFront**.

## AWS Services

* Amazon S3
* Amazon CloudFront
* CloudFront Origin Access Control (OAC)

## Architecture

           User
            ↓
       CloudFront
            ↓
           OAC
            ↓
    Private S3 Bucket
            ↓
      portfolio.html

## Features

* Static website hosting
* CloudFront CDN
* Private S3 bucket
* Secure S3 access using OAC
* HTTPS through CloudFront

## Project Structure

AWS-Static-Portfolio/
├── portfolio.html
├── screenshots/
└── README.md

## What I Learned

* S3 static website hosting
* CloudFront distribution
* Origin Access Control
* S3 bucket policies
* CDN concepts
* AWS deployment and testing

## Status

**Completed ✅**
