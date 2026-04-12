# Forward-Facing Step CFD Validation

## 📌 Overview
This repository presents a CFD validation study of flow over a forward-facing step. The results are compared against the experimental and numerical data reported by **Moss and Baker**.

The objective is to evaluate:
- Flow separation and reattachment
- Velocity profiles
- Reattachment length accuracy

---

## 🧪 Methodology

### Geometry
- 2D forward-facing step
- Step height: H
- Domain length: L

### Flow Conditions
- Incompressible flow
- Reynolds numbers: 500, 1000, 5000

### Solver
- Finite Volume Method
- Pressure-velocity coupling: SIMPLE / PISO
- Turbulence model: k-ε / k-ω SST

---

## 📊 Validation

Results are compared with:
> Moss, W. D., & Baker, S. (Reference paper)

Metrics used:
- Velocity profiles at multiple stations
- Reattachment length (x/H)
- Wall shear stress distribution

---

## 📈 Results

### Key Observations
- Good agreement in velocity profiles downstream
- Slight deviation in reattachment length at higher Reynolds numbers
- Turbulence model sensitivity observed
