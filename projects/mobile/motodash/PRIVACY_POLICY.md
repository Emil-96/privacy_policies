# Privacy Policy

This is the privacy policy for the MotoDash app.

## Table of contents

- [What information is accessed?](#what-information-is-accessed)
  - [Location](#location)
    - [Speed](#speed)
    - [Map](#map)
  - [Music](#music)
- [What information is stored?](#what-information-is-stored)
- [Permissions](#permissions)
- [Contact](#contact)

## What information is accessed?

### Location

The app accesses the user's location to display the current speed and optionally a map.

#### Speed

To display the current speed, the app uses the device's own location service. The app requires *precise* location access to get the speed.

The app does not send the location data anywhere.

#### Map

The map is generated using the [Mapbox](https://www.mapbox.com/) API. As specified in Mapbox's [telemetry specification](https://www.mapbox.com/telemetry/), the app sends anonymized location data to Mapbox which can be opted out of by the user.  

If the map is disabled, the app does not send any location data to Mapbox.

### Music

In order to be able to view and control the currently playing song, the app requires access to the device's notifications.

The app does not retrieve any information from the notifications other than the title, artist and album cover of the currently playing song.

The app does not send any information about the currently playing song or other notifications anywhere

### Ads

Ads will be shown when the user wants to access the map. The ads are provided by [Google AdMob](https://admob.google.com/home/).

As per [their documentation](https://developers.google.com/admob/android/privacy/play-data-disclosure#data_collected_and_shared_automatically), the Google Mobile Ads SDK collects the following information:
- IP address
- User product interactions
- Diagnostic information
- Device and Account identifiers

You can read more about the information collected by Google [here](https://support.google.com/admob/answer/7665968).

When the map is not enabled, ads will not be displayed and this information will not be collected..

## What information is stored?

The app stores only the user's preferences, such as the selected visibility of the components and other customization options.

No information about the user is stored and no information is sent anywhere other than [specified](#map).

## Permissions

The app requires the following permissions:
- `android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`
- `android.permission.ACCESS_FINE_LOCATION`
- `android.permission.ACCESS_COARSE_LOCATION`

The app requires the `BIND_NOTIFICATION_LISTENER_SERVICE` permission to be able to read the notifications to retrieve the currently playing song.

The app requires the `ACCESS_FINE_LOCATION` permission to be able to get the speed.  
The `ACCESS_COARSE_LOCATION` permission is required to be able to use the `ACCESS_FINE_LOCATION` permission.

## Contact

If you have any questions or concerns, please contact me at [play.developer.emil@gmail.com](mailto:play.developer.emil@gmail.com).