# Bone-marrow-classification

**Dataset**

 We used the Bone-Marrow-Cytomorphology_MLL_Helmholtz_Fraunhofer dataset with 21 classes

 
**Environments**

 NVIDIA GeForce RTX 3090
 
 PyTorch 1.10.0
 
 python 3.8.18
 
 cudatoolkit 11.3.1


**Result**
 |Mean|precision|recall|F1 score|
 |------|------|------|------|
 |Densenet-201|68.292|65.831|66.524|
 |Resnext50|70.268|65.140|66.953|
 |MobileNetV3|70.980|61.328|64.249|
 |Swin TransformerV2|73.370|65.020|67.992|
 |Regnet|68.183|63.722|65.155|
 |Matek|51|68.9|54.5|

 
**Reference**

 Matek, C., Krappe, S., Münzenmayer, C., Haferlach, T., & Marr, C. (2021). An Expert-Annotated Dataset of Bone Marrow Cytology in Hematologic Malignancies [Data set]. The Cancer Imaging Archive. https://doi.org/10.7937/TCIA.AXH3-T579
