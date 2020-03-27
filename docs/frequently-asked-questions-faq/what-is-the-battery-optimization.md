---
layout: default
title: What is the Battery Optimization?
nav_order: 5
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/what-is-the-battery-optimization
---

# What is the Battery Optimization?
{: .no_toc }

1. TOC
{:toc}

---

## What is the Battery Optimization
Broadly speaking, the Android platform provides two categories of help for you to optimize your app's battery use. First, it provides several APIs that you can implement in your app. You can learn more about these APIs in Guide to background processing.

There are also internal mechanisms in the platform to help conserve battery life. While they are not APIs that you implement programmatically, you should still be aware of them so that your app can leverage them successfully. For more information, see:
- **Doze and App Standby**
- **App Standby Buckets** - the system limits apps' access to device resources like the CPU or battery, based on the user's usage patterns.
- **Background restrictions** - if an app exhibits bad behaviors, the system prompts the user to restrict that app's access to system resources.
- **Power management restrictions** - see a list of power restrictions that can be imposed on apps under certain conditions.

## How to DISABLE Battery optimization
You have the option to disable this option on the login screen. On the login screen is also displaying the warning notification label, which is informing that you should disable the optimization. 

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_1.png" %}

Click on the warning block. The description with the steps, how to solve this optimization, will be displayed. Click on the <span class="text-green-200">**DISABLE**</span> button.

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_2.png" %}

- New list with the applications will be displayed. Click on the <span class="text-blue-100">**Not optimized**</span> label and switch to display **ALL APPLICATIONS**.

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_3.png" %}

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_4.png" %}

- Search the application **"Orderlord Caller ID"** (or the name **"Caller ID"**). Click on the row and change the option to **Don't optimize**. Then click on the <span class="text-blue-100">**Done**</span> button. Everything done, return to the application.

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_5.png" %}

{% include img_smartphone.html name="faq_what_is_the_battery_optimization_6.png" %}

## External links
- [Developer Android site](https://developer.android.com/topic/performance/power)
- [Don't kill the app](https://dontkillmyapp.com/)