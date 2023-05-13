# Digital_Switch
A simple electronic latching switch

Up to 12V 6A, LED indicator on board or external (you can choose with a solder jumper). On press : on. On press again : off. A little bit of delay between two contact is necessary (0.5s maybe)

Designed with KiCad.

Tool: Eeschema 6.0.2+dfsg-1. Component Count:17.

|Ref|Qnty|Value|Cmp name|Footprint|Description|Vendor|
|---|---|------|-------|----------|-----------|-------|
|C1| 1|2.2uF25V|C_Polarized|Capacitor_SMD:CP_Elec_4x5.4|Polarized capacitor|
|C2, C3 |2|0.1uf|C|Capacitor_SMD:C_1206_3216Metric_Pad1.33x1.80mm_HandSolder|Unpolarized capacitor|
|D1 |1|1N4007|1N4007|Diode_SMD:D_SMA|1000V 1A General Purpose Rectifier Diode| DO-41|
|D2| 1|D_Schottky|D_Schottky|Diode_THT:D_DO-27_P12.70mm_Horizontal|Schottky diode|
|D3| 1|LED|LED|LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder|Light emitting diode|
|J1| 1|Conn_01x08_Male|Conn_01x08_Male|Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical|Generic connector| single row| 01x08| script generated (kicad-library-utils/schlib/autogen/connector/)|
|JP1| 11|SolderJumper_2_Open|SolderJumper_2_Open|Jumper:SolderJumper-2_P1.3mm_Open_RoundedPad1.0x1.5mm|Solder Jumper| 2-pole| open|
|Q1| 1|BC557|BC557|Package_TO_SOT_THT:TO-92_Inline|0.1A Ic| 45V Vce| PNP Small Signal Transistor| TO-92|
|Q2| 1|BUZ11|BUZ11|Package_TO_SOT_THT:TO-220F-3_Horizontal_TabDown|30A Id| 50V Vds| N-Channel Power MOSFET| TO-220|
|R1| 1|220K|R|Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder|Resistor|
|R2| 1|330K|R|Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder|Resistor|
|R3, R4, R5, |3|10K|R|Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder|Resistor|
|R6| 1|330|R|Resistor_SMD:R_1206_3216Metric_Pad1.30x1.75mm_HandSolder|Resistor|
|U1| 1|LM78M05_TO252|LM78M05_TO252|Package_TO_SOT_SMD:TO-252-2|Positive 500mA 35V Linear Regulator| Fixed Output 5V| TO-252 (D-PAK)|



![Alt text](/Media/pic1.jpeg?raw=true "")
![Alt text](/Media/pic2.jpeg?raw=true "")
![Alt text](/Media/pic3.jpeg?raw=true "")
![Alt text](/Media/pic4.jpeg?raw=true "")

https://github.com/Polohpi/Digital_Switch/assets/26924710/ee93b867-ae03-4367-9020-4544baada03b

