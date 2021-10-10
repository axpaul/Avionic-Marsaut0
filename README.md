<h1>Avionic Marsaut 0</h1>
        
<h2>Marsaut_0 experimental rocket avionic (On-board electronics) created by Mines Space, Version 2021 launched at C'space</h2>

*Copyright (c) MINES SPACE and contributors. All rights reserved.*

<p>The electronic architecture of our rocket is divided into two parts, the flight controller (Sequencer) and the payload.
You can find the CAD of all the cards on this link : https://grabcad.com/library/avionics-system-for-marsaut-0-rocket-mines-space-1 </p>
        
        - Branch APU : The APU (Acquisition Process Unit) board is dedicated to the acquisition, 
        storage and transmission of data in the rocket.

        - Branch SEQ : The SEQ board (the flight controller) is dedicated to the control of the different 
        actuators according to the rocket's flight status.

        - Branch ALIM : The ALIM board (the power supply board) is the board in charge of the electrical 
        distribution and the control of the battery status.

        - Branch MOTOR : The MOTOR board is equipped with motor drivers for parachute deployment control.

        - Branch IHM : The HMI card is the card dedicated to the control and restitution 
        of information to the user.

        - Branch INT_LTS : The INT_LTS card is an interface card with the Lora TTGO-T BEAM card.

        - Branch LINK : The LINK card allows to link all the actuators and sensors 
        installed in the rocket to the electronics .
