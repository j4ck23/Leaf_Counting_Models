# Leaf_Counting_Models
Leaf counting computer vision models of 5 types of plants using YOLO

This Repo contains 5 YOLO v11 models for detecting and counting the leaves of 5 plants:
1. Agapanthus praecox subsp. orientalis
2. Fatsia japonica 'Tsumugi-shibori'
3. Yucca aloifolia red experimental
4. Solanum lycopersicum 'Totem'
5. Fragaria × ananassa 'Malling Centenary'

Each Folder contains the weights of the trained models so far. To access the path to the train folder inside the runs/detect folder and then point to the best.pt inside the weights folder. It will look something like this - "runs/detect/train/weights/best.pt" 

Each folder contains one model. Each folder contains the data used to train and test the YOLO v11 model stored in the corresponding folder. If you wish to train a new model, simply replace the Train, Test, and Val folders and data.YAML file with the new dataset, and then run the Python file named the same as the folder. (E.G. strawberry.py in the strawberry folder)

--Note: if you retrain the model, the weights may be saved in a new location. It will still be under the runs/detect folder, but may now be stored in a train2 or train3 folder. If so, just change that section of the path when pointing to the weights. the subsequent path of weights and best.pt will remain the same. (I've not retrained a model and kept the old version, so I cannot say if the path for the weights will 100% move, but keep this in mind if you train a new version and the accuracy does not increase!)

Each folder also contains a test script that lets you input a plant image to evaluate the model's accuracy.

