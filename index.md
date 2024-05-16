---
layout: default
title: Thermostat Controller iPhone app for Venstar
---

# About

**Thermostat Controller** is an iPhone app that lets you view the data from and control your **Venstar** thermostat locally.

*Note: Your Venstar thermostat has a local API. This app is interacting with this local API. Meaning, if your phone isn't connected to the same Wi-Fi network as your thermostat, you won't be able to read from it or control it. However, you will still get [push notifications]({{ 'push' | relative_url }}) if those are enabled.*

## Data you can view

* Current temperature
* Set temperature
* Humidity
* Mode
* Fan state
* Runtimes
  * Today's runtime
  * Runtime for each day of the past week
  * The average daily runtime for the past week

## What you can control

* Increase/decrease the set temperature
* Change the mode (heating, cooling, auto)
* Change the fan mode (always on or auto)

## Push notifications

Optional push notifications are available to let you know when the thermostat state changes from idle to active (e.g. heating or cooling) or vice versa. These push notifications require the companion app to be running on a computer as well as an API key. More info [here]({{ 'push' | relative_url }}).
