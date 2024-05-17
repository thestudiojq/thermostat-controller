---
layout: page
title: Push notifications
permalink: push
---

# {{ page.title }}

You can enable push notifications that get triggered any time the state of your thermostat changes. i.e. When it goes from idle to active (heating or cooling), or vice versa.

Since these push notifications are triggered by the companion app running on your computer at home (see below), they will actually still be sent to your phone even if you're out and don't currently have your phone on the same network as your thermostat. So, even though you won't be able to see the current thermostat data when you're away from your home network, you can still get notifications when the system becomes active or idle.

## Enabling/allowing push notifications

When you launch the app for the first time, it will ask for permission to send push notifications. You need to allow this in order to get push notifications. 

If you did not initially allow it, you can easily do so at any time by going to **Settings > Notifications > Thermostat Controller** on your phone and enabling it there.

## Companion app

In order for push notifications to work, you need to be running our companion app on a computer, as it's this app that will monitor your thermostat locally and actually trigger the notification. Since the app needs to be running in order to trigger notifications, you'll want to install it on a computer that you have running all the time (e.g. the computer you use for other home automation tasks).

This companion app, as well as instructions for how to install, configure and run it, are available here:

[https://github.com/thestudiojq/thermostat-control-companion](https://github.com/thestudiojq/thermostat-control-companion)

## API key

In order to connect the phone app to the computer app, you'll need to use an API key. You must generate the API key yourself, and it must be in valid **UUIDv4** format. If it isn't in this format, it will be rejected and you won't receive push notifications. There are many places that you can generate a UUIDv4 key. For example:

[https://generate-uuid.com](https://generate-uuid.com)

For info on how to add this key to the iPhone app, see the [Config]({{ 'config' | relative_url }}) section.

You will also need to add this same API key to the [companion app](#companion-app).

For info on how we store and use this key, see the [Security]({{ 'security' | relative_url }}) section.

## Disable push notifications

To disable push notifications, you can do one or both of the following:

* Clear the **API Key** field on the settings screen in the app. 
* Go to **Settings > Notifications > Thermostat Controller** on your phone and disallow notifications from the app there.