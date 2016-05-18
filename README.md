# rtkml
[Roadtrippers](https://roadtrippers.com/) to KML Converter

Usage:

````
python rtkml.py trip_id [trip_id trip_id ...]
````

The app will output a KML file in the current directory named for the entered trip IDs.

### Why?

Because Roadtrippers is an awesome app for planning road trips, but the resulting route isn't very portable if you want to display it elsewhere. (Yes, you can share and embed trips, but I couldn't find a way to share multiple legs of a longer trip on a single map.) Exporting it to KML also makes it easier to use other mapping tools.

For example, my upcoming road trip is split into 4 segments, but I want to display the whole thing on one map. [rtkml to the rescue](https://thetravelingmidget.com/the-route/)!

### Where do I find my trip IDs?

Go to Roadtrippers, log in, and click on "My Trips". Select the trip you want to export. In the address bar of your browser, you'll see something like this: `https://roadtrippers.com/map?lat=35.00000&lng=-120.00000&z=7&a2=t!12345678`. The last part, after `t!`, is your trip ID. In this case, it's `12345678`.
