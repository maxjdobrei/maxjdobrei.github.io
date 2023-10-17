---
layout: single
title:  "Resume"
date:   2023-10-16 13:30:00 -0500
permalink: /resume/
author_profile: false
toc: true
toc_sticky: false

---

#### **Maximilian Dobrei**
_maxjdobrei@gmail.com_


###### Objective
As a recent graduate I am seeking a position as a Junior Security Support Personnel to further hone my technical skills protecting an enterprise from Cyber threats. I am looking to cultivate my career by establishing myself in a workplace that interests and challenges me.

###### Education

_Bachelor of Computer Science Honors, Computer and Internet Security Stream, Minor in Neuroscience and Mental Health Carleton University, Ottawa, ON  (September 2018 - August 2022)_

* Graduated with a CGPA of 10.60/12 (A-)
* Recipient of the Henry Marshall Tory Scholarship
* Held a position on the Dean’s Honour List (September 2018 - August 2022)


###### Certifications and Security Clearances

* Reliability check (Level 0)
* Secret (Level II)

###### Programming experience

| Language             | Skill Level  | Experience |
| Python               | Intermediate | 4 years    |
| C++                  | Intermediate | 2 years    |
| Java                 | Intermediate | 5 years    |
| Javascript           | Beginner     | 2 years    | 
| HTML & CSS           | Beginner     | 2 years    |
| Rust                 | Beginner     | 1 years    |
| Racket               | Beginner     | 1 years    |

###### Technical Skills & Knowledge

* **Network Monitoring Software**: Utilized Portswigger Burp Suite software to monitor, inspect,  intercept, and modify packets being sent over my network in a sandbox environment. I used the Burp tool to assist my attempts at exploiting vulnerabilities found in “Damn Vulnerable Web Application” to achieve goals such as remote code execution, cross site scripting, and cross site request forgery.
* **Web based Penetration Tools**: By using a cross site scripting attack on “Damn Vulnerable Web Application”, I injected a payload to hook my browser to “Browser Exploitation Framework” software in a sandboxed environment. From there, I was able to use the software suite to gain information such as the DVWA session cookie, and to launch social engineering attacks like creating a fake flash update appear on the screen.
* **Network Firewalls**: Familiar with using the iptables tool on Linux to specify firewall rules. For example, specifying a rule to capture all outgoing packets to a particular device or program, and using DNAT to reroute the packets to a new address. 
* **Exploiting vulnerable code**: Successfully exploited a race condition vulnerability to write to a file owned by the root user. Specifically, the program had a “Time of check vs Time of Use” vulnerability, which I was able to leverage to replace the intended output file with a symbolic link to the root owned file. 
* **Privilege Escalation**: Devised a linux kernel module to overwrite entries in the sys_call_table to insert malicious functions that would be used instead of normal syscalls. This was only possible to do with old Linux kernels that had read/write priveleges to the sys_call_table. For example, I was able to overwrite the linux execve syscall to allow any user to execute any program with root privileges by replacing the credential structure being used for program execution. I was also able to overwrite the getdents syscall such that any file with a certain prefix was not viewable through commands such as “ ls ” that trigger the getdents syscall.
* **Object Oriented Software Engineering**: Collaborated on a project using the QT Framework with C++ to design and implement a simulation of a Cranial Electrical Stimulation device. Utilized object oriented design principles alongside QT slots & signals, events, and QT objects to create a GUI for the simulation.
* **Backend programming**:  Contributed to a Python script acting as the backend of a web application, which integrated the act of parsing information from the webapp and storing it, and subsequently performing the analysis required to give back meaningful data to the user. 
* **REST APIs**: Familiar with server-client architecture used in web development. Using NodeJS as the server environment, created a prototype for a simple food ordering webpage. 
* **Public Key Cryptography**: Knowledgeable of the semantics involved in PKI. Applied RSAES-OEAP (RFC8017) as a cipher suite to encrypt and decrypt data, as well as create and verify digital signatures for an academic project.
* **TCP Communications**: Designed, implemented, and tested multiple projects involving TCP servers and clients. The projects were written in Python, and have used both the low level socket module, and the higher level asyncio module for creating and managing communication channels.
* **MQTT Protocol**: Completed a project using MQTT as the basis for communication between simulated IoT devices. Modified and used aMQTT, an open source implementation of MQTT for Python.  
* **Prototyping**: Designed multiple lofi prototype webpages (in the form of wireframes) using Balsamiq, as part of a set of software proposals using specific design principles, including information visualization and external cognition.
* **Debugging**: Knowledgeable of debugging techniques, and plenty of practice using them to resolve issues while grading students’ assignments, and to facilitate my own software development in both academic and enterprise settings.
* **Version Control**: Experienced with using Github as a source control protocol to enable distributed development of a team project. Proficient using basic GIT operations such as pulling, pushing, branching, merging, committing, etc.

###### Communication Skills

* **Daily SCRUM Meetings**: Acted as an assistant to the Scrum Master for an IT driven solution, helping coordinate which team members were working on each respective work order, tracking progress, and ensuring the given timeline was followed to the best of the team’s ability. Other responsibilities included facilitating discussions between junior team members and business clients.
* **Mentoring**: Collaborated as a part of a team of teaching assistants conducting laboratory activities. This involved clarifying the professor’s instructions and conveying key concepts from the course material to the students, in order to facilitate the students’ understanding of the content and completion of exercises. To find success as a teaching assistant, not only do you need to quickly understand a student's query and the root of the problem, you must have the ability to communicate the solution effectively, in a friendly and polite manner.  
* **Technical Writing**: Wrote a technical paper for my Honour’s project that included architectural diagrams and implementation details, as well as a security analysis and recommendations for future work. 

###### Work Experience

**IT Analyst (CS 1) - Canada Revenue Agency May 2021 - February 2023**
_Travel and Control Team within the Corporate Enterprise Solutions Division, under the Information Technology Branch_
* Reviewed and resolved bugs and discrepancies found in IT systems such as webpages, internal databases, and programs used by business clients.
* Developed IT driven solutions for business clients as well as for internal use by the CRA using SAP technologies, such as the ABAP programming language, Webdynpro, workflows, and various SAP transaction codes.
* Worked one on one with business clients to identify business requirements, establish expectations,  and a plan for implementation.  Provided consistent progress updates, and adapted the solution to fix issues on the fly when needed.
* Utilized the Agile Framework through Jira to enhance our team's ability to track progress, collaborate on projects, and work effectively and efficiently. 
* Established and maintained RfCs through the design and creation stage, all the way through to volume testing, user acceptance testing, pre-deployment testing, and seeing it get implemented in the production environment.

**Teaching Assistant** 
_Intro to Computer Science II  - Prof Darryl Hill, Carleton U          September 2019 - December 2019_
_Intro to Computer Science II  - Prof Dave McKenney, Carleton U        January   2020 - April    2020_
_Intro to Computer Science II  - Prof Darryl Hill, Carleton U          September 2020 - December 2020_ 
_Intro to Software Engineering - Prof Christine Laurendeau, Carleton U January   2021 - April    2021_
* Conducted tutorial sessions in a computer laboratory environment in a manner to answer student questions and to provide clarifications of lecture content, as well as clearing up any misunderstandings regarding the programming evaluations.
* Held weekly office hours to offer more personal one on one guidance, in the hope of being able to help students understand assignment specifications, practice exam questions, and course material, and on occasion giving constructive feedback on assignments or midterm evaluations. 

###### Applied Projects

**Team Lead May 2022 - August 2022**

[_OE-MQTT_](https://github.com/maxjdobrei/oe-mqtt)

* Under Professor David Barrera at Carleton University, I created OE-MQTT as a proof of concept for my Honour’s Project.
* I developed a simple TCP client & server in one, dubbed a proxy, using Python’s default socket library to act on behalf of MQTT publishers, subscribers, and brokers. Utilizing the linux tool iptables to specify firewall rules, I took advantage of DNAT to reroute all outbound traffic from each MQTT entity to the proxies instead of the MQTT broker or subscriber. These proxies were able to connect with other proxies at the other end of the communication channel, and offered opportunistic encryption of all packets sent back and forth between an MQTT publisher and broker, or broker and subscriber.
* Encryption, decryption, and digital signature creation and validation were all done by using the RSAES-OEAP cipher suite offered by the Pycryptodome library.


**Team Member February 2021 - April 2021**

[_SQRL - Rust Client_](https://github.com/filipp-g/rust-sqrl-client)
* Built a simple terminal based client executable that implements the ‘Secure Quick Reliable Login’ (SQRL) API. Written in the Rust language, this project aims to allow a user to login to any website that supports the SQRL Server API.
* This process involves HTTP communication between the client application and the server, as well as  implementing and using various cryptographic functions to support creating a public/private key pair for the website in question, providing means for authentication and maintaining transmission integrity. 
* As recommended by the creators of SQRL, the program uses libsodium as the basis for the cryptographic functionality.
