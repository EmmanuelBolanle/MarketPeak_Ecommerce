## Table of Contents

- [Introduction]
- [Deployment_Step]
- [Challenges]
- [Troubleshooting]
- [Acknowledgments]

## Introduction
Welcome to our E-commerce website project

## Deployment Steps
I created a directory for my proeject "MarketPeak_Ecommerce
I downloaded a website template on Tooplate, i extracted the .zip file into my project directory.
I added, commit and push the chnages to my Github repository.
I set up AWSEC2 instance to deploy my website
On my AWS management console, i launched EC2 using Amazon Linux AMI and conncted to the instance vis SSH.
I cloned the repository on Linux Server using HTTPS method than i installed Apache HTTP Server (httpd) to host my website.
I later configured the httpd formy website by clearing the default derictory and replacing with my website file, i then reload to apply changes. 
I was able to access the website by using the EC2 public IP on a browser. 
For continuous integration and depolyment i created a development branch for new features and bug fixes. I then create pull request for code reveiw and merge with the main branch after review is done. Lates changes are pull on the server to reflect the new features and bug fixes. 
The new features and bug fixes are tested to be sure it's working perfectly.

## Challenges 
It was a bit challenging to ectract the download template into my woeking directory, i had to make search and later got assitance i needed.
My second challange was my deployed website not accessible on browser, i had to consult for assitance on slack.

## Troubleshooting
To fix deployed website not showing on broswer, i checked if httpd was running, wity the help of on an instructor i was ble to add port 80 to ec2 instance security.

## Acknowledgments

Thank you for being a part of this Git adventure! Your contributions make the story come alive.
