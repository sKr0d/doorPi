# doorPi
*RaspberryPi Doorbell*

It statarted one fine Halloween, when someone stole my wireless doorbell from the front door of our house.  All that was left was a bit of the double sided foam tape I had used to stick it to the door frame.  It's okay, really. The door frame metal, and half the time the signal couldn't reach the dinger, and it didn't go off.  Fast forward to September of the following year.  I decided it was time to install a new bell.  But no, i did not want another wireless bell, because of the problems I had last time.  Instead, I putchased a new doorbell and an 18" drill bit!  

The first version consisted of an Arduino Uno, an Adafruit sound board http://adafru.it/1381 and an Adafruit amplifier http://adafru.it/1552  It tested well in the lab, but when I put it in to production, it was so quiet that nobody could hear it.  Not good for a doorbell.

Then, I did some more research.  Adafruit just came out with a new, more powerful amplifier.  But then, I thought to mayself, "Self...  What if this doorbell could do more than just play a sound??"  And the rabbit hole had sucked me in.

The upgraded doorbell would now be powered by a Raspberry Pi, have a more powerful amplifier, and be able to send me a text message, and animate a crazy little Halloween trinket that I picked up at Target.  And there are plans to include more features in future releases, such as integration with my Sonos system.  But, lets calm down for a minute and focus on the current release.

Hardware:

  CORE
  * Raspberry Pi http://adafru.it/2358
  
  OPTIONAL
  * Amplifier http://adafru.it/1752
  * Speakers http://adafru.it/1732
  
  FUN
  * Target Halloween hand tapping device http://www.gemmy.com/Animated_Skeleton_Hand_p/59666.htm
  * Adafruit Huzzah 8266 breakout board http://adafru.it/2471
  * Adafruit Boost1000C http://adafru.it/2465
  * 3.7v Lithium Polymer battery
