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
![Step] <img width="838" height="755" alt="Step Response" src="https://github.com/user-attachments/assets/0fdbb678-aacc-44fd-96d4-7340d1bc0fed" />


### Ramp Response
![Ramp] <img width="833" height="746" alt="Ramp Response" src="https://github.com/user-attachments/assets/8eaa8971-6f7e-4e04-aa82-afad54fc2883" />


### Parabolic Response
![Parabolic] <img width="829" height="752" alt="Parabolic Response" src="https://github.com/user-attachments/assets/a70d7416-470a-49dc-acc9-554c3169ec34" />


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
