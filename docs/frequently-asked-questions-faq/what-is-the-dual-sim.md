---
layout: default
title: What is the Dual SIM?
nav_order: 6
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/what-is-the-dual-sim
---

# What is the Dual SIM?
{: .no_toc }

1. TOC
{:toc}

---

## What is the Disturb mode
Some mobile phones support use of {% include icon.html name="sim_card" %} {% include icon.html name="sim_card" %} two SIM cards, described as dual SIM operation. When a second SIM card is installed, the phone either allows users to switch between two separate mobile network services manually, has hardware support for keeping both connections in a "standby" state for automatic switching, or has individual transceivers for maintaining both network connections at once.

## How to handle DUAL Sim case
Most of the Android vendors have adjusted the logic of receiving the incoming call's information. If the user has two slots for the SIM cards, this issues could occurred. We investigated, that if the user has the SIM for receiving the calls set as SECONDARY in his **"SIM cards & mobile networks"** section, the application could have a issue with determining the received call and will obtain _empty text_ (the phone number information). For this cases, the user needs to set up this SIM card as **PRIMARY**. Also he needs to accept the permissions during starting the app, which are enabling receiving this incoming phone call's information.

- Navigate to the {% include icon.html name="settings" %} settings section. 
- If the highlighted red row is displaying {% include icon.html name="do_not_disturb_on" %} **"Do Not Disturb" mode**, click on this row. If this row is not displaying, enable the sound notification. If this setting is enabled, Check to see if this row appears after the sound notifications are enabled. If not, then that means, that this application already granted access to handle **"Do Not Disturb" mode**.

{% include img_smartphone.html name="faq_what_is_the_dual_sim_1.png" %}

- When the new screen is displayed (**Do not disturb access**), find in the list the kitchen application (**KDS**). 

{% include img_smartphone.html name="faq_what_is_the_dual_sim_2.png" %}

- Enable access for this application
