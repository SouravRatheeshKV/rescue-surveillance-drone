\# Rescue and Surveillance Drone for Women Safety



A rescue and surveillance system combining a smartwatch-based emergency module with a drone to support emergency response and location-based surveillance.



\## Project Overview



The project combines a wearable smartwatch module and an unmanned aerial vehicle (UAV).



The smartwatch module is designed to acquire the user's location and communicate emergency information through GSM.



The drone component can be directed toward the provided location and can collect images or video footage for use by the appropriate response personnel.



\## System Concept



The system consists of two major modules.



\### Module 1 — Location and Surveillance



The smartwatch obtains the user's location using GPS.



The location is communicated through the GSM module to the control system. The control system can then use the location to direct the drone.



The drone is equipped with a camera for collecting visual information from the location.



\### Module 2 — Severe Emergency



The second emergency mode is intended for severe emergencies.



The emergency location is communicated so that the drone and appropriate assistance can be directed toward the location.



\## Smartwatch Hardware



The smartwatch module uses:



\* Arduino Nano

\* GSM SIM800L

\* GPS NEO-6M

\* OLED display

\* Push buttons

\* 3.7V rechargeable battery

\* Capacitor

\* Dotted PCB



\## Drone Hardware



The drone uses:



\* ArduPilot APM 2.8

\* F450 frame

\* A2212 1000KV motors

\* 30A ESCs

\* FlySky FS-CT6B transmitter and receiver

\* Power module

\* Propellers

\* GPS NEO-7M

\* 3DR telemetry

\* LiPo battery

\* Camera

\* VTX and receiver



\## Software



The project documentation uses:



\* Arduino

\* Mission Planner

\* T6 Config

\* Go FPV



\## Repository Structure



```text

rescue-surveillance-drone/

│

├── README.md

├── .gitignore

│

├── docs/

│   ├── project-report.pdf

│   └── project-presentation.pptx

│

├── smartwatch/

│   ├── rescue\_watch.ino

│   └── README.md

│

├── drone/

│   └── README.md

│

├── hardware/

│   ├── block-diagram/

│   ├── circuit-diagram/

│   └── photos/

│

├── software/

│   ├── mission-planner/

│   ├── t6-config/

│   └── go-fpv/

│

└── media/

&#x20;   ├── smartwatch/

&#x20;   ├── drone/

&#x20;   └── testing/

```



\## Project Objectives



\* Provide an emergency location mechanism using GPS and GSM.

\* Provide a wearable emergency interface.

\* Communicate emergency location information to a control system.

\* Use a drone for location-based surveillance.

\* Collect visual information using an onboard camera.

\* Support emergency response.



\## Documentation



The complete project report and presentation are available in the `docs` directory.



\## Team



\* PRASUDHI A

\* SONAL SAJITH M

\* SOURAV RATHEESH K V

\* VYSHNA P



\## Guide



Mrs. Jyothi K

Assistant Professor

Department of Electronics and Communication Engineering



\## Institution



College of Engineering Trikaripur

APJ Abdul Kalam Technological University



\## Safety and Privacy



This project is an academic prototype.



Emergency communication and drone operation should be performed only in accordance with applicable laws, safety requirements, privacy requirements, and institutional procedures.



Personal contact information should not be committed to a public repository.



\## License



This project is provided for academic and educational purposes.



