# 🌞 Summer 1 ECE Bridge Plan (12 Weeks)

**Goal:** Build a strong foundation in Electricity & Magnetism, Embedded Systems Programming, and Applied Math to prepare for a Master’s in Electrical and Computer Engineering.

---

## 📘 Courses

### 🔌 Electricity & Magnetism Specialization (Rice University - Jason Hafner)
- Course 1: Electrostatics
- Course 2: Magnetic Fields and DC Circuits
- Course 3: Induction and AC Circuits
- Course 4: Maxwell’s Equations

### 💻 Embedded Systems (University of Colorado Boulder - Alex Fosdick)
- Introduction to Embedded Systems Software and Development Environments

---

## 🧮 Core Math Topics
- Vectors, Dot and Cross Product
- Gradient, Divergence, Curl
- Line and Surface Integrals
- Basic Differential Equations
- Complex Numbers and Phasors
- Basic Linear Algebra and Systems of Equations

---

## 📅 Weekly Breakdown

### 🔹 Weeks 1–4: Electrostatics, Voltage, Circuits

| Week | E&M Focus                 | Math Focus                | Embedded/STM32          | Stretch Goal                          |
|------|---------------------------|---------------------------|--------------------------|----------------------------------------|
| 1    | Charge & Coulomb’s Law    | Vector algebra, unit vectors | Toolchain setup, Git    | Derive electric field from Coulomb’s law |
| 2    | Electric Potential (V)    | Gradient ∇V                | STM32 ADC, voltage divider | Visualize E-field as gradient of V |
| 3    | Current, Power            | P = IV, algebra             | Resistor + ADC sensor reading | Build circuit simulator in Python |
| 4    | Ohm's Law, Kirchhoff Laws | Linear systems             | STM32 loop circuits       | Simulate and breadboard a 2-loop circuit |

---

### 🔹 Weeks 5–8: Magnetism, Induction

| Week | E&M Focus                | Math Focus             | Embedded/STM32        | Stretch Goal                             |
|------|--------------------------|------------------------|------------------------|-------------------------------------------|
| 5    | Magnetic Field (Biot–Savart) | Cross product         | GPIO + LED logic        | Visualize B-field of wire in simulation   |
| 6    | Lorentz Force            | Force laws, cross prod | Hall sensor readings    | Calculate charge velocity from B-field    |
| 7    | Faraday’s Law            | Derivatives, flux      | ADC logging coil voltages | Build a rotating magnet demo        |
| 8    | Maxwell’s Equations      | Div, Curl, Summary     | Integration testing     | Explain the physical meaning of ∇·E, ∇×B |

---

### 🔹 Weeks 9–12: AC Circuits, Filters, Capstone

| Week | E&M Focus              | Math Focus              | Embedded/STM32              | Stretch Goal                           |
|------|------------------------|-------------------------|------------------------------|----------------------------------------|
| 9    | AC, Phasors            | Euler's identity         | Simulate RC/RL circuits       | Animate RC charging using Matplotlib  |
| 10   | Impedance, Resonance   | Complex numbers, phasors | Build a breadboard filter     | Measure Q-factor of LC circuit         |
| 11   | Full review            | Basic ODEs (RLC circuit) | Final embedded integration    | Create GitHub repo with report         |
| 12   | Capstone + RPL Summary | Full course review       | Record project demo + certs   | Make a video walkthrough for RPL docs  |

---

## 🧪 STM32 Lab Projects

- Voltage Divider Measurement
- Hall Effect Current Sensor
- Induction Coil Logger
- AC Filter with STM32 + ADC
- Real-time Logging with UART

---

## 📂 Folder Structure (Recommended GitHub Repo)

```bash
ece-bridge-summer1/
├── PLAN.md
├── README.md
├── Rice_EandM_Notes/
│   ├── Week_01/
│   ├── ...
├── Embedded_Software_CU/
│   ├── Week_01/
│   ├── ...
├── STM32_Projects/
│   ├── Voltage_Divider/
│   ├── Hall_Sensor/
│   ├── AC_Filter_Logger/
├── Math_Practice/
│   ├── Fields_and_Vectors/
├── Simulations/
│   ├── Field_Line_Plot/
│   ├── Circuit_Solver/
├── Reflections/
│   ├── Weekly_Logs/
├── RPL_Docs/
│   ├── Coursera_Certificates/

