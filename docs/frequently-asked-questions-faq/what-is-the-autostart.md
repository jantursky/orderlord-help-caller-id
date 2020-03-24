---
layout: default
title: What is the AutoStart?
nav_order: 7
has_toc: false
parent: Frequently asked questions (FAQ)
permalink: /frequently-asked-questions-faq/what-is-the-autostart
---

# What is the AutoStart?
{: .no_toc }

1. TOC
{:toc}

---

## What is the AutoStart mode
When creating customized Android firmware, you must typically launch a specific Android application after system boots. Android has two mechanisms for this:
- **Start an application after Android boot**:
	- Valid for a standard Android system with multiple applications.
	- No need to modify and compile Android sources.
- **Replace the default Android Home application**:
	- Recommended if your system consists only of this application.
	- May require you to modify and compile Android sources.

## How to ENABLE AutoStart mode
You have the option to enable this option on the login screen. On the Driver screen is also displaying the warning notification label, which is informing that you should enable the mode. 

{% include img_smartphone.html name="faq_what_is_the_autostart_1.png" %}

Click on the warning block. The description with the steps will be displayed. Click on the <span class="text-green-200">**ADD**</span> button.

{% include img_smartphone.html name="faq_what_is_the_autostart_2.png" %}

- New list with the applications will be displayed. Search the application **"Orderlord Driver"** (or the name **"Driver"**). Switch the state to the right (ENABLE) for this application. Everything done, return to the application.

{% include img_smartphone.html name="faq_what_is_the_autostart_3.png" %}