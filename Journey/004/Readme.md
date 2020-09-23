

# How To SSH into an instance 

## Introduction

✍️ I will be continuing from where l left off yesterday. We created our EC2 instance and now we have to figure out how to connect to it. Different operating systems have different ways of accessing instances. Windows 10 users, Linux users and Mac users can use SSH to connect but users of the previous windows before 10 will have to use Putty. Interestingly Windows 10 users can use both Putty and SSH. In this tutorial l will be using Putty even though l am using windows 10, l could have used SSH but l just felt like using Putty. 

## Prerequisite

✍️ Anyone can follow along.

## Try yourself

✍️ SSH is a cool way of allowing a user access to fully control a machine remotely using the command line.

### Step 1 — Downloading Putty

The first thing we have to do is to download Putty. We just type 'Putty' on google and click on the first search result. After downloading we will install Putty which is just straightforward with not much hustle.

![Screenshot](https://user-images.githubusercontent.com/45802047/93952190-88093980-fd48-11ea-9916-fb59c708e370.png)

### Step 2 — Downloading A KeyPair 

When we created our Instance, the consile wizard(??) asked us to download a keypair. What is a Key Pair you might ask. A key pair consists of a public key(stored by AWS) and a private key that a user stores. Together, these keys allow us to connect to our instance securely. 

![Screenshot](https://user-images.githubusercontent.com/45802047/93953095-cacc1100-fd4a-11ea-80ad-9fd8f0509430.png)


### Step 3 — Using the Putty Key Generator

After downloading the Private Key, we will open Putty Key Generator(just search for it on Windows Start) Click on file then load a file, a dialogue file will open asking you to load the Private Key File. At this moment you just locate where the file was saved. This can be tricky just make sure you choose all files in the type section. After locating the key we then save the new coverted file in ppk format. 

![Screenshot](https://user-images.githubusercontent.com/45802047/93952227-a0795400-fd48-11ea-8426-a715916584e4.png)

### Step 2 — Connecting Using Putty 
Our key has been converted, we then open our Putty application and paste in our public key address. In the left panel, we click on SSH then AUTH and load our ppk file. We then save the file and click open. Voila we have connected to our instance!

![Screenshot](https://user-images.githubusercontent.com/45802047/93953095-cacc1100-fd4a-11ea-80ad-9fd8f0509430.png)

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
