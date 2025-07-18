---
title: "CP70 Pre-Amp Project Status Report"
date: [YYYY-MM-DD]
version: [vX.Y]
---

## 1. Project Overview  
**Background**  
The Yamaha CP70 is an iconic electric grand piano known for its unique sound, derived from real strings and hammers combined with a piezo pickup system. This project aims to provide a modern, high-fidelity replacement, with 72 separate output channels as an alternative pre-amplifier system.

**Key Objectives**
- High input impedance (470 kΩ) to preserve pickup characteristics
- Very-low noise floor (<20 nV/√Hz)
- Modular 16-channel PCB design
- Open-source hardware documentation

---

## 2. Current Progress  
### 2.1 Version Status
**Current Version**: [v0.3 - Prototype Validation]  
**Project Status**: [🟢 Prototyping | 🟡 Testing | 🔴 In Design]

### 2.2 Key Milestones  
| Milestone | Status | Last Updated |
|-----------|--------|--------------|
| 16-channel PCB layout | ✅ Completed | 2025-06-10 |
| Input impedance validation | 🟡 In Progress | 2025-07-15 |
| Noise floor measurement | ❌ Pending | - |
| Full 72-channel assembly | ❌ Pending | - |

### 2.3 Technical Updates

**Design Progress**  
- Finalized 2-layer PCB stackup with dedicated ground plane 
- Implemented JFET-based input stage for impedance buffering
- Tested input stage, tested on CP70 pickups, OK (see images)
- Added per-channel gain adjustment (-inf to 0dB)
- designed and built PCB with 16 Audio Log Pots and 40 pin flat cables
  

**Component Selection**  
- Op-amps: TL072/TL052 (selected for 15nV/√Hz noise)
- Connectors: 3M 2.54mm pitch terminal blocks
- Power: ±15V rails with TL7815 TL7915 regulators

