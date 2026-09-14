# Battery-Free Sensor Seed

This repository provides the design files for a battery-free sensor seed intended for large-scale aerial deployment in environmental monitoring. Through its structural design, more than 94% of the sensor seeds land with the solar panel facing upward when released in the specified orientation. This improves energy harvesting reliability and significantly reduces the cost of each sensor node.

We designed two sensor-node variants based on different chip platforms: a Nordic nRF52833 version and a version based on the crystal-free [SCuM chip platform](https://scum.berkeley.edu/). Our demo received the **Best Demo Runner-Up** award at MobiSys 2026.

## Repository Structure

```text
.
├── Demo__A_Battery_Free_Sensor_Seed_for_Large_Scale_Aerial_Deployment_in_Environmental_Monitoring.pdf
├── Seed_52833Chip/
│   ├── AD_52833Leaf.zip
│   ├── BOM_52833Leaf.xlsx
│   └── Gerber_52833Leaf.zip
└── Seed_scumChip/
	├── ADscumLeaf.zip
	├── BOM_scumLeaf.xlsx
	└── Gerber_scumLeaf.zip
```

- `Demo_*.pdf`: Project paper and technical details.
- `Seed_52833Chip/`: Design files for the nRF52833-based sensor node.
- `Seed_scumChip/`: Design files for the crystal-free SCuM-based sensor node.
- `AD*.zip`: Assembly data; `BOM*.xlsx`: bill of materials; `Gerber*.zip`: PCB fabrication files.
