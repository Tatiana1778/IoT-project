# IoT-project - The RestRoom Status Light 
Code starts with printing 'Start' on the Grove screen with aqua background.
The main purpose of the project is to show people when the toilets are vacant or occupant.
The trigger of the code is touch sensor, which we assume is located on the door frame.
The moment the door closes it touches the sensor and other sensors react to it accordingly. Red LED light turns on, LCD screen displays "Occupant" with the red background. 
In case of code with wifi, when the touch sensor is pressed, it sends data to the spreadsheet through PushingBox. Information that is displayed consists of date and time the button was pressed and the LED color which is always red as it was defined previously.
When a door opens the buzzer rings to indicate that it is available. Moreover, LCD screen turns to green colour with "Vacant" sign and green LED light turns on.


