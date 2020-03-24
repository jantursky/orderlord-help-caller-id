---
layout: default
title: GPS issues
nav_order: 2
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/gps-issues
---

# GPS issues
{: .no_toc }

1. TOC
{:toc}

---

## "High accuracy required!" warning
Once the GPS module isn't enabled or the mode of GPS localization is low, <span class="text-red-200">the dialog with warning message **High accuracy required!** is displayed.</span> This issue could be occurred because of one from multiple things. The courier needs to be sure, that the GPS has the correct setup. Click on the <span class="text-red-200">CHANGE SETTINGS</span> button.

{% include img_smartphone.html name="troubleshooting_gps_issues_1.png" %}

- the Location screen will be displayed. The courier needs to change the **LOCATION MODE** to **HIGH ACCURACY** (some vendors will a moment after this change displays the dialog, which the courier needs to approve). 

{% include img_smartphone.html name="troubleshooting_gps_issues_2.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_3.png" %}

- the courier needs also on this screen to scroll down to the list of **LOCATION SERVICES** <span class="text-red-200">(some vendors and models don't need to contain this part of the Location screen).</span> He needs to click on every option from there services and after opening the detail of specific service, the courier needs to **ENABLE** that specific service. This specific restriction is because some models aren't considered, that they are using **HIGH ACCURACY** mode, only after enabling all of these services.

{% include img_smartphone.html name="troubleshooting_gps_issues_4.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_5.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_6.png" %}