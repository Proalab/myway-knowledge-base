# Planning Multi-Day routes

MyWay Route Planner, like no other apps on the market, supports multi-day routes, road trips, and travels and has many settings that can help you build, follow, and understand routes better.

<div>

<figure><img src="../.gitbook/assets/AB6E8348-31B2-417E-AB44-1ACD66435298.PNG" alt="" width="188"><figcaption><p>Multi-Day Optimization</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/71EDB218-ACF0-45E5-B462-DC6EE9C78174.PNG" alt="" width="188"><figcaption><p>Multi-Day Trip</p></figcaption></figure>

</div>

However, when you plan a multi-day route, you must be aware of a few things you might need to remember. When you see the +1 index next to the time, that means this time has a place the next day. This is very similar to what you see when you buy plane tickets.

### Time Zones

Almost all route planner apps on the market show you time and ETAs of all stops in your local time zone. It makes routes they build inaccurate if you drive through time zone changes or set time windows for locations in different time zones. MyWay, on another side, knows the time zone of stops you add and will apply the correct time zone to time windows and ETA's. It will also show you when the time zone will change. This is similar to how airlines show arrival times in the destination time zone. If there's a time zone difference between your time zone and the stop's time zone, you will see additional time zone information (like GMT +03:00).

### Time Windows

The next thing is the Time Window. The Time Window setting does not have a concept of the day but simply a period From - To. We have a pretty intelligent algorithm that predicts if the time window belongs to another day (if you plan a multi-day route), but in a nutshell, you can use the rule of 4 hours to understand the app logic. If you plan the route and set time windows at the latest time 4 hours later than your start time (or earliest 8 hours later than start time), then it will almost certainly be pushed to another day.

{% hint style="info" %}
If your route starting time is 10 am and the time window for some stops is set Earliest(From) 04 am - Latest(To) 06 am, the app will assume that the time window is set for tomorrow. It will calculate the time difference between the route start time and the latest time, and if the time is greater than 4 hours, it will move the time window to another day and show +1 next to it.&#x20;

If your route starting time is 10 am and the time window for some stops is set Earliest(From) 02 am - Latest(To) 09 am. In this case, the time window will be moved as the stop's latest time is earlier than the route start time and the stop's earliest time is more than 8 hours earlier than the route start time.

There is much more logic, but these rules always work.
{% endhint %}
