🪲 RicePest-30 Dataset


📘 Overview

RicePest-30 is a multi-class rice pest detection dataset designed to support intelligent agricultural monitoring and pest recognition research. It contains 30 pest species, 8,848 images, and 62,227 annotated instances in COCO format.

📷 Data Sources

Images were collected from:

Field traps — UV light traps deployed in Hunan Province (Suining, Taoyuan, Wangcheng, etc.), covering different rice growth stages.

Web sources — Carefully screened to ensure visual consistency with field images.

Laboratory samples — Including single-pest and white-background images for fine-grained recognition.

🧩 Annotation

Format: COCO

Tool: CVAT v2.45.0

Rules: Each identifiable pest was annotated, even if partially occluded or slightly blurred. Severely occluded or unrecognizable objects were excluded.

Quality Control: Dual annotation with cross-checking and triple review of 10% randomly sampled images.

Total Labels: 62,227 pest instances across 30 categories.

🐛 Categories

The dataset includes 30 common rice pests such as:
Chilo suppressalis, Cnaphalocrocis medinalis, Athetis spp., Ostrinia furnacalis, Spodoptera frugiperda, Agrotis segetum, etc.
Detailed statistics are provided in Table 2-1 (images and instances per species).

📊 Dataset Statistics
Type	Count
Pest species	30
Images	8,848
Annotated instances	62,227
Format	COCO
Annotation tool	CVAT v2.45.0
