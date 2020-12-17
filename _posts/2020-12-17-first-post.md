---
layout: post
title: "OSCP Journey"
date: 2020-12-17 12:00:00 -0500
---

<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Since there are so many resources and blogs on OSCP preparation stage, I haven't thought to write a blog. After sharing my happiness on Twitter, I wanted to share my experiences and how I worked after the messages.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It was good for me that my certification preparation process coincided with the pandemic. I had to reduce the time I spent on the activities I liked but I was already in home most of the time.

<p align="center">
  <img width="300" height="300" src="https://media.giphy.com/media/VIEEC7Jl1LnxE6ntlF/giphy.gif">
</p>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;First of all, I will talk about my preparation process before discussing about the exam. You don't need to be an expert in any programming language. However, reading and understanding the code are very important. It is crucial to understand what the code does, what it calls and which part of it should be changed. It will be useful for you to be familiar with **bash scripting, python, C and ruby**.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the OSCP exam, we can use Metasploit’s exploit/multi/handler on every machine, but you are only allowed to use auxiliary, exploit and post modules on [1 machine](https://help.offensive-security.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide). That's why I recommend trying the manual way first in every machine solution. You have tried everything and if there is no solution, make yourself a habit of using Metasploit as the last technique.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;During the preparation process, using an application for taking note will make your job easier for writing the solutions of the machines in a way that you can understand.

<p align="center">
  <img width="300" height="300" src="../../../../../img/toolsjoplin.PNG">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used the CherryTree to take notes. When I wanted to copy and use the commands I wrote in Cherry Tree single and double quotes were causing problems. That's why I used Joplin in my Lab and Exam process.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After solving 20 machines from Linux and Windows machines in the [TJ_Null](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=0) list, my OSCP lab started. I completed the PDF document (853 pages) provided with the lab materials (PDF + video) with exercises in 1 month. I skimmed through the topics that I know and elaborated on the topics that I don’t know. Performing the exercises in the PDF accurately and reporting at least 10 machines from the machines in the Lab will give you bonus 5-points.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There are more than 100 exercise. In the beginning, doing these may seem time-consuming and dull. However, I can say that, the 5 points will give you a relief in the exam.
After completing the PWK pdf, I started to solve the lab machines. OSCP Lab machines are easier than HTB machines but they are not similar to OSCP exam Lab machines. The exam is similar to HTB Medium and higher-level machines.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There are Public, IT, Dev and Admin networks in the lab environment. There are also sandbox environments and a forum. I have completed **40** of the machines on the Public Network. You can also solve machines on other networks with pivoting. I couldn’t figure it out. You can get help from the forum, but remember that this is a training, you can solve it without assistance. There will be no forum where you can get help in the exam.

<p align="center">
  <img width="350" height="150" src="https://media.giphy.com/media/MmFVEhDzF0UUw/giphy.gif">
</p>

Don't let the BOF scare you. It scared me so much, but I can say that it was futile. I recommend you to watch [CyberMentor's buffer overflow videos](https://www.thecybermentor.com/buffer-overflows-made-easy) before studying it in PWK pdf. After watching the BOF lesson from the Cyber Mentor, you will be relieved, and you can take a shot at “VulnApp1 / 2/3" exercises in the PWK pdf. Personally, I have done them one more time along with the BrainPan and BrainStorm machines on [TryHackMe](https://tryhackme.com)  before the exam .

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Try to create your own methodology while solving the lab machines, it will help in the exam and also in the future pentesting processes. Each machine in the OSCP lab environment is already prepared to reinforce the methodology. Always make sure that you are doing the enumeration right because it will affect your solution process. I got into a habit of keeping time while solving the machines because I was wasting time in unnecessary points on the machines. I solved this problem by using [https://pomofocus.io/](https://pomofocus.io/).

**In my preparation for the exam:**

***Before the lab***
* HackTheBox
* VulnHub
* Linux & Windows Privilege Escalation - Cyber Mentor

***After taking the lab***
* PWK PDF + Video + exercises
*  Lab machines
* Buffer Overflow - Cyber Mentor

*If you want to do mock exam, there is a list for you below. I haven't done any mock exam but I read the write-ups of all of them.*

| 1 		          | 	2            | 		3       | 4               |5	        |
| :----:          | :-----------:     | :-----------: |:-----:      |:-----:|:------:
|Tabby - HTB      | Jerry - HTB      |Buff - HTB	|Sense - HTB      |Traverxec - HTB
| DC9 -VulnHub    | Bastard - HTB    |Sedna - VulnHub   |Mango - HTB      |Canape - HTB
|Easy - HTB 	    | Cronos - HTB     |Chaos - HTB  	|Lightweight - HTB|Bitlab - HTB
| Jarvis - HTB 	  | Kotarak -  HTB   |Jeeves - HTB      |Canape - HTB     |RedCross - HTB
| BrainPan - THM  | BrainStorm - THM |VulnApp1 - PWK    |VulnApp2 - PWK   |VulnApp3 - PWK



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I decided to take the exam 1 month after my lab period expired. It is useful to set your exam date early since the remaining hours when I was choosing the exam date were like (03:00, 05:00, 06:00, 07:00, 22:00). I set my test date for **22:00 on November 26th**.)

***During the period until the exam (1 month):***
* I quickly went through the notes of the lab machines.
* I solved the buffer overflow exercises in the PDF.
* I kept looking at the VulnHub and HackTheBox machines in the TJ_NULL list. I usually read write-ups.
* I solved the machines in the [Offensive Pentesting Learning Path](https://tryhackme.com/path/outline/pentesting) in TryHackMe.
* [Tiberius](https://twitter.com/tibsec) Linux & Windows Privilege Escalation

*I tried to sharpen my axe until 2 days before the exam.*

And that day has come 😊 When that day comes, calm down, calm down!!
<p align="center">
  <img width="350" height="250" src="https://media.giphy.com/media/xT5LMFzytmJ07GmqkM/giphy.gif">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Make sure you have a good internet connection. You are required to be at the session 15 minutes before your exam starts. During the exam, both you and your screen will be watched by Offsec staff. After making sure that they see both you and your screen, the staff asks you to show every corner of your room where you will be taking the exam.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After all these processes are over, your proctor will notify you that you can start your exam and you will receive a mail consist of VPN information that you’ll use.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the exam, the points of the machines and what you need to do when you get that machine are written. You have a total of 24 revert rights. When you have a problem with the machines, you can reach the technical team with the help of live chat.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;During my exam preparation time, I was finishing my BOF solutions in approximately 30 minutes by taking notes and screenshots. However, in the exam, due to the slowness of my internet, I had problems, for example the machine I connected with RDP was freezing or showing late results.
<p align="center">
  <img width="350" height="250" src="https://media.giphy.com/media/S8ToH7Zt8gZ4u2iClh/giphy.gif">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the exam, I started an Nmap scan of two machines (10-points & 20-points) when I started the BOF question. I finished the BOF machine in 45-minutes and made sure that I had all the necessary screenshots and notes, then I moved on to my next machines which were on the Nmap scan. After carefully examining the enumeration output, I captured the 10-points target in a short time. I took a 15-minute break with the permission of the proctor. I went back to the exam with cold milk and some biscuit 😊 and informed the supervisor that I was back. (You need to inform the proctor that you came back to the exam.
<p align="center">
  <img width="350" height="250" src="https://media.giphy.com/media/nAErqE3k2C3fy/giphy.gif">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reminding myself that I am at 40-points, including the 5-points from lab report, I left the other 2 machines to scan for enumeration as well. I started solving the first 20-points machine. At the 3rd hour of my exam, I got a low user login to the system. After having escalated my privileges on the machine, I took a break.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I was planning to look for the Nmap results and sleep like 3-4 hours, however it was so stressful so that I have refused to go to bed. I couldn't manage this and at that moment I refused to sleep. I couldn’t manage the stress, but I advise you to do so.
<p align="center">
  <img width="350" height="250" src="https://media.giphy.com/media/xT5LMz2DWrwmbfVBK0/giphy.gif">
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When I started to solve the other 20-points machine, it was around 4-5 am. I was finding something, but I could not move forward. I panicked and moved on to the next machine. The mistake I made here was refusing the sleep. If I got a little sleep there, I would be fresher when I woke up in the morning.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After looking more for the 20-points machine, I got a way and got the low user and escalated to root around 6-7 am. Without taking break, I started to solve the 25-points machine.  After doing the work on it, I faced some questions and asked them to test and revert the system with live chat. I couldn’t find a way to solve.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*At 9am,* I went to bed. I’ve slept for 1.5 hours and had my breakfast. With the power of breakfast, I had a low shell on the system around 1 o'clock. After a while, I escalated my privileges to root. I reached the required score for the exam (25 + 10 + 20 + 25 + 5). I was so relieved. I took a break  I celebrated this situation with Turkish coffee and chocolate 😍

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I came back around *4pm*. One can see my loosening for the long period of break 😎. Since I got enough points, I first looked at my screenshots and notes on my local. I’ve wanted to check them before the due date of my exam.

*At 5pm…*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I started to look for the last (20-points) machine.

*At around 9pm*, I got a low shell in the system. I managed to become an authorized user on the system **3** minutes before the end of my exam 🤘
<p align="center">
  <img width="300" height="300" src="https://media.giphy.com/media/KzM1lAfJjCWNq/giphy.gif">
</p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The proctor reported that my exam was over and reminded me of the reporting stage. You have extra 24 hours to write the exam report as soon as you finish your exam.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My report writing process, which started around 12pm, ended at 8pm. I’ve used the v1.1 exam report format. Afterwards, I’ve uploaded my report.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When reporting, it will make your job easier to write by thinking that the other person is skilled enough. Otherwise, your report will be filled with unnecessary photos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1 day after uploading my exam report to the system..

<p align="center">
  <img src="../../../../../img/certificate.PNG">
</p>
