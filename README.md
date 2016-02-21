#Smart-Weather-Lamp

A SmartThings app for a color changing smart weather lamp that changes color with the weather. 

If you're like me, you've had your share of weather this year.  I decided to use SmartThings to better visualize the weather - and to know whether I need an umbrella, a coat, a snow shovel or sandals and shorts when I head out the door. 

Enter the color changing smart weather lamp app.  It uses a motion sensor, contact sensor and can also be manually triggered and one or more Phillips Hue LED bulbs to visually display the weather forecast. Use your favorite lamp fixture.

Features include
 - Choose which colors you want to use for each weather event or disable any unwanted weather events.
 - Specify the "cold" temperature(actual or apparent), the "hot" temperature(actual or apparent), the wind speed, the cloud cover %, the humidity, and snow or rain to trigger weather events
 - Select the number of hours that you want to look ahead. This means you can install a version of the app for workdays that will check the weather for the next 8 hours and let you know if, during those 8 hours, it is going to be cold, hot, windy, rainy or snowy. You can install another instance of the app for the evening, that only looks at the next 2 hours. You can select to look ahead from 1-24 hours or just check the current conditions
 - If multiple weather conditions are matched, the lamp will cycle through all the applicable weather colors. For instance, if it's going to be cold, windy and snowing, the light will turn on and change from blue to yellow to pink.
 - In the event of a weather alert, the light will work as it always does, but all applicable colors will flash
 - Select which type of weather alerts you want to see (Advisory, Watch, and/or Warning)
 - The lights can remember their last settings and revert to those settings after the weather is done displaying. You can disable this feature to have the lights turn off when the display is complete.
 - The light can be set to "Always On" to display the weather continuously

Weather Lamp Colors

     •	Blinking (any color)  -- A weather watch, warning, or advisory is in effect in your area.  
     •	Weather events including Cold, Hot, Raining, Snowing, Sleeting, Windy, Cloudy and Humid can be set to a number of preset colors
     
   
To get accurate weather information the specific latitude and longitude from your SmartThings Hub is used to take advantage of weather micro-targeting API at forecast.io that powers the App DarkSky.  They believe they can predict when it will rain — down to the minute — at your exact location.  To use the forecast.io API for your weather forecast, visit https://developer.forecast.io/register, register to get an API key, and insert it on line 129 of the groovy script.


Here’s to good weather!

