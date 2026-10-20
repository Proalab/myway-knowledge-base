---
description: What the messages, warnings and errors in MyWay mean and what to do about them
---

# Error messages and what they mean

{% hint style="info" %}
**Using MyWay on Android?** This page describes the iOS app version 3. See [Version 2 of this knowledge base](https://help.mywayroute.com/).
{% endhint %}

Find your message by its text (use your browser's search or the search on this site) to see what it means and what to do.

## Building and optimizing a route

| Message | What it means | What to do |
| --- | --- | --- |
| "Couldn't calculate the route. Try again." | The route couldn't be built this time. | Check your internet connection and tap the round blue button again. If it keeps happening, [contact us](../how-to-contact-us.md). |
| "The route calculation is taking too long. Try again later." | Our servers didn't finish in time. This happens more often with very large routes. | Try again in a few minutes. |
| "The route calculation was cancelled on the server." | The calculation was stopped on our side. | Build the route again. |
| "Error" with a number, or "The server sent an unexpected response" | A temporary problem on our servers. | Try again in 10–15 minutes. If it doesn't help, [contact us](../how-to-contact-us.md) and send the error number. |
| "Too many stops: this vehicle allows up to …, including skipped ones." | The route has more stops than your [vehicle type](../guides/understand-vehicle-settings.md#stop-limits) allows. | Remove some stops, split the route, or choose another vehicle type. |
| "Couldn't determine where the route starts from." | The route has no start location. | Add a start location. |
| "Couldn't determine your current location. Check that location access is allowed and try again." | MyWay needs your location to update the route from where you are, but can't get it. | Allow location access for MyWay in iOS Settings, or turn off **My Location** in the [map layers](../guides/how-to-use-myway-route-planner.md#map-layers). |
| "Route Changed: The route changed during optimization, so the result is out of date." | You changed the route while MyWay was building it. | Tap **Calculate Again**. |
| "Some stops have issues and may be skipped." | MyWay can't fit some stops into the route. | Tap **Fix It** to go to the first stop with a problem. See [stop issues](why-do-some-of-my-stops-have-issues-path-not-found-or-unexpected-error.md). |
| "Please add at least one stop." | The route has no stops to build. | Add a stop. |

## Issues and warnings on a stop

| Message | What it means | What to do |
| --- | --- | --- |
| "Route not found" | There is no road to this stop for your vehicle. | Check the address and the pin on the map, or choose a smaller [vehicle type](../guides/understand-vehicle-settings.md). |
| "No route to this stop in the current order" | The stop can't be reached in the order you set. | Optimize the route or change the order. |
| "Time window constraint could not be satisfied" | You can't arrive within the stop's [time window](../guides/understanding-stop-settings.md#time-windows). | Widen the time window, change the departure time, or move the stop. |
| "Late arrival is expected at this stop" | You will arrive after the time window ends. | Same as above. |
| "A long wait is expected at this stop" | You will arrive long before the time window starts and wait. | Change the departure time or the stop order. |
| "Priority stop is not at the beginning" | In your own (Current) order, a [priority](../guides/understanding-stop-settings.md#priority-asap-button) stop isn't at the start. | Optimize the route or move the stop. |
| "Pickup must come before its delivery" | In your own order, a delivery comes before its [pickup](../guides/understanding-stop-settings.md#pickup-and-delivery). | Optimize the route or move the stops. |
| "It looks like the stop coordinates are the same as stop …" | Two stops have the same location. | Check whether it's a duplicate, and delete one if it is. |
| "This stop is far from others (… to the nearest stop)" | The stop is much farther away than the rest. Often it's a wrong address in another city or state. | Check the address. |
| "The route crosses a state line on the way to this stop" / "The route crosses a border on the way to this stop" | The way to this stop goes to another state or country. Arrival times don't include the border crossing. | Check that the address is correct. |

## Adding stops and searching

| Message | What it means | What to do |
| --- | --- | --- |
| "No results for "…". Try a different geocoder." | The address search provider didn't find the address. | Add more details or [change the geocoder](../i-cant-find-an-address.md). |
| "Failed to determine the exact address. Please try again." / "No results found for the given address." | The address couldn't be found. | Check the address or pick the point on the map. |
| "Unable to determine your current location." | MyWay can't get your location. | Allow location access for MyWay in iOS Settings. |
| "This address is … from where you tapped." | You picked a point on the map, and the nearest address is some distance away. | Check the address. The stop stays where you tapped. |
| "Clipboard is empty." | There is nothing to paste. | Copy an address or a map link first. |
| "Can't paste this content. The link contains no coordinates." | You pasted a link that has no location in it. | Copy a link that shows a point (for example, from Google Maps or Apple Maps) or copy the address text. |
| "No Address: Couldn't determine this contact's location. Please set an address to continue." | The contact has no address that can be found on the map. | Tap **Set Address** and enter the address. |
| "No Access to Contacts" | MyWay can't read your contacts. | Tap **Open Settings** and allow access to Contacts. |

## Importing files

| Message | What it means | What to do |
| --- | --- | --- |
| "The file is too large. The maximum size is …" | The file is larger than 5 MB. | Split the file. |
| "This file type isn't supported. Use a CSV or XLSX file." | The file is not .CSV or .XLSX. | Save the file as .XLSX or .CSV. |
| "Enter a valid HTTP or HTTPS link to a CSV or XLSX file." | The web link doesn't point to a file. | Use a direct link to an .XLSX or .CSV file. |
| "Couldn't process the file. Try again." | The file couldn't be read. | Check the [file format](../guides/import-from-file-and-multi-line-import.md#import-from-file-file-example) and try again. |
| "Processing the file is taking too long. Try again later." | Processing didn't finish in time. | Try again later or split the file. |
| "Processing the file was cancelled on the server." | Processing was stopped on our side. | Import the file again. |
| "Geocode unmatched" on a row | MyWay couldn't find this row's address. | Fix the address in the file, or add the stop with the regular search. |
| "To import stops from the file, save or discard your changes first." | You opened a file while editing something. | Save or discard your changes, then open the file again. |

## Shared route links

| Message | What it means | What to do |
| --- | --- | --- |
| "Couldn't load route: No route was found for this link." | The link is wrong, or the route was deleted (links work for 30 days). | Ask the sender to share the route again. |
| "This link format is no longer supported." | The link is from an older format. | Ask the sender to share the route again from the latest version of the app. |
| "Couldn't open this link. Try again later." | A temporary problem. | Check your connection and try again. |
| "To open the route from the link, save or discard your changes first." | You opened a link while editing something. | Save or discard your changes and open the link again. |

## Changing a route

| Message | What it means |
| --- | --- |
| "The route is in progress. If you edit it, you'll have to start it again." | Editing a started route resets its start. Tap **Edit Route Anyway** to continue. |
| "The route is completed. If you edit it, it will lose its completed status." | Editing a completed route makes it active again. |
| "The route is already in progress. To delete the start location, restart the route or undo all finished stops first." | You can't delete the start after the route has started. Tap **…** > **More** > **Restart Route**, or undo the finished stops. |
| "This stop is already completed. Its completion status and proof of delivery will be deleted." | Deleting a completed stop also deletes its proof of delivery. |
| "All progress will be lost. This can't be undone." | **Restart Route** removes all statuses and proof from the route. |
| "The route has unfinished stops (…)" | Some stops are still open when you complete the route. Tap **Complete Route Anyway** to complete it. |
| "The route is already completed" | You can't change statuses in a completed route. |

## Contacts and calls

| Message | What it means |
| --- | --- |
| "This device can't make phone calls." / "This device can't send messages." | Your device (for example, an iPad without cellular) can't call or send SMS. |
| "No email app is available on this device." | There is no email app set up. Set up the Mail app or another email app. |
| "This link can't be opened on this device." | The app for this contact channel (for example, WhatsApp or Telegram) is not installed. |

## Subscription

| Message | What it means | What to do |
| --- | --- | --- |
| "Couldn't load subscription plans" | MyWay couldn't load the plans. | Check your internet connection and open the screen again. |
| "Purchase is awaiting approval" | Ask to Buy: your family organizer needs to approve the purchase. | Wait for approval. |
| "No purchases to restore" | This Apple ID has no active MyWay subscription, or there's no connection. | See [MyWay does not recognize my subscription](../subscription-management/myway-does-not-recognize-my-subscription.md). |
| "Payment Problem" | Apple couldn't charge your payment method. | Tap **Manage Subscription** and [update your payment method](../subscription-management/how-to-change-or-add-a-payment-method.md). |

## Live Activity and photos

| Message | What it means | What to do |
| --- | --- | --- |
| "Live Activities for MyWay are turned off in iOS Settings." | iOS doesn't allow MyWay to show the Live Activity. | Turn on Live Activities in iOS Settings > MyWay. |
| "Couldn't process the photo. Please try again." | The photo couldn't be saved. | Take or choose the photo again. |

Don't see your message here? [Contact us](../how-to-contact-us.md) and send a screenshot.
