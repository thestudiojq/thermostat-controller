---
layout: page
title: Using
permalink: using
---

# Using the app

Using the app is also pretty straightforward. After you've added in the IP address [on the settings page]({{ 'config' | relative_url }}), you'll then be able to read your thermostat data and control it.

*Note: Your Venstar thermostat has a local API. This app is interacting with this local API. Meaning, if your phone isn't connected to the same Wi-Fi network as your thermostat, you won't be able to read from it or control it. (Unless you use DDNS, but that is an advanced topic not covered here and not encouraged unless you're experienced/comfortable implementing/configuring it.)*

## What's this I see?

In the area under the thermostat name, you will see four pieces of data. The top left shows the current temperature from the thermostat. The top right shows the humidity level. The bottom left shows the fan state. When it's set to always on, it will just show **ON**. When it's set to auto, it will show **AUTO** and the current state (**off** or **on**). The bottom right shows the runtime for today.

The temperature inside the circle is the current set temperature of the thermostat. If you have your thermostat on auto mode, then you can see the current set heat temp by pressing the **H** button and the current set cool temp by pressing the **C** button.

When the system is heating, the circle will be <span style="color: #FF5555; font-weight: 700;">red</span>. When it is cooling, the circle will be <span style="color: #8BE9FD; font-weight: 700;">blue</span>. When it is idle, the circle will be a faint colour, closer to the background colour. 

The button under the plus and minus buttons shows the current mode.

The time readout at the bottom shows the time of the last refresh. It is also occasionally used to read out messages (e.g. please refresh or update failed, etc.).

## Refreshing the data

Refresh the theromostat data as often as you want by pressing the refresh icon or by pulling to refresh.

## Change the set temperature

Use the minus button to decrease the set temperature and the plus button to increase it. If you have your thermostat on auto mode, then you can control the heat and cool temperatures separately by pressing the **H** and **C** buttons.

## Change the mode

The button under the plus and minus buttons shows the current mode. If you press this button, you will be able to change the mode to off, heat, cool or auto.

## Change the fan mode

You can change the fan mode by pressing on the area that reads out the fan data (bottom left of the area at the top of the screen.)

## Runtimes

If you tap the area that reads out today's runtime (bottom right of the area at the top of the screen), it will bring up another screen that shows all of the runtimes for the past week as well as the average daily runtime for the past week.

Note that the displayed runtime is for stage 1 and is based on your selected mode. i.e. If you have the mode set to cool, it will show cooling times. If you have it set to heat, it will show heating times. And, if you have it set to auto, it will show a combination of heating and cooling times.
