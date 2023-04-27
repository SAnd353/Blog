---
title: "Lesson 1 Hacks"
description: "Hacks for lesson one"
layout: post
toc: true
---

# KASM hacks
- Virtual desktops like those created with KASM could allow us to flexibly access backends for AP CSP. This could greatly streamline DevOPs work. Furthermore, virtual desktops could provide a way for us to safely test applications.
# AWS Database Hacks
## Quiz 1
- Q1: C
- Q2: A
- Q3: C

## Quiz 2
- Q1: C
- Q2: D
- Q3: C
# DuckDNS and AWS HACKS

| DuckDNS Pros | DuckDNS Cons |
| ------------ | ------------ |
| Free | limited to duckdns.org domains |
| Simple | limited customizability for end user |

![DuckDNS diagram]({{ site.baseurl }}/images/duckdnsdiagram.png)
- AWS is a cloud-computing service
- AWS gives us options for creating backends that are always active
- We use DNS to hide IP addresses and to make easy-to-remember website names. DuckDNS provides a dynamic DNS service where users can use DuckDNS domains and map them to IP addresses. DuckDNS is unique in providing this service for free. DuckDNS is useful in our projects because it allows us to use domain names wihtout spending money. Setting up DNS is very simple. You simply need to make an account and then claim a domain and map it to an IP address of your chosing.
- I don't have anything to say regarding outdated Nginx/Docker functionalities that may need to be addressed. However, in regards to confusion in the deployment process, I'd like to mention that the template for the Nginx file in the newest deployment guide doesn't work. The quotes it uses aren't standard quotes (") but rather special left and right quotes. I brought this up in Slack, but I don't know if the deployment guide has been updated at all.
![Lighttpd vs. Nginx]({{ site.baseurl }}/images/lighttpdvsnginx.png)
```Hello, steven running /home/steven/anaconda3/bin/python
You will be asked 11 questions.
Are you ready to take a test! Press Enter key to begin. Best of luck :)

Question 1 : What does Domain Name Server represent?
DNS
DNS is correct! Good Job!
Question 2 : What does this Represent: Amazon Web Services, which is a cloud computing platform provided by Amazon.
AWS
AWS is correct! Good Job!
Question 3 : What is the first Step to setting up an AWS Server? 1: Connecting to a Ubuntu EC2 Instance, 2: Start updating the system, 3: Clone the repository which one wishes to deploy, 4: Run the command: main.py to start the project
1
1 is correct! Good Job!
Question 4 : What is the third Step to setting up an AWS Server? 1: Connecting to a Ubuntu EC2 Instance, 2: Start updating the system, 3: Clone the repository which one wishes to deploy, 4: Run the command: main.py to start the project
3
3 is correct! Good Job!
Question 5 : What is the fourth Step to setting up an AWS Server? 1: Connecting to a Ubuntu EC2 Instance, 2: Start updating the system, 3: Clone the repository which one wishes to deploy, 4: Run the command: main.py to start the project
4
4 is incorrect! Better Luck next time.
Question 6 : What is the second Step to setting up an AWS Server? 1: Connecting to a Ubuntu EC2 Instance, 2: Start updating the system, 3: Clone the repository which one wishes to deploy, 4: Run the command: main.py to start the project
3 
3 is incorrect! Better Luck next time.
Question 7 : What files are you supposed to edit after finishing the first steps of setting up the server and cloning it within the AWS Server? 1: Edit the docker files and docker.yml, 2: Edit the main.py file to change the characteristcs.
1
1 is correct! Good Job!
Question 8 : What is the first step to setting up a DuckDNS Server? 1: Sign in with your DuckDNS account using Github, 2: Configure current ip to the IP address that you want to access and click update ip button , 3: Create the subdomain, 4: Access site by typing in subdomain.duckdns.org
1
1 is correct! Good Job!
Question 9 : What is the second step to setting up a DuckDNS Server? 1: Sign in with your DuckDNS account using Github, 2: Configure current ip to the IP address that you want to access and click update ip button , 3: Create the subdomain, 4: Access site by typing in subdomain.duckdns.org
3
3 is correct! Good Job!
Question 10 : What is the third step to setting up a DuckDNS Server? 1: Sign in with your DuckDNS account using Github, 2: Configure current ip to the IP address that you want to access and click update ip button , 3: Create the subdomain, 4: Access site by typing in subdomain.duckdns.org
2
2 is correct! Good Job!
Question 11 : What is the fourth step to setting up a DuckDNS Server? 1: Sign in with your DuckDNS account using Github, 2: Configure current ip to the IP address that you want to access and click update ip button , 3: Create the subdomain, 4: Access site by typing in subdomain.duckdns.org
4
4 is correct! Good Job!
steven you scored 9/11
Total Percentage: 81.82%
```

# Certbot hacks
- ## OpenSSL security features vs LibreSSL security features
    - OpenSSL/LibreSSL have recently been dealing with a vulernability that would allow for DOS attacks
    - CVE-2022-3786 and CVE-2022-3602

### I have 2 sections complete and the other two half complete (2+0.5+0.5/4)