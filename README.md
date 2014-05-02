Beagle
======
The objective is to to build a device for data acquisition that can be collected using Google Analytics.  The idea is to attach this device to the shopping carts in the retail shops to track the customer behavior . This customer behavior can be useful in the context of predictive analytics , marketing performance ,  automated insights and storefront conversions .  BeagleBoard Bone can be configured to capture the following data points 

BeagleBone Board is registered in Google Analytics using a unique device ID , dynamically populated 

1- When the customer dispatches the cart from the cart station - BeagleBoard Bone senses it and fires an event in Google Analytics 

2- As the Customer moves the cart , the duration of cart moves is detected by BBB and captured in Google Analytics using time intervals (milli seconds) 

2a- As the Customer moves the cart , the speed of the cart be detected by BBB and captured in Google Analytics 

3-If the cart pauses for more than 3 minutes , Beagleboard Bone captures the data and a separate event is fired in Google Analytics signifying customer’s high interest area 

4-Beagleboard Bone detects the cart’s motion and expires the data capture session in Google Analytics 30 minutes after the cart stays unmoved 

5-Beagleboard Bone detects the cart’s motion and upon it’s return at the cart station , pings Google Analytics to capture the return of the cart 
 

Desired Result 

Increase comparable store sales
actionable in-store data ,
Generate higher shopper engagement

Some useful Links 

http://nicomiceli.com/tracking-your-home-with-google-analytics/
http://nicomiceli.com/tracking-home-google-analytics-part-2-door-sensors/
https://www.youtube.com/watch?v=_ylggGtdUGA






1- The first person who will use my project is a  medium to large retailer with shopping carts 

2  (I) will be happy If my project exists If  marketers . national  brands 

3- The first 10 minutes of using/interacting with my projects will look like 

A populated Google Analytics dashboard firing relevant data events

4- By the end of tonite , i would like to be able to 

Finalize If I should raspberry Pi or BeagleBoard . Research the limitations . 
