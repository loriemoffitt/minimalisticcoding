---
layout: post
title:  "How to create a new MongoDB database"
date:   2024-06-11 00:54:09 -0400
categories: homepage
permalink: /2024/06/12/create_mongodb_database.html
author: Lorie Moffitt
---
[Create new account for Mongo DB here](https://account.mongodb.com/account/register)

After creating your account and verifying your email address, log into MongoDB.

After logging in you will see the screen below, lets create a new cluster by clicking the "Create Cluster" button in the middle of the screen. 

![Create a Cluster](https://github.com/loriemoffitt/lessons/blob/main/create_a_cluster.jpg)

Select Advanced Configuration at the bottom of the screen.

![Advanced Config](https://github.com/loriemoffitt/lessons/blob/main/advanced_config2.jpg)

Next select the free Shared button at the top.

![Free Shared](https://github.com/loriemoffitt/lessons/blob/main/free_shared.jpg)

Scroll down and make sure M0 Sandbox is selected.  Click "Create Cluster" at the bottom of the screen. 

![M0 Sandbox](https://github.com/loriemoffitt/lessons/blob/main/m0_sandbox.jpg)

Enter an admin user and password and click "Create User".  

![Create Admin User](https://github.com/loriemoffitt/lessons/blob/main/create_admin_user.jpg)

Your ip address should already be in the list so you can click "Finish and Close" button at the bottom. 

Now, click the ellipses (...) in the middle of the screen to see the drop down menu and select "Load Sample Dataset". 

![Load Sample Dataset](https://github.com/loriemoffitt/lessons/blob/main/load_sample_data.jpg)

Click the button to load the sample data. 

![Load Data](https://github.com/loriemoffitt/lessons/blob/main/load_dataset.jpg)

Verify that the sample dataset is loaded by clicking on the "Collections" tab in the center of the screen and browsing the collections. 

![Verify Data](https://github.com/loriemoffitt/lessons/blob/main/verify_data.jpg)

You are now ready to connect to your data base with a Java application. 
[Click here for the next tutorial](Connect-to-MongoDB-with-Java)
