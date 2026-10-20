---
description: or address is wrong
---

# I can't find an address

{% hint style="info" %}
**Using MyWay on Android?** This page describes the iOS app version 3. See [Version 2 of this page](https://help.mywayroute.com/i-cant-find-an-address).
{% endhint %}

MyWay has the most up-to-date database of addresses and places from Apple, ArcGIS and HERE combined into one route planner. It means we do not rely on data from only one provider. However, it might be the case when an address is not in our database or it's inaccurate. Let's face it - every provider out there works better in some areas and not that great in others.

### Changing Data Provider (Address Geocoding Service)

No data providers build the same. Some data providers work best in one region, another one in another. Sometimes it can be useful to change data providers and MyWay provides you with such an option. If you can't find addresses often, try to change the data provider in the app settings: menu (three lines, top right corner of the map) > Preferences > "Geocoder". You can choose Apple, ArcGIS or HERE. By default, MyWay picks the provider that works best for your iPhone's region.

<figure><img src=".gitbook/assets/Screenshot 2024-04-15 at 10.05.43.jpeg" alt="" width="188"><figcaption><p>Geocoding Data Provider Options</p></figcaption></figure>

{% hint style="info" %}
You also can change the geocoding provider from the address search screen: tap "Select Geocoder" under "Can't find address?", or "Change Geocoder" when the search has no results, and try a different one. The search screen shows which provider found the results ("Search data provided by…").
{% endhint %}

{% hint style="success" %}
For the USA, United Kingdom, Europe, Canada, and Australia we recommend Apple or HERE, for the rest of the countries ArcGIS or HERE.
{% endhint %}

### If the app recognizes addresses wrong, suggest another state or country

The app relies on a geocoding service and uses the stops already in your route (the last added stop, start or end) or your current location as a reference for searches. If location access is disabled or you previously added a stop in another state or country, that location might be affecting your results.

**How to Fix It:**

* Check Location Access – Ensure the app has permission to access your location.
* Verify Geocoding Provider – If there were recent changes, the app might be using a different provider with less accurate results.
* Set the Correct Search Context – Manually add the first stop in your actual area before pasting the full list.

### If the app navigates you to a wrong address

The app may navigate you to a different address if navigation "By Address" is selected in "Navigation Precision". MyWay offers two methods for sending stops to navigation apps like Google Maps, Apple Maps, and Waze. [Check this article to understand the difference between these navigation options](guides/understand-navigation-settings.md#navigation-types-coordinates-or-address).

### How to report an incorrect address in MyWay Route Planner?

In MyWay Route Planner, tap the menu button (three lines, top right corner of the map) and then "Talk to Us". Write us a message, and we will try to fix this incorrect address for you. Please provide us with addresses and screenshots so we can identify the problem and get it fixed in address databases.

### How to report an incorrect address in Navigation Apps?

If you want to report an incorrect (or missing) address, we recommend doing this through **Google Maps** (short instructions on how to do this [here](https://support.google.com/maps/answer/6194894?co=GENIE.Platform%3DDesktop\&hl=en\&oco=1)) or through OpenStreetMap ([here](https://www.openstreetmap.org/fixthemap))

As soon as your report is reviewed and approved by Google or the OpenStreetMap community, you will see the correct address in your navigator and in MyWay Route Planner as well.
