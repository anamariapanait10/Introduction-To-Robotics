<div align="center"> 
  <h1>🪛Introduction to Robotics (2023 - 2024) 🔧</h1>
</div>

Welcome!  👋

This repository is a showcase of my journey in the field of robotics and contains a collection of projects and homework assignments completed during the `Introduction to Robotics` course  at the "University of Bucharest". 

### 📝 Homework :zero:

> <i>Create this repo and install the Arduino IDE.</i> ✔️

<details>
 <summary><b>Photo</b></summary>
 
 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework0/ArduinoIDE.png">
 </div>
</details>

### 📝 Homework :one:

> <i>Controled each channel of an RBG LED using individual potentiometers. The program reads the potentiometer’s value with Arduino and then write a
mapped value to the LED pins. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework1-RGB-LED/Homework1/Homework1.ino)

<details>
 <summary><b>Photo</b></summary>

 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework1-RGB-LED/Homework1-Photo.jpeg" alt="Photo">
 </div>
</details>

<details>
 <summary><b>Video</b></summary>

 <div align="center"> 
   <a href="https://youtu.be/iEVsYE2pid4"><img src="https://img.youtube.com/vi/iEVsYE2pid4/0.jpg" alt="Video"></a>
 </div>
</details>

### 📝 Homework :two:

> <i>Designed a control system that simulates a 3-floor elevator using the Arduino
platform. This project involves button state changes, the implementation of debouncing technique and the
coordinating multiple components to represent real-world scenarios. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework2-Elevator-Simulator/Homework2/Homework2.ino)

<details>
 <summary><b>See all requirements</b></summary>
 <br>
 
⚙️ Components:
  - 4 LEDs 💡(3 for the floors and 1 for the elevator’s operational state)
  - 3 Buttons 🕹️ (for floor calls)
  - 1 Buzzer 🔉(for door opening/closing or elevator moving sounds)
  - Resistors and wires

✏️ Requirements:

- **LED Indicators:** Each of the 3 LEDs represents one of the 3 floors.
The LED corresponding to the current floor is light up. Additionally, another
LED represents the elevator’s operational state. It blinks when the elevator
is moving and remains static when stationary.
- **Buttons:** Contains 3 buttons that represent the call buttons from the
3 floors. When pressed, the elevator simulates movement towards
the floor after a short interval (2-3 seconds).
- **Buzzer:**
The buzzer sounds briefly during the following scenarios:
  - Elevator arriving at the desired floor
  - Elevator doors closing
  - Elevator moving between floors
- **State Change & Timers:** After
a button press, the elevator waits for the doors to close and then
moves to the corresponding floor. If the elevator is in movement, it
stacks its decision (gets to the first
programmed floor, opens the doors, waits, closes them and then go to the
next desired floor).
- **Debounce:** Implement debounce for the buttons to avoid
unintentional repeated button presses.

</details>

<details>
 <summary><b>Photo</b></summary>

 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework2-Elevator-Simulator/Homework2-Photo.jpeg" alt="Photo">
 </div>
</details>

<details>
 <summary><b>Video</b></summary>

 <div align="center"> 
   <a href="https://youtu.be/jx6ErbiJzYk"><img src="https://img.youtube.com/vi/jx6ErbiJzYk/0.jpg" alt="Video"></a>
 </div>
</details>

### 📝 Homework :three:

> <i>Used a joystick to control the position of the segment and ”draw” on a 7 segment display. 
The movement between segments is natural, meaning it jumps from the current position only to neighbors, but without passing through ”walls”.
This project involves button state changes, the implementation of debouncing technique and the use of interrupts. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework3-7-Segment-Display/Homework3/Homework3.ino)

<details>
 <summary><b>See all requirements</b></summary>
 <br>
 
⚙️ Components:
  - 7-segment display 
  - 1 joystick 🕹️
  - Resistors and wires

✏️ Requirements:
- The initial position is on the DP. The current position always blinks (irrespective of the fact that the segment is on or off). 
- Short pressing the button toggles the segment state from ON to OFF or from OFF to ON. 
- Long pressing the button resets the entire
display by turning all the segments OFF and moving the current position to the decimal point.

</details>

<details>
 <summary><b>Photo</b></summary>

 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework3-7-Segment-Display/Homework3-Photo.jpeg" alt="Photo">
 </div>
</details>

<details>
 <summary><b>Video</b></summary>

 <div align="center"> 
   <a href="https://youtu.be/Nnydq2iCbcs"><img src="https://img.youtube.com/vi/Nnydq2iCbcs/0.jpg" alt="Video"></a>
 </div>
</details>


### 📝 Homework :four:

> <i>Implemented a stopwatch timer that counts in 10ths of a second
and has a save lap functionality (similar to most basic stopwatch functions on most phones) using a 4 digit 7 segment display and 3 buttons. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework4-4-digit-7-Segment-Display/Homework4/Homework4.ino)


<details>
 <summary><b>See all requirements</b></summary>
 <br>
 
⚙️ Components:
  - 4 digit 7-segment display 
  - 1 shift register
  - 3 buttons 🕹️
  - Resistors and wires

✏️ Requirements:

The starting value of the 4 digit 7 segment display is `000.0`. The buttons have the following functionalities:
- **Button 1:** Start / pause.
- **Button 2:** Reset (if in pause mode). Reset saved laps (if in lap
viewing mode).
- **Button 3:** Save lap (if in counting mode), cycle through last saved
laps (up to 4 laps).

✏️ Workflow:
1. Display shows `000.0`. When pressing the Start button, the timer starts.
2. During timer **counter**, each time the lap button is pressed, the timer's value is saved in memory, up to 4 laps; pressing the
5th time overrides the 1st saved one. If the reset button is pressed while the timer works, nothing happens. If the pause button is pressed the timer stops.
3. In **Pause Mode**, the lap flag button doesn’t work anymore. Pressing
the reset button resets you to 000.0.
4. After **reset**, the flag button can be pressed to cycle through the lap times. Each time the flag button is pressed, it displays the
next saved lap. Pressing it continuously cycles you through it
continuously. Pressing the reset button while in this state resets all
your flags and takes the timer back to `000.0`.

</details>

<details>
 <summary><b>Photo</b></summary>

 <div align="center"> 
  <img width="480px" src="https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework4-4-digit-7-Segment-Display/Homework4-Photo.jpeg" alt="Photo">
 </div>
</details>

<details>
 <summary><b>Video</b></summary>

 <div align="center"> 
   <a href="https://youtu.be/99ecpExxoHw"><img src="https://img.youtube.com/vi/99ecpExxoHw/0.jpg" alt="Video"></a>
 </div>
</details>



