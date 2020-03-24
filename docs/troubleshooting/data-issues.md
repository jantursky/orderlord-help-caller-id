---
layout: default
title: Data issues
nav_order: 5
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/data-issues
---

# Data issues
{: .no_toc }

1. TOC
{:toc}

---

## No deliveries
If you are sure, that you should received the delivery and the setup of settings in the application is correct, and you are still not receiving any orders, check the other options below or contact [the support](mailto:support@orderlord.com).

## Not receiving assigned deliveries
It could happened, that the application isn't receiving the notifications about newly assigned deliveries. This is caused by the push message logic, that is renewing the token for the device approximatelly every 1-2 hours. Once this state will occur, the application is trying to send this new token to the server and fix with that receiving the notifications. But it could happen, that during sending this information to the server, the Android device is not connected to the network. In that case, the application is displaying the warning message "The application isn't synced with the server!". In that case, you need to click on that message, and syncing the token with the server will be initialized.

## Your GPS position is older than 5 minutes
Once the courier succesfully log into the application, the warning message on the top could be displaye. This message means, that even if the GPS of the device is running, it could took a time, once the GPS is stable and is receiving the  

## Wrong timezone
If the orders are showing the wrong time, the issue could be with the wrong timezone, date or time. <span class="text-red-200">Be aware, that some manufacturer devices (mostly _Chinese brands_) contains a bug, which is causing that even if you setup correct timezone for your area, the device will (mostly after restart the Android device or synchronization with their website) change the timezone to the wrong timezone (for instance timezone of the manufacturer).</span> For a better overview, you could notice that through wrong date+time information on the **Kitchen screen** on the bottom. You just need to compare the device date and time with the real-time. For a better final solving this bug, you could set up manually timezone of the device in {% include icon.html name="settings" %} _the Android device settings_.

## Wrong date or time
<span class="text-red-200">Same as the issue with the [wrong timezone issue](#wrong-timezone), check if the device date and time is the correct one.</span> You could also set up device date and time manually for better control of the device in {% include icon.html name="settings" %} _the Android device settings_.

## Past events in the Timeline section
Once the user needs to check the history of the events, that he performed during working with the application, he could use the {% include icon.html name="timeline" %} [**Timeline**]({{site.baseurl}}{% link docs/timeline-section/timeline-section.md %}) section. <span class="text-red-200">But be aware, the number of events logged for the timeline is limited, depending on the device. Once the application was uninstalled, or the cache of the application was deleted (through device Settings), **the timeline data will be deleted**. The application is also storing the only limited value of Timeline data, approximately for the last 7 days.</span>

## Insufficient permission for the restaurant
<span class="text-red-200">If the user is not receiving the orders, it could be because of that the user hasn't permission to work the restaurant. Ask the manager to add the correct restaurants, which he could work with.</span>