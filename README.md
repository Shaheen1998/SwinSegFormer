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

**Published Paper:** [IEEE Xplore](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10979465)

📌 **Code Repository:** [SwinSegFormer GitHub](https://github.com/Shaheen1998/SwinSegFormer)

---

## 🔥 SwinSegFormer Model and Supported Models
This repository contains the **SwinSegFormer** model along with other supported models, their predicted results, and corresponding configuration files.

### 🚀 SwinSegFormer & Model Variants
1. **SwinSegFormer Model:** [Link](https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SwinSegFormer_Model)
2. **SwinSegFormer Model Inference on Real-World Images & Flood-Affected Area Estimation:** [Link](https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SwinSegFormer_Model_Inference%20and%20Flooded_Affected_Area_Estimation)

### 📌 Baseline Models
6. **Swin Transformer Model:** [Link](https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/Swin_Transformer_Model)
7. **SegFormer Model:** [Link](https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/SegFormer_Model)
8. **DeepLabV3+ Model:** [Link](https://github.com/Shaheen1998/SwinSegFormer-Research_All-Supported_Models/tree/main/DeepLabV3%2B%20Model)

### 📊 Dataset
9. **FloodNet Dataset:** [Download from Kaggle](https://kaggle.com/datasets/c46b2c738b08fcb6a494f66c17572c9844936498062f7b1884ad8d4c0bbad349)

---

## 🤝 Contact
For any inquiries, feel free to reach out:
- **Author:** Muhammad Tariq Shaheen
- **GitHub:** [@Shaheen1998](https://github.com/Shaheen1998)
- **Email:** mshaheen.msee20seecs@seecs.edu.pk

🚀 **Happy Coding!** 🚀
