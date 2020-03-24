---
layout: default
title: Update the data
nav_order: 8
has_children: false
has_toc: false
parent: Getting Started
permalink: /getting-started/update-the-data
---

# Update the data
{: .no_toc }

1. TOC
{:toc}

---

## Description
The kitchen application contains the logic, that every 15-30 seconds, the update mechanism contacts the server and updates the orders and the meals to the latest one. But the courier has also an option for manually updating the **Deliveries screen**.

## How to manually update
There are 2 ways, how to manually update the data:
1. If the **Deliveries screen** is not displaying any deliveries and orders, then the _empty status_ is displayed. The courier just needs to click on the red button <span class="text-red-200">**REFRESH DELIVERIES**</span> and the device will try to contact the server and reload the screen.
2. There may be situations where there are deliveries and orders on the screen. In this case, the red button <span class="text-red-200">**REFRESH DELIVERIES**</span> is not visible. The only way, how to update the data manually is with the mechanism called. **pulled to refresh** - this means, that in the area of deliveries you need to **swipe down {% include icon.html name="arrow_downward" %} with a finger** till the refresh icon <span class="text-orange-200">{% include icon.html name="refresh" %}</span> in the center top of the screen will display, then release the finger and the application will trigger manually update (indicating by rotating refresh icon).

{% include img_smartphone.html name="getting_started_update_the_data_1.png" %}

{% include img_smartphone.html name="getting_started_update_the_data_2.png" %}