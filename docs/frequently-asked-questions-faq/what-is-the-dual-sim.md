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

- the user could click on the warning message. The list of options should be displayed (or directly display the SIM cards screen, depends on the vendor)

{% include img_smartphone.html name="faq_what_is_the_dual_sim_1.png" %}

- new screen **SIM cards & mobile networks** will be displayed. Try to check how many sim cards are insterted into phone and what SIM card is used for the preferred **Dial setting**. If you are receiving the phone calls from the 2. SIM card, switch this SIM card within the 1. SIM card, to be sure, that the SIM card will be placed in the **primary slot**. Also be sure, that Dial setting is selected for the correct SIM card (or _not set_ if only one SIM card is inserted).

{% include img_smartphone.html name="faq_what_is_the_dual_sim_2.png" %}