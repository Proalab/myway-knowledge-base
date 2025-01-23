---
description: >-
  Learn why routes might not look optimal and what settings affect optimization
  quality.
---

# The route MyWay produced doesn't look correct?

## How optimization works <a href="#vehicleroutingproblemdescription" id="vehicleroutingproblemdescription"></a>

MyWay uses data from Google Maps, Mapbox, Here, ArcGis, Apple, and OpenStreetMap to calculate the most efficient route by simulating thousands of combinations. However, the result might not always match your expectations.

The optimization algorithms consider factors like stop priorities, time windows, vehicle capacity, road conditions, traffic, tolls, u-turns, roadside preferences, left turns, weather, and more. [Some of these settings can be adjusted to suit your needs](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization), while others are fixed or influenced by road layout and limits. Below are common issues and explanations for why they occur.

## ETAs seem incorrect

ETAs may differ from actual arrival times for a few reasons: incorrect service times (the most common one, usually it's too short or too long), changing traffic, or the navigation app sending you on a different route. You can update your route in MyWay to recalculate ETAs, reflecting the latest weather, traffic, and stop order changes. We recommend [updating your route](../guides/how-to-use-myway-route-planner.md#update-and-actualize-route) whenever it's modified to keep the ETAs accurate.

## Why does my route not look "optimal"?

If the route seems inefficient, it might be due to settings not aligning with your preferences. For example, if you don’t allow U-turns, the app will avoid them even if they would make the route faster. [Adjusting settings](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization) to match your real-world preferences can lead to better results.

### Why do I return to previously visited areas?

The most efficient route often resembles a clover shape, meaning you may revisit areas you already visited. While it might seem counterintuitive, shortcuts like crossing streets or avoiding U-turns usually take more time, add risks, and reduce convenience. The clover shape results from settings like [Optimization Type, Allow U-Turns, and Road Side (set to Any Road Side by default)](the-route-myway-produced-doesnt-look-correct.md#settings-that-affect-route-optimization). Adjusting these can improve the route while minimizing risks and ensuring compliance with traffic rules.

### Why does a non-optimized (my own order) route seem faster?

A non-optimized route ignores time windows and constraints, which can make it seem faster. However, this greatly increases the chances of missed stops or deliveries, leading to a higher rate of unsuccessful visits. MyWay will show all possible issues it might catch on the optimization screen.

## Road Settings that affect route optimization.

### **Vehicle Type**

[Vehicle Type](../guides/understand-vehicle-settings.md) is a very important setting that determines what is available and what is not. If you drive a "car," it's pretty straightforward and it's set by default. However, if you are a van or truck driver, the optimization algorithm will try to avoid small roads and penalize intersections. The algorithm also knows which areas are not allowed for truck drivers (like tunnels, low bridges, or restricted roads) and will avoid that, so your route will look longer but will be suitable for your specific vehicle type. Also, pick "truck" as a vehicle type only when you drive a big truck, not a small one. For the van option, stick to "van" or even a "car." If, after changing your vehicle type, you see some issues, please check [this article](why-do-some-of-my-stops-have-issues-path-not-found-or-unexpected-error.md).

### **Optimization type**

[Optimization type](../guides/understand-optimisation-settings.md) is one of the most fundamental settings that affect route optimization. There are two options available. Optimization by time (more efficient) and optimization by distance.&#x20;

Clearly, the “best route” means different things to different people. For most people, the best route would be the fastest one. For some, though, it may be the shortest path. And some may prefer a trip that uses highways or avoids tolls and tunnels. Besides, the fastest or shortest route may not always be the most efficient. For instance, the quickest route might have many left turns, and the shortest mileage route may drive through heavy traffic. In both these route options, your fuel consumption will go up significantly. Also, what if the fastest route is three minutes faster but several miles longer? Is it still an efficient one? What if the shortest path allows you to drive 5 miles less but makes you go through two tolls? Is it an efficient one? Pick the one you believe will serve you better or keep Optimization by time by default.

### **Allow U-turns**

The app can build more efficient routes if you turn on Allow U-turns settings in the app settings (it's turned off by default). The downside of this is going to be more u-turns, which in most cases are less efficient from the time perspective and less safe if you drive a bigger vehicle. Below, you can see an example of how this setting affects route optimization. On the left option, the app will suggest making a u-turn and on the right one to go through a roundabout.

<div><figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.50.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned ON</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.47.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned OFF</p></figcaption></figure></div>

### **Road Side**

Road Side setting, on the other hand, is responsible for app behavior that builds routes considering your preference (as a driver) to cross the road. If you choose "Any roadside," the app will build the most optimal route, but sometimes you have to park on another side from your stop and cross the road. If you choose "Same Side, " you don't have to cross the road, but the road will be longer.

{% hint style="info" %}
Examples:

**If you need the most efficient (convenient) route,** please choose optimization type by time, turn off the allow u-turns setting, and pick the roadside you want (or keep default settings). In this case, the route might look like a clover shape.

**If you need the best-looking (but not optimal) route,** please choose optimization by distance, allow u-turns, and keep the roadside setting by default (any side of the road).
{% endhint %}

## Stop Settings that affect route optimization

### Service Time

Service Time greatly affects overall route time and can play a significant role when you build your route. [Please make sure you set the correct service time ](what-service-time-should-you-choose.md)when you plan your route.

### Time Windows&#x20;

Time windows play a crucial role in route optimization. Each stop has a designated time window—an interval when deliveries or visits must occur. The app ensures that all stops are scheduled within their time windows, which can significantly influence the route order and timing.

If a stop has a strict time window, the app may prioritize it even if it's not in the most geographically efficient sequence. This can cause the route to take detours or adjust the timing of other stops to meet these constraints. The more [restrictive the time windows](../guides/understanding-stop-settings.md#time-windows), the more they can impact the overall optimization, often at the expense of shorter distances or faster completion times. [ASAP flag](../guides/understanding-stop-settings.md#priority-asap-button) also affects optimization algorithms, pretty much enforcing visit a stop with ASAP flag a first stop in the list.

## My route goes "forward/backward" direction from what I need.

Routes don't follow a "forward/backward" concept. Route has two states, it's either optimal or not. The app builds the most efficient path based on many parameters that we described above, but also has, start, and end locations. If the route seems "backward," from what you need try removing the end location to reduce this chance. Keep in mind, that app still optimizes the route and may not perfectly match your desired order.

Alternatively, you can manually reverse the route by going to route options (three dots next to the route name) > More > Reverse Route. This flips the stop order to better suit your needs.

## How to report bad optimization?

In MyWay Route Planner, click on a menu icon in the top right. Then go to "Routes," click on three dots next to the route you want to report, and choose the option "Report an Issue". Write down a message to us, and we will try to fix optimization for you. Please also share a screenshot that highlights the issue so we can easily see a problem on our side.

Also, you can report lousy optimization when you have an active route. Please click on the three dots at the top left side when you have an active route and choose the option. "Report an Issue". Write down a message to us, and we will try to fix optimization for you.

The app can optimize full-loop routes and even routes without an endpoint. We work with thousands of drivers across the globe to make sure the optimization works as efficiently as possible.&#x20;

