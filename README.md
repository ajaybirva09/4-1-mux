 # 4:1 Multiplexer Design 
 This project simulates the designed 4:1 MUX circuit to determine its performance characterisitics pre-layout design.

Note: Circuit requires further optimization to improve performance. Design yet to be modifi

## A Glance at the 4:1 MUX Reference IP

The 4:1 Multiplexer (MUX) Reference IP provides a high-performance digital multiplexer solution using transmission gates for efficient data selection and low power operation. Ideal for high-speed applications, this MUX is designed to offer low propagation delay and minimized power consumption, leveraging transmission gates to achieve reliable signal integrity across various frequencies.
## Block Diagram of the Bandgap Reference IP
<img width="254" alt="Screenshot 2024-10-25 at 1 30 21 PM" src="https://github.com/user-attachments/assets/66351375-3f55-4e8e-adae-59d55cc690df">

## Circuit Diagram of the Bandgap Reference IP

## 4:1 Multiplexer Performance Parameters

This section provides the performance parameters for the 4:1 MUX designed using transmission gates.

| Parameter        | Description                          | Min    | Type   | Max    | Unit    | Condition                                    |
|------------------|--------------------------------------|--------|--------|--------|---------|----------------------------------------------|
| **Technology**   | CMOS Process Technology              |        | 0.18 µm|        |         |                                              |
| **VDD**          | Supply Voltage                       | 1.8    |        | 3.3    | V       | T = 25°C                                    |
| **VIL**          | Low-Level Input Voltage              | 0      |        | 0.4    | V       |                                              |
| **VIH**          | High-Level Input Voltage             | 1.4    |        | VDD    | V       |                                              |
| **VOL**          | Low-Level Output Voltage             | 0      |        | 0.2    | V       |                                              |
| **VOH**          | High-Level Output Voltage            | VDD-0.2|        | VDD    | V       |                                              |
| **RL**           | Load Resistance at Output            | 10     | kΩ     |        |         | VDD = 3.3V, T = 27°C                         |
| **CL**           | Load Capacitance at Output           |        |        | 20     | pF      | VDD = 3.3V, T = 27°C                         |
| **tpd**          | Propagation Delay                    | 2      | ns     | 6      | ns      | Load = 15pF, VDD = 3.3V                      |
| **ICC**          | Supply Current                       |        | 0.2    | mA     |         |                                              |
| **IDD**          | Static Supply Current                |        | 1.5    | μA     |         | EN = 1, VDD = 3.3V                           |
| **IOZ**          | Output Leakage Current (Disabled)    |        | 1      | μA     |         | EN = 0, VDD = 3.3V                           |
| **P_static**     | Static Power Consumption             |        |        | 0.5    | μW      | VDD = 3.3V, T = 27°C                         |
| **P_dynamic**    | Dynamic Power Consumption            |        |        | 1      | μW      | f = 1MHz, Load = 15pF, VDD = 3.3V            |
| **Switching Speed** | Maximum Input Switching Frequency   |        |        | 500    | MHz     |                                              |
| **Tc**           | Temperature Coefficient of Output    |        | 20     | ppm/°C | T = -40°C to 125°C, VDD = 3.3V               |
| **EN**           | Enable Signal Voltage Level          |        |        | VDD    | V       | EN = 1: Enabled, EN = 0: Disabled            |


