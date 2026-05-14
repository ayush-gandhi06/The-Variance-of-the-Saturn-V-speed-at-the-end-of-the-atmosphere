# 🚀 Saturn V Rocket Launch Simulation

A physics-based rocket launch simulation inspired by the Apollo 11 Saturn V rocket.
This project uses Python and Euler’s Method to simulate the ascent of a multi-stage rocket through Earth’s atmosphere while accounting for:

* Air drag
* Gravity
* Fuel consumption
* Atmospheric density
* Stage separation
* Coasting motion

The main objective of this project was to analyze how changing the total fuel mass affects the rocket’s speed at 100 km above sea level.

---

# 📌 Features

✅ 3-stage rocket simulation
✅ Atmospheric density calculations
✅ Air drag modeling
✅ Euler numerical integration
✅ Fuel burn simulation
✅ Stage separation system
✅ Rocket trajectory visualization
✅ Speed vs Fuel analysis graphs
✅ Coasting phase after fuel depletion

---

# 🧠 Physics Concepts Used

This project combines programming with real physics concepts such as:

* Newton’s Second Law
* Drag Force
* Gravitational Force
* Atmospheric Pressure Models
* Numerical Methods
* Rocket Propulsion
* Multi-stage Rockets

---

# 🛠 Technologies Used

* Python
* NumPy
* Matplotlib

---

# 📈 Simulation Overview

The rocket launches vertically through different layers of the atmosphere.

Each stage has:

* A unique thrust
* Different fuel mass
* Different burn rate
* Different total mass

As fuel burns:

* The rocket mass decreases
* The net force changes
* The acceleration changes dynamically

After all fuel is depleted, the rocket enters a coasting phase where only gravity and air drag act on it.

---

# 📊 Results

The simulation produced several graphs including:

* Rocket trajectory
* Density vs altitude
* Speed evolution
* Speed at 100 km vs fuel amount

One major finding was that increasing fuel mass only helps up to a certain point.
Beyond the optimal fuel amount, the extra weight begins reducing the rocket’s performance.

The simulation found an optimal fuel amount of approximately:

```text
116,000 kg
```

for maximizing speed at 100 km altitude.

---

# ⚠️ Limitations

This model simplifies several real-world rocket behaviors:

* Constant thrust
* Constant fuel burn rate
* Constant gravitational acceleration
* Simplified drag coefficient
* Simplified rocket geometry

These assumptions were made to keep the simulation computationally manageable while still producing realistic behavior.

---

# 🔮 Future Improvements

Potential future upgrades include:

* Variable thrust models
* Real Saturn V aerodynamic coefficients
* Variable gravity with altitude
* Orbital mechanics
* Wind effects
* Runge-Kutta numerical methods
* Real-time rocket animation

---

# ▶️ How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/rocket-simulation.git
cd rocket-simulation
```

## 2. Install Dependencies

```bash
pip install numpy matplotlib
```

## 3. Run the Program

```bash
python rocket_simulation.py
```

---

# 📁 Suggested Project Structure

```bash
rocket-simulation/
│
├── rocket_simulation.py
├── README.md
├── graphs/
│   ├── trajectory.png
│   ├── density_vs_altitude.png
│   ├── speed_vs_fuel.png
│
└── report/
    └── final_report.pdf
```

---

# 📚 References

* NASA Saturn V documentation
* International Standard Atmosphere
* Barometric Formula
* Euler Numerical Integration
* Rocket propulsion physics resources

---

# 👨‍💻 Author

Ayush Gandhi & Mathieu Latendresse

Programming + physics simulation project combining aerospace concepts with numerical methods.
