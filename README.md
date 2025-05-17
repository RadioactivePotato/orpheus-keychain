# orpheus-keychain
This is a PCB of a keychain shaped like Orpheus.

The LEDs and the motor will turn on if the button is pressed

Speed of the motor is controlled by a LDR

# Schematics
![](https://raw.githubusercontent.com/RadioactivePotato/orpheus-keychain/refs/heads/main/assets/schem.png)

# PCB
![](https://raw.githubusercontent.com/RadioactivePotato/orpheus-keychain/refs/heads/main/assets/pcb.png)

# 3D View

![](https://raw.githubusercontent.com/RadioactivePotato/orpheus-keychain/refs/heads/main/assets/modelfront.png)
![](https://raw.githubusercontent.com/RadioactivePotato/orpheus-keychain/refs/heads/main/assets/modelback.png)

# BOM

| Id | Designator | Footprint                                         | Quantity | Designation   |
|----|------------|---------------------------------------------------|----------|----------------|
| 1  | D1, D2     | LED_D5.0mm                                        | 2        | LED            |
| 2  | R1, R2     | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal   | 2        | R              |
| 3  | SW1        | SW_PUSH_6mm                                       | 1        | SW_Push        |
| 4  | M1         | PinHeader_1x02_P2.54mm_Vertical                   | 1        | Motor_DC       |
| 5  | R3         | R_LDR_5.1x4.3mm_P3.4mm_Vertical                   | 1        | LDR07          |
| 6  | BT1        | BatteryHolder_Keystone_3034_1x20mm                | 1        | Battery_Cell   |
