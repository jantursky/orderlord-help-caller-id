---
layout: default
title: How to use the Caller ID application
nav_order: 3
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/how-to-use-the-caller-id-application
---

# How to use the Caller ID application
{: .no_toc }

1. TOC
{:toc}

---

## How to use the Caller ID application
- once the user will log into the Caller ID application, he don't need to do anything. The application is working automatically and once the phone will receive inocming call, the mechanism will try to send this **phone number (no contact details, name, surname, etc.)** to the DMS/POS system. The phone must to be connected to the network, even if it's {% include icon.html name="network_wifi" %} Wi-Fi or {% include icon.html name="network_cell" %} Mobile network. If the user is disconnected from the network, the green circle on the top of the screen will be changed to <span class="text-red-200">red blinking circle</span> notifying that the connection with network was lost. The user can keep the application running in the background ([needs to have solved battery optimization issue]({{site.baseurl}}{% link docs/frequently-asked-questions-faq/what-is-the-battery-optimization.md %})). 

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_1.png" %}

## Different states of the screen
The screen is responding to the received call with changing the colors and texts dynamically. List of the states:
- {% include icon.html name="call" %} the application is listening for any received phone call

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_1.png" %}

- {% include icon.html name="phone_in_talk" %} the application is receiving incoming phone call

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_2.png" %}

- {% include icon.html name="phone_forwarded" %} the application is trying to send the phone number to the DMS/POS systems (to the server)

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_3.png" %}

- {% include icon.html name="check_circle" %} the application successfully sent the phone number

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_4.png" %}

- {% include icon.html name="phone_missed" %} the user wasn't able to respond to the incoming phone call, but he has the option to call back the customer

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_5.png" %}

- {% include icon.html name="signal_wifi_off" %} the phone isn't connected to the network, and wasn't able to send the phone number to the server

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_6.png" %}

- {% include icon.html name="signal_wifi_off" %} the issue with the phone or server occured and wasn't able to send the phone number to the server. The user can call back the user from the [Phone calls section]({{site.baseurl}}{% link docs/phone-calls-section/phone-calls-section.md %})).

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_7.png" %}

## Description of the "Caller ID" screen
1. **Menu icon** - opening the menu with all application sections
1. **Logo of the company**
1. **Internet connection indicator** - <span class="text-green-200">**the green circle**</span> is indicating, that the network is stable and the application is successfully connected to the server. <span class="text-red-200">**The red circle**</span> will display, once the internet is not available.
1. **Icon of the last status**
1. **Information about the last status**

{% include img_smartphone.html name="getting_started_how_to_use_the_caller_id_screen_description_1.png" %}