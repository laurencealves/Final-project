# Final-project
######Laurence Pereira

##Where to? The wearable GPS

**Summary**

    My project it’s a wearable that allows the user to get to a location by using the lights in the watch to direct you as you walk. All the behavior of the lights happen by using a GPS Module and an Accelerometer. The GPS Module connects to satellites allowing the wearable to know your exact location on earth and the accelerometer allows the Flora board to know in what direction you’re moving your arm and walking towards to. 
    The case it’s 3D printed to make a home for the circuit and everything in it it’s independent from the computer, so you can walk around the streets with the watch normally. The 3D model was made in Fusion 360, exported to MeshMixer to convert to a STL file and allowing it to be printed in a 3D printer. 
    The wearable has 3 modes, to switch betweens modes, there’s a button attached to it in the case. The modes are respectively to mode in button: clock mode, GPS navigation mode and a compass mode.
    During the compass mode one purple LED will light on in the North direction and, as you walk with the watch, the compass will always make you move forward in the north direction. 
    In the Navigation mode, you can set target location in the arduino code by the coordinates (latitude and longitude) and one LED will turn on directing you to path to get to the location. While you’re far away from your target, the LED will be yellow, as you’re getting closer, it will gets green and, when you arrive at the location, all LEDs will turn on in a rainbow mode, telling the user that you arrived at the set destination.
    In the clock mode, the top LED acts like the hour by turning on a orange light and the minutes are shown with a yellow LED. As the minutes gets higher in a hour, the yellow LED will get closer to the orange LED.


**Component parts** 

1. Flora main board(from adafruit)

2. Flora GPS module (from adafruit)

3. Flora Accelerometer/ Compass sensor - LSM303 (from adafruit)
 
4. Switch button (from Hybrid Lab)
 
5. 3.7V lipoly battery (from adafruit)
 
6. Neopixel ring (with 16 LEDs) (from adafruit)

7. Leather strap (from Fossil)

8. 3D printed case (printed in Hybrid Lab)


**Challenges**

For sure, the hardest part will be calibrating the GPS to make it work according to the coordinates and make it know that you got to your destination. Also, the 3D printed case will be a challenge because everything is really tiny, and working in such a small dimention is a challenge, so make everything fit inside. 

**Project timeline**

*week 1* - research and assemble components to start building

*week 2* - start 3d model and soldering eletronic parts

*week 3* - 3d model test with eletronics / start coding

*week 4* - test with the wearable in the streets / final 3D print / adjustments in the code 

*week 5* - final coding / filming the project in use / last adjustments
