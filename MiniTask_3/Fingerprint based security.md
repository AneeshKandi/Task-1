# Debugging Tutorial of Fingerprint based Security Project

## Project

https://github.com/AneeshKandi/Task-1/blob/main/MiniTask_2/Fingerprint%20based%20security.md

This is the analysis and description of the project.

## Testing Components

The sequence is:

*Fingerprint scanner -> Microcontroller -> Servo motor*

### Testing the Fingerprint scanner

After updating your fingerprint in the system, try testing if it is working or not. Now touch the scanner with the finger which is authorized. Then try with other fingers. Make sure your finger is neat and dry. Try the same finger in all angles and see if it is working. Now let unauthorized user test it.

If the scanner is not able to identify then there is a problem in the scanner. Try purchasing a new one, better quality this time.

### Testing the Arduino Mega

Connect to the system properly and see if it lights up on connection. Test it with a simple LED to see if all the pins are working. Check all the connections to the board and make sure that no pins are shorted. Check all the system settings are configured properly or not.

If the board heats up and gets burned in a short time, then it is better to check for new board.

### Testing the Servo motor

First test it with arduino directly if it is moving accurately and the positions are properly matched. We can follow this [tutorial](https://www.instructables.com/Servo-Motor-Tester/) to test the Servo motor.

Now connect all the components properly and now start debugging the code.


