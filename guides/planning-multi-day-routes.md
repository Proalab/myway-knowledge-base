# Planning Multi-Day routes

{% hint style="info" %}
**Using MyWay on Android?** This page describes the iOS app version 3. See [Version 2 of this page](https://help.mywayroute.com/guides/planning-multi-day-routes).
{% endhint %}

MyWay Route Planner, like no other apps on the market, supports multi-day routes, road trips, and travels and has many settings that can help you build, follow, and understand routes better.

<div>

<figure><img src="../.gitbook/assets/AB6E8348-31B2-417E-AB44-1ACD66435298.PNG" alt="" width="188"><figcaption><p>Multi-Day Optimization</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/71EDB218-ACF0-45E5-B462-DC6EE9C78174.PNG" alt="" width="188"><figcaption><p>Multi-Day Trip</p></figcaption></figure>

</div>

However, when you plan a multi-day route, you must be aware of a few things. When you see a small "+1" (or "+2", etc.) next to a time in the stop list, it means this time falls on the next day (or later) after the route start. This is very similar to what you see when you buy plane tickets. To plan the start of a route, set the departure time ("Depart at…") under [Route Settings](how-to-use-myway-route-planner.md#route-settings).

### Time Zones

Almost all route planner apps on the market show you the time and ETAs of all stops in your local time zone. It makes the routes they build inaccurate if you drive through time zone changes or set time windows for locations in different time zones. MyWay, on the other hand, knows the time zone of the stops you add and applies the correct time zone to time windows and ETAs. This is similar to how airlines show arrival times in the destination time zone. If a stop's time zone differs from your iPhone's time zone, you will see the time zone next to the time (like GMT+2).

### Time Windows

The next thing is the Time Window. A time window does not have a date, only a period From - To. MyWay places it on the right day relative to the route start (your departure time):

* **If the window ends before the route starts**, MyWay moves the whole window to the next day.
* **If "To" is earlier than "From"** (for example, From 10 PM, To 2 AM), it's an overnight window that ends the next day.
* **Only "From"**: you arrive at the stop any time after this time, starting from the route start day.
* **Only "To"**: you arrive at the stop before the nearest such time after the route start.

{% hint style="info" %}
If your route starts at 10 AM and the time window for some stops is From 04 AM - To 06 AM, the window ends before the route starts, so MyWay places it on the next day: from 4 AM to 6 AM tomorrow.

If your route starts at 10 AM and the time window for some stops is From 02 AM - To 09 AM, the window also ends before the route starts, so MyWay moves it to the next day as well.
{% endhint %}
