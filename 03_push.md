---
layout: page
title: Push notifications
permalink: push
---

# {{ page.title }}

You can enable push notifications that get triggered any time the state of your thermostat changes. i.e. When it goes from idle to active (heating or cooling), or vice versa.

In order for push notifications to work, you need to be running our companion app on a computer, as it's this app that will monitor your thermostat locally and actually trigger the notification. Since the app needs to be running in order to trigger notifications, you'll want to install it on a computer that you have running all the time (e.g. the computer you use for other home automation tasks).

This companion app, as well as instructions for how to install, configure and run it, are available here:

[https://github.com/thestudiojq/thermostat-control-companion](https://github.com/thestudiojq/thermostat-control-companion)

## API key

In order to connect the phone app to the computer app, you'll need to use an API key. You must generate the API key yourself, and it must be in valid **UUIDv4** format. If it isn't in this format, it will be rejected and you won't receive push notifications. There are may places that you can generate a UUIDv4 key. For example:

[https://generate-uuid.com](https://generate-uuid.com)

For info on how to add this key to the iPhone app, see the [Config]({{ 'config' | relative_url }}) section.

For info on how we store and use this key, see the [Security]({{ 'security' | relative_url }}) section.
