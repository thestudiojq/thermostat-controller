---
layout: page
title: Remote mode
permalink: remote
---

# {{ page.title }}

With remote mode enabled, you can view the data from your thermostat while not on your Wi-Fi network. This  does not allow you to control your thermostat remotely, but only view the data.

## Enabling remote mode

Just go to the [app settings]({{ 'config' | relative_url }}) section and toggle **Remote Mode** on. 

## Companion app

In order for the remote retrieval to work, you need to be running our companion app on a computer, as it's this app that will monitor your thermostat locally. Since the app needs to be running in order to trigger notifications, you'll want to install it on a computer that you have running all the time (e.g. the computer you use for other home automation tasks).

This companion app, as well as instructions for how to install, configure and run it, are available here:

[https://github.com/thestudiojq/thermostat-control-companion](https://github.com/thestudiojq/thermostat-control-companion)

## API key

In order to connect the phone app to the computer app, you'll need to use an API key. You must generate the API key yourself, and it must be in valid **UUIDv4** format. If it isn't in this format, it will be rejected and the remote mode won't work. (The app will tell you if the key you entered is not in the correct format.) There are many places that you can generate a UUIDv4 key. For example:

[https://generate-uuid.com](https://generate-uuid.com)

For info on how to add this key to the iPhone app, see the [Config]({{ 'config' | relative_url }}) section.

You will also need to add this same API key to the [companion app](#companion-app).

For info on how we store and use this key, see the [Security]({{ 'security' | relative_url }}) section.

## Disabling remote mode

When you are at home, you probably want to disable the remote mode in the settings to regain the ability to actually control your thermostat.