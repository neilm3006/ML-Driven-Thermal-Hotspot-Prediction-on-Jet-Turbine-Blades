# ML-Driven-Thermal-Hotspot-Prediction-on-Jet-Turbine-Blades

Built a data-driven framework to predict thermal hotspot formation on a parametric 3D NACA 65-421 turbine blade, eliminating the need for repeated high-cost CFD/FEA simulations in early-stage design.
Using local blade geometry features (spanwise position, curvature, LE/TE proximity, twist) combined with engine operating conditions (TIT, pressure ratio, RPM, cooling effectiveness), I trained two XGBoost models:
→ Regression: R² = 0.93 | MAE ±8.4 K
→ Classification: 94.7% accuracy | AUC = 0.96
Predicted thermal fields visualised directly on 3D blade geometry using Plotly, enabling spatially localised risk assessment at a fraction of simulation cost.
Key finding: hotspot formation driven primarily by turbine inlet temperature, cooling effectiveness, blade-tip proximity, and leading-edge geometry — consistent with known aerothermal failure modes.
