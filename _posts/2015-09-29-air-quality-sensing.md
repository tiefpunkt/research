---
layout: post
title:  "Air Quality Sensing (AirCasting)"
---

Taken from http://aircasting.org : "AirCasting is an open-source, end-to-end solution for collecting, displaying, and sharing health and environmental data using your smartphone."

Think of it as a movable air quality sensor thath sends its measurements to a web service, which allows then to plot them on maps, e.g. creating graphics similar to heat maps.

I'm amazed the idea, but the way it's built doesn't seem ideal. So some research on what exists, and what could be done.

## Some theory
* http://publiclab.org/wiki/particle-sensing
* http://publiclab.org/wiki/indoor-air-quality-monitoring

## Air Quality Monitor builds
* The first AirCasting sensor: http://www.instructables.com/id/AirCasting-Air-Monitor/
* AirCasting Sensor by @tamberg: http://www.instructables.com/id/Laser-cut-AirCasting-Sensor/
* http://www.instructables.com/id/Air-Pollution-Detector/
* http://publiclab.org/wiki/dustduino
* http://www.citizensensor.cc/
* http://publiclab.org/wiki/roomba-indoor-air-quality-mapping
* http://publiclab.org/wiki/air-column-monitor
* SafeCast (who did a similar thing with Geiger counters after Fukushima) seems to be working on something: https://twitter.com/safecast/status/645324936173719552
* AirCasting Kickstarter: https://www.kickstarter.com/projects/741031201/airbeam-share-and-improve-your-air (Blog post: http://www.takingspace.org/watch-our-kickstarter-video-get-an-airbeam/)

### Commercial
* http://joinclarity.io/
* http://www.tzoa.com/
* https://getawair.com/


## Sensors
### Particulate Matter Sensors
#### Shinyei PPD42NS
* http://irq5.io/2013/07/24/testing-the-shinyei-ppd42ns/
* http://www.howmuchsnow.com/arduino/airquality/grovedust/
* http://www.exp-tech.de/Sensoren/Seeedstudio-Grove---Dust-Sensor.html
* http://indiaairquality.com/2014/12/14/measuring-the-pickle-jr-a-modified-ppd42-with-an-attached-fan/

#### Sharp GP2Y1010AU0F
* http://www.howmuchsnow.com/arduino/airquality/
* http://www.watterott.com/de/Sharp-GP2Y1010AU0F-optischer-Staubsensor

#### DSM501A
* ftp://imall.iteadstudio.com/Sensor/IM130618001_DSM501A_Dust_Sensor/DS_IM130618001_DSM501A_Dust_Sensor.pdf
* https://github.com/alexjx/AqiMon/blob/master/DSM501.cpp

### Gas Sensors
* http://www.co2meter.com/products/k-30-co2-sensor-module
* http://www.firstcypress.com/store/p10/K30_CO2_Sensor.html
* http://www.senseair.se/products/oem-modules/k30/
* http://www.seeedstudio.com/wiki/Grove_-_Multichannel_Gas_Sensor
* http://publiclab.org/wiki/hydrogen-sulfide-sensor
* (https://hackaday.io/page/1124-environment-parameter-monitoring-system)
* How to connect MQ* Sensors:
  * http://www.staceyk.org/airSensors/sensorsetup.php
  * http://wiring.org.co/learning/basics/airqualitymq135.html
  * http://thesis.jmsaavedra.com/prototypes/technology/mq-7-carbon-monoxide-sensor-breakout/

### Water sensing
Not exactly the same as AirCasting, but there's still some overlap.
* http://publiclab.org/wiki/water-quality-sensor
* http://www.citizensense.net/pollution/articulating-domestic-taps-with-public-infrastructures/
* http://openwaterproject.io/
* http://publiclab.org/wiki/mae-d-agua

## Related
* HabitatMap and AirCasting Blog: http://www.takingspace.org/
* Always a good spot for interesting projects tackling environmental monitoring: http://publiclab.org/tools

### Education
* http://www.takingspace.org/aircasting-education-edition/
* http://www.newtowncreekalliance.org/community-health/aircasting/

### News coverage
* http://www.greenbiz.com/article/how-google-startups-aim-help-us-breathe-better
* http://well.blogs.nytimes.com/2013/06/03/microsampling-air-pollution/?ref=health&_r=1

### White papers
* Info on different gases and pollutants: http://www.libelium.com/smart_cities_wsn_air_pollution/
