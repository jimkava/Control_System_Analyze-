# ⚙ Control Systems Analyzer

**Author:** Dimitrios Kavalieros — Electrical Engineering and Information Technology MSc. & MEd.

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=jimkava/Control_System_Analyze-&file=ControlSystemsAnalyzer.m)
[![View Control Systems Analyzer on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/183790-control-systems-analyzer)

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
