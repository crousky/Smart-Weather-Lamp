# Smart-Weather-Lamp
A SmartThings app for a color changing smart weather lamps that changes color with the weather. 

If you're like me, you've had your share of weather this year.  I decided to use SmartThings to better visualize the weather - and to know whether I need an umbrella, a coat, a snow shovel, some tissues (for high pollen) or sandals and shorts when I head out the door. 

Enter the color changing smart weather lamp app.  It uses a motion sensor (can also be manually triggered) and one or more Phillips Hue or LifX LED bulbs to visually display the weather forecast. Use your favorite lamp fixture.

Weather Lamp Colors

     •	Blinking (any color)  -- A weather watch, warning, or advisory is in effect in your area.  
     
     •	Red  -- It's going to be at or above the specified maximum temperature  
   
     •	Purple  -- Rain: Rain is forecast for specified time period.
     
     •	Cold: It's going to be at or below the specified minimum temperature
     
     •	Pink  -- Snow: Snow is forecast for specified time period.
     
     •	Yellow  --  Wind: Wind is forecast to meet or exceed the specified maximum wind speed
     
     •	Green  -- All clear
   
To get accurate weather information it, for example, uses the specific latitude and longitude from your SmartThings Hub to take advantage of weather micro-targeting API at forecast.io that powers the App DarkSky.  They believe they can predict when it will rain — down to the minute — at your exact location.  To use the forecast.io API for your weather forecast, visit https://developer.forecast.io/register, register to get an API key, and insert it on line 129 of the groovy script.


Here’s to good weather!

