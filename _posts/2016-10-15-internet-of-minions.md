---
published: true
layout: post
---
   ![CuAcbo9WEAAt8Ly.jpg]({{site.baseurl}}/images/CuAcbo9WEAAt8Ly.jpg)

**IoT**, AKA internet-of-shit, AKA internet-of-hacked-things. IoT has been in the spotlight for a while now after [two](https://krebsonsecurity.com/2016/09/krebsonsecurity-hit-with-record-ddos/) [consecutive](https://www.ovh.com/us/news/articles/a2367.the-ddos-that-didnt-break-the-camels-vac) DDoS incidents where IoT devices were the source of the attack, just to state the problem is little bit older, many experts did warn about the situation, it started with a small impact, like a [fridge sending spam](http://www.bbc.com/news/technology-25780908) but now the situation is getting out of hand.

### A little bit of history
This kind of hacks is not new , it goes back to the dawn of internet, back then devices were not "smart" yet hence the attack was mainly on PCs, Trojans like [Sub7](https://en.wikipedia.org/wiki/Sub7) were a famous method to infect and control PCs, people lacking technical experience were an easy target, anti-viruses were not that good also at this time, which made Trojans like Sub7 gain a handful of ground to launch DDos attacks , but what has changed making the situation now dangerous ?


### Now everything is smart!
First what are these IoT devices ? , You know this "smart" TV, Tea kettle connected to your phone, "smart" door lock that shows you a video feed when someone knocks your door and "smart" cars etc... these are IoT devices, some argue that we have given internet hands and feet through IoT .

Gartner estimates a typical household could contain more than 500 IoT Devices by 2022 ,but do we really need all these shit !? frankly I think NO ! 

There are some factors which makes the IoT ecosystem catastrophic:

- The rapid growth of personal internet speed
![courtesy of xahlee.info]({{site.baseurl}}/images/internet_speed_growth.png)

- IoT vendors doesn't have proper framework to provide updates to their devices.

- IoT average consumer doesn't know/care how to update his device (When was the last time you updated your router firmware ?)

- IoT vendors uses the same default easy-to-guess password on all their devices .


These factors are the main contributors making the whole situation a ticking bomb, but is it really that bad ? , what can hackers do with these IoT devices ?

Well, a lot can be done, lets see some examples :

- DDos doh!, specially with these high speed connection we all have now, IoT minions once owned by a hacker can be used for his own benefit or even rented as in DDos-as-a-service, Mirai botnet in action:
![Mirai_botnet in action]({{site.baseurl}}/images/Ct_01peWcAAb5m0.jpg)


- SOCKS Proxies, hackers can use owned IoT devices to hack other machines online, so the attack will appear as if its coming from your home camera , hence your IP, and police will accuse you instead ! , once more the hacker can rent your devices to gain money .

- spam campaigns , sending spam emails through your devices .

- "smart" cars connected online, regardless driven or self-driving, cars can be hacked and stolen or even to kill on-board passengers, scary right ?!

- RansomWare hitting IoT devices, think of your "smart" heart pacemaker being hijacked by ransomware.

![CuFDEPXWAAAGuOe.jpg]({{site.baseurl}}/images/CuFDEPXWAAAGuOe.jpg)


Bottom line we are building very powerful things - yet most of them are useless - without proper policies or regulations, and we are hoping for the worst scenario wont happen, **and it will happen** .

---

### So, can this situation be fixed

Yes, but needs huge efforts from all parties , I will try to list some here :

**Governments:**
- Establish policies and regulations for manufacturing, updating and importing IoT devices and their components.
- Enforce polices on IoT manufacturers .
- Monitor and penalize non-adhering IoT manufacturers .

**IoT manufacturers:**
 - Adhere to government regulations .
 - Deliver constant updates ([OTA](https://en.wikipedia.org/wiki/Over-the-air_programming) style) to their devices throughout their lifetime .
 
**IoT Consumers:**
 - Only buy an IoT device from a manufacturer providing regular updates .
 - Check for username/password reset functionality .
 - Check for the ability to disable telnet service.
 - Check for the ability to disable SSH service.
 - Check for the ability to change telnet/ssh port .
 - Only buy an IoT device with backup/restore functionality .
 
 ---
 
 ### Further reads :
 
 [Security Economics of the Internet of Things](https://www.schneier.com/blog/archives/2016/10/security_econom_1.html)
 
 [Europe to Push New Security Rules Amid IoT Mess](https://krebsonsecurity.com/2016/10/europe-to-push-new-security-rules-amid-iot-mess/)
