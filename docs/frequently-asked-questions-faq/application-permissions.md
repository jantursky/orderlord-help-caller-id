---
layout: default
title: Application permissions
nav_order: 7
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
- **Get accounts** - during sending log report, list of added google accounts will be provided as a "Sender" for the [**Report the problem**]({{site.baseurl}}{% link docs/troubleshooting/report-your-problem.md %}) functionality
- **Install shortcut** - once the application is installed from the [Google Play link]({{site.baseurl}}{% link docs/getting-started/how-to-install-the-application.md %})
- **Read/Write external storage** - this permission is used for local backup of the settings, which are set up in the settings section for the user
- **Wake lock** - for the purpose of long-running background services and the setting "Keep the screen on"
- **Call phone** - option to initiate calling with the customer
- **Read/Write call log, Read phone state** - once the phone will receive the call, the application needs to determine this case and notify about that the POS/DMS system. And for some specific vendors, it's needed to have access also to "Read phone state" permission
- **Telephony module** - the user needs to receive incoming calls and contact the customer by calling


## First installation
During the logging first time on the login screen, the user will be prompted to **Accept Read/Write external storage** ([usage](#list-of-permission)). Once the user accepts this permission, he will be logged in. _This process is only one-time_, he must repeat it only when <span class="text-red-200">_the application was uninstalled and installed again_</span> or when the <span class="text-red-200">_application cache was deleted_</span>.

{% include img_smartphone.html name="faq_application_permissions_1.png" %}