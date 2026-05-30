---
description: >-
  Write-ups regarding my experience with the platform, the "a-ha" moments, and
  how this simulates a SOC's mindset
---

# SOC-146 - Phishing - Mail - Detection.

Lets dive in into my first (_second)_ investigation!

## Investigation

![Prompted which Project/Investigation you want to take ownership of](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 8.44.30 AM.png>)

After you sign up, you're given options of which logs you would like to take over. From left to right you see the severity of the issue, and to the right you see the type of damage it is.

For the sake of this write-up well be doing SOC-146 - Phishing - Mail - Detection.

Next you're given a series of prompts and questions that you answer regarding the scenario you're given. A few of these answers are pretty straight forward like (whats the ip of the attackers address). Others you have to play around the platform to understand what's actually happening in your investigation.&#x20;

![Phishing Mail](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 8.56.46 AM.png>)

Since my investigation prompted a phishing mail it gave me an overview of what is going on. \
\
\* _On a side note this is where I goofed up on my first investigation. I wasn't thinking big picture, or as an overseer. That and getting accustomed to the platform. You'll see my failed attempt in the end_

You see here that an email has been sent to Lars. We download the file (_yes actually download the file to your desktop)_ because you'll be prompted to run it on a scanner.

![Choose A Scanner (super smash announcer voice)](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 9.09.34 AM.png>)

LetsDefend prompts the next step where you choose a scanner to investigate the .zip file you just downloaded. I personally went with VirusTotal.

![](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 8.57.39 AM.png>)

We uploaded the .zip file to VirusTotal and we were informed that there are malicious codes within this file.&#x20;

The next question asked if this file was either false-positive or true-positive. _I know I know, I read this in Sec+ but my logic always goofs me._&#x20;

![Total noob move](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 9.10.07 AM.png>)

After creating the playbook you're finished!&#x20;

![That low severity fail though](<../../../.gitbook/assets/Screen Shot 2021-08-18 at 9.11.04 AM.png>)

_Viola!_&#x20;

### So what did we learn

LetsDefend.io gives a fresh and new taste _(for me)_ on what a SOC Analyst does on their day-to-day. Monitoring alerts, investigating the root, and how to respond and create a repair for it. I will definitely continue to do more Investigations through this platform due to the simplicity of it.
