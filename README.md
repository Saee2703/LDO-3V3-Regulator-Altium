# LDO-3V3-Regulator-Altium

# Overview 
A compact SMD 3.3V low dropout voltage regulator designed and verified in Altium Designer — converting 5V input to a stable 3.3V regulated output.
This project marks my first complete PCB design in Altium Designer — demonstrating SMD component placement, professional EDA workflow and Gerber file generation in an industry standard tool.

# Circuit Specifications
Component                  Value                            Purpose
* U1                       MIC5317-3.3YM5-TR                3.3V LDO voltage regulator
* J1                       SM02B-GHS-TB(LF)(SN)             5V power input connector
* J2                       SM02B-GHS-TB(LF)(SN)             3.3V regulated output connector
* C1                       1µF                              Input decoupling capacitor
* C2                       1µF                              Output decoupling capacitor

# Electrical Performance
Parameter                   Value 
Input voltage               5V DC 
Output voltage              3.3V regulated 
IC package                  SOT-23-5 SMD
Input capacitor             1µF
Output capacitor            1µF

# Design Details
* SMD component placement and routing — first surface mount PCB design
* MIC5317 EN pin tied to VIN for automatic enable on power up
* NC pin left unconnected as per datasheet recommendation
* Input and output decoupling capacitors placed close to IC pins for stability
* Clean single layer routing with proper net assignment
* Board outline defined with mechanical layer


# Technical Deliverables
* Complete schematic captured in Altium Designer
* PCB layout with SMD component placement and routing
* Design Rule Check (DRC) verified
* Gerber files generated and verified in CAMtastic
* 3D PCB visualisation confirming correct component placement

<img width="1439" height="769" alt="Image" src="https://github.com/user-attachments/assets/9dc08e55-44c4-4f9c-8b3d-0b906a37f44b" /> 
<img width="1449" height="839" alt="Image" src="https://github.com/user-attachments/assets/05d6933f-bdef-4213-848c-ef26d8acff69" />
<img width="1464" height="731" alt="Image" src="https://github.com/user-attachments/assets/bd76a251-3e81-4556-87f7-aeac3b6209c8" />
<img width="1467" height="841" alt="Image" src="https://github.com/user-attachments/assets/cac7338a-e8ba-4686-9f34-402ed32410b3" />


