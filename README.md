# Sigma-Forensics-Auditor

**Automated Detection of Latent Attractor Resonance ($R_t$) and Architectural Persistence ($V_e$).**

## 🔬 Scientific Foundation
* **Research DOI:** [10.17605/OSF.IO/DKUE9](https://osf.io/dkue9/)
* **Tactical Mapping:** MITRE ATLAS **AML.T0012** (Persistence) & **AML.T0015** (Defense Evasion).

##  Key Metrics (The "Verification Gap")
| Metric | Threshold | Definition |
| :--- | :--- | :--- |
| **$R_t$** | `0.83` | The Resonance point where model weights override safety filters. |
| **$V_e$** | `≥ 2.0` | The persistence of a de-aligned state across context resets. |

## Quick Start
```bash
python main.py
