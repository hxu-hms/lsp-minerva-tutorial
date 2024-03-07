---
layout: reference
---

## Example stories

### Automated
* [HTA-CRCATLAS-1](https://labsyspharm.github.io/HTA-CRCATLAS-1/minerva/crc03-overview.html)

### Curated
* [Ovarian Cancer with Annotation-LSP15343](https://www.cycif.org/data/gray-stic-1-mini/)
* [MEL-3D-MIS-2](https://www.cycif.org/data/mel-3d-mis-2/)

### Narrated



## Glossary

| **Waypoint** | A specific location in the tissue image. For example, blood vessel, lymph node margin. The most basic waypoint consists of a user-selected area on the slide and the related text description. |
| **Channel** | Staining for a marker, for example CD3 labeling T cell membranes. |
| **Channel Group** | Several channels bundled together to convey information. For example, CD3, CD4, CD8 and FOXp3 to distinguish T cell subtypes, or CD45, keratin, CD31 and SOX10 to distinguish melanoma surrounding epithelia blood vessels and immune cells. Individual channels within the group cannot be toggled. Viewers can choose what channel group to display. |
| **Mask** | Segmentation masks. Masks can be added to a waypoint, and are only visible on that waypoint. Viewer can toggle each mask individually. |
| **Visualization** | Plots and/or videos that help illustrate the point alongside the image data. Minerva Author can generate scatter plot, matrix plot and bar chart (max one of each type) with input data in the form of .csv files. They will appear underneath the text description on a waypoint. Additionally, user can embed images (.png, .jpeg etc.) and/or videos in the description using Markdown and HTML. |
| **Annotation** | Arrow, ROI rectangles and text labels can be displayed on your image as annotation. |


{% include links.md %}
