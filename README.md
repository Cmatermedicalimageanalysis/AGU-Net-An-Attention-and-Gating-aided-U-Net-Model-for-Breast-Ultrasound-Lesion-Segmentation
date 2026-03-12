**AGU-Net: An Attention and Gating-aided U-Net Model for Breast Ultrasound Lesion Segmentation**

**Model Architecture**
<img width="1280" height="720" alt="Sayan_Segmentation_Arch" src="https://github.com/user-attachments/assets/52c03caf-2c25-475e-be4a-b1afd9806aac" />

## Error Analysis Visualization

This section presents qualitative error analysis of the proposed AGU-Net model. 
The visualizations highlight cases where the model performs well and where segmentation errors occur, including boundary inaccuracies, missed lesion regions, or false positives. 
Such analysis helps understand model limitations and guides future improvements.

<img width="1066" height="630" alt="erroranalysisviz (1)" src="https://github.com/user-attachments/assets/c9382fec-9a84-4af2-b22f-6a27da15bf47" />

## Grad-CAM Visualization

To interpret the model’s decision-making process, Grad-CAM (Gradient-weighted Class Activation Mapping) is used to visualize the regions of the input ultrasound images that contribute most to the model’s predictions. 
These heatmaps provide insights into whether the model focuses on the relevant lesion areas during segmentation.

<img width="705" height="635" alt="Vizualization drawio (1) (1)" src="https://github.com/user-attachments/assets/c32abc87-502f-41c7-833a-a84e56852e1d" />

## Results Table

| Dataset | Dice (%) | IoU (%) |
|--------|--------|--------|
| BUSI | **79.20** | **71.08** |
| BUS-BRA | **89.13** | **81.62** |
