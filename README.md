# CUB-Bird-Classification
CUB is a bird dataset by UCSD created in 2011, containing over 11788 images and 200 different species. 

Link: https://paperswithcode.com/dataset/cub-200-2011

|Model    | Optimizer | Layers | Accuracy |Remarks|
|---------|-----------|--------|----------|-------|
|ResNet50 | Adam      | 1 hidden (512 nodes)  | 60       | Took everything as feature extractor except final neural layers |
|ResNet50 | Adam      | 1 hidden (2048 nodes) |58        | Took everything as feature extractor except final neural layers |
|ResNet18 | Adam      | No hidden             |66        | Fine tuned with setting all grads to be true| 

I have an accuracy of about 66% and want to improve more. If you have any ideas, mail me: peeyu704@gmail.com
