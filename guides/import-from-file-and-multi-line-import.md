# Import from file and multi-line import

{% hint style="info" %}
**Using MyWay on Android?** This page describes the iOS app version 3. See [Version 2 of this page](https://help.mywayroute.com/v2/guides/import-from-file-and-multi-line-import).
{% endhint %}

Add many stops at once instead of one by one: paste a list of addresses (multi-line import), [take a photo of a list or a table](#addresses-from-a-photo), or import an .XLSX or .CSV file from your iPhone, from a web link or from [another app](#import-a-file-from-another-app).

<figure><img src="../.gitbook/assets/how-to-use-add-stop.png" alt="" width="188"><figcaption><p>Two ways to add stops to the route</p></figcaption></figure>

To start, tap **Add Stop** (or the magnifier button in the top left corner of the map). In the row of icons under the empty search field, tap **List** (the third icon) for multi-line import and addresses from a photo, or **Import** (the last icon, a document with an arrow) to import a file.

If you import a file, make sure it uses the right format: see the [file example](import-from-file-and-multi-line-import.md#import-from-file-file-example). Processing can take a few minutes, as MyWay recognizes every address and matches it to the address database.

<div><figure><img src="../.gitbook/assets/import-multi-search.png" alt="" width="188"><figcaption><p>Multi-Line Import</p></figcaption></figure> <figure><img src="../.gitbook/assets/import-file.png" alt="" width="188"><figcaption><p>Import from file</p></figcaption></figure> <figure><img src="../.gitbook/assets/import-file-results.png" alt="" width="188"><figcaption><p>Import results</p></figcaption></figure></div>

### Multiline import

1. Tap **List** to open Multi Search.
2. Type or paste up to 30 addresses, one address per line, and tap **Search**. The paste button (bottom right corner of the field) adds the copied lines to the end of the list, so you can paste several times. You can also [take a photo of the list](#addresses-from-a-photo).
3. The results open under a map of the addresses MyWay found. Each row shows its line number, the address MyWay found in blue and the line you entered under it. While MyWay is still looking for a row's address, the row shows a spinner.
4. Check the list:
   * Rows with a found address are selected, and their pins on the map are filled in. Tap a row to select it or clear the selection, or tap **Select All**.
   * If MyWay found the wrong place for a row, tap the address (it ends with a pencil) and choose the right one. The row gets this address and is selected.
   * Rows whose address MyWay couldn't find are marked "Address Not Found". Tap such a row to choose its address.
   * To remove a row, swipe it to the left.
   * Tap a row number to see it on the map, or tap a pin to find its row in the list.
5. Tap **Add to Route**. The button shows how many rows are selected out of all rows, for example **Add to Route (12 of 15)**, and MyWay adds only the selected ones. On a route in progress, the new stops go to the end of the route.

### Addresses from a photo

Take a photo of a list of addresses (on paper, on a screen or in a note), and MyWay puts the addresses into the list for you. Spreadsheets work too: MyWay finds the address column and adds the city and ZIP code from their own columns. This needs iOS 26 or later.

1. Tap **List** to open Multi Search.
2. Tap the camera button in the bottom right corner of the field, next to the paste button.
3. On the **Scan Addresses** screen, swipe through the tips on how to take the photo, then tap **Take Photo**. To use a photo or a screenshot you already have, tap **Choose from Library**.
4. MyWay looks for addresses in the photo and adds them to the list, after any lines that are already there.
5. Check the lines, then tap **Search** and go on as in [Multiline import](#multiline-import).

**How to take a photo that MyWay reads well**

* **Only addresses in the frame.** Point the camera at the addresses and leave out as much of everything else as you can: text around the list may get into it.
* **A clear shot.** Avoid glare and shadows on the text, and hold the phone parallel to the page or the screen.
* **Keep the header row.** If the list is a table, include the row with the column names. MyWay finds the address, city and ZIP code columns by their names, like "Address", "Street", "City", "ZIP" or "Postal Code". Without the header row, the addresses go into the list without the city and ZIP code.
* **Check before you search.** An address written on two lines in one cell becomes two lines in the list: join them before you tap **Search**. Fix or delete any line that isn't an address.

**What MyWay takes from the photo**

* From a table, only the address column, with the city and ZIP code added. Order numbers, phone numbers, dates and other numbers stay out of the list. To add phone numbers, notes or time windows to your stops, [import a file](#import-from-file) instead.
* From a list that isn't a table, the lines that start at the same left edge, one under another. If there are no such lines, MyWay takes all the text in the photo, apart from phone numbers, links, dates and numbers.
* Up to 30 lines in all, like a typed list. If the photo has more, MyWay adds what fits and tells you how many lines didn't fit. Take a long list in parts: add one part to the route, then open **List** again for the next one.

{% hint style="info" %}
The photo is read right on your iPhone and isn't sent anywhere. If you don't see the camera button in the field, check your iOS version: the button is there on iOS 26 or later. If the camera doesn't work after you tap **Take Photo**, allow camera access in iOS Settings > Apps > MyWay.
{% endhint %}

### Import from file

1. Tap **Import**, then **Select File** and choose an .XLSX or .CSV file (up to 5 MB) on your iPhone. To use a file on the internet, tap **Web Link** instead and paste a link to an .XLSX or .CSV file.
2. Wait while MyWay processes the file. The results open on a map: each row of the file is a numbered pin, and the list of stops with their details (tracking ID, time window, time at stop, contact, notes) is in a panel over the map. Drag the panel up or down. Each row shows its number in the file, the address MyWay found in blue and the address from the file under it. Tap a row number to see it on the map, or tap a pin to find its row in the list.
3. Check the list:
   * Rows with a found address are selected, and their pins on the map are filled in. Tap a row to select it or clear the selection.
   * To change a row's address, tap the address (it ends with a pencil) and choose the right one. The row gets this address and is selected.
   * Rows whose address MyWay couldn't find are marked "Address Not Found", and a note at the top of the list says how many there are. Tap such a row to choose its address and add it too.
   * To remove a row you don't need, swipe it to the left.
4. Tap **Add to Route**. The button shows how many rows are selected out of all rows in the file, for example **Add to Route (12 of 55)**, and MyWay adds only the selected ones.

If MyWay finds no stops in the file, it shows "No stops found in the file." Compare your file with the [file example](#import-from-file-file-example).

To see how the import file should look, download the file example ([example.xlsx](import-from-file-and-multi-line-import.md#import-from-file-file-example)). The order of columns doesn't matter: MyWay recognizes the columns by their titles and validates the data. If something doesn't go as expected, compare your file with the example to see the data formats we use.

{% hint style="info" %}
The file needs to be on your iPhone first: send it from your computer by email, a messenger of your choice or AirDrop, or save it to the Files app.

If the file is already on your phone, you can also [open it from another app](#import-a-file-from-another-app).
{% endhint %}

{% hint style="warning" %}
If the app recognizes addresses wrong, suggesting another state or country, follow the advice in [this article](../i-cant-find-an-address.md#if-the-app-recognizes-addresses-wrong-suggest-another-state-or-country). MyWay finds the addresses from the file with the geocoder you chose in **Preferences** (rows with coordinates aren't looked up).
{% endhint %}

{% hint style="info" %}
**Rows with coordinates.** If a row has latitude and longitude, MyWay puts the stop exactly at these coordinates and doesn't look up the address. The address from the file is shown as it is, without checking it, so it may not match the point on the map. Navigate to these stops **By GPS Coordinates** (the default): with **By Address**, the navigation app searches for the address text and can lead you to a different place. [More about navigation types](understand-navigation-settings.md#navigation-types-coordinates-or-address)
{% endhint %}

### Import a file from another app

If the file is already on your iPhone (for example, in Mail, Files or a messenger), send it to MyWay directly:

1. Open the file in that app and tap the Share button.
2. Choose MyWay in the list of apps. If you don't see it, swipe the row of apps to the end, tap **More** and find MyWay there.
3. MyWay opens the Import screen with this file and starts processing it.

This works with .XLSX and .CSV files.

### Import from file - file Example

{% file src="../.gitbook/assets/myway_example.xlsx" %}

Use the file above as an example of an .XLSX file you can import into MyWay Route Planner.

{% hint style="info" %}
The order of columns doesn't matter, but the column titles and the format of the data do:

* Use English column titles, like in the example file. The address column can be called "address", "Full Address", "FullAddress", etc., but its content must be an address that geocoding services can recognize.
* Write time at stop as hours, minutes and seconds (00:10:00) or with units (10m, 1h30m). A plain number like 10 is read as seconds.
* Write times as 09:00, 15:00 or 3:00 PM.
* MyWay reads only the first sheet of an .XLSX file.

If you can, keep the column names exactly as in the example file to avoid processing issues.
{% endhint %}

<table data-full-width="false"><thead><tr><th>order number</th><th>name</th><th>address</th><th>latitude</th><th>longitude</th><th>duration</th><th>start time</th><th>end time</th><th>phone</th><th>contact</th><th>notes</th><th>color</th></tr></thead><tbody><tr><td>1020</td><td>Central Park</td><td>830 5th Ave, Central Park, New York</td><td></td><td></td><td>00:10:00</td><td>10:00 AM</td><td>15:00 PM</td><td>1234567890</td><td>John Dow</td><td></td><td></td></tr><tr><td>1022</td><td></td><td>350 5th Ave, Koreatown, New York</td><td></td><td></td><td>00:10:00</td><td></td><td>19:00 PM</td><td></td><td></td><td>Some notes</td><td></td></tr><tr><td>1023</td><td></td><td></td><td>40.6893</td><td>-74.0445</td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr><tr><td>1024</td><td>Apple Store</td><td>103 Prince St, Soho, New York</td><td></td><td></td><td>00:25:00</td><td></td><td></td><td></td><td></td><td></td><td>red</td></tr></tbody></table>

**We recommend building your files from our example file to reduce possible errors.** A copy of the file is below:

{% file src="../.gitbook/assets/myway_example.xlsx" %}
