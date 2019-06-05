Weather App
=====================

This is a weather app written in javascript, created as a project for [Free Code Camp](https://www.freecodecamp.org/) in December 2017.

You can view it live here: [Weather App](https://jlollis.github.io/fcc-weatherapp/).


![screenshot](https://github.com/jlollis/fcc-weatherapp/blob/master/screenshot.png)

Notes
-----------

The app needed to fulfill the following criteria:
- I can see the weather in my current location.
- I can see a different icon or background image (e.g. snowy mountain, hot desert) depending on the weather.
- I can push a button to toggle between Fahrenheit and Celsius.

In order to create the app, you would need to use an API, or application programming interface, to obtain weather data to populate the fields in your app. At the time, there were several free APIs to choose from, and every single one of them had issues.

When I first completed the project last December, the icons were broken in the Open Weather API. Despite this, it was still the best free weather API available at the time. I created a workaround to assign font awesome icons to the availble weather conditions. When I came back to it the following summer I found that the work around no longer worked, as changes had been made to the API in the intervening months. However, the icons were now working, which was great. I changed the code accordingly.

This demonstrated one of the potential drawbacks of relying on APIs. When they break or change, the provider of that API may have no way to contact you, or no incentive to do so. In that case, you may not even be aware that there is an issue. This would be an even bigger problem with more complicated projects. You would definitely need to build error handling and notification into your app to stay on top of any unforseen changes.

Oddly enough, seeing these issues unfold, while mildly frustrating, also made this one of the more interesting FCC challenges.
