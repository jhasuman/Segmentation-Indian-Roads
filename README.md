# Segmentation-Indian-Roads
A deep Learning mdoel for segmentation for India roads, finetuned for Indian conditions 

Download the weights from : https://drive.google.com/open?id=1cUVMPFeaL79XLkbFfOiv21l1gd54iDJt
Add your image to the input directory.
Then run `python inference.py --img-path=./input/<imagename.png> --dataset=cityscapes --filter-scale=1`

We have used Cityscape dataset to train the model. The trained model has been tested with Indian dataset and the accuracy is also good. The model accuracy will increse drastically by training the model with Indian dataset which we have started on GPU and we will present the final model which will have higher accuracy.  

## Input
![input](input/test.png?raw=true "Input")

## Output
![input](output/prediction.png?raw=true "Input")
