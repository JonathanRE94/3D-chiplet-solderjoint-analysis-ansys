# Thermo-Mechanical Analysis of Solder Joints in 3D Chiplet Packaging

Investigates how **pitch gap and solder joint height** influence thermal accumulation, stress, and reliability in **3D chiplet packages**.

## Research Question
How does varying the pitch gap and solder joint height affect **thermal accumulation, solder joint reliability, and electromigration**, and what role can **Thermo-Mechanical Analysis** play in optimizing advanced packaging?

## Methodology
- **Modeling:** Quarter-chiplet geometry designed in SolidWorks, imported into ANSYS Workbench.  
- **Thermal Analysis:** Steady-state simulations to study temperature distribution, hotspots, and dissipation.  
- **Mechanical Analysis:** Static structural simulations to assess stress/strain behavior.  
- **Electrical Analysis:** Electromigration reliability comparison between Sn–Ag–Cu (SAC) solder joints and Cu Core Solder Balls (CCSBs).  
- **Parametric Variations:** Pitch gap (0.9 mm, 1.77 mm, 2.5 mm) and solder joint height (0.18 mm, 0.37 mm, 0.5 mm).  

## Key Results
- **Thermal:** Reduced pitch increases hotspot intensity; taller joints improve thermal dissipation.  
- **Mechanical:** Smaller pitch/height → higher stress concentration, greater fatigue risk.  
- **Electrical:** CCSBs showed ~1.73× longer **time-to-failure** than SAC joints, with lower current density (2.66×10⁶ A/cm² vs. 2.93×10⁶ A/cm²):contentReference[oaicite:3]{index=3}.  

| Property                 | SAC Joint       | CCSB Joint      |
|---------------------------|----------------|----------------|
| Max Current Density (A/cm²) | 2.93 × 10⁶     | 2.66 × 10⁶     |
| Time-to-Failure (hrs)     | 18.0           | 31.2           |
| Void Formation Rate       | High           | Low            |
| Post-Reflow Integrity     | Reduced        | Maintained     |
 

## Importance
This work addresses **design and reliability challenges** in miniaturized semiconductor devices by integrating **thermal, mechanical, and electrical performance analyses**. Insights support **3D chiplet packaging reliability improvements** for high-performance computing and advanced electronics.

## Acknowledgement
Project completed at **Arizona State University** (EEE 598, Prof. Christopher Bailey).  
Team: Sherry Daniel Sajan, Jonathan Reggie Ebenezer, Vamshi Vemuri, Himanshu Parashar, Jay Nanavati.  
