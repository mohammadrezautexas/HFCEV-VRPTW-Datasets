# HFCEV-VRPTW Datasets

Benchmark instances (Solomon-based) and a Florida case-study dataset
used in the paper:

> Ghorbanali Zadegan, M.R. & Guo, Z.  
> “Optimizing On-site Green Hydrogen Consumption using Heavy-duty FCEVs,”.

---

## Folder layout
| Path | Contents |
|------|----------|
| `Data/Solomon Benchmark/` | 64 CSV files 
| `Data/Case Study/` | 7 CSV files
| `README.md` | You’re reading it |
| `LICENSE` | CC-BY-4.0 data licence |

---

## File format (`Data/benchmark/*.txt`)

The first line is a header; rows are space-separated.

| column | unit | description |
|--------|------|-------------|
| `StringID` | – | `D0` depot, `S*` hydrogen-refuel-station candidate, `C*` customer |
| `Type` | – | `d` = depot, `f` = facility (HRS), `c` = customer |
| `x`, `y` | km | Cartesian coordinates (same scale as Solomon) |
| `demand` | kg | freight to be delivered (0 for depot & HRS) |
| `ReadyTime`, `DueDate` | min | time-window \[e\_i, l\_i] |
| `ServiceTime` | min | unloading or refuelling time |
| `wp1` … `wp21` | – | hourly solar-irradiance coefficients 
---

## How to cite

> Ghorbanali Zadegan, M.R., & Guo, Z. (2025). **HFCEV-VRPTW Datasets** (v1.0)  
> [Data set]. GitHub. <https://github.com/mohammadrezautexas/HFCEV-VRPTW-Datasets>

