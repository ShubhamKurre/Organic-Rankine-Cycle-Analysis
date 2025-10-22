# Thermodynamic Analysis of Organic Rankine Cycle (ORC)

This project analyzes an Organic Rankine Cycle (ORC) for recovering low-grade waste heat (140–180°C) from textile exhaust. 
The model was developed in MATLAB and DWSIM using CoolProp for thermophysical properties.

## 🔧 Tools & Software
- MATLAB (Cycle Modeling, Optimization)
- DWSIM (Process Simulation)
- CoolProp (Thermophysical Property Library)

## ⚙️ Methodology
1. Defined heat source (250 kW, 150°C exhaust gas)
2. Evaluated 6 working fluids (R245fa, R134a, n-pentane, etc.)
3. Simulated at 8–14 bar evaporator, 25–40°C condenser
4. Calculated thermal & exergy efficiencies

## 📊 Results
| Parameter | Value |
|------------|--------|
| Net Power Output | 15–22 kW |
| Thermal Efficiency | 12% |
| Exergy Efficiency | 48% |

## 📈 Graphs
![Efficiency vs Pressure](Results/efficiency_plot.png)

## 📚 Learning Outcomes
- Gained experience with ORC cycle thermodynamics
- Learned DWSIM–MATLAB integration via CoolProp
- Understood exergy analysis and optimization
