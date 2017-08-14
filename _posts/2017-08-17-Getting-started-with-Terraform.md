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
3. Add the location of the Terraform binary to the PATH System Variable by opening Windows Explorer, right click on "This PC/Computer", select Properties -> Advanced System Settings -> Environment Variables. 
4. In the "System variable" box scroll down, select PATH and choose edit. 
5. Add the directory to the end of the PATH variable. 
6. If you have a Command Prompt or Powershell console open, they'll need restarting to recognise the amended PATH variable.

To verify the installation of Terraform was successfull open a Command Prompt or Powershell console and enter terraform -v

<p align="center"> 
<img src="https://raw.githubusercontent.com/ukpdb111/ukpdb111.github.io/master/images/tf_verify.jpg">
</p>
