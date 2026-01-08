# Battery Health Monitoring and Second-Life Assessment

This project analyzes lithium-ion battery operational data to estimate
State of Health (SoH), identify key degradation drivers, and provide
second-life usage recommendations.

## Features
- State of Health (SoH) estimation
- Feature-based explainability (temperature, SOC, voltage effects)
- Operational stress and stability analysis
- Second-life battery classification
- Human-readable health summary (decision support)

## Dataset
- Single battery operational dataset
- High-frequency time-series data
- Single charge cycle (Cycle = 1)

## Limitations
- Remaining Useful Life (RUL) estimation is not performed due to
  absence of multi-cycle aging data.
- Degradation analysis is limited to short-term operational behavior.

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest)
- Matplotlib

## Output
- Health trend visualization
- Feature importance analysis
- Decision-grade battery assessment

