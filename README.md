# Leaf_Counting_Models
Leaf counting computer vision models of 5 types of plants using YOLO

This Repo contains 5 YOLO v11 models for detecting and counting the leaves of 5 plants:
1. Agapanthus praecox subsp. orientalis
2. Fatsia japonica 'Tsumugi-shibori'
3. Yucca aloifolia red experimental
4. Solanum lycopersicum 'Totem'
5. Fragaria × ananassa 'Malling Centenary'

Each folder contains one model - Each folder contains the data used to train and test each YOLO v11 model stored in the corresponding folders. If you wish to train a new model, simply replace the Train, Test, Val folders and data.YAML file with the new dataset and run the file named the same as the folder.

Each folder also contains a test script where you can input a plant image to test the accuracy of the model.
