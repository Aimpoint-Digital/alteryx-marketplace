# AWS Tools User Guide

## Installation Instructions

1. Download the AWS tools.yxi file from the Alteryx Marketplace, here.

2.  Run the AWS Tools.yxi file to launch the installation. You may
    require admin rights on the machine to complete the installation.

3.  Click ‘Install’ on the 'Tool Installer' window as per image below:

4.  The tools have now been installed and are added to the palette as a
    new tab, typically on the far right of existing tabs as in the image
    below. You may also find the tools using the search bar.

> Click the image below to view a recording of how to install the tools.

[![AWS Tools Installation Guide](https://github.com/Aimpoint-Digital/alteryx-marketplace/blob/a96277c2615c2f504bc8126fb4ee3e395609f8f2/aws-tools/supporting-files/AWS%20Tools%20Installation%20Guide.png)](https://aimpointdigital.sharefile.com/d-s2b239fc6a540481da0b6d133dab3535f "AWS Tools Installation Guide")

## AWS Authentication

In order to authenticate with AWS users will need to generate an access key and secret. This can be done by following [this guide.](https://aws.amazon.com/blogs/security/wheres-my-secret-access-key/)

Below is a table of the required permissions for the identity you are using within AWS in order to use each tool.

| Tool      | Operation |
| ----------- | ----------- |
| Amazon S3 List      | s3:ListBucket       |
| Amazon S3 Download   | s3:ListBucket, s3:GetObject        |
| Amazon S3 Upload   | s3:PutObject          |
