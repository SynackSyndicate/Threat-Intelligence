# IR Review



{% embed url="https://www.youtube.com/watch?v=NmoPUPdTso8" %}
Totally new to video content development&#x20;
{% endembed %}

**Disclaimer**&#x20;

**I have not had any formal IR jobs, nor any cybersecurity jobs when creating this video. My experiences come from personal cybersecurity tinkering, CTFs, and on my own learning.  My approach to this pathway is to show new comers the trials of it, and veterans how powerful it can be.**

### **Approach**

Understand that I do not have any formal IR training whatsoever, so this review is completely coming from a "fresh meat" perspective. Jumping right in we're given an Alert that has been monitored that Tier 1 SOCs aren't able to conclude. These alerts are rated from Low to High severity.&#x20;

### Into the Thick of It

If you watch the video above you'll see some impressive Linux directory manipulation and findings (_kidding!)_ Coming from a newbie, it was difficult to assess what the question was being asked or how to find it. (LetsDefend does have an Academy, which we'll look over as well) However, with the obscure objectives, and no clear linear trajectory, it is difficult to know what to put in into the playbook. Playbooks are used to determine what the IR found, discovered artifacts, and how to remediate the incident. Think P . I . C . E . R . L. or Protection, Identification, Containment, Eradication, Recovery, and Lessons Learned

At times, I've had to go back and re-read the hints, and notes left from the T1 to actually try to understand what is being asked of me, how can I get there, is that really the answer, and so on. While I got lost into understanding the question and how IRs think, maybe you didn't and that leads us to our next topic.

After bombing my Alert, we are fortunate enough to be given a walkthrough at the end. THANK YOU! This totally helps out new players like myself. Without it, we would be left discouraged, and unsure if cybersecurity no less IR is the right career for us. From the writeup we can learn how to approach this alert, how understand the thought process - as to why the IR would do it this way, possible artifacts, and how to properly fill out the playbook!

This was taken from my text to Gunal the founder of Letsdefend.

1. I might suggest having a TryHackMe approach to the alerts. Its hard for newcomers like myself to know what they are looking for. If you include a step-by-step question to answer list then it will help new players obtain that train of thought to look for.
2. _\[_&#x31;:49 P&#x4D;_]_&#x46;or example I just finished the SOC 151 unauthroized root access.
3. _\[_&#x31;:50 P&#x4D;_]_&#x49; had no idea I had to open up Jacks email to system admin
4. _\[_&#x31;:50 P&#x4D;_]_&#x4D;aybe include the question in the playbook, what was the password that Jack sent to System Admin?

### Appreciation

First of all I would want to give a round of applause to Letsdefend.io. Not only are they switching up the game, but they are -- to my knowledge -- the only platform to give a gamified IR. Both in Linux and in Windows. During the investigation, you're caught wondering what exactly you're trying to find. It is too much of a free for all for beginners like myself. And thats not necessarily a bad thing; but if users have too much open play and no direct questions being asked through the investigations, we get lost in translation.  Questions that could help point the IR to the right direction is key into shaping the IRs of tomorrow. Their hard work, dedication, and hardware integration have been coming through. What I can say that to have an open Linux terminal dedicated on your browser is amazing. Their platform offers a SOC / IR environment that puts players in the headspace, that you are actually working the tickets brought to your attention. LetsDefend Io encapsulates your mind and places into a real working SOC.



### Review & Considerations

From my experience on LetsDefend IR Pathway there are a lot of things to consider. Being a novice - intermediate player in the cybersecurity field it was still difficult for me to comprehend what were the questions being asked. From the start of the playbook, to the end, there were missing gaps of knowledge that failed to have me connect the dots. Things I might suggest to help improve player to application playability/ learnability

* User and platform relationship (i.e, having a clear set of answerable questions)
* Have a specific layout or Rules of Engagement (_yes I know thats red team)_ but it will definitely help the scope of new coming Incident Responder players
* Create a rubric before hand so players know exactly what they're looking for
* More Readme.txt hints.
