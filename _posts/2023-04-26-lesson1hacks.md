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
# Certbot hacks
- ## OpenSSL security features vs LibreSSL security features
    - OpenSSL/LibreSSL have recently been dealing with a vulernability that would allow for DOS attacks
    - CVE-2022-3786 and CVE-2022-3602

### I have 2 sections complete and the other two half complete (2+0.5+0.5/4)