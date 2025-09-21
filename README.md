# Real-time display of a chessboard
# Authors 
- Eryk Bluj
- Mateusz Janus
# Description of the project 
For our final project during Garage of Complexity course we decided to create a chessboard with an integrated display system. The board detects the arrangement of pieces and shows their positions on a computer screen. To identify each piece, we placed a certain resistor inside it. The electric circuit in our project is based on a voltage divider. Each square on the board has two wires. When a piece is placed on it, a given resistor completes the circuit. This results in a characteristic voltage drop. Multiplexers (MUX in short) were used to determine a position of a piece. Each multiplexer corresponds to a row of the chessboard, with its digital pins assigned to individual squares. The voltage value on every square is read cyclically by an Arduino board and a representation of a chess board is created in a terminal. 
<p align="center">

<img src="https://github.com/user-attachments/assets/fc20bb24-6716-4a46-b886-19e6c10ea949" width="500">


# Science and tech used 
List of equipment:
1. wooden chessboard with plastic chess and chequers pieces
2. ridiculous number of wires 
3. 12 resistors representing each chess piece (a list of reistance values corresponding to chess pieces can be found below)
4. 8 10k&Omega; resistors
5. 8 CD4051 multiplexers
7. Arduino mega 2560 and Arduino Uno Rev3 boards

List of resitors with a matching piece (value --- piece):
### white pieces:
1. 510 &Omega; --- pawn
2. 1.2 k&Omega; --- knight
3. 2.2 k&Omega; --- bishop
4. 4.7 k&Omega; --- rook
5. 6.8 k&Omega; --- queen
6. 10 k&Omega; --- king
### black pieces:
1. 47 k&Omega; --- pawn
2. 68 k&Omega; --- knight
3. 100 k&Omega; --- bishop
4. 220 k&Omega; --- rook
5. 300 k&Omega; --- queen
6. 680 k&Omega; --- king

Two wires were attached to each square of the chessboard. Resitors were placed on chequers pieces and then glued to chess pieces.   The current time and time of an alarm are displayed on an lcd screen. A photoresistor placed in the chimney serves as a switch. An rtc module keeps track of  time. Two buttons in front of a garage allow a user to change both current and alarm time. There is also an analogue speaker, which plays a simple melody when an alarm goes off. All constituents are connected to an Arduino UNO board through a breadboard.
# State of the art 
We learned many useful things throughout this project and the whole course in general. We extended our knowledge about Arduino boards. We are now familliar with basic working principle of multiplexers. We also gained experience in understanding documentation and wiring related to new components. The terminal available in Arduino IDE software wasn't suitable for our project, that's why we had to learn to use PuTTY software, which enabled us to display chess pieces on a screen. In addition to that, we learned how to efficiently divide tasks and deal with troubleshooting.
# What next?
Right now we are thinking about what our next project could be and looking forward to the next edition of the course.
# Sources 
- [LCD screen] ( https://docs.arduino.cc/learn/electronics/lcd-displays/ )
- [RTC module library] ( https://www.arduino.cc/reference/en/libraries/ds1302/ )
- [Simple melody example] ( https://docs.arduino.cc/built-in-examples/digital/toneMelody/ )
- [Garage project] (https://www.tinkercad.com/things/0RcNsphQe3S-garage)
