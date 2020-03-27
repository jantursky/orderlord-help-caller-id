---
layout: default
title: How to login
nav_order: 2
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/how-to-login
---

# How to login
{: .no_toc }

1. TOC
{:toc}

---

## "Unsupported version" message
- Open the application **"Orderlord Caller ID"**. The new screen will be displayed.

<!-- - **During first logging into the application**, the Android system will prompt the dialog to allow access for "GPS position", "Reading/Writing into storage" and "Call the customer". This permissions are explained in [this section]({{site.baseurl}}{% link docs/frequently-asked-questions-faq/application-permissions.md %}). -->

- if the warning "Unsupported version" message will appear, that means, that you are using Android 9 verion (Android Pie or above, [see the reason]({{site.baseurl}}{% link docs/troubleshooting/call-issues.md %})). In that case, you need to download the alternative Android version of Caller ID application. The application was adjusted to do most of the work, for you. Follow these steps for updating to the alternative version:
- click on the green <span class="text-green-200">**DOWNLOAD**</span> button

{% include img_smartphone.html name="getting_started_how_to_login_1.png" %}

- downloading of the alternative version will be started

{% include img_smartphone.html name="getting_started_how_to_login_2.png" %}

- once the version is downloaded, the installation screen will be displayed. For some devices (mostly newer one) you need to allow installing unknown apps from this source. Simply do that by clicking on the green <span class="text-green-200">**SETTINGS**</span> button.

{% include img_smartphone.html name="getting_started_how_to_login_3.png" %}

- the new screen will be displayed, where you need to allow installing unknown apps by switching the switch to the right. Once you will do that, go back to the previous screen by clicking on the back icon.

{% include img_smartphone.html name="getting_started_how_to_login_4.png" %}

- if you followed everything correctly, the installation button should be allowed. Just click on the green <span class="text-green-200">**INSTALL**</span> button, and the current version of the Caller ID application will be overriden by this alternative version with additional permissions for receiving incoming calls.

{% include img_smartphone.html name="getting_started_how_to_login_5.png" %}

- wait, until the installation will be done and open this newly installed version (should be the same icon as previous version, on the home screen).

{% include img_smartphone.html name="getting_started_how_to_login_6.png" %}

## Basic login
- Open the application **"Orderlord Caller ID"**. The new screen will be displayed. You could notice, that for the first time, you need to enable some permissions or allow access for some features for proper working of the application:
	- {% include icon.html name="battery_alert" %} **Battery Optimization** - for better working of background services, like GPS localization and sending/received updates. [You could solve it in this section]({{site.baseurl}}{% link docs/frequently-asked-questions-faq/what-is-the-battery-optimization.md %})

{% include img_smartphone.html name="getting_started_how_to_login_7.png" %}

- Type on the first input line **Email** assigned email for the user. The format of the login name should be an email address, like **test@gmail.com** (just as an example). Be aware to not add spaces on the start or end of the input. Type the password for the user. Once you click on the {% include icon.html name="visibility_off" %} eye icon on the right, the password will be displayed (for control purposes). Then click on the <span class="text-orange-200">**SIGN IN**</span> button.

{% include img_smartphone.html name="getting_started_how_to_login_8.png" %}

- the new screen with the authentication with the token will be displayed. The user needs to input the **API password** that was assigned to his user.

{% include img_smartphone.html name="getting_started_how_to_login_9.png" %}

- The application will try to check that the API password is valid and sign in. The user is then moved to the [**main application page**]({{site.baseurl}}{% link docs/getting-started/how-to-use-the-caller-id-application.md %}).

{% include img_smartphone.html name="getting_started_how_to_login_10.png" %}

## Disable Battery Optimization
Click on the warning block. The description with the steps, how to solve this optimization, will be displayed. Click on the <span class="text-green-200">**DISABLE**</span> button.

{% include img_smartphone.html name="getting_started_how_to_login_disable_battery_optimization_1.png" %}

- New list with the applications will be displayed. Click on the <span class="text-blue-100">**Not optimized**</span> label and switch to display **ALL APPLICATIONS**.

{% include img_smartphone.html name="getting_started_how_to_login_disable_battery_optimization_2.png" %}

{% include img_smartphone.html name="getting_started_how_to_login_disable_battery_optimization_3.png" %}

- Search the application **"Orderlord Caller ID"** (or the name **"Caller ID"**). Click on the row and change the option to **Don't optimize**. Then click on the <span class="text-blue-100">**Done**</span> button. Everything done, return to the application.

{% include img_smartphone.html name="getting_started_how_to_login_disable_battery_optimization_4.png" %}

{% include img_smartphone.html name="getting_started_how_to_login_disable_battery_optimization_5.png" %}

## "Dual SIM" warning message 
Most of the Android vendors have adjusted the logic of receiving the incoming call's information. If the user has {% include icon.html name="sim_card" %} {% include icon.html name="sim_card" %} two slots for the SIM cards, this issues could occurred. We investigated, that if the user has the SIM for receiving the calls set as SECONDARY in his **"SIM cards & mobile networks"** section, the application could have a issue with determining the received call and will obtain _empty text_ (the phone number information). For this cases, the user needs to set up this SIM card as **PRIMARY**. Also he needs to accept the permissions during starting the app, which are enabling receiving this incoming phone call's information.

- the user could click on the warning message. The list of options should be displayed (or directly display the SIM cards screen, depends on the vendor)

{% include img_smartphone.html name="getting_started_how_to_login_dual_sim_1.png" %}

- new screen **SIM cards & mobile networks** will be displayed. Try to check how many sim cards are insterted into phone and what SIM card is used for the preferred **Dial setting**. If you are receiving the phone calls from the 2. SIM card, switch this SIM card within the 1. SIM card, to be sure, that the SIM card will be placed in the **primary slot**. Also be sure, that Dial setting is selected for the correct SIM card (or _not set_ if only one SIM card is inserted).

{% include img_smartphone.html name="getting_started_how_to_login_dual_sim_2.png" %}