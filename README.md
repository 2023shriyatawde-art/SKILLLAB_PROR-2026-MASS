# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4/3 students  
> **Project Duration:** 16 hours  
> **Total Time Available:** 32 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository

After forking this repository, rename it using the format:

`SKILLLAB_PROR-2026-TeamName`

### Example

`SKILLLAB_PROR-2026-AuroWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the build period.  
By the final review, this README should clearly show:

- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules

- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Group Name - MASS

`Project^2`

## 1.2 Team Members

| Name               | Primary Role                 | Secondary Role   | Strengths Brought to the Project        |
| ------------------ | ---------------------------- | ---------------- | --------------------------------------- |
| Aryamaan Patra     | System Coordination / Coding | Setup            | Technical support, Coordination         |
| Mitesh Chaurasiya  | Coding / Integration         | Testing          | Technical support, Debugging            |
| Satvik Bhusa       | Coding / Integration         | Testing          | System Planning, Debugging              |
| Shriya Tawde       | Documentation                | System Design    | Clear Documentation, System Planning    |

## 1.3 Project Title

Virtual Mouse

The project implements a computer vision-based system that enables mouse control through hand gestures, eliminating the need for a physical mouse.

<img width="842" height="487" alt="01 05 2026_10 25 07_REC" src="https://github.com/user-attachments/assets/5270d6fa-92df-4dab-b410-846986120f38" />


## 1.4 One-Line Pitch

`A vision-based virtual mouse system that uses hand gestures to enable intuitive and contactless human-computer interaction.

## 1.5 Expanded Project Idea

In 1–2 paragraphs, explain:

- what your project is,
- what kind of experience it creates,
- what technologies are involved.

**Response:**  
The project is an interactive projection-based system that integrates real-time object tracking, gesture recognition, and a physical robotic platform to create a hybrid physical-digital environment. A robotic car operates within a projected space where elements such as obstacles, paths, and targets are dynamically displayed using projection mapping. A camera continuously tracks the position and orientation of the car, and this data is processed in real time to update the projected environment accordingly, ensuring synchronization between physical movement and digital feedback. The system is controlled using a Raspberry Pi 4 Model B, which manages processing, communication, and hardware control.

The system is designed to deliver an immersive and engaging user experience by allowing interaction with a virtual, game-like environment through physical actions. Users control and navigate the car through projected challenges, effectively blending gameplay with real-world interaction. The implementation involves computer vision techniques using OpenCV for tracking, microcontroller-based motor control through drivers, wireless communication for command transfer, and projection systems for visual output. This combination of technologies enables a seamless interaction between the digital and physical domains.

---

# 2. Inspiration

## 2.1 References

List what inspired the project.

| Source Type |                           Link                                   | What Inspired You              |
| ----------- | --------------------------------------------------------------   |--------------------------------|
| [Video]     | https://youtu.be/ufm6tfgo-OA?si=yGRgK6GDuQBSjQ1w                 | Projection mapping interaction |
| [Video]     | https://www.instagram.com/reel/DXdhxdVgNgG/?igsh=b2c5a3B6c2hlM3dp| Immersive visual environments  |
| [Video]     | https://youtu.be/s7S4vco6bUk?si=OlaKAmpLrod_cQva                 | Real-time object tracking      |
| [Article]   | https://ieeexplore.ieee.org/document/10060367                    | Image processing basics        |
| [Project]   | https://www.geeksforgeeks.org/computer-vision/ai-virtual-mouse/  | Wireless hardware control      |


## 2.2 Original Twist

**Response:**
The originality of this project lies in the integration of projection mapping, real-time object tracking, and gesture-based interaction into a unified hybrid system. Unlike conventional projection systems that are passive or limited to touch interaction, this project introduces both a physical robotic platform and a vision-based gesture interface, enabling users to interact with the system through multiple input modalities.

In addition to controlling a robotic car within a dynamically projected environment, the system incorporates a hand gesture-based Rock–Paper–Scissors game using computer vision. This extends the interaction beyond navigation to include intuitive, contactless gameplay, demonstrating the system’s flexibility in supporting different types of user experiences within the same framework.

The combination of physical movement, gesture recognition, and real-time visual feedback creates a seamless connection between the digital and physical domains. By integrating computer vision, embedded systems, and interactive design, the project offers a novel and immersive approach that goes beyond traditional screen-based or single-mode interaction systems.

---

# 3. Project Intent

## 3.1 User Journey

The user interacts with the system in a controlled environment where a projector displays an interactive interface on a flat surface. Once the system is started, a camera captures input and the projected interface becomes active.

The user provides input either through a control interface or through hand gestures. The system processes these inputs in real time and updates the projected visuals accordingly. The user observes the changes on the projection and adjusts their input to interact with different elements displayed on the surface.

In a separate interaction mode, the user places their hand in front of the camera to perform gestures for a Rock–Paper–Scissors game. The system detects the gesture using computer vision techniques and displays the result immediately.

Overall, the user experiences a responsive system that allows interaction through simple inputs, with real-time visual feedback provided through projection.
                                                
---

# 4. Definition of Success

## 4.1 Definition of “Usable”

The system is considered usable if it responds reliably and accurately to user inputs, including control commands and hand gestures, with minimal delay. The projected interface should update in real time and clearly reflect the system’s state, allowing the user to understand and interact with it without confusion.

Additionally, the system should operate consistently under normal conditions, with stable camera tracking, smooth processing, and clear visual output. A usable system should not require repeated attempts for input recognition and should provide predictable and understandable feedback to the user during interaction.

## 4.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

**Response:**  

The minimum usable version of the project consists of a working system where the camera can detect and process user input, and the projector displays a basic interactive interface. The system should be able to respond to at least one form of input, either through a control interface or hand gestures, and provide real-time visual feedback on the projection.

At a basic level, the system should support simple interaction such as detecting a gesture and displaying a corresponding output, or allowing the user to interact with a projected element in a predictable way. The Rock–Paper–Scissors gesture module can serve as the core interaction in this version, where the system detects hand gestures and displays the result accurately.

This minimal setup ensures that the core concept of real-time interaction between user input and projected output is demonstrated, even without advanced features or multiple interaction modes.


## 4.3 Stretch Features

-Rock Papers Scissors Game

# 5. System Overview

## 5.1 Project Type

Check all that apply.

- [✅] Electronics-based

- [ ] Mechanical

- [ ] Sensor-based

- [ ] App-connected

- [ ] Motorized

- [ ] Sound-based

- [ ] Light-based

- [✅] Screen/UI-based

- [ ] Fabricated structure

- [✅] Game logic based

- [ ] Installation

- [ ] Other:

## 5.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
The system works by using a camera to capture live video of the user’s hand and interpreting the hand gestures to control different functions.

**Input:**  
The primary input is the live video feed from a camera. The user performs hand gestures in front of the camera, which are captured frame by frame.

**Processing:**  
The captured video frames are processed using computer vision techniques. MediaPipe is used to detect hand landmarks, and these landmarks are analyzed by a gesture recognition module to identify specific gestures. Based on the detected gesture, the system either switches modes or performs an action. The system also applies smoothing and cooldown mechanisms to ensure stable and accurate operation.

**Output:**  
The output depends on the active mode. The system can control the mouse cursor, perform clicks, control media playback, toggle appliances, or trigger an emergency alert. Visual feedback is displayed on the screen, showing the current mode and detected gesture. Audio feedback is also provided for certain actions like SOS or appliance control.

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/49e0520c-9fc7-4195-bc33-9845fecbcc83" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/f673b17f-8bf8-4325-ae29-7dd8b7d98715" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/4a4bf15f-c64b-4745-a83c-00360b1cee86" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/58c05c9d-7121-462a-a89b-5e9eb75df0de" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/28bff787-b95f-458c-b919-bcff4d7cd7c1" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/436f9545-a377-4743-936d-b7865870c8b2" />


**Physical Structure:**  
The system consists of a camera connected to a computing device such as a Raspberry Pi 4 Model B or a laptop. The setup does not require complex hardware and operates using a simple camera-based interface.

**App Interaction:**  
The system does not rely on a dedicated mobile or web application. Instead, it directly interacts with the operating system using libraries to simulate mouse and keyboard inputs, allowing it to control existing applications such as media players.

## 5.3 Input / Output Map

| System Part            | Type       | What It Does                                                                 |
| ---------------------- | ---------- | ---------------------------------------------------------------------------- |
| Camera (Webcam)        | Input      | Captures live video of the user’s hand gestures                              |
| Hand Gestures          | Input      | Provides commands to control different modes and actions                     |
| MediaPipe              | Processing | Detects hand landmarks from video frames                                     |
| Gesture Recognizer     | Processing | Interprets landmarks to identify specific gestures                           |
| Mode Controller        | Processing | Switches between modes like Mouse, Media, Appliance, and SOS                 |
| Virtual Mouse Module   | Output     | Controls cursor movement and mouse clicks                                    |
| Media Control Module   | Output     | Sends commands like play/pause, next, previous, volume control               |
| Appliance Control      | Output     | Toggles appliance states like light and fan (simulated)                      |
| SOS System             | Output     | Triggers emergency alert with audio feedback                                 |
| Display Interface      | Output     | Shows camera feed, current mode, and detected gestures on screen             |
| Audio Output (espeak)  | Output     | Provides voice feedback for actions like SOS and appliance control           |

# 6. System Design, Sketches and Visual Planning (NOT APPLICABLE)

## 6.1 Concept Architecture/sketch/schematic

Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`

Example:

```md

```



## 6.2 Labeled Build Sketch/architecture/flow diagram/algorithm

Add a sketch with labels showing:

- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[Upload image and link here]`

<img width="1326" height="1600" alt="image" src="https://github.com/user-attachments/assets/ba86d49c-e3bc-43a4-a25c-53d92d36bc09" />


## 6.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 7. Electronics Planning (NOT APPLICABLE)

## 7.1 Electronics Used

| Component                 | Quantity | Purpose                               |
| ------------------------- | --------:| ------------------------------------- |
| `[Raspi/FPGA]`                 | `1`      | `[Main controller]`                   |
| `[L298N Motor Driver]`    | `1`      | `[Control Motors]`                    |
| `[BO Motors]`             | `2`      | `[Rotate wheels]`                     |
| `[Buck Converter]`        | `1`      | `[Power ESP32]`                       |
| `[Li Ion Battery Pack]`   | `2`      | `[Power]`                             |
| `[Projector]`             | `1`      | `[Display obstacles]`                 |
| `Camera (Webcam / Phone)` | `1`      | `[Tracks car position using markers]` |

## 7.2 Wiring Plan

Describe the main electrical connections.

**sample Response:**  
`The RASPI is connected to the motor driver (L298N) using four GPIO pins (18,19; 22,23) to control motor direction (IN1, IN2, IN3, IN4). Two PWM-capable pins (ENA and ENB; 25 and 26) are connected to control the speed of each motor.

The motors are connected to the output terminals of the motor driver. The motor driver is powered directly by the battery pack (higher voltage), while the ESP32 receives regulated 5V from the buck converter.

All components share a common ground to ensure stable operation. The projector and camera are connected to the laptop, which handles tracking and game logic separately.`

## 7.3 Circuit Diagram/architecture diagram

Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`
<img width="867" height="1156" alt="" src="" />


# 7.4. Power Plan

| Question         | Response                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Power source     | `Battery (Li-ion pack)`                                                                                                                           |
| Voltage required | `~6–8.4V for motors (via driver), stepped down to 5V for ESP32 (buck converter)`                                                                  |
| Current concerns | `Motors can draw high current under load, which may cause voltage drops affecting ESP32 and WiFi stability`                                       |
| Safety concerns  | `Avoid over-discharging Li-ion batteries, ensure proper voltage regulation, prevent short circuits, and secure wiring to avoid loose connections` |

---

# 8. Software Planning/

## 8.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `[Python/PyGame/OpenCV]`       | `Track markers, game logic, create projection` |

## 8.2 Software Logic/Algorithm

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  

**Startup Behavior:**  
When the program starts, the camera is initialized and configured for resolution and frame rate. MediaPipe Hands is initialized for real-time hand tracking. System variables such as mode, smoothing buffers, cooldown timers, and appliance states are also initialized. The default mode is set to "IDLE".

**Input Handling:**  
The system continuously captures frames from the camera. Each frame is flipped horizontally and converted to RGB format for processing. MediaPipe detects hand landmarks if a hand is present in the frame.

**Sensor Reading / Data Extraction:**  
If a hand is detected, landmark coordinates are extracted and converted into pixel values. These landmarks are passed to a gesture recognition module, which identifies the current gesture (e.g., OPEN_PALM, PEACE, PINCH, etc.).

**Decision Logic:**  
- The system first checks for mode-switching gestures (such as OPEN_PALM, PEACE, THUMBS_INDEX, SPIDERMAN, FIST).  
- A cooldown mechanism ensures that modes are not switched repeatedly within a short time.  
- Based on the detected gesture, the system switches to one of the modes: MOUSE, MEDIA, APPLIANCE, SOS, or IDLE.  

Once a mode is active, further gestures are interpreted as actions specific to that mode.

**Output Behavior:**  

- **Virtual Mouse Mode:**  
  The position of the index finger is mapped from camera coordinates to screen coordinates using interpolation. Cursor movement is smoothed using a moving average filter. Gestures such as PINCH and TWO_PINCH trigger left and right mouse clicks with cooldown control.

- **Media Control Mode:**  
  Gestures trigger keyboard media keys such as play/pause, next track, previous track, and volume control using the pynput library. A gesture lock prevents rapid repeated inputs.

- **Appliance Control Mode:**  
  Specific gestures toggle appliance states (light and fan). The system updates internal states and provides audio feedback using text-to-speech.

- **SOS Mode:**  
  A predefined gesture triggers an emergency alert. The system plays an audio message and visually highlights the screen to indicate the alert.

- **Idle Mode:**  
  No actions are performed, and the system waits for new input.

**Communication Logic:**  
The system interacts directly with the operating system using libraries such as pynput to simulate mouse and keyboard inputs. No external communication protocol is used.

**Feedback System:**  
Visual feedback is provided through an on-screen display showing the current mode, detected gesture, and appliance states. Audio feedback is generated using the espeak text-to-speech system for certain actions.

**Reset Behavior:**  
If no hand is detected for a certain duration, the system automatically returns to IDLE mode. Cooldown timers and gesture locks reset over time to allow new inputs.

## 8.3 Code Flowchart

Insert a flowchart showing your code logic.

Suggested sequence:

- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  


<img width="758" height="1041" alt="flowchart26 drawio (1)" src="https://github.com/user-attachments/assets/e111ad2d-6f3c-4c48-a33d-393713aaef58" />



# 9. Bill of Materials (NOT APPLICABLE)

## 9.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `[RASPI]`                        | `1`      | `Yes`   | `No`         | `0`            | `38 Pin ESP32`                | `[To control components]` |
| `[Motor Driver]`                 | `[1]`    | `[Yes]` | `[No]`       | `0`            | `[LN296]`                     | `[To drive both motors]`  |
| `[DC Motors and wheel]`          | `[2]`    | `[No]`  | `[Yes]`      | `[150]`        | `[BO Motors and 6 cm wheels]` | `[high torque motors]`    |
| `[Buck Converter]`               | `[1]`    | `[No]`  | `[Yes]`      | `[75]`         |                               |                           |
| `[Li-ion batteries with holder]` | `[1]`    | `[No]`  | `[Yes]`      | `[200]`        |                               |                           |

## 9.2 Material Justification

Explain why you selected your main materials and components.

**Response:**  
`DC motors (BO motors) were chosen instead of servos or steppers because the system requires continuous rotation for movement rather than precise angular control (Previously, we were considering using steppers as we were planning on tracking movement on the ESP using its relative position from an origin, but since we're using a camera now, this is not required). A motor driver (L298N) was used to allow bidirectional control and speed variation using PWM.`


## 9.3 Items You chose

| Item                 | Why Needed               | Purchase Link | Latest Safe Date to Procure | Status       |
| -------------------- | ------------------------ | ------------- | --------------------------- | ------------ |
| `BO Motors + Wheels` | `Drive system for car`   | `robu.in`     | `15th April`                | `[Received]` |
| `Buck Converter`     | `Stable power for ESP32` | `local store` | `before testing`            | `[Received]` |
| `Li-ion Batteries`   | `Portable power`         | `local store` | `before testing`            | `Recieved`   |

## 9.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics           | `[400]`                     |
| Mechanical parts      | `[200]`                     |
| Fabrication materials | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[900]`                     |

## 9.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  

---

# 10. Planning the Work

## 10.1 Team Working Agreement

Write how your team will work together.

Include:

- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  


## 10.2 Task Breakdown

## 10.2 Task Breakdown

| Task ID | Task                                  |  Owner  | Estimated Time      | Dependency | Status    |
| ------- | ------------------------------------- | ------- | --------------------|----------- |---------- |
| T1      | Brainstorming & Finalizing concept    | ALL     |    15-20 min        | None       | Done      |  
| T2      | Implement hand detection and gestures | ARYAMAAN|    2 hrs            | T1         | Done      |
| T3      | Develop all control modes             | SATVIK  |    2 hrs            | T1         | Done      |
| T4      | Integrate system and perform testing  | MITESH  |    2 hs             | T3         | Done      |
| T5      | Documentation and System Design       | SHRIYA  | Parallel with tasks | ALL        | Updating  |

## 10.3 Responsibility Split

| Area                 | Main Owner     | Support Owner |
| -------------------- | ----------     | ------------- |
| Concept              | Aryamaan       | Satvik        |
| Coding               | Satvik         | Mitesh        |
| Testing              | Mitesh         | Aryamaan      |
| Documentation        | Shriya         |  ALL          |

---

# 11 hour Milestones

## 11.1 8-hour Plan(tentetively you may set)

### Bi Hour 1 — Plan and De-risk

Expected outcomes:

- [x] Idea finalized
- [x] Core interaction decided
- [ ] Sketches made
- [ ] BOM completed
- [ ] Purchase needs identified
- [x] Key uncertainty identified
- [x] Basic feasibility tested

### Bi Hour 2 — Build Subsystems

Expected outcomes:

- [x] Camera and hand tracking tested
- [x] Gesture detection implemented
- [x] UI design (Not applicable – minimal UI)
- [x] Core modules partially working

### Bi Hour 3 — Integrate

Expected outcomes:

- [x] Modules integrated (mouse, media, appliance, SOS)
- [x] Code connected and running
- [ ] External app connection (Not applicable)
- [x] First working version achieved

### Bi Hour 4 — Refine and Finish

Expected outcomes:

- [x] Technical bugs reduced
- [x] Playtesting completed
- [x] Improvements made
- [x] Documentation completed
- [x] Final build ready
      
## 12.2  Update Log 

## 12.2 Update Log

| Days  | Planned Goal                 | What Actually Happened        | What Changed                    | Next Steps             |
| ----- | ---------------------------- | ----------------------------- | ------------------------------- | ---------------------- |
| Day 1 | Build core system            | Implemented gesture modules   | Improved gesture accuracy       | Integrate modules      |
| Day 2 | Integrate and finalize       | Completed testing and docs    | Added smoothing and cooldown    | Final review           |

---

# 13. Risks and Unknowns

## 13.1 Risk Register

                                                                                                                                                                  |          Risk                   | Owner               | Type     |  Likelihood  | Impact     | Mitigation Plan                                              |
| --------------------------------|---------------------|--------- | ------------ | ---------- | -------------------------------------------------------------|
|Mediapipe only works on python.11|
|Integration of tkinter           |
|rps gesture mode accuracy        |


## 13.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage

**Response:**  
The biggest uncertainty is the reliability of gesture recognition under different lighting conditions and backgrounds. Variations in environment and hand positioning can affect detection accuracy and may lead to inconsistent system behavior.

---

# 14. Testing 

## 14.1 Technical Testing Plan

| What Needs Testing        | How You Will Test It                          | Success Condition                         |
| ------------------------ | --------------------------------------------- | ------------------------------------------ |
| Hand detection           | Show hand to camera                           | Hand landmarks detected correctly          |
| Gesture recognition      | Perform predefined gestures                   | Correct gesture is identified              |
| Mode switching           | Use mode switch gestures                      | Mode changes accurately                    |
| Mouse control            | Move hand and perform click gestures          | Cursor moves and clicks correctly          |
| Media control            | Use media gestures                            | Media actions trigger correctly            |
| Appliance control        | Perform ON/OFF gestures                       | Correct action is executed                 |
| SOS detection            | Perform SOS gesture                           | Alert is triggered                         |                                                  
                       
## 14.2 Testing and Debugging Log

| Date         | Problem Found                  | Type       | What You Tried                  | Result            | Next Action               |
| ------------ | ------------------------------ | ---------- | ------------------------------- | ----------------- | ------------------------- |
| 30th April   | Gesture not detected properly  | Technical  | Adjusted lighting and angles    | Improved          | Fine-tune thresholds      |
| 30th April   | Multiple clicks triggered      | Logic      | Added cooldown delay            | Fixed             | Optimize timing           |
| 30th April   | Cursor movement not smooth     | Performance| Added smoothing algorithm       | Improved          | Further optimize          |

## 14.3 Playtesting Notes

| Tester   | What They Did                     | What Confused Them           | What They Enjoyed           | What You Will Change         |
| -------- | -------------------------------- | ---------------------------- | --------------------------- | ---------------------------- |
| User 1   | Tested mouse and gestures        | Some gestures hard to perform| Smooth cursor movement      | Simplify gestures            |
| User 2   | Tested media control             | Mode switching unclear       | Easy media control          | Improve mode indication      |
| ALL      | Tested full system               | Occasional misdetection      | Interactive experience      | Improve accuracy             |

---

# 15. Build Documentation 

## 15.1 Fabrication Process(if any) (NOT APPLICABLE)

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`The fabrication process involved designing, manufacturing, assembling, and refining both the physical structure and electronic integration of the system.`

`Design (CAD Modeling):
The initial model was created using CAD software, where components were designed based on the actual dimensions of the electronic parts. This ensured accurate fitting and minimized errors during assembly.
Cutting (Laser Cutting):
The designed parts were fabricated using laser cutting techniques. Sheets were cut precisely according to the CAD model to create the structural base and mounts for components.`

`Components were fixed using adhesives and mechanical supports. Certain parts were intentionally kept modular (not permanently fixed) to allow easy replacement and modification of electronics.
Surface Finishing:
Some parts were sanded to smooth rough edges after cutting. Sawdust mixed with adhesive was used to fill gaps and uneven edges, improving structural finish. The final structure was then painted for better aesthetics and durability.`

`Environment Setup (Dark Room Fabrication):
To enhance projection visibility, a controlled dark environment was created using Z-boards, paper sheets, and bedsheets. This minimized external light interference and improved projection clarity.
Revisions and Iterations:
Multiple adjustments were made throughout the process, including refining alignment, improving structural stability, repositioning components, and optimizing the interaction between the physical car and projected environment.`

## 16 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.
- <img width="960" height="1280" alt="WhatsApp Image 2026-04-24 at 9 46 02 AM (1)" src="https://github.com/user-attachments/assets/74baa570-5770-483e-be6d-d2f03386e37c" />





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

**Response:**  
The final system is a gesture-based virtual control platform developed using a webcam and computer vision techniques. It enables users to interact with their system using hand gestures without physical contact. The system supports multiple modes, including virtual mouse control, media control, appliance control, SOS detection, and a gesture-based rock–paper–scissors game. 

Hand movements are captured through a camera, processed using MediaPipe for hand tracking, and interpreted into gestures. These gestures are mapped to specific actions such as cursor movement, clicking, media playback control, and triggering alerts. The system runs in real time and provides a smooth and interactive user experience.


## 17.2 What Works Well
- Accurate hand detection and tracking  
- Reliable gesture recognition for most predefined gestures  
- Smooth cursor control with gesture-based clicks  
- Proper mode switching between different functionalities  
- Integration of multiple features into a single system  


## 17.3 What Still Needs Improvement
- Performance under varying lighting conditions  
- Gesture recognition consistency across different users  
- Reduction of occasional false detections  
- Improved feedback or visual indicators for active mode  


## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

**Response:**  
The initial idea focused on a basic gesture-controlled system. During development, the project was expanded to include multiple modes such as media control, appliance control, and SOS detection. Additionally, a gesture-based rock–paper–scissors game was added to enhance interactivity. The final system became more feature-rich and integrated compared to the original plan.

---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
The team worked well in terms of clear role distribution and effective collaboration. Each member contributed to their respective areas, with coding, testing, and documentation handled efficiently. Communication within the team was consistent, which helped in quick decision-making and problem-solving during development.

One of the main challenges was managing gesture accuracy and ensuring smooth integration of multiple features within limited time. Debugging and fine-tuning the system took longer than expected, especially while handling real-time performance issues.

Overall, time and tasks were managed effectively within the hackathon constraints. The team was able to prioritize core functionalities first and then gradually add additional features. Responsibilities were handled properly, and coordination between members ensured that the project was completed successfully within the given time.


## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
Through this project, we gained practical understanding across multiple technical areas.

In electronics, we learned how to interface and utilize a Raspberry Pi for real-time applications, including handling camera input and system-level interactions.

In coding, we developed strong skills in Python, especially using libraries such as OpenCV and MediaPipe for computer vision. We learned how to implement gesture recognition, apply smoothing techniques, and manage real-time processing with efficient logic.

Mechanisms and fabrication were not a primary focus in this project, as the system was software-oriented and did not involve physical structures.

In integration, we learned how to combine multiple modules—such as gesture detection, mode switching, and different control functionalities—into a single cohesive system. Ensuring that all components worked together smoothly in real time was a key learning outcome.


## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

**Response:**  
We learned that designing a gesture-based system requires simplicity and clarity. Gestures must be easy to perform and clearly mapped to actions so users can understand the system quickly.

User delight comes from smooth and responsive performance. Stable cursor movement and quick response improve the overall experience.

Clarity is important in indicating the current mode and system behavior to avoid confusion.

Physical interaction through hand gestures highlighted the need for natural and comfortable movements.

Iteration was essential, as multiple refinements were needed to improve accuracy, reduce errors, and enhance usability.


## 18.3 Design Reflection

We learned that designing a gesture-based system requires simplicity and clarity. Gestures must be easy to perform and clearly mapped to actions so users can understand the system quickly.

User delight comes from smooth and responsive performance. Stable cursor movement and quick response improve the overall experience.

Clarity is important in indicating the current mode and system behavior to avoid confusion.

Physical interaction through hand gestures highlighted the need for natural and comfortable movements.

Iteration was essential, as multiple refinements were needed to improve accuracy, reduce errors, and enhance usability.

---

## 18.4 What would you do if you had one more hour

With one more hour, we would focus on improving gesture recognition accuracy and system stability. This includes refining thresholds, reducing false detections, and optimizing performance under different lighting conditions. We would also enhance user feedback by adding clearer visual indicators for active modes.



---
# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [ ] Sketches are added
- [x] BOM is complete
- [ ] Purchase list is complete
- [ ] Budget summary is complete
- [ ] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [ ] Weekly logs are updated
- [ ] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
<img width="1131" height="1600" alt="image" src="" />

---


---


