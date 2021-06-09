# LED Skateboard

This project uses LED lights controlled by an accelerometer and gyroscope to challenge your skateboarding creativity. The LED lights change according to what trick is being
performed. For example, a shuvit (180-degree yaw rotation) changes the lights blue. a kickflip (360-degree roll) changes the color to red. when both tricks are done
simultaneously (varial flip) the colors are added together, turning the lights purple. This functionality of adding colors challenges the skater to come up with new trick
variations to create interesting colors.

## Principle

The basic concept is using additive colors to change the R B G values of the LED strip. Each value is controlled by a different trick. just popping the board up (like an ollie)
represents blue. A kickflip represents red, and a shuvit represents green. Each time a trick is performed 10 is added to the respective R B G value.
