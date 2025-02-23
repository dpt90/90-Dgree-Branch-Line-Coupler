90-Degree Branch Line Coupler at 2.4 GHz

1. Introduction

A 90-degree branch line coupler is designed to operate at 2.4 GHz. The coupler consists of four wave ports, enabling signal splitting and phase shifting between different ports.

2. Design Specifications

Substrate (FR4 Epoxy)

Position: (-15, -20, 0) mm

Size: (30 x 40 x 1.6) mm

Ground Plane

Position: (-15, -20, 0) mm

Size: (30 x 40 x 1.6) mm

Patch (Branch Line Structure)

Position: (-12.35, -9.8, 1.6) mm

Size: (24.7 x 19.7) mm

Feed Line Ports

Port 1: (-10.05, -20, 1.6) mm, Size: (3 x -1.6) mm

Port 2: (10.05, -20, 1.6) mm, Size: (3 x -1.6) mm

Port 3: (-10.05, 20, 1.6) mm, Size: (3 x -1.6) mm

Port 4: (10.05, 20, 1.6) mm, Size: (3 x -1.6) mm

Radiation Boundary

Position: (-25, -25, -25) mm

Size: (50 x 50 x 15) mm

3. Simulation Setup

Frequency: 2.4 GHz

Solver: HFSS (Ansys 2024 R2)

Solution Setup:

Maximum Passes: 6

Maximum Delta S: 0.02

Sweep Setup:

Type: Interpolating

Frequency Range: 1 - 5 GHz

Step Size: 0.01 GHz

4. Results and Analysis

S-Parameters (Scattering Matrix) Analysis

The S11 (Return Loss) shows good impedance matching at 2.4 GHz.

The S21 and S31 (Coupling Coefficients) indicate equal power split between output ports.

The S41 (Isolation) is significantly low, demonstrating proper isolation between ports.

The Phase Shift between coupled ports confirms a 90-degree phase difference.

Observations

The branch line coupler achieves good power splitting with minimal losses.

The isolation is maintained between adjacent ports.

The design meets the expected performance criteria for a 90-degree branch line coupler at 2.4 GHz.

5. Conclusion

This 90-degree branch line coupler effectively operates at 2.4 GHz, achieving efficient power division with proper impedance matching and isolation. It is well-suited for wireless communication applications including Wi-Fi, Bluetooth, and RF front-end modules.

Keywords: Branch Line Coupler, HFSS, 2.4 GHz, S-parameters, RF Circuit, Microwave Engineering


