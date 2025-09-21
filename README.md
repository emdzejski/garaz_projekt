# Real-time display of a chessboard
# Authors 
- Eryk Bluj
- Mateusz Janus
# Description of the project 
For our final project during Garage of Complexity course we decided to create a chessboard with an added display system. A current arrangement of pieces on the board is shown on a computer screen. In order to distinguish between each chess piece, we placed a particular resistor inside of it. The electric circuit in our project works as a voltage divider. Two wires are glued to every square on the board, therefore by placing a given piece on it, a certain resistor is connected to the circuit. This results in a voltage drop, which can be read by an Arduino board. Multiplexers helped us in determining the position of a piece. 

<p align="center">
<img src="https://github.com/ComplexityGarage/ExemplaryProject1/assets/104577187/8e26472c-64b3-4d22-9e41-16306ed59c64" width="500">

# Science and tech used 
List of items used during the making of the cheesboard:
1. wooden chessboard with plastic chess and chequers pieces
2. ridiculous number of wires 
3. four 10k&Omega; resistors
4. potentiometer
5. DS1302 real time clock module
6. two buttons
7. YD36 analogue speaker
8. Arduino Uno Rev3 board

The case was 3D printed and placed on a styrofoam base. The current time and time of an alarm are displayed on an lcd screen. A photoresistor placed in the chimney serves as a switch. An rtc module keeps track of  time. Two buttons in front of a garage allow a user to change both current and alarm time. There is also an analogue speaker, which plays a simple melody when an alarm goes off. All constituents are connected to an Arduino UNO board through a breadboard.
# State of the art 
We learned many useful things throughout this project and the whole course in general. Wiring and programming an Arduino board isn't a mystery to us anymore. We now know how to include many parts in a circuit and make them work simultaneously. We also gained experience in understanding documentation and wiring related to new components. The whole process of 3D printing became much more intuitive. In addition to that, we learned how to efficiently divide tasks and deal with troubleshooting.
# What next?
Right now we are thinking about what our next project could be and looking forward to the next edition of the course.
# Sources 
- [LCD screen] ( https://docs.arduino.cc/learn/electronics/lcd-displays/ )
- [RTC module library] ( https://www.arduino.cc/reference/en/libraries/ds1302/ )
- [Simple melody example] ( https://docs.arduino.cc/built-in-examples/digital/toneMelody/ )
- [Garage project] (https://www.tinkercad.com/things/0RcNsphQe3S-garage)
