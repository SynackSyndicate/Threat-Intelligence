---
description: Searching malicious files that are being sent through email attachments
---

# SOC143 - Password Stealer Detected

## Capturing and Parsing Data

Lets get straight to the point shall we.

![Choose an Investigation ](<../../../../.gitbook/assets/1 (1).png>)

_( \* next to the the name indicate this attachment was actually used in a real life cyber attack)_

![Event has been created](../../../../.gitbook/assets/2.png)

&#x20;Our next window prompts us what we should take into account.

![Gather Intel on the email, sender, and recipient](../../../../.gitbook/assets/4.png)

These questions are important to ask yourself when deciphering potential threats to you and your organization. Placing yourself into that mindset early on can not only save you time, but also prepare yourself to have an effective and clear objective into Incident Response and Handling these situations.

### The Process

Once we prepare ourselves with what we should look out for, we begin digging in and dissecting who the sender is, what they had sent, and how it affected the recipient.

![See who the source is](<../../../../.gitbook/assets/5 (1).png>)

_(Its important to note when using LetsDefend.io, you should have multiple tabs open)_

We find the source sender and then we go into our mailbox to find what they had sent.

![](../../../../.gitbook/assets/6.png)

![](<../../../../.gitbook/assets/7 (1).png>)

After viewing the file, the user bill@microsoft.com has sent a .zip file to our user ellie@letsdefend.io

### Analyzing the Data

The next question requests that we download the zip file and analyze the contents of it.

![](../../../../.gitbook/assets/9.png)

![VirusTotal FTW](../../../../.gitbook/assets/10.png)

As you can see we're given 6 Malicious files attached within this .zip file.&#x20;

![Mail has been delivered to user](<../../../../.gitbook/assets/11 (1).png>)

![Deletion of malicious mail from Bill](../../../../.gitbook/assets/12.png)

#### Containment and Incident Response Process

![Time to contain](../../../../.gitbook/assets/13.png)

The reason for containment is to block the user from doing any more damage. We wouldn't want to leave his user account unchecked. In doing so, we are allowing this user to keep on sending malicious mail to users within our organization.

![Quarantined...(too soon?)](../../../../.gitbook/assets/14.png)

![](../../../../.gitbook/assets/15.png)

Completed! The playbook is fairly user friendly once you get used to it. This simple and user friendly interface not only asks players the bigger questions, but it also gets us into the mindset of a SOC Analyst / Incident Responder/Handler as well.

![Case Closed Watson!](../../../../.gitbook/assets/16.png)

Another one for the books Watson.

![](https://media.giphy.com/media/26gJzdwIgfiDBChDa/giphy.gif?cid=ecf05e472a6u4nslzk315b6p10uke5soquunvnqv3n9su1k5\&rid=giphy.gif\&ct=g)

