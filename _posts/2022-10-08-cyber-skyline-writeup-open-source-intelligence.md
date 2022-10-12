---
title: "Open Source Intelligence"
layout: post
date: 2022-10-08
feature_image: images/cloudnetwork.png
tags: [cyberskyline] [basics] [opensource]
---
Open Source Intelligence is the act of finding and gathering information from public sources on a target. You'll probably be surprised by the amount of information that can be found online with a bit of prodding! OSINT is great because it's typically not very expensive and and can reveal a lot of information about a target. Something to watch out for, however, is fake information that may be posted.
<!--more-->

Some OSINT strategies:
- **Google Dorking** - *a method of fine-tuning Google searches through advanced query searches*
- **Metadata** - *looking at data about the data*
- **Reverse Image Searching** - *searching an image against online databases*
- **Repositories** - *online code repositories*
- **Internet Archive** - *a digital library of the Internet*
- **Profiles** - *looking up information about people*

#### Google Dorking
Google dorking, also called Google Hacking, is a method of fine-tuning Google searches thorugh advanced query searches in order to filter out fluff. Here are some common commands: 

##### Intext & allintext
```
Intext:*usernames*
allintext:*"username" "password"*
```
This command finds specific text. <span style = "color:aqua;">allintext</span> is used to search multiple keywords. 

##### Intitle & allintitle
```
intitle:*"snapchat"*
allintitle:*"ip camera" "dvr"*
```
This command filters results based off their HTML page title. 

##### Inurl & allinurl
```
inurl:capitalone
allinurl:
```
This filters results based off the URL.

##### Filetype 
```
filetype:*log*
filetype:*txt*
```
This command filters files by their filetype. 
