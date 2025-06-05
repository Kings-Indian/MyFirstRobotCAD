---
title: "My First Robot"
author: "Tanishq Goyal"
description: "This is a small car"
created_at: "2024-05-10"
---

# May 10th: Base Structure and Hardware Selection

I created a fundamental base structure and experimented with dimensions to find optimal tolerances. I also found some hardware.

![image](https://github.com/user-attachments/assets/3138b7b6-a10b-4aa8-bcd2-7cd15fe408ad)


**Total time spent: 0h 59m**

---

# May 11th: Component Creation

Created the following components:
- Gears
- Wheels
- Motor Enclosure
- Motor Negative Model (a representation of the motor)

Main challenges included:
- Motor interference with other parts
- Maintaining appropriate tolerances
- Accurately modeling the negative motor model

![image](https://github.com/user-attachments/assets/7a034028-3aff-4d87-8321-53e1e21fcd00)


**Total time spent: 1h 30m**

---

# May 11th: Printer Setup and Troubleshooting

I installed Klipper and Mainsail on my Raspberry Pi and created a printer.cfg file. I've been working on this for days with almost no progress, but my progress stopped after 1.5 hrs. But still haven't fixed it (even tried it a month ago), so I'm just using Marlin for now—I give up until I feel ready to retry.

![image](https://github.com/user-attachments/assets/8c6f400d-bb41-4694-a640-6ba24a131683)

**Total time spent: 1h 30m**




---

# May 12th: Alternate Drivetrain Design Exploration

I started creating an alternate open drivetrain design. 

![image](https://github.com/user-attachments/assets/05647965-b54c-4dea-a0ae-3a1752d6ff83)


**Total time spent: 1h 30m**

---

# May 13th: Open Drivetrain Completion

I finished the open drivetrain (excluding fasteners and board-related stuff).

![image](https://github.com/user-attachments/assets/10021609-7fba-4af9-892e-e2e1fcc9ec2e)


**Total time spent: 1h 30m**

---

# May 13th: Circuit Planning and Fastener Creation

I planned out my circuits for my ESP32 and created fastener screws. I also chose my hardware for drivetrain fastening and separated the drivetrain into Tank modules and the normal drivetrain.

![image](https://github.com/user-attachments/assets/b0f154cb-dba3-42e1-aa2b-cb57e20e9d25)


**Total time spent: 1h 30m**

---

# May 13th: Robot Completion (Except Battery)

I completed the entirety of the robot (besides some light cleanups), excluding the battery, which will be included after testing.

![image](https://github.com/user-attachments/assets/cce68c02-b084-4780-84d8-9c1ea2d729ed)


**Total time spent: 1h 30m**

---

# May 13th: Surface Smoothing and Animation

- Smoothed all surfaces and verified they are manifold.
- Ensured all parts are non-intersecting.
- Added additional supports for the motors.
- Animated the entire assembly with proper relational movement.

![image](https://github.com/user-attachments/assets/783dc45b-79aa-4038-bcbe-b24263c6a13e)


**Total time spent: 1h 19m**

---

# May 16th: Battery Modeling and Mount Implementation

I modeled my battery and began implementing its mount. I went through multiple designs before landing on the final one.

![image](https://github.com/user-attachments/assets/3781a147-3cc8-4568-9bab-875c134ea571)


**Total time spent: 1h 30m**

---

# May 17th: Battery Mount and Tank Drive Modules Completed

I finished the battery mount and recreated the tank drive modules. This also required me to create an extra set of "negative" screw hole sets. I recreated the Tank drive geometry in order to allow for the center of rotations to be further apart while still allowing for multiple modules. This allows a higher radius, providing more space under the robot. As a result, less space needs to be extruded from the drivetrain, making for a more stable base while still maintaining enough thickness for stability.

![image](https://github.com/user-attachments/assets/c76d4ede-9811-43aa-b211-26a8e440ab81)
---

# June 4th: Updated Everything to Github

I added everything to Github, previously it was all elseware. 

**Total time spent: 4h (On-Call)**

**Total time spent: 1h 30m**

**Time Spent in Total: 18.30 hr**
