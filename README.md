# Smart-Garden
( using  arduino )
 This system makes a pump work 2 times per day(in early morning and sunset, which is determined using an LDR sensor) if the temperature is low, otherwise,
 it would work 3 times.
   Every time before opening the water it checks the moisture of the soil that it is below 18%.
   If it rains, the next time of watering will be canceled.
   Led would be turned on at night.
   Time and sensors values would be displayed on an LCD.
   When we turn on the pump, we write a 0 on its pin. We use a relay module with low level trigger.
