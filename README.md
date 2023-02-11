# MobileNet_V2_Classification_Analysis

 The steps to run inference with a pre-trained MobileNetV2 model on the differenct dataset are as
 
# 1- Import necessary libraries
# 2- Load the pre-trained MobileNetV2 model
# 3- Load the CIFAR-10 dataset and apply transformations
# 4- Run inference on a sample image from the CIFAR-10 dataset
# 5- Get the predicted class
# 6 - Print the predicted class

# Results

| Model_name     | Dataset       | No.of Classes | Resolution| Training sample| Validation Sample   | dataset Length| Accuracy|
| -------------  | ------------- | --------------|-----------|----------------|---------------------|---------------|---------|
| MobileNet_V2   | CINIC 10      | 10            | 32X32     | 9000            |9000                  | 27000          | 47%     |
| MobileNet_V2   | Cifar10       | 10            | 32X32     | 50000           |10000                 | 60000          | 58.36%  |
| MobileNet_V2   | Cifar100      | 100           | 32X32	   | 40000	         |10000	                |60000	         |33.11%   |
| MobileNet_V2   | Pets          | 23            | 224x224   | 3766	           |115	                  |3881 	         |94%      |
| MobileNet_V2   | DTD           | 47            | 224x224	 | 2961	           |329	                  |3290 	         |74%      |
| MobileNet_V2   | Flower102     | 102           | 224x224	 | 6552	           |818	                  |8927 	         |95.59%   |
| MobileNet_V2   | Air Craft     | 100           | 224x224	 | 3334	           |3333	                |10001	         |39%      |
| MobileNet_V2   |Food101	       |101	           |224x224	   |73629	           |8181	                |81807	         |66.76%   |
| MobileNet_V2   | Cars	         |196	           |224x224    |8144             |8041	                |16185	         |52.00%   |
| MobileNet_V2   | STL_10	       |10             |96x96      |4500             |500	                  |5000	           |87.2%    |
