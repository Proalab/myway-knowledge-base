---
description: >-
  Learn why routes might not look optimal and what settings affect optimization
  quality.
---

# The route MyWay produced doesn't look correct?

{% hint style="info" %}
**Using MyWay on Android?** This page describes the iOS app version 3. See [Version 2 of this page](https://help.mywayroute.com/v2/faq/the-route-myway-produced-doesnt-look-correct).
{% endhint %}

## How optimization works <a href="#vehicleroutingproblemdescription" id="vehicleroutingproblemdescription"></a>

MyWay uses data from Google Maps, Mapbox, HERE, TomTom, Apple Maps, ArcGIS and OpenStreetMap and simulates thousands of combinations to find the most efficient route. Still, the result might not always match your expectations.

The optimization algorithms consider stop priorities, time windows, vehicle capacity, road conditions, traffic, tolls, U-turns, side of road, left turns, weather and more. [You can adjust some of these settings to suit your needs](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization); others are fixed or depend on the road layout and limits. Below are the questions we hear most often and why these things happen.

## ETAs seem incorrect

ETAs can differ from actual arrival times for a few reasons: a wrong time at stop (the most common one; usually it's too short or too long), changing traffic, or the navigation app taking you a different way. When you update your route in MyWay, it recalculates the ETAs with the latest weather, traffic and stop order changes. We recommend [updating your route](../guides/how-to-use-myway-route-planner.md#update-and-actualize-route) every time you change it, so the ETAs stay accurate.

## Why does my route not look "optimal"?

Usually it's because the settings don't match your preferences. For example, if you turn off U-turns, the app avoids them even where a U-turn would make the route faster. [Adjust the settings](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization) to match how you really drive, and you'll get better results.

### Why do I return to previously visited areas?

The most efficient route often looks like a clover: you come back to areas you've already visited. It may seem counterintuitive, but shortcuts like crossing the street or avoiding U-turns usually take more time, add risk and are less convenient. The clover shape comes from settings like [Optimization Mode, Allow U-turns on Waypoints and Side of Road (Any Side by default)](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization). Adjusting them can improve the route while keeping risks low and following traffic rules.

### Why does a non-optimized (my own order) route seem faster?

A route in your own order ignores time windows and other constraints, so it can look faster. In practice, it greatly increases the chance of missed stops and failed deliveries. MyWay shows all the issues it can catch on the optimization screen.

## Road Settings that affect route optimization <a href="#settings-that-affect-route-optimization" id="settings-that-affect-route-optimization"></a>

You'll find these settings in two places:

* **Route Settings** below the stop list while you plan a route: Vehicle, Side of Road, Optimization Mode and Road Restrictions.
* Open the menu (☰, top right) and tap **Preferences** > **Directions**: Allow U-turns on Waypoints and Snap to Road.

### **Vehicle Type**

[Vehicle Type](../guides/understand-vehicle-settings.md) is a very important setting: it decides which roads are available to you. If you drive a car, it's straightforward, and Car is the default. If you drive a van or a truck, the optimization algorithm tries to avoid small roads and penalizes intersections. It also knows which areas are off-limits for trucks (like tunnels, low bridges or restricted roads) and avoids them, so your route may look longer, but it will suit your vehicle. Choose **Truck** only when you drive a big truck, not a small one. If you drive a van, stick to **Van** or even **Car**. If you see issues after changing the vehicle type, see [this article](why-do-some-of-my-stops-have-issues-path-not-found-or-unexpected-error.md).

MyWay builds the route for your vehicle, but turn-by-turn directions come from your navigation app, and it builds its own path between stops. **Set the same vehicle type in your navigation app**, so it leads you along roads your vehicle can use. Some apps don't support trucks at all: Google Maps, for example, doesn't take truck restrictions (low bridges, weight or height limits) into account. If you drive a truck, use a navigation app made for trucks. See [Understand Vehicle Settings](../guides/understand-vehicle-settings.md).

### **Optimization Mode**

[Optimization Mode](../guides/understand-route-settings.md#optimization-mode) is one of the most fundamental settings for route optimization. There are two options: **Optimize for Time** (more efficient) and **Optimize for Distance**.

Clearly, the "best route" means different things to different people. For most people, the best route is the fastest one. For some, though, it's the shortest path. And some prefer a trip that uses highways or avoids tolls and tunnels. Besides, the fastest or shortest route isn't always the most efficient. For instance, the quickest route might have many left turns, and the shortest one might go through heavy traffic. On both of these routes, your fuel consumption goes up significantly. And what if the fastest route is three minutes faster but several miles longer? Is it still efficient? What if the shortest path saves you 5 miles but takes you through two tolls? Is that efficient? Pick the option you believe will serve you better, or keep the default, **Optimize for Time**.

### **Allow U-turns on Waypoints**

The app can build more efficient routes when **Allow U-turns on Waypoints** is on (**Preferences** > **Directions**; on by default). The downside is more U-turns, which are sometimes less convenient and less safe if you drive a bigger vehicle. Turning U-turns off can make the route longer. Below is an example of how this setting changes the route: on the left, the app suggests a U-turn; on the right, it goes through a roundabout.

<div><figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.50.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned ON</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.47.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned OFF</p></figcaption></figure></div>

### **Side of Road**

**Side of Road** tells the app which side of the road you (as a driver) want to park on:

* **Any Side**: the app builds the most optimal route, but sometimes you park on the other side from your stop and cross the road.
* **Same Side as Stop**: you don't have to cross the road, but the route may be longer.
* **Across from Stop**: you park on the opposite side and cross the road on foot.

### **Snap to Road**

**Snap to Road** (**Preferences** > **Directions**, on by default) moves each stop to the nearest point on a main road, so the route and navigation avoid backyards and service roads. The point may be a bit farther from the actual location. Turn it off if your stops are inside large areas (like campuses or industrial parks) and you need to drive closer to the entrance.

### **Road Restrictions**

[Road Restrictions](../guides/understand-route-settings.md#road-restrictions) let you avoid highways, ferries, toll roads and unpaved roads. Avoiding them can make the route longer.

{% hint style="info" %}
Examples:

**If you need the most efficient (convenient) route,** choose **Optimize for Time**, turn off U-turns and pick the side of road you want (or keep the default settings). The route might look like a clover.

**If you need the best-looking (but not optimal) route,** choose **Optimize for Distance**, allow U-turns and keep **Any Side**.
{% endhint %}

## Stop Settings that affect route optimization

### Time at Stop (Service Time)

Time at stop has a big effect on the total route time and can play a significant role when you build your route. [Make sure you set the right time at stop](what-service-time-should-you-choose.md) when you plan your route.

### Time Windows

Time windows play a crucial role in route optimization. A time window is the interval when a delivery or visit must happen. The app schedules every stop within its time window, which can change the route order and timing a lot.

If a stop has a strict time window, the app may prioritize it even if that breaks the most efficient sequence geographically. This can cause detours or shift the timing of other stops. The more [restrictive the time windows](../guides/understanding-stop-settings.md#time-windows), the more they affect the optimization, often at the cost of distance or total time. [Priority](../guides/understanding-stop-settings.md#priority-asap-button) also affects optimization: **First** stops stay at the beginning of the route, **Last** stops at the end, and **High** stops are visited among the first.

## My route goes "forward/backward" direction from what I need.

Routes don't have a "forward" or "backward" direction: a route is either optimal or not. The app builds the most efficient path based on all the parameters described above, including the start and end locations. If the route seems "backward" from what you need, try removing the end location: this makes it less likely. Keep in mind that the app still optimizes the route, so the order may not match exactly what you want.

You can also reverse the route yourself: tap **…** in the route header > **More** > **Reverse Stop Order**. This flips the stop order (except priority stops).

## How to report bad optimization?

Open the menu (☰, top right) and tap **Talk to Us**. Write us a message, and we will try to fix the optimization for you. Add a screenshot that shows the issue and [share the route copy](../guides/export-your-route-and-share-it-with-others.md#share-route-copy) with us, so we can see the problem on our side.

You can also tell us when you complete a route: MyWay asks "How was your route?". Tap **Had Issues** and then **Send Feedback**: the chat opens with your route attached, so we can see which route you mean.

The app can optimize full-loop routes and even routes without an end location. We work with thousands of drivers across the globe to make sure the optimization works as efficiently as possible.
