---
description: Route modes, stop parameters, optimization modes, etc.
---

# How to use MyWay Route Planner

MyWay Route Planner is a very straightforward planner that will help you build your routes in seconds. After downloading the app from [Apple AppStore](https://apps.apple.com/us/app/delivery-route-planner-myway/id1557014712) or [Google Play Market,](https://play.google.com/store/apps/details?id=com.proalab.mywayapp) you need to open it, and the first thing you see is the app's main screen.

## Build and Edit Routes

### Add Stops

<figure><img src="../.gitbook/assets/31E7C164-62C4-4D63-BF39-61DC41908108.PNG" alt="" width="188"><figcaption><p>Main Screen (Route Edit Mode)</p></figcaption></figure>

All you need to do is add your first stop (and as many stops as you want), your Start Location, and End Location (optional). The route must have a Start Location, but the End Location is optional. **To add a stop, you can either click the "Add Stop" button, check the screenshot above, or the magnifier button at the top left corner of the app.** You also can [save Start and Finish](understanding-stop-settings.md#start-and-finish-settings) locations as a default for future routes.

**There are multiple sources you can add addresses from, like basic "address search," "map,"** [**"places,"**](managing-your-contacts-and-places.md#places) [**"contacts,"**](managing-your-contacts-and-places.md#contacts) [**"list,"**](import-from-file-and-multi-line-import.md) [**"file,"**](import-from-file-and-multi-line-import.md) [**"from an external link,"**](export-your-route-and-share-it-with-others.md#share-route-copy) **"photo", and "dictation (audio input)."** Check the screenshot below to see what the "Add Stop" process looks like.

<figure><img src="../.gitbook/assets/IMG_05721C672DDD-1.jpeg" alt="" width="188"><figcaption><p>Add Stop options</p></figcaption></figure>

{% tabs %}
{% tab title="iOS - Photo and Voice Input" %}
**IOS**

**Photo Input -** If you don't see a photo icon in search input, it means your iPhone or iOS does not support photo input - [https://support.apple.com/en-au/guide/iphone/aside/iph691752bc0/17.0/ios/17.0](https://support.apple.com/en-au/guide/iphone/aside/iph691752bc0/17.0/ios/17.0) or does not support your language - [https://www.apple.com/ios/feature-availability/#live-text-live-text](https://www.apple.com/ios/feature-availability/#live-text-live-text)

\
**Voice Input -** If you don't see dictation input (microphone icon), you might want to turn on dictation in iOS settings - [https://support.apple.com/en-au/guide/iphone/iph2c0651d2/ios](https://support.apple.com/en-au/guide/iphone/iph2c0651d2/ios)
{% endtab %}

{% tab title="Android  - Photo and Voice Input" %}
**Android:**

**Photo Input -** Android currently does not support photo search input, but we will be adding that feature in the future.&#x20;



**Voice Input -** If you don't see dictation input (microphone icon), please follow this instruction to turn it on - [https://support.google.com/gboard/answer/2781851?hl=en\&co=GENIE.Platform%3DAndroid](https://support.google.com/gboard/answer/2781851?hl=en\&co=GENIE.Platform%3DAndroid) also some manufacturers have a different way to turn it on, please refer to your phone manual.
{% endtab %}
{% endtabs %}

If you want to add multiple stops at once please add them by using the "+" button, if you want to see where is that stop on the map first please click on the address in a list (on the left side from the + button).

{% hint style="warning" %}
Some addresses may be missing from the search. If this is the case we recommend adding more details to the search address filed and if it does not help to change a geocoding provider. MyWay is the first and only app on the market that supports multiple address geocoding providers. [You can change it in the app settings.](../i-cant-find-an-address.md#changing-data-provider-address-geocoding-service)
{% endhint %}

## Route Parameters (Route Settings)

After you add all necessary stops at the bottom of the Main Screen in Route Editing Mode, you can find route settings like [Vehicle Type](understand-vehicle-settings.md), Departure Time, [Avoid options](how-to-use-myway-route-planner.md#avoid-options), Road Side (for all stops in the route, can be: any side of the road, your driving direction side or opposite road side), and [Optimization Mode (Time/Distance)](how-to-use-myway-route-planner.md#optimization-mode). After you add all your stops and choose suitable parameters, you need to click the big blue button on the bottom right side, and the app will provide you with a few route options (similar to what Nav apps do).&#x20;

**All route parameters are very important and can dramatically change your route time, distance and it looks**. We recommend taking some time to experiment with them, because there is no one fits all solution. At the end, you will get a route that looks exactly how you want it set up for your specific needs.

{% hint style="info" %}
When planning future routes with a “Departure Time” set in advance, you can optimize the route and view ETAs. However, avoid clicking the “Start Now” button, as it will recalculate all ETAs to reflect the current time. This ensures you always have accurate ETAs exactly when you go on route (click "Start Now" button). \
Just remember - when you’re ready to begin your route, click “Start Now” and mark your “Start Location.”
{% endhint %}



<figure><img src="../.gitbook/assets/Screenshot 2024-07-08 at 13.56.00.jpeg" alt="" width="188"><figcaption><p>Route Parameters</p></figcaption></figure>

### Optimization Mode

**One of the most important settings that can dramatically change route and its convenience is Optimization Mode.** Optimization Mode has two options: by Time and by Distance. This setting is general and affects optimized routes provided by the app and routes in your order.&#x20;

**Optimization by Time is preferable in 90% of cases.** Optimization by Time is how most Navigation Apps build your routes, and the route provided can be a little longer from a distance perspective but much more efficient from a fuel economy perspective and driver convenience. Route optimized by time usually has fewer cross-turns, fewer traffic lights, and fewer route changes.

Optimization by Distance is a use case that can shorten your route by sacrificing convenience and time. Route optimized by distance usually has more cross-turns, traffic lights, and route changes. In most cases, this distance saved does not justify convenience sacrifice but can be helpful for those drivers who know places very well.

### Avoid Options

Avoiding is the simple way to exclude some specific parts of the route, like highways, ferries, etc., from the final route. Note that those route elements, like highways, are sometimes required to complete a route, so it's not guaranteed that all chosen elements (like highways) will be excluded entirely.

{% hint style="warning" %}
Please keep in mind that you need to set avoid settings in your Navigation Apps the same way you set them in MyWay. Some Nav apps can not receive these settings from an external app, so the Nav app will ignore these when you pass the route to the Nav app.
{% endhint %}

## Stop's Settings

Yeach stop has[ stop parameters like time windows, priority, notes, color, etc](understanding-stop-settings.md). To change stop settings, click on the stop added to the route.

{% hint style="info" %}
Please remember that the "Optimization for Distance" setting can ignore stop settings like priority and time windows. The only option that supports time windows and priority setting in full is "Optimization for Time."
{% endhint %}

{% hint style="danger" %}
_When you add stops, please pay attention to the warnings and errors MyWay is showing you. For example, if the app believes the stop is incorrect or placed in the wrong place (like another country), it will show you an orange exclamation mark next to the stop. If you get any errors, please check_ [_our article that explains what they mean and how to get them sorted_](../faq/why-do-some-of-my-stops-have-issues-path-not-found-or-unexpected-error.md)_._
{% endhint %}

MyWay Route Planner also supports multi-day routes. If you want to know how to build them, please [check this article](planning-multi-day-routes.md).

When you are done with all route parameters and all stops added, you need to click on a blue button with two arrows on the bottom right side of the screen. After you do that, the route will be sent to the route builder, and you will be presented with Optimization Options.

## Optimization Options (Build and Optimize your route)

After you add all stops and set route parameters you can build the route and pick the optimization option. To build the route simply press the blue button with 2 arrows on the bottom right side. After you do that MyWay will build routes and allow you to choose from two options.

<figure><img src="../.gitbook/assets/Screenshot 2024-07-08 at 14.02.19.jpeg" alt="" width="188"><figcaption></figcaption></figure>

[Optimization options](understand-optimisation-settings.md) like the "Current" option mean the stop order will stay as you added them (the app will not optimize the stop order), and the "Optimized" option means the stops order will be optimized for either [fastest or quickest](how-to-use-myway-route-planner.md#optimization-mode).&#x20;

![Choose optimization type.](../.gitbook/assets/7BED01AC-A777-44AC-A05A-71EE5F247974.PNG)

{% hint style="warning" %}
Sometimes, an optimized route traveling time or distance can be more significant or take more time than the route without optimization. It happens because optimization considers all stop parameters. [Parameters like "time windows," "priority," and "service time" will affect your route's overall time and distance](understanding-stop-settings.md)Don't worry. Our **algorithm built the most efficient route possible, considering all these parameters**. It just may look like it is less efficient than the current order, as the current order simply ignores all parameters. If you want more about this, please check our [article that explains how the route optimization algorithm works](../faq/the-route-myway-produced-doesnt-look-correct.md).
{% endhint %}

{% hint style="warning" %}
MyWay will show you late arrivals and [issues](../faq/why-do-some-of-my-stops-have-issues-path-not-found-or-unexpected-error.md#stops-with-issues) so you can make informed decisions about what to do with them. In some cases, like tight time windows or messed stop priorities, there is a possibility that the algorithm can't find the best order that satisfies all parameters. Sometimes, the app can't even build your (Current) order as there are many issues with stops. In this case, the app will show you a warning and will suggest you modify some of those stops (or simply skip them). It will show you late arrivals and issues so you can make informed decisions about what to do with your stops.
{% endhint %}

<div><figure><img src="../.gitbook/assets/5F8EB0C0-74FA-4E04-9E17-9091301ECD1A.PNG" alt="" width="188"><figcaption><p>Late Arrival</p></figcaption></figure> <figure><img src="../.gitbook/assets/6604EF22-6539-452A-BF72-E17CF903FA08.PNG" alt="" width="188"><figcaption><p>Optimization Warning</p></figcaption></figure></div>

{% hint style="info" %}
Our users also told us that some apps "build your route anyway" and show you those missed stops after the fact. It creates a feeling that everything is okay until it's not. We show you this so you can decide what to do before it's too late.
{% endhint %}

### Confirm your Route

After you pick the route type (Current or Optimized), the app will ask you to click the "Let's go" button. and if you are finished with your route planning, you can do that, or you can continue adding stops and changing stop parameters and having some routes built for you as a reference. After you press "Let's go," the app will recalculate all route time and parameters, taking the newest data into account (like time windows, traffic, etc.). You also can close the "Let's Go" button or simply continue building your route afterward. When you finish making changes, click the blue button with an arrow on the bottom right side.

{% hint style="success" %}
If you build a route for the future, we recommend pressing the "Let's go" button exactly when you leave for your route so it will start your route exactly when you go for it.
{% endhint %}

## Follow Route

Choose your preferred option and click the "Start Route" button, and the app will move you to "Route Mode," where you can Navigate to stops (Navigate button), close stops (Done button), and do many other things.

<div><figure><img src="../.gitbook/assets/1-3F78D9B7-8816-41AE-B59B-0442BD57C441 (1).PNG" alt="" width="188"><figcaption><p>Route - Main View</p></figcaption></figure> <figure><img src="../.gitbook/assets/3-63CB8C78-5601-4EBB-AD5E-B0AB2FC374BA (1).PNG" alt="" width="188"><figcaption><p>Route - List View</p></figcaption></figure> <figure><img src="../.gitbook/assets/2-68B8323C-BBE3-4691-AA24-9753F7EFAFDB (1).PNG" alt="" width="188"><figcaption><p>Route - Map View</p></figcaption></figure></div>

If you need to change a [Navigation style](understand-navigation-settings.md) (navigate by address/coordinates), click on the 3-dots button next to the "Nav" button ("Go" button). The app will show you a modal window to change navigation mode and the final destination navigation app (Google Maps, Apple Maps, Waze, etc.)

The "Done" button lets you close a stop and activate the next one. In case of "proof of delivery turned on" in App Settings, it will open your Proof Of Delivery Screen. You can read more about [Proof of Delivery](proof-of-delivery.md) here.

Click on a stop to see additional parameters and to add some notes, skip stops, etc.

### Fitting Modes

MyWay has three major route representation modes:

* Fit the whole route
* Fit route from point A to B
* Show destination

To activate the desired mode, click the button above the "current location button" (below map scale +- buttons). When you plan a route, only "Fit the whole route" can be turned on, but when you follow the route, the button will switch modes from one to another (check images below; modes are going to be activated from left to right)

<div><figure><img src="../.gitbook/assets/2A24D363-BD22-41AA-A331-BB67CC47E999.PNG" alt="" width="188"><figcaption><p>Fit the whole route mode</p></figcaption></figure> <figure><img src="../.gitbook/assets/1D4A6402-CD66-420C-A7A3-9C710B3177EE.PNG" alt="" width="188"><figcaption><p>Fit current route from point A to B mode</p></figcaption></figure> <figure><img src="../.gitbook/assets/649E2BF9-8589-485E-A568-DB2A0792E4BF.PNG" alt="" width="188"><figcaption><p>Show destination mode</p></figcaption></figure></div>



### Your Location

You can hide your current location to make it easy to work with the route. It's handy when you build and manage routes outside of your area. To hide your location, go to layers (top right button below the main menu) and uncheck the "My Location" checkbox. When you have "My location" on, "Fit the whole route" mode will include your location and all route stops. When "My Location" is off, only your stops in the fitting mode will be included.&#x20;

<figure><img src="../.gitbook/assets/DE6D4CA8-762B-4D0F-B659-28AE19C00EEF.PNG" alt="" width="188"><figcaption><p>My location checkbox in the Layers Screen</p></figcaption></figure>

When you follow your route and want' to ["Update"](how-to-use-myway-route-planner.md#update-and-actualize-route) it to actualize ETAs, if access to your location is ON, MyWay will take your location as an "intermediate starting" point. That will greatly improve ETA calculation and will build you a much more accurate route. However, this can cause issues when your location is in a different country or can't be accessed by public roads. We recommend checking [Optimisation Settings ](understand-optimisation-settings.md#starting-location)to see how location can affect your routes.

### Update and Actualize Route

If you see that you are running late or have changed your route, you can update all ETA's and stop the order. You can do that by pressing the 3 dots menu button (in the route header) and picking the "Update Route" option or do complete Reoptimization. [Read more about those options](understand-optimisation-settings.md#route-update-and-reoptimize).

### Changing the route after you started it

One of the greatest MyWay features that separates it from every other route planner is the ability to change the route after you start a route. You can change your route using either of two techniques:\
\
If you simply need to add one or two stops you can do that by using the top left search icon (with a magnifier glass), searching for a new stop, clicking on it, and picking the "add to route" option. The app will set it to the closest location that is already on the route. You can drag & drop location with the long press on the stop and then apply changes by clicking a blue button with arrows on the bottom right. Pick "update" and the app will actualize all ETAs.\
\
The second option is to go back to the edit mode. Click the three dots button in the route subheader, pick "edit route", and add stops by using the top left search icon (with a magnifier glass), or with the "add stop" menu, You can drag & drop location with the long press on the stop and then apply changes by clicking a blue button with arrows on the bottom right. Either pick "current order" to keep the order you set, or "optimized" for the app to build you the most optimal route. This approach is better to use if you have to make multiple changes to your route.

## Video Guide

{% hint style="info" %}
[**MyWay Route Planner - How To - Build Route - Video Instruction (YouTube)**](https://youtube.com/shorts/PnuFrcaUkiE?feature=share)
{% endhint %}

{% hint style="info" %}
If at this stage you have any questions, please drop us a line through online chat. In the MyWay app, go to the Main Menu (top right corner, three lines button) > Support section > Talk to Us.
{% endhint %}
