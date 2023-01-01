# fault_detection_system
## Description
Notebook to detect defective cells from non-defective cells.
The dataset used in this project can be downloaded from [this repo](https://github.com/zae-bayern/elpv-dataset)

The notebook builds a binary classification model using Transfer Learning from a pre-trained EfficientNetv2B2 on ImageNet Dataset.
The notebook also shows how to use ScoreCam to explain the predictions of the model.

## Notes
* To reproduce this work, you can download the repo of the dataset then put the notebook of this repository inside of it.
* The images folder is empty, you can place inside of it the images of the dataset after downloading it from [here](https://github.com/zae-bayern/elpv-dataset).


## References:

[1] Buerhop-Lutz, C.; Deitsch, S.; Maier, A.; Gallwitz, F.; Berger, S.; Doll, B.; Hauch, J.; Camus, C. & Brabec, C. J. A Benchmark for Visual Identification of Defective Solar Cells in Electroluminescence Imagery. European PV Solar Energy Conference and Exhibition (EU PVSEC), 2018. DOI: 10.4229/35thEUPVSEC20182018-5CV.3.15

[2] Deitsch, S., Buerhop-Lutz, C., Sovetkin, E., Steland, A., Maier, A., Gallwitz, F., & Riess, C. (2021). Segmentation of photovoltaic module cells in uncalibrated electroluminescence images. Machine Vision and Applications, 32(4). DOI: 10.1007/s00138-021-01191-9