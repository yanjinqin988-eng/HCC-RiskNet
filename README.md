This is the implementation of the article "HCC-Risk Model: Multimodal Fusion of Clinical, Radiomics, and Body Composition Features via Multichannel Deep Learning Framework for Risk Stratification of Hepatocellular Carcinoma in Patients with Cirrhosis."

Acknowledgements:

The radiomics modeling, deep learning networks, and multimodal feature fusion networks used in this study are based on modules from the Onekey AI platform. We sincerely thank the platform for its contribution. (https://github.com/OnekeyAI-Platform/onekey)

Body composition metrics were  quantified using the following methods:
Deep learning-based segmentation of thoracic and abdominal subcutaneous adipose tissue, skeletal muscle, visceral adipose tissue, and paraspinal muscles was performed using TotalSegmentator (Citation 1: https://doi.org/10.1148/radiol.241613; Citation 2: https://www.nature.com/articles/s41592-020-01008-z). Area and signal intensity measurements of these tissues at corresponding vertebral levels were calculated using NumPy (Version: 1.26.4), NiBabel (Version: 5.1.0), and Pandas (Version: 2.3.2) within Python (Version: 3.12).
