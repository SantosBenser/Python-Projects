# Ultraviolet Catastrophe: Resolution Using Planck's Law

## 📌 Title

Ultraviolet Catastrophe: Resolution Using Planck's Law

A Python-based scientific visualization project that demonstrates the failure of the classical Rayleigh-Jeans Law at high frequencies (the Ultraviolet Catastrophe) and shows how Planck's Quantum Theory successfully resolves the problem. The project compares the spectral energy density predicted by both models and visualizes their behavior across a wide frequency range.

---

## 🛠 Technologies

### Programming Language
- Python

### Libraries
- NumPy
- Matplotlib

### Concepts
- Blackbody Radiation
- Ultraviolet Catastrophe
- Planck's Quantum Theory
- Rayleigh-Jeans Law
- Quantum Physics
- Spectral Energy Density
- Data Visualization
- Scientific Computing

---

## ✨ Features

- Implements Rayleigh-Jeans Law
- Implements Planck's Radiation Law
- Demonstrates the Ultraviolet Catastrophe
- Uses logarithmic scaling for clear comparison
- Visualizes spectral energy density over a broad frequency range
- Compares classical and quantum predictions
- Educational tool for understanding quantum mechanics
- High-quality scientific graph generation

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Function |
|-----------|-----------|
| Ctrl + N | Create New Python File |
| Ctrl + O | Open Existing File |
| Ctrl + S | Save File |
| F5 | Run Script (VS Code) |
| Ctrl + F5 | Run Without Debugging |
| Ctrl + C | Stop Execution |
| Ctrl + / | Comment/Uncomment Code |
| Ctrl + Z | Undo |
| Ctrl + Shift + P | Command Palette (VS Code) |

---

## ⚙️ The Process

### 1. Define Physical Constants

The script initializes:

- Planck's Constant (h)
- Speed of Light (c)
- Boltzmann Constant (k)
- Temperature (T)

### 2. Generate Frequency Range

A frequency range from:

```text
1 × 10¹² Hz to 1 × 10¹⁵ Hz
```

is created to analyze blackbody radiation behavior.

### 3. Implement Rayleigh-Jeans Law

The classical Rayleigh-Jeans equation is used to calculate spectral energy density.

This model predicts that energy density increases indefinitely at high frequencies.

### 4. Implement Planck's Law

Planck's quantum radiation formula is implemented.

The exponential term prevents energy density from diverging at high frequencies.

### 5. Calculate Spectral Energy Density

The script computes:

- Classical Prediction (Rayleigh-Jeans)
- Quantum Prediction (Planck)

for every frequency point.

### 6. Visualize Results

Both curves are plotted on the same graph.

The logarithmic y-axis clearly highlights the divergence between classical and quantum theories.

---

## 📚 What I Learned

- Fundamentals of blackbody radiation
- Origin of the Ultraviolet Catastrophe
- Limitations of classical physics
- Development of quantum theory
- Implementation of scientific equations in Python
- Numerical computation using NumPy
- Scientific visualization using Matplotlib
- Data interpretation and graph analysis
- Importance of Planck's contribution to modern physics

---

## 📈 Overall Growth

This project improved my understanding of modern physics by demonstrating one of the most important problems that led to the development of quantum mechanics. Through coding and visualization, I gained practical experience in translating theoretical physics equations into computational models and interpreting scientific results.

The project strengthened my skills in Python programming, numerical methods, scientific plotting, and mathematical modeling while connecting computational techniques with real-world physical phenomena.

---

## 🚀 How Can It Be Improved

- Add interactive parameter controls
- Allow user-defined temperatures
- Compare multiple blackbody temperatures simultaneously
- Create 3D radiation visualizations
- Develop a GUI using Tkinter or PyQt
- Generate automated reports
- Add Wien's Displacement Law analysis
- Add Stefan-Boltzmann Law calculations
- Export graphs as PDF reports
- Create web-based visualization using Plotly

---

## ▶️ Running the Project

### Requirements

#### Python Libraries

```bash
pip install numpy matplotlib
```

### Steps

1. Install Python.
2. Install NumPy and Matplotlib.
3. Save the script as:

```text
uv_catastrophe.py
```

4. Open terminal or command prompt.
5. Navigate to the project directory.
6. Run:

```bash
python uv_catastrophe.py
```

### Expected Output

The graph should show:

- Red Curve → Rayleigh-Jeans Law
- Blue Curve → Planck's Law

At high frequencies:

- Rayleigh-Jeans prediction diverges rapidly.
- Planck's Law reaches a peak and then decreases.

This demonstrates the resolution of the Ultraviolet Catastrophe.

---

## 📊 Theory

### Rayleigh-Jeans Law

Classical prediction of blackbody radiation:

- Accurate at low frequencies
- Fails at high frequencies
- Predicts infinite energy emission

### Planck's Law

Quantum mechanical solution:

- Introduces energy quantization
- Matches experimental observations
- Resolves the Ultraviolet Catastrophe

### Significance

The resolution of the Ultraviolet Catastrophe marked the birth of quantum mechanics and transformed modern physics.

---

## 🎯 Applications

- Physics Education
- Quantum Mechanics Demonstrations
- Scientific Visualization
- Computational Physics
- Numerical Analysis
- Academic Research
- Engineering Simulations

---

## 👨‍💻 Author

**Santos**

ECE Student | Python | Scientific Computing | Physics Simulations | AI | FPGA | Embedded Systems

---

*"The failure of classical physics became the foundation of quantum mechanics."*
