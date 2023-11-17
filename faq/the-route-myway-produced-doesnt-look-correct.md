---
description: Learn why routes might not look optimal at first glance.
---

# The route MyWay produced doesn't look correct?

With access to the most up-to-date maps, addresses, and places databases from Google Maps, Mapbox, Here, and OpenStreetMap, MyWay calculates your optimal route by simulating thousands of combinations to determine the most efficient order. However, in some cases, the route built might look different from what you believe is optimal.

## Problem description <a href="#vehicleroutingproblemdescription" id="vehicleroutingproblemdescription"></a>

The route optimization algorithms build a route based on hundreds of parameters and take all stop settings (like stop priorities and time windows) into account. Those algorithms also consider specific route settings like allowing u-turns, roadside, etc. as well as road conditions, vehicle capacity constraints, left turns, tolls, and tunnels. All those settings combined may significantly affect an optimized route, and we recommend sticking to default settings (Any Road Side, Snap Location to the Road, and Allow U-turns) if you want to get the "most optimal route ever". However, [sometimes changing some of those settings to your specific needs might serve you better](the-route-myway-produced-doesnt-look-correct.md#options-that-affect-route-optimization.). Even if it increases the route distance, it can provide you with much convenience in return.

## Why does my route not look "optimal"?

In some cases, you might feel like the route built is not optimal, and you see some "improvements," like visiting a few stops without going back to the vehicle or simply making a u-turn where traffic signals do not recommend it. One of the reasons why you might see that is that you did not choose all settings to your liking in the first place. Let's say you did not allow the app to make u-turns, but in reality, you are okay with them. We recommend setting your route setting as close to your reality as possible. In this case, the app provides you with much better results.

### Why does the app make me return to the areas I have visited

The most efficient route will most likely have a clover shape. That's why, in some cases, you'll end up returning to the same neighborhoods in one route. It might look bizarre from the first point of view. It happens because of three parameters in the app settings: Optimization type, Allow U-turns, and Road Side (Any Road Side by default). By changing these settings, you can find the best possible result in optimization that works for you.

### Why not optimized route (in my current order) take less time than the optimized one?

When the app builds a route keeping your order, it ignores all time windows. In case you build a route without optimization, your route really can take less time, but you will not meet stop requirements, so the rate of unsuccessful visits/deliveries is going to be very high.

## Settings that affect route optimization.

### **Optimization type**

Optimization type is one of the most fundamental settings that affect route optimization. There are two options available. Optimization by time (more efficient) and optimization by distance.&#x20;

Clearly, the “best route” means different things to different people. For most people, the best route would be the fastest one. For some, though, it may be the shortest path. And some may prefer a trip that uses highways or avoids tolls and tunnels. Besides, the fastest or shortest route may not always be the most efficient. For instance, the quickest route might have many left turns, and the shortest mileage route may drive through heavy traffic. In both these route options, your fuel consumption will go up significantly. Also, what if the fastest route is three minutes faster but several miles longer? Is it still an efficient one? What if the shortest path allows you to drive 5 miles less but makes you go through two tolls? Is it an efficient one? Pick the one you believe will serve you better or keep Optimization by time by default.

### **Allow U-turns**

The app can build more efficient routes if you turn on Allow U-turns settings in the app settings (it's turned off by default). The downside of this is going to be more u-turns, which in most cases are less efficient from the time perspective and less safe if you drive a longer vehicle. Below, you can see an example of how this setting affects route optimization. On the left option, the app will suggest making a u-turn and on the right one to go through a roundabout.

<div>

<figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.50.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned ON</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/photo_2022-11-25 20.32.47.jpeg" alt="" width="375"><figcaption><p>Allow U-turns turned OFF</p></figcaption></figure>

</div>

### **Road Side**

Road Side setting, on the other hand, is responsible for app behavior that builds routes considering your preference (as a driver) to cross the road. If you choose "Any roadside," the app will build the most optimal route, but sometimes you have to park on another side from your stop and cross the road. If you choose "Same Side, " you don't have to cross the road, but the road will be longer.

{% hint style="info" %}
Examples:

**If you need the most efficient route,** please choose optimization type by time, turn off the allow u-turns setting, and pick the roadside you want (or keep default settings). In this case, the route might look like a clover shape.

**If you need the best-looking (but not optimal) route,** please choose optimization by distance, allow u-turns, and keep the roadside setting by default (any side of the road).
{% endhint %}

### **Vehicle Type**

Vehicle Type is the last but not least setting that affects the optimized route. If you drive "car," it's pretty straightforward, and you don't need to change anything. However, if you are a van or truck driver, the optimization algorithm will try to avoid small roads and penalize intersections. The algorithm also knows which areas are not allowed for truck drivers (like tunnels, low bridges, or restricted roads) and will avoid that, so your route will look longer but will be suitable for your specific vehicle type. Also, pick "truck" as a vehicle type only when you drive a big truck, not a small one. For the van option, stick to "van" or even a "car." If, after changing your vehicle type, you see some issues, please check [this article](why-some-of-my-points-are-marked-as-incorrect-or-path-not-found-or-unexpected-error.md).

## My route goes "forward/backward" direction from what I need.

None of the route planners has the concept of forward/backward routes, as the app simply builds the most efficient route based on time windows, start location, and finish location. If your route looks " backward, " you can simply delete the end location and leave it blank. It does not mean the app will build a route precisely as you need ([for this use case, you can build a route without optimization in the order you want](../guides/how-to-use-myway-route-planner.md)), but the chance of getting a backward route will be much lower. Also, you can go to route options (3 dots next to route name) > More > Reverse route. In this case, all stops in your route will be reversed, and the stop order will change.&#x20;

## How to report bad optimization?

In MyWay Route Planner, click on a menu icon in the top right. Then go to "Routes," click on three dots next to the route you want to report, and choose the option "Report an Issue". Write down a message to us, and we will try to fix optimization for you. Please also share a screenshot that highlights the issue so we can easily see a problem on our side.

Also, you can report lousy optimization when you have an active route. Please click on the three dots at the top left side when you have an active route and choose the option. "Report an Issue". Write down a message to us, and we will try to fix optimization for you.

The app can optimize full-loop routes and even routes without an endpoint. We work with thousands of drivers across the globe to make sure the optimization works as efficiently as possible.&#x20;

####

