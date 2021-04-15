# interactive-google-maps
This code helps you interact with the Google Maps API, allowing to extract information live, and automatically fill a form with the appropriate information

Using Javascript, the code adds several functions to capture specific informations, mainly with an on-click action from the user.
Once the map is clicked by the user, it first creates a marker and position it on the map, and capture the longitude and lattitude of that specific point, and fill the form with that information.
If the user clicks on a different point on that map, the marker move to that new location, and the form is automatically updated again with the new data.

The map also listen to the on-drag event, so that when the user drags the marker around on the map, it also record the location data live and update the form.

Few other settings on the map are that it has been limited to a specific area/city, so that user is unable to select a location outside of that area. Anytime the user will navigate the map up to the limit set, it will bring the user back to the edge allowed.
