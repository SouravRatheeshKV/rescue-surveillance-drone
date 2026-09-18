\# Smartwatch Emergency Module



The smartwatch module is designed to assist in emergency situations by acquiring the user's location and transmitting the location information through GSM.



\## Main Components



\* Arduino Nano

\* GSM SIM800L

\* GPS NEO-6M

\* OLED display

\* Push buttons

\* 3.7V rechargeable battery

\* Capacitor

\* Dotted PCB



\## Functions



\### Minor Emergency



The minor-emergency button is used to send the user's GPS location to the designated control system.



\### Major Emergency



The major-emergency button is intended for severe emergencies and is designed to communicate the user's location so that assistance can be dispatched.



\## Software



The smartwatch module uses Arduino code for:



\* GPS location acquisition

\* GSM communication

\* OLED display

\* Emergency button input



\## Security Note



Personal phone numbers and other private contact information should not be stored directly in publicly accessible source code. Configure destination numbers locally when testing the system.



