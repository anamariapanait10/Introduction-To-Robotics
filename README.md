<div align="center"> 
  <h1>🪛Introduction to Robotics (2023 - 2024) 🔧</h1>
</div>


Welcome! 	👋

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

> <i>Control each channel of an RBG LED using individual potentiometers You need to read the potentiometer’s value with Arduino and then write a
mapped value to the LED pins. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework1-RGB-LED/Homework1.ino)

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

> <i>Design a control system that simulates a 3-floor elevator using the Arduino
platform. By the end of this task, you will gain experience in using button state change, implementing debouncing techniques,
and coordinating multiple components to represent real-world scenarios. </i> ✔️

[💻 <b>Code</b>](https://github.com/anamariapanait10/Introduction-To-Robotics/blob/main/Homework/Homework2-Elevator-Simulator/Homework2-Code/Homework2/Homework2.ino)

<details>
 <summary><b>See more specific requirements</b></summary>
 
⚙️ Components:
-  4 LEDs 💡 (3 for the floors and 1 for the elevator’s operational state)
-  3 Buttons 🕹️ (for floor calls)
-  1 Buzzer 🔉(for door opening/closing or elevator moving sounds)
-  Resistors and wires

✏️ Requirements:

- **LED Indicators:** Each of the 3 LEDs should represent one of the 3 floors.
The LED corresponding to the current floor should light up. Additionally,
another LED should represent the elevator’s operational state. It should
blink when the elevator is moving and remain static when stationary.

- **Buttons:** Implement 3 buttons that represent the call buttons from the
3 floors. When pressed, the elevator should simulate movement towards
the floor after a short interval (2-3 seconds).
- **Buzzer:**
The buzzer should sound briefly during the following scenarios:
– Elevator arriving at the desired floor (something resembling a ”cling”).
– Elevator doors closing and movement (pro tip: split them into 2
different sounds)
- **State Change & Timers:** If the elevator is already at the desired floor,
pressing the button for that floor should have no effect. Otherwise, after
a button press, the elevator should ”wait for the doors to close” and then
”move” to the corresponding floor. If the elevator is in movement, it
should either do nothing or it should stack its decision (get to the first
programmed floor, open the doors, wait, close them and then go to the
next desired floor).
- **Debounce:** Remember to implement debounce for the buttons to avoid
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
   <a href="https://youtu.be/zJqB7nYcSQg"><img src="https://img.youtube.com/vi/zJqB7nYcSQg/0.jpg" alt="Video"></a>
 </div>
</details>
