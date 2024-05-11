---
layout: page
title: Config
permalink: config
---

# Configuring the app

Configuring the app is pretty straightforward. Just click the settings icon in the top left or swipe to reveal the settings screen. There you will have the following options:

* **IP Address**: This is the local IP Address of your thermostat. You can find it by doing the following on your thermostat (instructions are for the T7900 model):
  * Tap MENU.
  * Then Wi-Fi.
  * Then WiFi Status.
  * Here it will display the IP address of the unit.
* **Thermostat Name**: The name that you want to display at the top of the main screen in the app. This will also be the title for [push notifications]({{ 'push' | relative_url }}), if you have those enabled.
* **Theme**: *Dracula* is the same regardless of whether your phone is on light or dark mode. *System* follows your phone's light/dark mode settings.
* **Refresh Button Position**: How big is your phone, and how long is your thumb? You can also pull to refresh, so just do that instead.
* **API Key**: In order to connect the phone app to the computer companion app and receive [push notifications]({{ 'push' | relative_url }}), you’ll need to use an API key. You must generate the API key yourself, and it must be in valid UUIDv4 format. If it isn’t in this format, it will be rejected and you won’t receive push notifications. There are many places that you can generate a UUIDv4 key. For example: [https://generate-uuid.com](https://generate-uuid.com).