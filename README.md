# matlab-steady-state-error-analysis
Steady state error analysis of Type 0, 1, and Type 2 systems using MATLAB

# 📊 Steady State Error Analysis using MATLAB

## 📌 Introduction
This project analyzes steady-state error for different types of control systems using MATLAB.

---

## 🧠 Concept
Steady-state error is the difference between input and output as time approaches infinity.

System type is based on number of poles at origin:
- Type 0 → No pole
- Type 1 → One pole
- Type 2 → Two poles

---

## 📊 Performance Summary

| System Type | Step | Ramp | Parabolic |
|------------|------|------|-----------|
| Type 0     | Finite | Infinite | Infinite |
| Type 1     | Zero | Finite | Infinite |
| Type 2     | Zero | Zero | Finite |

---

## 💻 MATLAB Code
Single reusable code is used for all systems. Only numerator and denominator change.

📁 See: `steady_state_error.m`

---

## 📷 Outputs

### Step Response
![Step](outputs/step_response.png)

### Ramp Response
![Ramp](outputs/ramp_response.png)

### Parabolic Response
![Parabolic](outputs/parabolic_response.png)

---

## 🔍 Observations
- Increasing system type reduces steady-state error
- Type 2 system gives best tracking performance
- MATLAB results match theoretical predictions

---

## ✅ Conclusion
Steady-state error depends on system type. Higher type systems improve accuracy and tracking ability.

## Author
Kunal Gadhave

## 🛠 Tools Used
- MATLAB
- Control System Toolbox
