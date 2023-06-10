# Linux Project: Setting up an Apache HTTP Web Server using Linux to host a Website

## Overview

This project showcases how to apply Linux Server skills in a DevOps project by setting up a web server using Ubuntu Linux and hosting a website. The step-by-step guide provided in this repository will walk you through the entire process, from creating a Ubuntu server on DigitalOcean to configuring Apache web server and testing the website. Whether you're new to DevOps or looking for a tutorial, this guide will help you bring a website to life.

## Skills Covered in This Project

- Linux Server Administration
- Networking Fundamentals
- Cloud Computing
- Infrastructure as Code
- Server Monitoring

## Prerequisites

Before you begin, make sure you have the following:

- A DigitalOcean account (or any cloud provider you prefer)
- Basic understanding of Linux commands and terminal usage
- A domain name for your website (optional, but it adds a professional touch)

## Documentation

Follow the steps below to complete the project:

1. **Step 1: Creating My Ubuntu Server:** Create a new Ubuntu droplet on DigitalOcean, choosing the appropriate configuration. Set up SSH key authentication for a secure remote connection.

2. **Step 2: Connecting to My Server:** Use SSH to connect to your Ubuntu server using the provided IP address. Gain access as the root user using your SSH key or password.

3. **Step 3: Updating the system packages:** Update the system packages by executing the commands "apt update" and "apt upgrade" to ensure you have the latest software updates installed.

4. **Step 4: Installing and Configuring Apache Web Server:** Install the Apache web server by running the command "sudo apt install apache2". Modify the Apache configuration file to specify your Droplet's IP address and set the document root.

5. **Step 5: Enable necessary Apache modules:** Enable the required Apache modules by executing the commands "a2enmod rewrite" and "a2enmod headers". These modules are essential for configuring URL rewriting and managing HTTP headers.

6. **Step 6: Restart Apache:** Restart the Apache web server using the command "sudo service apache2 restart" to apply the configuration changes.

7. **Step 7: Test the Web Server:** Open a web browser and enter your Droplet's IP address in the address bar. If everything is set up correctly, you should see the default Apache landing page.

For a more detailed explanation of each step, please refer to the [Medium blog post](https://medium.com/@michaelobasa2/2-linux-project-setting-up-an-apache-http-web-server-using-linux-to-host-a-website-d83fefe148be).

## Conclusion

Setting up a web server using Linux to host your website is a creative and empowering option worth exploring. This project allows you to showcase your skills, express your vision, and connect with the world. Follow the step-by-step guide provided in the blog post and let your website do the talking on the digital stage.

Happy hosting!
