This repository contains the Google Colab notebook used to conduct the initial DeepLabCut feasibility check for the project. The pilot successfully trained a ResNet-50 network to track 8 invariant keypoints with a test RMSE of 3.44 pixels.
[Watch the labeled output video here](https://drive.google.com/file/d/1IOg2pYKO64VzHwlO9WMj5372WY-q5ZIN/view?usp=sharing)
## Data and Annotation
* **Tool used:** [CVAT](https://www.cvat.ai/) 
* **Dataset size:** 20 manually annotated frames. This small dataset was used to demonstrate the end-to-end DeepLabCut workflow.

## Training Details
* **Environment:** Google Colab 
* **Training duration:** 200 epochs 
* **Goal:** Proof of concept to verify the pipeline from data annotation to model evaluation.
