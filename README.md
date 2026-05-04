# ⚙ Control Systems Analyzer

**Author:** Dimitrios Kavalieros — Electrical Engineering and Information Technology MSc. & MEd.

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=jimkava/Control_System_Analyze-&file=ControlSystemsAnalyzer.m)
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/183790)

A MATLAB App for analysis of automatic control systems.  
Built with MATLAB R2019b+ and the **Control System Toolbox**.

---

## 🚀 Run instantly — no installation needed

Click **"Open in MATLAB Online"** above to run the app directly in your browser.

> **Requires:** Free MathWorks account at [mathworks.com](https://www.mathworks.com)

---

## Features

| Tab | Description |
|-----|-------------|
| **Block Diagram** | Visual closed-loop diagram: Controller, Plant, Sensor |
| **T.F. Results** | Open-loop, closed-loop & characteristic equation |
| **Routh–Hurwitz** | Full Routh array + automatic stability verdict |
| **Poles / Zeros** | CL/OL poles and zeros with LHP/RHP classification |
| **Root Locus** | Root locus plot over K ∈ [0, K_max] |
| **Bode** | Magnitude & phase + Gain Margin & Phase Margin |
| **Nichols** | Nichols chart with critical point |
| **Step Response** ⭐ | Step response plot + ζ, ωn, h%, tr, th, ts(2%), ts(5%) |

---

## Usage

```matlab
>> ControlSystemsAnalyzer
```

Enter coefficients space-separated, highest power first:
```
Example:  1 3 2  →  s² + 3s + 2
```
Results update **automatically** on every field change.

---

## Step Response Metrics (v0.2)

The **Step Response** tab computes all standard time-domain performance specifications:

| Parameter | Description |
|-----------|-------------|
| **ζ** | Damping ratio (from dominant closed-loop poles) |
| **ωn** | Natural frequency (rad/s) |
| **h%** | Percentage overshoot |
| **tr** | Rise time (10% → 90%) |
| **th** | Peak time (time to first maximum) |
| **ts(2%)** | Settling time — 2% criterion |
| **ts(5%)** | Settling time — 5% criterion |

The plot includes annotations for peak, rise time, settling time, and the ±2% steady-state band.

---

## Changelog

### v0.2
- ✅ Added **Step Response** tab (8th tab)
- ✅ Time-domain metrics: ζ, ωn, h%, tr, th, ts(2%), ts(5%)
- ✅ Annotated step response plot with peak marker, rise/settling time lines, ±2% band
- ✅ Dominant-pole extraction for ζ and ωn (works for any system order)
- ✅ Color-coded metrics: 🟢 h% < 5% / 🟡 h% < 20% / 🔴 h% ≥ 20%

### v0.1
- Initial release: Block Diagram, T.F. Results, Routh–Hurwitz, Poles/Zeros, Root Locus, Bode, Nichols

---

## Repository

```
Control_System_Analyze-/
├── ControlSystemsAnalyzer.m   # Main App (classdef, single-file)
└── README.md
```

---

## Requirements

- MATLAB R2019b+
- Control System Toolbox

---

## Author

**Dimitrios Kavalieros**  
Electrical Engineer MSc. & MEd.  
[github.com/jimkava](https://github.com/jimkava)
