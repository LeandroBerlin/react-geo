# React-Geo

GeoPosition App exercise

- Clone this repo

- Refactor App by creating a new component named called `<GeoPosition>`

- <GeoPosition> should use a child render callback that passes to <App> the latitude and longitude state

- When you're done, <App> should no longer have anything but a render method

## Got extra time?

- Now create a <GeoAddress> component that also uses a render callback with the current address. You will use `getAddressFromCoords(latitude, longitude)` to get the address, it returns a promise.

- You should be able to compose <GeoPosition> and <GeoAddress> beneath it to naturally compose both the UI and the state needed to render it

- Make sure <GeoAddress> supports the user moving positions

- Fix soon-to-be deprecated method (16.3) ;)
