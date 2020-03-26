---
layout: default
title: Call issues
nav_order: 2
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/call-issues
---

# Call issues
{: .no_toc }

1. TOC
{:toc}

---

## "Unsupported version" warning
This warning message is not the issue on the application side, mostly it's the problem with some specific permissions. From the specific _Android version (9.0 and above)_, we were forced to add **Read/Write Call log** permissions, because from this Android version, the system changed the logic of receiving incoming calls. But if our applications isn't considered as the classic **CALL application**, we weren't approved to submit the application to the Google Play and to be accepted by the rules of the application on the store. That was the reason, why we adjust this logic of first start the application, and once we will check, that the Android device has this specific Android version (or above), we stopped him from the using and are forcing him to install the alternative version from our servers. The user just need to **download the application** (application will do that instead of him) and **install this alternative version** (user needs to do that). We would love to keep it **more simple**, but the rules forced us to adjust the application logic (even after a long communication with Google Play helpdesk itself).

## DUAL SIM warning
Most of the Android vendors have adjusted the logic of receiving the incoming call's information. If the user has two slots for the SIM cards, this issues could occurred. We investigated, that if the user has the SIM for receiving the calls set as SECONDARY in his **"SIM cards & mobile networks"** section, the application could have a issue with determining the received call and will obtain _empty text_ (the phone number information). For this cases, the user needs to set up this SIM card as **PRIMARY**. Also he needs to accept the permissions during starting the app, which are enabling receiving this incoming phone call's information.