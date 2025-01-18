The dataset consists of 184 2D MRI images and corresponding masks, categorized into Alzheimer's Disease (AD), Mild Cognitive Impairment (MCI), and normal cases. It is split into a training set of 139 images and a validation set of 45 images. The algorithm follows several key steps:

Dataset Preparation: Images and masks are accessed through a specified directory in the dataset.py file.
Model Building: A U-Net architecture is implemented, featuring contraction, expansion, and bottleneck paths, utilizing 3x3 convolutions and max pooling.
Hyperparameter Definition: Key parameters such as learning rate, number of epochs, and image dimensions are set, along with the loss function and optimizer.
Evaluation and Accuracy: After training, the model's output is saved, and segmentation accuracy is assessed using pixel accuracy, which compares the output pixels to the ground truth.
This structured approach aims to effectively segment MRI images for better diagnosis and understanding of cognitive impairments.
