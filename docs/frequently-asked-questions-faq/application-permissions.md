---
layout: default
title: Application permissions
nav_order: 9
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/application-permissions
---

# Application permissions
{: .no_toc }

1. TOC
{:toc}

---

## List of permission
For the purposes of 100% usage of the app, the kitchen application requires these permissions:
- **Internet/Access network state/Access wifi state** - check, if the connection with the internet is available, running or disconnected
- **Access notification policy** - for handling the {% include icon.html name="do_not_disturb" %} [**Do Not Disturb mode**]({{site.baseurl}}{% link docs/frequently-asked-questions-faq/what-is-the-disturb-mode.md %})** - play sound/notifications even if this mode is enabled
- **Get accounts** - during sending log report, list of added google accounts will be provided as a "Sender" for the [**Report the problem**]({{site.baseurl}}{% link docs/troubleshooting/report-your-problem.md %}) functionality
- **Install shortcut** - once the application is installed from the [Google Play link]({{site.baseurl}}{% link docs/getting-started/how-to-install-the-application.md %})
- **Read/Write external storage** - this permission is used for local backup of the settings, which are set up in the settings section for the user
- **Wake lock** - for the purpose of long-running background services
- **Vibrate** - once the notification in the notification bar will be displayed, the device will vibrate
- **Foreground service** - for the purpose of long-running background services
- **Call phone** - option to initiate calling with the customer
- **Modify audio settings** - if the courier is using headphones, then once the notification will come to the phone, the application will decrease the volume to lower value (loudness)
- **Gps module/Access fine/coarse location/Access background location** - localization purposes of the courier

Optional permissions:
- **Nfc module** - if the courier needs to be authenticated in the restaurant 
- **Accelerometer sensor** - for usage of the compass for showing the direction to the restaurant in the application
- **Telephony module** - if the courier wants to call the customer to contact him

## First installation
During the logging first time on the login screen, the user will be prompted to **Accept Read/Write external storage** ([usage](#list-of-permission)). Once the user accepts this permission, he will be logged in. _This process is only one-time_, he must repeat it only when <span class="text-red-200">_the application was uninstalled and installed again_</span> or when the <span class="text-red-200">_application cache was deleted_</span>.

{% include img_smartphone.html name="faq_application_permissions_1.png" %}