
# 🛸 SKY EVIDENCE — Drone Digital Forensics Platform

> **AR:** منصة تحقيق جنائي رقمي للطائرات بدون طيار (Drones/UAV): من استحواذ الدليل والتحقق من سلامته، إلى تحليل سجلات الطيران وإحداثيات GPS، وإعادة بناء الخط الزمني، وتوليد تقرير جنائي.
>
> **EN:** A drone/UAV digital forensics platform — from evidence acquisition and integrity verification to flight-log and GPS analysis, timeline reconstruction and forensic report generation.

🎓 Graduation project — solo work (research + working implementation).

---

## ⚙️ Highlights
- **Python CLI** for Kali Linux
- **Standard library only** — no external dependencies
- **Modular** design: each forensic stage is its own module

## 🧩 Modules
| # | Module | Purpose |
|---|---|---|
| 1 | Evidence Acquisition | Collect drone evidence |
| 2 | Extraction | Parse files & artifacts |
| 3 | Hash Verification | Integrity & chain of custody |
| 4 | Metadata / Flight Log Analysis | Altitude, speed, events |
| 5 | GPS 3D Visualization | Flight path reconstruction |
| 6 | Evidence Correlation | Link artifacts together |
| 7 | AI Forensics Agent | Assisted analysis |
| 8 | Timeline Reconstruction | Ordered event timeline |
| 9 | Risk Analysis | Flag anomalies |
| 10 | Report Generation | Final forensic report |

![Architecture](screenshots/architecture.png)

## 🧪 Training Case — `CASE-2026-DR07`
A synthetic drone case with deliberately planted anomalies for investigation practice:
- GPS spoofing indicators
- Hash-chain tampering

![Case analysis](screenshots/case-dr07.png)

## 🚀 Usage
```bash
git clone https://github.com/sahla-hassan/sky-evidence.git
cd sky-evidence
python3 main.py --help
```
> ✏️ Adjust the entry point/commands to match the code.

## 📸 Screenshots
| CLI | GPS Path | Report |
|---|---|---|
| ![](screenshots/cli.png) | ![](screenshots/gps.png) | ![](screenshots/report.png) |

## 👩‍💻 Author
**Sahla Hassan | سهلة حسن** — DFIR
[Portfolio](https://sahla-hassan.github.io) · [LinkedIn](https://linkedin.com/in/sahla-hassan)
