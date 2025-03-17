# SwinSegFormer: Advancing Aerial Image Semantic Segmentation for Flood Detection

## Abstract
Semantic segmentation of aerial images is vital for unmanned aerial vehicle applications,
such as land cover mapping, surveillance, and identifying flood-affected areas for effective natural
disaster management and flood impact mitigation. Traditional CNN-based techniques face challenges in
capturing global semantic information due to their limited receptive fields and, existing transformer-based
architectures often require high computational resources or produce single-scale, low-resolution features,
which impairs segmentation performance. To address these limitations, we propose a novel transformer-
based model named SwinSegFormer, which leverages the strengths of SegFormer with a lightweight MLP
decoder to overcome computational overhead and Swin Transformer (SwinT) with a hierarchical encoder
to generate multi-scale resolution features. Our model is trained on the FloodNet dataset and benchmark
evaluations, focusing on challenging classes such as vehicles, pools, and flooded and non-flooded roads,
which are crucial for effective disaster management. Additionally, we developed a post-processing module
to categorize predicted masks into flooded and non-flooded areas based on the affected area. We further
validate the performance of our model by making inferences over a small, unlabeled dataset of real-world
flood images, potentially enabling its use in first aid activities during floods. The proposed model achieved
notable results with a validation mIoU of 75.1%, mDice of 85.4%, and mAcc of 87.1%, representing a 10-
12% improvement compared to vision transformer-based SOTA methods. Future work includes exploring
SwinSegFormer’s interpretability and real-time deployment in diverse aerial imagery conditions. Code is
available at: https://github.com/Shaheen1998/SwinSegFormer.

## My Proposed SwinSegFormer Model and All Supported Models with Thier Predicted Results and Config Files

### 1. SwinSegFormer Model: https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SwinSegFormer_Model
### 2. SwinSegFormer Model Inference on Real Word Images, and Flooded Affected Area Estimation: https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SwinSegFormer_Model_Inference%20and%20Flooded_Affected_Area_Estimation
### 3. Hybrib Model __SwinT_ViTs-decoder: https://github.com/Shaheen1998/SwinSegFormer/blob/main/Hybrid%20Model__SwinT_Vit-decoder.ipynb
### 4. Hybrib Model __SegFormer_Swin-decoder: https://github.com/Shaheen1998/SwinSegFormer/blob/main/Hybrid%20Model__SegFormer_Swin-decoder.ipynb
### 5. Hybrib Model __Segformer_ViTs-decoder: https://github.com/Shaheen1998/SwinSegFormer/blob/main/Hybrib%20Model%20__SegFormer_Vit-decoder.ipynb
### 6. Swin Transformer Model: https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/Swin_Transformer_Model
### 7. SegFormer Model: https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SegFormer_Model
### 8. DeepLabV3+ Model: https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/DeepLabV3%2B%20Model
### 9. FloodNet_dataset: https://kaggle.com/datasets/c46b2c738b08fcb6a494f66c17572c9844936498062f7b1884ad8d4c0bbad349
