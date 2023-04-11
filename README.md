# Multimedia-Disaster-Classification

We have created 3 separate machine learning models which can classify text, image and video data, and see if it pertains to a disaster or not

## Required Python Packages
* tensorflow
* pandas, numpy, matplotlib
* keras
* cv2

`Note`: Install the above mentioned package using command - "pip install <package_name>"

## How to Run ?
* Clone the repository
* Download dataset mentioned in Data/Dataset_links.txt 
* Change the path to the respective dataset file in  ipynb files.
* Run the text_classifier.ipynb file
* Run image_classifier.ipynb file
* For video classification - 
    1. Train the model using command - "python train.py"
    2. Run the predict by providing the path to the input file using the command - "python predict.py --input <input_file_path> --output <output_file_path>"

## Future Works - 
* Try and integrate all the models for real time data classification
* Get tweepy access for that
* Build web interface for the product which can provide better insights on the data
* Feature to extract useful information from the text data
* If only, image, or video dataset, then try to find how many people were invloved in the disaster or what is the location of place. This feature could be added