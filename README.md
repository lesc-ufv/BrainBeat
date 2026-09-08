## Status & Notice

> **Notice:** This repository and dataset are currently a work in progress and **under review** (Major Review at IEEE JBHI). The data is not yet intended for external use or distribution.

---

## Dataset Structure & Metadata

* **`dataset_inventory.json`:** A summary inventory detailing which experimental recording files are present or missing for each subject.
* **Native XDF Metadata:** Each `.xdf` file internally contains its own complete stream metadata (including channel names, nominal sampling rates, and hardware timestamps), which can be accessed directly using standard tools such as `pyxdf`.