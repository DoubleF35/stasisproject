# stasisproject
My repository for my stasis projects
# Seeker-II Rocket Project

This is my high-power model rocket project for **Stasis**. The goal is to design, simulate, and build a stable rocket capable of reaching an apogee of 280m using a Class E motor.

## 🛠 Design & Simulations

### 1. Flight Simulations (OpenRocket)
I used OpenRocket to define the basic geometry and verify the stability margin.
- **Motor:** Class E
- **Target Altitude:** ~280m
- **Stability:** Validated with center of pressure (CP) and center of gravity (CG) analysis.

![OpenRocket Design](openrocket_sim.png)

### 2. CAD Modeling (Fusion 360)
The rocket was fully modeled in 3D to create custom components.
- **Engine Mount:** Features a custom honeycomb structure for strength and weight reduction.
- **Fins:** Dual-set fin configuration for aerodynamic control and aesthetics.

![Fusion 360 CAD Model](cad_model.png)

### 3. CFD Analysis (SimScale)
I performed a Computational Fluid Dynamics analysis to validate the external aerodynamics at 85 m/s.
- **Convergence:** Residuals reached 1e-4, ensuring stable results.
- **Pressure Mapping:** Verified high-pressure zones on leading edges and flow separation.

![SimScale Pressure Map](cfd_sim.png)
![CFD Residuals](residuals.png)

## 🚀 Build Phase
I already possess all the physical materials (tubes, motor mount, fins, and motor). I am ready to start the assembly as soon as the design is approved.
