**Amazon EC2**
![placeholder image](https://github.com/TinoMako/100DaysOfCloud/blob/main/AWS-EC2.png)

# AMAZON ELASTIC COMPUTE CLOUD

## Introduction

✍️ So today l will be creating an EC2 instance then launch it using the AWS Console. EC2 is one of the most popular offering from AWS and l want to know more about it.

## Prerequisite

✍️ General knowledge of a computer and the internet is enough to understand this topic.


## Short Introduction

✍️ Amazon Elastic Compute Cloud(EC2) is a web service that provides secure, resizable compute capacity in the cloud. Knowing EC2 is fundamental to understanding how the cloud works. 

### Step 1 — Creating an Amazon Machine Image(AMI)

I navigated to the the AWS console then typed EC2 into the services section.The next step was to click on Launch instances. After that l had to choose an AMI as shown below.
An AMI is the operating system that will be launced on the server. 

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(56).png)


### Step 2 — Choosing the Instance type

So when we choose an AMI we also have to choose the type of machine. When choosing the type of machine we will be specyfing how powerful we want our machine to be. The options are shown on the image below.

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(57).png)

### Step 3 — Configuring Instance Details
This step has so many options and as shown by the image below we can configure different details. A noteable element that l want to point out is that this where we
can put the user data. This is a question that l have seen a lot in my Practice tests for SAA-C02.

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(58).png)

### Step 4 — Choosing Storage Type

On this step we have to use EBS volumes, these are storage attachments that we have to connect to our instance. Think of this as hard drives for our computer in the cloud. We can also connect instance store which is described as ephemeral. Ephemera means this type of storage will lose data as soon as the instance is stopped or deleted. 

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(59).png)

### Step 4 — Adding Tags

Tags are a very important part of the cloud, they help us to manage, search and filter resources. I watched a very informative video on Youtube about tags by Tieho-The-Engineer, this is the link to the video https://www.youtube.com/watch?v=zcAWYMeTLAE 

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(60).png)

### Step 4 — Configuring Security Groups

l struggled differentiating security groups and NACLs when l was studying for the cloud practitioner but now l think l have firm knowledge of their differences because of more hands on. Security group is a set of firewalls that control the traffic coming in and out of your instances. I created a security group, check the image below

![Screenshot](https://github.com/TinoMako/100DaysOfCloud/blob/main/Screenshot%20(61).png)

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
