DISCLAIMER!
-----------

The idea of combining these two sensors is not mine. After watching the following video from "Everything Smart Home" channel on Youtube (https://www.youtube.com/watch?v=VEqWlOeJ2YA&t=62s), i decided to develop my own board. 

This is still a work in progress. 


Description
-----------

This is a presence detection sensor for ESPHome which combine both a PIR motion and mmWave sensor. The PIR sensor, has a faster response time to movement but lack the ability to reliably detect small movements. On the other end, the mmWave sensor is able to reliably detect the smallest movements. Standing still in front of the sensor, it will still be able to detect movement just from breathing. Since it uses radio waves, it can detect a person behind a shower curtain which the PIR is unable to do making it the prefect sensor for bathrooms. However, the initial detection when entering the room can sometime be delayed a bit, enough to be noticeable. By combining these two sensor types, we get the best of both world.

I designed the board so that the PIR sensor can be mounted either facing the same direction as the mmWave sensor but also in a downward position. This way, the enclosure can be mounted near the ceiling above the door so that the PIR can detect a person entering the bathroom without detecting someone walking by in the hallway. 


Components
----------

- DFRobot SEN0395 mmWave sensor
- PIR motion sensor
- SHT45 Temperature/humidity sensor
- ESP32-C3
- USB-C (for power only)



![alt tag](/pictures/board-rev-a.jpg "Board (Revision A)")

