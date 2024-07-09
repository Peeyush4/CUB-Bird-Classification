# CUB-Bird-Classification
CUB is a bird dataset by UCSD created in 2011, containing over 11788 images and 200 different species. 

Link: https://paperswithcode.com/dataset/cub-200-2011

|Model    | Optimizer | Layers | Accuracy |Remarks|
|---------|-----------|--------|----------|-------|
|ResNet50 | Adam      | 1 hidden (512 nodes)  | 60       | Took everything as a feature extractor except the final neural layers |
|ResNet50 | Adam      | 1 hidden (2048 nodes) |58        | Took everything as a feature extractor except the final neural layers |
|ResNet18 | Adam      | No hidden             |66        | Fine-tuned with setting all grads to be true| 
|DenseNet121| Adam    | No hidden             |66.82     | Took everything as a feature extractor except the final neural layers. Tried for 40 epochs - 67.25 |
|DenseNet161| Adam    | No hidden             |69.399    | Took everything as a feature extractor except the final neural layers |
|YOLOv8n| AdamW       |                       |73.1      | lr=0.000714, momentum=0.9, 100 epochs | 
|YOLOv8s| AdamW       |                       |77.4      | lr=0.000714, momentum=0.9, 100 epochs | 
|YOLOv8m| AdamW       |                       |78.5      | lr=0.000714, momentum=0.9, 100 epochs | 

I have an accuracy of about 69.399% and want to improve more. If you have any ideas, mail me: peeyu704@gmail.com
