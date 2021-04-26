# DeepFruit
Reproduction of the paper "Deep Fruit Detection in Orchards"

Link to the dataset : http://data.acfr.usyd.edu.au/ag/treecrops/2016-multifruit/


Data_preparation.ipynb was used to combine the annotated image data. 

Reproducibility_Project_Fruit_Detection.ipynb was used to train models for various dataset sizes and transforms to generate the data required for reproduction.
Follow the link to the google drive to see how to set up the directories for using the notebook. The directories cannot be uploaded to github due to their large size. 

Use the following commands in bash to download the vision repository used in the project.

`git clone https://github.com/pytorch/vision.git

cd vision

git checkout v0.3.0

cp references/detection/utils.py ../

cp references/detection/transforms.py ../

cp references/detection/coco_eval.py ../

cp references/detection/engine.py ../

cp references/detection/coco_utils.py ../`
