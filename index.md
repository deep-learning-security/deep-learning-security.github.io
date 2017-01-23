---
layout: page
title: Deep Learning Security Workshop
---

# Overview

Deep learning has made huge advances and impact in many
areas of computer science such as vision, speech, NLP, and
Robotics. Many exciting research questions lie in the
intersection of security and deep learning.

**First**, how will these deep learning systems behave in the
presence of adversaries? Research has shown that many of the
state-of-the-art deep learning systems can be easily fooled by
adversarial examples. We will explore fundamental questions in
this area including what types of attacks are possible on deep
learning systems, why they exist, and how we can defend
against them.

**Second**, how can deep learning techniques help security
applications? We will explore this area and study example
security applications using deep learning techniques including
program binary analysis, password security analysis, malware
detection and fraud detection

For more information, [sign up on the mailing list](https://groups.google.com/d/forum/deep-learning-security).

# Schedule

**Feb 19**

**9:00 - 9:10am** - Overview of the workshop. *Dawn Song.*

**9:10 - 10:10am** - Introduction and overview of deep learning and security. *Dawn Song.*

**10:10 - 10:30am** - Break

**10:30 - 12:00** - Introduction and overview of adversarial deep learning. *Chang Liu and Dawn Song.*

**12:00 - 1:00pm** - Lunch

**1:00 - 2:00pm** - Invited talk: [Machine Learning in Computer Security for Fun and Profit: Password Meters, Face Recognition and Online Tracking](#machine-learning-in-computer-security-for-fun-and-profit-password-meters-face-recognition-and-online-tracking). *Lujo Bauer.*

**2:00 - 3:00pm** - Invited talk: [Discover Maliciousness Among URLs: A Deep Learning Approach](#discover-maliciousness-among-urls-a-deep-learning-approach). *Zhifeng Geng and Xiaodong Su.*

**3:00 - 3:30pm** - Break

**3:30 - 5:00pm** - Hands-on lab. *Chang Liu and Jernej Kos.*

**5:00 - 5:00pm Feb 20** - Hackathon

<br/>

# Invited Talks

#### Machine Learning in Computer Security for Fun and Profit: Password Meters, Face Recognition and Online Tracking

**Abstract:** This talk will discuss three ongoing projects that together show how
machine learning can help us stay more secure online, but also how it
could be used by attackers.

First, we show that state-of-the-art face-recognition algorithms
are vulnerable to physically realizable and inconspicuous attacks,
which allow an attacker to evade recognition or impersonate another
individual.  We develop a systematic method to automatically generate
such attacks, which are realized through printing a pair of eyeglass
frames.

Second, we harness neural networks to model the strength of text
passwords. To prevent users from creating weak passwords, we must
detect such passwords at creation; unfortunately, existing methods for
measuring password strength are too inaccurate or too inefficient for
this. We show how a neural network can be trained to accurately and
quickly measure password strength and then shrunk to fit in a web page
for easy deployment.

Third, we revisit exactly what makes people comfortable (or not) with
online tracking. We show that understanding this in detail makes it
feasible to use classifiers to selectively stop unwanted online
tracking while still allowing its beneficial uses.

**Author bio:** *Lujo Bauer* is an Associate Professor in the Electrical and
Computer Engineering Department and in the Institute for Software Research at
Carnegie Mellon University. He received his B.S. in Computer Science from Yale
University in 1997 and his Ph.D., also in Computer Science, from Princeton
University in 2003.

Dr. Bauer's research interests span many areas of computer security and privacy,
and include building usable access-control systems with sound theoretical underpinnings,
developing languages and systems for run-time enforcement of security policies on
programs, and generally narrowing the gap between a formal model and a practical,
usable system. His recent work focuses on developing tools and guidance to help users
stay safer online.

Dr. Bauer recently served as the program chair for the flagship computer security
conferences of the IEEE (S&P 2015) and the Internet Society (NDSS 2014) and is an
associate editor of ACM Transactions on Information and System Security.

#### Discover Maliciousness Among URLs: A Deep Learning Approach

**Abstract:** Malicious web sites are one of the cornerstone of cyber criminal actions.
It is estimated that there are nearly 1 billion malicious URLs, and more than 100 of
billions YUAN economic damage was brought by these URLs.

Effective and efficient technique is urgently required for detecting task. Recently,
surprising advances are made by deep learning in tasks like speech recognition, machine
translation, autonomous driving, and Go playing. This greatly inspires us to transfer
deep learning technique into well-defined detection problems in security. Many machine
learning frameworks are proposed to detect URLs while seldom based on deep learning.

In this talk, we will give a gentle introduction on how deep neural networks work for
malicious URL detection in production environment, using both text and image features.
And we will also give some thoughts on practical threat intelligence system construction,
model adversary in URL detection and AI+Security. 

**Author bio:** *Zhifeng Geng* leads the Cloud Detection team in Baidu Security. He mainly
focuses in the Threat Intelligence construction and application. He is an expert of
detecting different types of Internet abuses including malicious URLs, SMS, harassing
phone numbers, fake-WiFi, as well as website vulnerabilities. He is leading the efforts
building and providing Threat Intelligence services to many enterprise customers and
Baidu's own businesses.
 
*Xiaodong Su*, staff software engineer at Baidu, joined Baidu Security in March 2015. He has
more than 5 years' experiences applying machine learning and big data technology in
security area. He is focusing in detecting malicious webpages by machine learning,
especially deep learning technologies.

