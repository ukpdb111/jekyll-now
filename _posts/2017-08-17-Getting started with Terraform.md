---
layout: post
title: Installing Terraform on Windows
comments: true
categories: [Terraform]
published: true
---
The installation of Terraform is very simple. It requires the downloading of a zip archive, extracting the binary from the archive then adding the location of the extracted binary to the PATH variable.

Step by step for Windows:

1. Download the latest version from [Terraform Downloads](https://www.terraform.io/downloads.html).
2. Extract the binary from the archive into a directory of your choice. 
3. Add the location of the Terraform binary to your PATH variable on Windows by opening Windows Explorer, right click on This PC, and selecting Properties -> Advanced System Settings -> Environment Variables. 
4. In the "System variable" box scroll down, select PATH and choose edit. 
5. Add the directory to the end of the path variable WITHOUT spaces. 

To verify the installation of Terraform was successfull open a command or Powershell console and enter Terraform -v

Inline-style: 
![alt text](images/tf_verify.jpg "Verify Terraform has installed successfully")

That's it.
