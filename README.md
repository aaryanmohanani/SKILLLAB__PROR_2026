# SKILL LAB PRATICAL HACKATHON

## Final Project README

> **Project Weight:** 100%  
> **Team Size:** 4 students  
> **Project Duration:** 8 hours  
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

## 1.1 Studio / Group Name

`SKILLLAB_PROR-2026-RoboForge`

## 1.2 Team Members

| Name           | Primary Role                    | Secondary Role | Strengths Brought to the Project |
| -------------- | ------------------------------- | -------------- | -------------------------------- |
| `Aaryan Mohanani` | `Documentation/PPT` | `Project & Application Help`  | `Documentation, Presentation, Communication`|
| `Hussain Patanwala`  | `Documentation/PPT`   | `Making the Project Skeleton(Robotic Arm)`     | `Material Handling, Mechanical Assembly`    |
| `Jaisingh Sangtani` | `Coding` | `Project Implementation`  | `Programming, Logic Building, Debugging`|
| `Yogesh Thankar`  | `Project Implementation`   | `Coding`     | `Implementation, Testing, System Integration`    |

## 1.3 Project Title

`"IR-Remote Controlled Robotic Arm For Painting Applications in the Industry (Spray Paint/Normal Painting) using RP2040"`

![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/ChatGPT_Generated_Image_logo.png?raw=true)

## 1.4 One-Line Pitch

`A low-cost, IR-controlled robotic arm powered by RP2040 that enables precise, remote-operated industrial painting with improved safety and efficiency.`

## 1.5 Expanded Project Idea

This project presents an IR remote controlled robotic arm designed for industrial painting applications using the RP2040 microcontroller. The system uses servo motors to control multiple joints of the arm, allowing it to perform precise movements required for spray painting or brush-based painting tasks. An IR remote is used to wirelessly control the arm’s motion, enabling the user to operate it from a safe distance. The goal is to simulate a low-cost automation solution that can be used in industries to reduce manual effort and improve consistency in painting operations.

The project creates an interactive experience where the user can control the robotic arm in real time, observing how each input from the remote translates into mechanical motion. This demonstrates key concepts of industrial automation such as remote operation, precision control, and repeatability. The system integrates technologies including the RP2040 microcontroller, IR communication, PWM-based servo control, and basic embedded programming. Together, these components form a compact and efficient system that highlights how automation can enhance productivity and safety in industrial environments.


---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem

This project focuses on creating an interactive and engaging experience rather than solving a large social problem. The IR-controlled robotic arm acts as a playful yet functional machine that allows users to control movements in real time and perform painting actions. It combines elements of a toy, a kinetic artifact, and an industrial simulation, making it both entertaining and educational.

The experience is designed to be visually satisfying and interactive, where users can remotely operate the arm and observe precise movements translating into painting actions. It highlights the joy of controlling a mechanical system while also demonstrating the principles of automation in a simplified and accessible way.



# 3. Inspiration

## 3.1 References

List what inspired the project.

| Source Type | Title / Link                                                        | What Inspired You                                                                         |
| ----------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| `[Chatgpt]`   | `(https://chatgpt.com/share/69f043bc-d244-8322-ac57-1588f2ae686a)` | 'Helped in generating the project idea, refining the concept, and assisting with implementation logic' |
|   '[Chatgpt]'          |   (https://chatgpt.com/share/69f047fb-762c-8321-8e0d-087596900b7d)                                                                  | 'Helped in structuring the report, refining explanations, and organizing content clearly'                                                                                          |
|             |                                                                     |                                                                                           |

## 3.2 Original Twist

What makes your project original?

-->The originality of this project lies in combining industrial robotic arm concepts with a low-cost, hands-on, and interactive setup using cardboard and simple components. Instead of focusing purely on automation, the system emphasizes user interaction through an IR remote, turning it into a controllable experience. The use of accessible materials like cardboard and basic electronics makes it a playful yet functional prototype that bridges the gap between industrial machinery and creative experimentation.
**Response:**  


---

# 4. Project Intent

## 4.1 User Journey 

-->A user approaches the RoboForge system and picks up the IR remote placed beside the robotic arm. After switching on the system, the arm comes to its initial resting position, ready for operation. The user then presses different buttons on the remote to control the movement of the arm. As each button is pressed, the robotic arm responds instantly—rotating, lifting, or adjusting its gripper position. The user can carefully position the arm as if performing a painting task, simulating how industrial robotic arms spray or apply paint on surfaces.

As the user continues interacting, they begin to understand how each control affects the arm’s motion, gaining a sense of precision and coordination. The experience becomes engaging as the user tries to mimic real industrial painting movements, adjusting angles and positions for better control. By the end of the interaction, the user not only enjoys controlling the robotic arm but also gains insight into how automation works in industrial environments, making the system both educational and interactive.

                                                  |



---

# 5. Definition of Success

## 5.1 Definition of “Usable”

-->The system is considered usable when the robotic arm responds correctly to inputs from the IR remote and performs controlled movements such as lifting, rotating, and gripping. The user should be able to operate the arm smoothly without errors, and each button press should result in a predictable and stable motion. The structure should be physically stable, and the servos should move without jitter or power issues.

## 5.2 Minimum Usable Version

What is the smallest version of this project that still delivers the core experience?

-->The smallest version of this project that still delivers the core experience includes:

1)A simple cardboard robotic arm structure.

2)At least 2 servo motors (one for arm movement and one for gripper).

3)Basic IR remote control for movement.

4)Predefined motions (up/down, open/close).

This version allows the user to experience remote-controlled mechanical movement, which is the core idea of the project.


## 5.3 Stretch Features

What features are nice to have but not essential?

-->These are additional features that improve the project but are not essential:

1)Adding more servo motors for extra degrees of freedom (base rotation, wrist movement).

2)Smoother and more precise control (fine angle adjustments).

3)Adding a paint mechanism simulation (spray bottle / marker attachment).

4)Improved structure using stronger materials.

5)Preset automated movements (record and replay actions).

6)LED indicators for system status.

---

# 6. System Overview

## 6.1 Project Type

Check all that apply.

- [x] Electronics-based

- [x] Mechanical

- [x] Sensor-based

 [⛌] App-connected

- [x] Motorized

 [⛌] Sound-based

 [⛌] Light-based

 [⛌] Screen/UI-based

- [x] Fabricated structure

 [⛌] Game logic based

 [⛌] Installation

 [⛌] Other:N/A

## 6.2 High-Level System Description

Explain how the system works in simple terms.

Include:

- input,
- processing,
- output,
- physical structure,
- app interaction if any.

-->The system is a robotic arm controlled using an IR remote, with the RP2040 (Shrike Lite) acting as the main controller.

Input:
The user provides input through an IR remote. The IR receiver module detects the signals and sends digital input to the RP2040. (Earlier a potentiometer was considered, but it was removed for simplicity and reliability.)

Processing:
The RP2040 processes the received IR signals, identifies which button is pressed, and maps each input to a specific servo movement. The logic ensures correct angle control and smooth motion using PWM signals.

Output:
The system outputs movement through three servo motors:

MG996R for the base rotation (high torque),
SG90 servos for arm segments (precise movement).

These servos rotate to specific angles based on user commands, enabling controlled movement of the robotic arm.

Physical Structure:
The robotic arm is built using cardboard, designed with multiple joints. Servos are mounted at these joints to allow rotational movement. The structure is lightweight but reinforced for stability.

Power System:
An external 5V power supply powers the servo motors to ensure stable performance, while all components share a common ground for proper operation.

App Interaction:
There is no mobile or web app involved. The system works entirely through IR remote control, making it simple and user-friendly.

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|-------------|------|--------------|
| `IR Remote` | `Input` | `Sends user commands wirelessly (button presses)` |
| `IR Receiver Module` | `Input` | `Receives IR signals and converts them to digital signals for RP2040` |
| `RP2040 (Shrike Lite)` | `Processing` | `Processes input signals and generates PWM outputs for servo control` |
| `MG996R Servo Motor` | `Output` | `Controls base rotation of robotic arm (high torque movement)` |
| `SG90 Servo Motor #1` | `Output` | `Controls first arm segment movement` |
| `SG90 Servo Motor #2` | `Output` | `Controls second arm segment movement` |
| `External 5V Power Supply` | `Power` | `Provides stable power to servo motors` |
| `Common Ground` | `Support` | `Ensures all components share a reference voltage for proper operation` |
---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch

![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/Robotic_Arm_Ideas.jpeg?raw=true)


## 7.2 Labeled Build Sketch

![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/Labeled_Build_Sketch.png?raw=true)

## 7.3 Approximate Dimensions

| Dimension        | Value   |
| ---------------- | ------- |
| Length           | `16 cm` |
| Width            | `16 cm` |
| Height           | `8 cm`  |
| Estimated weight | `400 g` |

---

# 8. Electronics Planning

## 8.1 Electronics Used

| Component                 | Quantity | Purpose                               |
| ------------------------- | --------:| ------------------------------------- |
| `RP2040 (Vicharak Shrike Lite)`                 | `1`      | `Main controller for processing inputs and controlling the robotic arm`                   |
| `IO Shield Board`    | `1`      | `Provides easy GPIO connections and power distribution`                    |
| `SG90 Servo Motors`             | `2`      | `Used for basic arm movement (lifting and positioning)`                     |
| `MG996R Servo Motor`        | `1`      | `Used for high-torque operation (base or gripper control)`                       |
| `IR Remote`   | `1`      | `Used to send control commands wirelessly`                             |
| `Jumper Wires (M-M, F-M, F-F)`             | `Multiple`      | `Used for electrical connections between components`                 |
| `External Power Supply` | `1`      | `Provides sufficient power to servo motors for stable operation` |

## 8.2 Wiring Plan

Describe the main electrical connections.

The RP2040 (Shrike Lite) microcontroller is used as the main controller for the robotic arm. The SG90 and MG996R servo motors are connected directly to the GPIO pins of the RP2040 through the IO shield.

Each servo motor has three connections:

1)VCC (5V power)
2)GND (Ground)
3)Signal (connected to GPIO pins)

The signal pins of the servos are connected to PWM-capable GPIO pins on the RP2040 to control their angular movement.

An external 5V power supply is used to power the servo motors to ensure stable operation and prevent overloading the RP2040 board. The RP2040 is powered separately via USB.

The IR receiver module is connected to one GPIO input pin of the RP2040 to receive signals from the IR remote. Based on the received signals, the microcontroller sends control signals to the servo motors.

All components share a common ground to ensure proper signal reference and stable functioning of the system.

## 8.3 Circuit Diagram

![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/ckt_diagram.jpeg?raw=true)


## 9. Power Plan

| Question           | Response                                                                 |
| ------------------ | ------------------------------------------------------------------------ |
| Power source       | `External 5V Power Supply`                                               |
| Voltage required   | `5V for servo motors and RP2040 (regulated supply)`                      |
| Current concerns   | `Servo motors draw high current → may cause voltage drop if unstable`    |
| Safety concerns    | `Ensure proper wiring, avoid short circuits, use common ground, stable supply` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform                | Purpose                                        |
| ------------------------------ | ---------------------------------------------- |
| `Arduino IDE`                | `Used for programming the RP2040 microcontroller, controlling servo motors, and implementing IR remote-based robotic arm movement`                                | 

## 10.2 Software Logic

Describe what the code must do.

Include:

- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

-->

1)Startup behavior:
When powered on, the RP2040 initializes all servo motor pins and the IR receiver module. The servos are set to their default (home) positions to ensure a known starting state.

2)Input handling:
The system receives input from the IR remote. Each button press is detected by the IR receiver and decoded by the RP2040.

3)Sensor reading:
The IR receiver continuously reads incoming infrared signals and converts them into digital codes corresponding to specific buttons on the remote.

4)Decision logic:
The RP2040 compares the received IR code with predefined commands. Based on the button pressed, it decides which servo motor to move and in which direction (increase/decrease angle).

5)Output behavior:
The microcontroller sends PWM signals to the servo motors (SG90 and MG996R), controlling their angular movement to move different parts of the robotic arm (base, joint, gripper).

6)Communication logic:
There is no wireless or network communication. All control is done locally through the IR remote and receiver.

7)Reset behavior:
If no button is pressed, the arm holds its current position. A specific button can be assigned to reset all servos to their default (home) position.

## 10.3 Code Flowchart

![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/flowchart.png?raw=true)

# 11. Bill of Materials

## 11.1 Full BOM

| Item                             | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec               | Why This Choice?          |
| -------------------------------- | --------:| ------- | ------------ | --------------:| ----------------------------- | ------------------------- |
| `RP2040 (Shrike Lite)`                        | `1`      | `Yes`   | `No`         | `400`            | `RP2040 Microcontroller`                | `Main controller for project` |
| `IO Shield Board`                 | `1`    | `Yes` | `No`       | `0`            | `GPIO Expansion Shield`                     | `Easy wiring and stable connections`  |
| `SG90 Servo Motor`          | `2`    | `No`  | `Yes`      | `200`        | `Micro Servo (180°)` | `Used for lightweight movements`    |
| `MG996R Servo Motor`               | `1`    | `No`  | `Yes`      | `250`         |     High Torque Servo                          |           Used for heavy load / main motion                |
| `IR Remote` | `1`    | `Yes`  | `No`      | `0`        |               Infrared Remote                |     User input control                      |
| `IR Receiver`          | `1`    | `Yes`  | `No`      | `0`        | `IR Sensor Module` | `Receives signals from remote`    |
| `Jumper Wires (M-M, F-M, F-F)`               | `1 Set Each Type`    | `Yes`  | `No`      | `0`         |    Connecting wires                           |         For all circuit connections                  |
| `External Power Supply (5V)` | `1`    | `No`  | `Yes`      | `150`        |           5V Adapter / Battery                    |                   Stable power for servos        |


## 11.2 Material Justification

Explain why you selected your main materials and components.

-->The RP2040 (Shrike Lite) was selected as the main controller because it provides stable performance, sufficient GPIO pins, and is easy to program using the Arduino IDE. It is well-suited for controlling multiple servo motors and handling real-time input from sensors like the IR receiver.

The SG90 servo motors were chosen for lightweight movements due to their low cost, ease of use, and adequate torque for small mechanical actions. For heavier or load-bearing movement, the MG996R servo motor was selected because of its high torque capability, making it suitable for more demanding motion requirements.

An IR remote and receiver module was used for input control because it provides a simple, reliable, and wireless method of user interaction without the complexity of WiFi or Bluetooth communication.

The IO shield board was included to simplify wiring and ensure stable connections between components, reducing the chances of loose connections during testing.

Jumper wires were used for flexible and quick prototyping, allowing easy modification of connections during development.

An external 5V power supply was used to power the servo motors separately, as high-torque servos like the MG996R require stable current that cannot be reliably provided by the microcontroller alone.

Overall, the selected components provide a balance of simplicity, reliability, cost-effectiveness, and sufficient performance for the project requirements.


## 11.3 Items You chose

## 11.3 Items You Chose

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|------|-----------|-------------|---------------------------|--------|
| `RP2040 (Shrike Lite)` | `Main controller for system` | `Provided in lab kit` | `N/A` | `[Available]` |
| `SG90 Servo Motors (2)` | `Lightweight movement control` | `robu.in / Amazon` | `Before testing` | `[Purchased]` |
| `MG996R Servo Motor (1)` | `High torque movement` | `robu.in / Amazon` | `Before testing` | `[Purchased]` |
| `IR Remote + Receiver` | `User input control` | `Provided in kit` | `N/A` | `[Available]` |
| `IO Shield Board` | `Easy and stable wiring` | `Provided in kit` | `N/A` | `[Available]` |
| `Jumper Wires` | `Connections between components` | `Provided in kit` | `N/A` | `[Available]` |
| `External 5V Power Supply` | `Stable power for servos` | `Local store / adapter` | `Before testing` | `[Purchased]` |

## 11.4 Budget Summary

| Budget Item           | Estimated Cost              |
| --------------------- | ---------------------------:|
| Electronics (RP2040, IO Shield, 2× SG90, 1× MG996R, IR Remote, Jumper Wires, 5V Supply)         | `[1200]`                     |
| Mechanical Parts (Cardboard structure, joints, servo mounts)      | `[200]`                     |
| Fabrication materials (Glue, tape, basic tools – available in lab) | `[0 (Available on campus)]` |
| Purchased extras      | `[0]`                       |
| Contingency           | `[300]`                     |
| **Total**             | `[1700]`                     |

## 11.5 Budget Reflection

If your cost is too high, what can be simplified, removed, substituted, or shared?

-->The overall cost of the project is already kept low by using components available in the lab. However, if the cost needs to be reduced further, certain optimizations can be made. The MG996R servo motor can be replaced with another SG90 servo if high torque is not strictly required. The external power supply can be shared among team members instead of using a dedicated unit. Additionally, fabrication materials like cardboard, glue, and wiring can be reused or shared from common lab resources. This approach ensures that the project remains cost-effective while still maintaining its core functionality.

---

# 12. Planning the Work

## 12.1 Team Working Agreement

The team will work collaboratively by dividing tasks based on individual strengths. The mechanical structure of the robotic arm will be handled by members skilled in fabrication and assembly, while coding and electronics integration will be managed by members comfortable with programming and wiring. Documentation and presentation tasks will be assigned to members with strong communication and organizational skills.

Decisions will be made through quick group discussions, ensuring that all members contribute their ideas while keeping time constraints in mind. Progress will be checked regularly after each major step, such as structure completion, wiring, and testing. If any task is delayed, responsibilities will be redistributed among team members to ensure timely completion of the project.

All documentation will be maintained in a shared GitHub repository, where updates, code, and reports will be uploaded regularly. This ensures transparency, easy access, and proper tracking of the project development process.


## 12.2 Task Breakdown

| Task ID | Task                         | Owner     | Estimated Hours | Deadline   | Dependency        | Status |
| ------- | ---------------------------- | --------- | --------------- | ---------- | ----------------- | ------ |
| T1      | Project Planning & Concept   | Aaryan    | 1               | Hour 1     | None              | Done   |
| T2      | Component Selection (BOM)    | Hussain   | 1               | Hour 1     | T1                | Done   |
| T3      | Electronics Setup            | Yogesh    | 2               | Hour 2-3   | T2                | Done   |
| T4      | Mechanical Build             | Jaisingh  | 2               | Hour 4     | T2                | Done   |
| T5      | Wiring & Integration         | Aaryan    | 1               | Hour 5     | T3, T4            | Done   |
| T6      | Coding & Control Logic       | Hussain   | 2               | Hour 6     | T3                | Done   |
| T7      | Testing & Debugging          | Yogesh    | 1               | Hour 7     | T5, T6            | Done   |
| T8      | Final Assembly & Finishing   | Jaisingh  | 1               | Hour 8     | T7                | Done   |
| T9      | Documentation & Reporting    | Aaryan    | 1               | Hour 8     | All               | Done   |


## 12.3 Responsibility Split

| Area                 | Main Owner | Support Owner |
| -------------------- | ---------- | ------------- |
| Concept              | `Yogesh`  | `Jaisingh`    |
| Electronics          | `Jaisingh`       | `Yogesh`     |
| Coding               | `Jaisingh`       | `Yogesh`     |
| Mechanical build     | `Hussain`       | `Yogesh`    |
| Testing              | `Aaryan`       | `Jaisingh`    |
| Documentation        | `Aaryan`       | `Yogesh`     |

---

# 13.1 hour Milestones

The project was completed following a structured 8-hour development plan to ensure efficient progress and timely completion. In the initial hour, the team finalized the project idea, defined the core interaction, and prepared basic sketches along with the bill of materials. In the next two hours, all electronic components such as the RP2040, servo motors, IR receiver, and potentiometer were tested individually to ensure proper functionality.

The fourth hour was focused on building the mechanical structure using cardboard and mounting the servo motors securely. During the fifth and sixth hours, the electronics were integrated with the structure, and the code was connected to the hardware to enable real-time control using the IR remote and potentiometer. In the seventh hour, the system was thoroughly tested, and issues such as servo instability and IR compatibility were identified and resolved. Finally, in the eighth hour, the project was refined, documentation was completed, and the system was prepared for demonstration. This structured approach ensured smooth development, proper debugging, and a fully functional final output.

## 13.2  Update Log
### 13.2 Work Progress Log

| Time | Planned Goal | What Actually Happened | What Changed | Next Steps |
|------|--------------|----------------------|--------------|------------|
| `Hour 1` | `Plan design and gather components` | `Finalized robotic arm design and collected all parts` | `Simplified structure for faster build` | `Start fabrication` |
| `Hour 2` | `Begin structure fabrication` | `Cut and assembled base and arm using cardboard` | `Reinforced weak joints with double layers` | `Mount servos` |
| `Hour 3` | `Mount servo motors` | `Installed SG90 and MG996R servos in joints` | `Adjusted positions for better movement` | `Start wiring` |
| `Hour 4` | `Complete wiring` | `Connected servos and IR receiver to RP2040` | `Used IO shield for stable connections` | `Test individual components` |
| `Hour 5` | `Test servo movement` | `Checked servo control using basic code` | `Fixed power issue using external 5V` | `Integrate IR control` |
| `Hour 6` | `Implement IR control` | `Mapped remote buttons to servo movement` | `Refined command mapping` | `Full system testing` |
| `Hour 7` | `Test complete system` | `Ran full robotic arm using IR remote` | `Improved response and reduced delay` | `Final adjustments` |
| `Hour 8` | `Finalize project` | `Completed integration and testing` | `Minor improvements in wiring and stability` | `Ready for demo` |
---

# 14. Risks and Unknowns

## 14.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|------|------|-----------|--------|------------------|--------|
| `IR signal not detected properly` | `Technical` | `Medium` | `Medium` | `Ensure proper alignment, avoid obstacles, test range before demo` | `Jaisingh Sangtani` |
| `Servo motors jitter or behave unpredictably` | `Technical` | `Medium` | `High` | `Use stable 5V external supply, avoid powering from board, check wiring` | `Yogesh Thankar` |
| `MG996R servo draws high current causing instability` | `Technical` | `High` | `High` | `Use dedicated 5V supply, test under load, ensure proper grounding` | `Jaisingh Sangtani` |
| `Loose jumper wire connections` | `Mechanical` | `Medium` | `Medium` | `Secure connections, use IO shield, double-check before testing` | `Hussain Patanwala` |
| `IR code mismatch or no response` | `Software` | `Low` | `High` | `Verify IR codes, use serial monitor, debug input signals` | `Aaryan Mohanani` |


## 14.2 Biggest Unknown Right Now

What is the single biggest uncertainty in your project at this stage?

-->The biggest uncertainty right now is achieving smooth and stable movement of the robotic arm using servo motors. Since the structure is made of cardboard, maintaining proper balance and alignment while handling load is challenging. Additionally, ensuring accurate response from the IR remote without delay or signal loss is also a key uncertainty.


---

# 15. Testing 

## 15.1 Technical Testing Plan

| What Needs Testing     | How You Will Test It                                                                 | Success Condition                                                                                    |
| ---------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| `IR Remote Control`    | `Press buttons and observe servo movement`                                              | `All servos respond correctly to assigned buttons`                                                   |
| `Servo Movement`    | `Move arm in all directions`                                              | `Smooth and stable motion without jitter`                                                 
| `Power Stability`    | `Run all servos together`                                              | `No reset or power drop`                                                   |
                       
### 15.2 Testing and Debugging Log

| Time | Problem Found | Type | What You Tried | Result | Next Action |
|------|--------------|------|----------------|--------|-------------|
| `Hour 1` | `Servo not moving due to potentiometer issue` | `Technical` | `Removed faulty potentiometer and directly tested servo` | `Worked` | `Avoid unnecessary components` |
| `Hour 2` | `IR remote and receiver not compatible` | `Technical` | `Replaced with compatible IR remote-receiver pair` | `Worked` | `Verify component compatibility before use` |
| `Hour 3` | `Initial servo testing` | `Testing` | `Checked basic servo movement using code` | `Worked` | `Proceed to integration` |
| `Hour 4` | `IR signal reading setup` | `Software` | `Configured IR library and tested signal input` | `Worked` | `Map remote buttons` |
| `Hour 5` | `Servo control via IR` | `Integration` | `Linked IR input to servo movement` | `Worked` | `Refine control logic` |
| `Hour 6` | `Response optimization` | `Software` | `Improved code execution and reduced delay` | `Worked` | `Test consistency` |
| `Hour 7` | `System stability check` | `Testing` | `Ran multiple trials for reliability` | `Worked` | `Prepare for final demo` |
| `Hour 8` | `Final system integration` | `Integration` | `Tested complete system together` | `Worked` | `Ready for demo` |


### 15.3 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|--------|--------------|--------------------|-------------------|----------------------|
| `Aaryan Mohanani` | `Tested full system control using IR remote` | `Slight delay in response` | `Smooth servo control` | `Optimize code for faster response` |
| `Yogesh Thankar` | `Tested power stability and servo movement` | `Servo jitter at low voltage` | `Stable motion after fix` | `Ensure consistent power supply` |
| `Jaisingh Sangtani` | `Tested IR input mapping and button response` | `Button mapping confusion initially` | `Accurate control after mapping` | `Label controls clearly` |
| `Hussain Patanwala` | `Tested physical setup and wiring` | `Wire placement clarity` | `Clean setup after adjustments` | `Improve cable management` |


---

# 16. Build Documentation

## 16.1 Fabrication Process

Describe how the project was physically made.

Include:

- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

-->The robotic arm was fabricated using lightweight cardboard as the primary structural material. The process began with marking and cutting the required shapes for the base, arm segments, and gripper using a cutter and scale to ensure straight and accurate edges. Multiple layers of cardboard were used in critical sections to increase strength and durability.

No 3D printing was used in this project, as the focus was on low-cost and rapid prototyping using easily available materials.

During assembly, the arm segments were connected using servo motors placed at the joints. The servos were fixed in position using glue and tight fitting slots in the cardboard to ensure stability. The base structure was reinforced to support the movement and weight of the arm.

For fastening, hot glue and adhesive were used to secure components, while ensuring that moving joints were not restricted. Servo horns were properly aligned with the cardboard parts to allow smooth rotational movement.

The wiring was done using jumper wires connected through the IO shield board to the RP2040. Care was taken to organize the wires neatly to avoid tangling and accidental disconnections. An external 5V power supply was used to power the servo motors.

In terms of finishing, edges were cleaned, excess glue was removed, and the structure was adjusted for better balance and appearance. The arm was tested multiple times to ensure smooth motion.

Several revisions were made during the build process, including improving joint alignment, reinforcing weak sections, and adjusting servo positions for better control and stability.

## 16.2 Build Photos

Add photos throughout the project.

Suggested images:

- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

-->![image alt](https://github.com/aaryanmohanani/SKILLLAB__PROR_2026_RoboForge/blob/main/images/finalproject.jpeg?raw=true)





# 17. Final Outcome

## 17.1 Final Description

Describe the final version of your project.

-->The final project is an IR remote-controlled robotic arm built using the RP2040 microcontroller. The structure is made using lightweight cardboard, and movement is achieved using SG90 and MG996R servo motors. The arm can perform basic pick-and-place and painting-like motions by responding to commands from an IR remote.

The system demonstrates how simple hardware components can be used to simulate industrial robotic arm applications in a cost-effective and interactive way.


## 17.2 What Works Well

-->

1)Servo motors respond accurately to IR remote inputs.

2)Robotic arm structure is lightweight and functional.

3)Easy and intuitive control using remote.

4)Fast assembly and working prototype within limited time.


## 17.3 What Still Needs Improvement

-->

1)Stability of the cardboard structure under load.

2)Precision and smoothness of movements.

3)Wire management and overall finishing.

4)More degrees of freedom for advanced motion.

## 17.4 What Changed From the Original Plan

How did the project change from the initial idea?

-->Initially, the project idea involved more complex systems using ESP32, motors, and wireless control. However, due to time constraints and hardware restrictions, the project was simplified to a robotic arm using RP2040 and IR remote control. This change allowed faster implementation while still demonstrating core concepts of robotics and control systems.


---

# 18. Reflection

## 18.1 Team Reflection

What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

-->The team worked efficiently by dividing tasks such as hardware setup, coding, and documentation. Communication was clear, and everyone contributed to completing the project on time.

Some delays occurred during initial setup and servo calibration, but they were resolved quickly through teamwork. Overall, time and responsibilities were managed effectively.

## 18.2 Technical Reflection

What did you learn about:

- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

-->We learned about interfacing servo motors with a microcontroller, handling IR signals, and managing power requirements. We also gained experience in debugging hardware issues and ensuring proper connections.

Additionally, we understood the importance of calibration and synchronization between hardware and code.

## 18.3 Design Reflection

What did you learn about:

- designing ,
- delight,
- clarity,
- physical interaction,
- understanding,
- iteration?

-->We learned how to design a functional structure using simple materials like cardboard. The importance of balance, weight distribution, and joint placement became clear during the build process.

We also learned that iterative improvements are necessary to achieve better performance and usability.


## 18.4 If You Had One More hour

What would you improve next?

-->If given one more hour, we would improve the stability and finishing of the robotic arm, optimize servo movements for smoother operation, and enhance the overall appearance of the project.

` `

---

# 19. Final Submission Checklist

Before submission, confirm that:

- [x] Team details are complete
- [x] Project description is complete
- [x] Inspiration sources are included
- [x] Sketches are added
- [x] BOM is complete
- [x] Purchase list is complete
- [x] Budget summary is complete
- [x] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [x] Code flowchart is added
- [x] Task breakdown is complete
- [x] Weekly logs are updated
- [x] Risk register is complete
- [x] Testing log is updated
- [x] Playtesting notes are included
- [x] Build photos are included
- [x] Final reflection is written
---


---


