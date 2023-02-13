# MobileNet_V2_Classification_Analysis


#Requirements

Python >= 3.7.x, PyTorch >= 1.13.0, torchvision.__version= 0.14

# Results

| Model_name     | Dataset       | No.of Classes | Resolution| Training sample| Validation Sample   | dataset Length| Accuracy|
| -------------  | ------------- | --------------|-----------|----------------|---------------------|---------------|---------|
| MobileNet_V2   | CINIC 10      | 10            | 32X32     | 9000           |9000                 | 27000         | 47%     |
| MobileNet_V2   | Cifar10       | 10            | 32X32     | 50000          |10000                | 60000         | 58.36%  |
| MobileNet_V2   | Cifar100      | 100           | 32X32	    | 40000	         |10000	               |60000	         |33.11%   |
| MobileNet_V2   | Pets          | 23            | 224x224   | 3766	          |115	                 |3881 	         |94%      |
| MobileNet_V2   | DTD           | 47            | 224x224	  | 2961	          |329	                 |3290 	         |74%      |
| MobileNet_V2   | Flower102     | 102           | 224x224	  | 6552	          |818	                 |8927 	         |95.59%   |
| MobileNet_V2   | Air Craft     | 100           | 224x224	  | 3334	          |3333	                |10001	         |39%      |
| MobileNet_V2   |Food101	       |101	           | 224x224	  | 73629	         |8181	                |81807	         |66.76%   |
| MobileNet_V2   | Cars	         |196	           | 224x224   | 8144           |8041	                |16185	         |52.00%   |
| MobileNet_V2   | STL_10	       |10             | 96x96     | 4500           |500	                 |5000	          |87.2%    |
