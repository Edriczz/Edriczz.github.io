---
trigger: always_on
---

---
name: strict-code-style
description: Enforces code formatting, linting, and structural standards across the project.
---
# Code Style & Formatting Rules

* **Python & AI Engineering:** Strictly adhere to PEP 8 guidelines. Run formatting tools to ensure clean syntax. 
* **Hardware Deployments:** Keep model definitions modular, ensuring hardware-specific optimizations (like TensorRT configuration, MQTT brokering, or frame-skipping logic) are decoupled from the core inference scripts.
* **Frontend/Web:** Enforce consistent utility class ordering (e.g., Tailwind) and use standard formatters for component structures.
* **General Hygiene:** Prune all dead code, remove unused dependencies, and ensure variables use clear, descriptive casing.