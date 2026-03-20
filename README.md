# Welcome to my coding garage!

**Sensing Systems · Embedded Hardware · Wearable Devices · Program Management**
BS/MS Mechanical Engineering — Georgia Institute of Technology · Atlanta, GA

---

## Repositories

### [embedded](https://github.com/ekim3991217/embedded) — Firmware & Hardware Design
Microcontroller firmware and PCB design projects targeting TI MSP432, Arduino, and custom biosensor boards.

| Folder | Description |
|--------|-------------|
| `msp432/` | CCS embedded C projects — UART, motor control, ultrasonic sensor, IMU |
| `arduino/` | Arduino sketches — LED control, sensor interfacing |
| `energia/` | Energia IDE projects for TI LaunchPad — IMU motion capture |
| `kicad-electrode/` | KiCad PCB schematics and layouts — electrode array and strain sensor |
| `ti-sdk/` | TI MSP432 driverlib, SYSBIOS RTOS, CCS target configs |

```bash
git clone https://github.com/ekim3991217/embedded.git
# MSP432: open CCS → import projects from embedded/msp432/
# Arduino: set sketchbook root to embedded/arduino/
```

---

### [research](https://github.com/ekim3991217/research) — Analysis & Lab Data
MATLAB and Python scripts from Georgia Tech graduate coursework and BITN bioelectronics lab research.

| Folder | Description |
|--------|-------------|
| `matlab/ME4056-systems-lab/` | Blackbody radiation, system ID/controls, IC engine, refrigeration |
| `matlab/ME6105-modeling-simulation/` | Optimization, Monte Carlo, ANOVA, linear regression (HW1–8 + group project) |
| `matlab/ME6407-robotics/` | Robot kinematics, dynamics, trajectory planning — course notes and HW |
| `ml-python/ME8813/` | ML for Mechanical Engineers — regression, Bayesian networks, dimensionality reduction, KNN motion classifier |
| `ien-research/data/` | In-vitro microneedle implant PCB stimulation experiment data |

```bash
git clone https://github.com/ekim3991217/research.git
# MATLAB: open any .m or .mlx in MATLAB R2022a+ (requires Control System,
#         Statistics & ML, and Robotics System Toolboxes)
# Python: conda activate me8813  # Python 3.10
```

---

### [scripts](https://github.com/ekim3991217/scripts) — Automation & Utilities
Python automation scripts for instrument control, data analysis, and workflow automation.

| Folder | Description |
|--------|-------------|
| `lcr-meter/` | Serial instrument control for Mark-10 LCR meter — automated impedance measurement |
| `ml-analysis/` | GMM clustering, autoencoder, K-means silhouette — output figures included |
| `busway_project_automation/` | BOM parsing, SharePoint crawler, GitHub repo setup automation |

```bash
git clone https://github.com/ekim3991217/scripts.git
conda activate base
python scripts/lcr-meter/LCRmeter_mark10_script.py
```

---

## Skills & Tools

| Domain | Stack |
|--------|-------|
| Embedded / Firmware | C, MSP432, Arduino, Energia, CCS, PlatformIO, nRF Connect |
| PCB Design | KiCad, Fusion 360 |
| Data Analysis | MATLAB, Python (NumPy, pandas, scikit-learn, TensorFlow) |
| ML / Modeling | GMM, KNN, autoencoders, Bayesian networks, linear regression, ANOVA |
| Automation | Python, GitHub Actions |
| Dev Environment | VS Code, Git, Conda, Homebrew |
