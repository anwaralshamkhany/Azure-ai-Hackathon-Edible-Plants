# Azure-ai-Hackathon-Edible-Plants
This repository has the set values and model for training and creating a CNN capable of predicting edible plant species in a local Canadian forest
which includes a dataset of over 6000 images with an accuracy of roughly 89%. The image recognition model has a lot of adjustments to the values that aid in identifying what species a plant is based on its outline of color saturation. The stronger the outline the stronger the correlation between the model and the image. The dataset already has seperate folders for test and split so there is no need to to do a datasplit. The transformations on the images mainly just convert the images to a 224 by 224 pixel ration so that the model is easier to process. Best results are with roughly 100 epochs.

# Link to download dataset
https://www.kaggle.com/gverzea/edible-wild-plants
