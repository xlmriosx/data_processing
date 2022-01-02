# Numerical data scaling

Data set: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

### Linear transformation
#### Normalize
##### Normalize with max-min

![image](https://user-images.githubusercontent.com/78567418/147889844-0de14a58-db50-4d61-8f12-f4761b10792f.png)

##### Normalize with Z-Score

![image](https://user-images.githubusercontent.com/78567418/147889847-821f6ecf-c45c-4c7d-8f3b-f62819adfc29.png)

##### Normalize with raw

![image](https://user-images.githubusercontent.com/78567418/147889838-ad895d59-65c3-4898-8390-6ea2adbfcc0e.png)

#### Calculate time to normalize models.

![image](https://user-images.githubusercontent.com/78567418/147889938-5cd19855-9ece-45d9-aada-acb2743e0387.png)

· max-min scaling: best for evenly distributed data
· Z-score scale: best for "normally" distributed data (gaussian bell shape)

Tools of Scikit Learn : https://scikit-learn.org/stable/modules/preprocessing.html

### No linear transformation.
#### Histogram by price.

![image](https://user-images.githubusercontent.com/78567418/147889984-511757bc-0afd-45d7-9402-282f4cd00804.png)

### Histogram apply tan(1/x)

![image](https://user-images.githubusercontent.com/78567418/147890016-1b502ad1-d4f7-445e-93fe-b1bc29f4cbf4.png)

· mapping data to a gaussian distribution: https://scikit-learn.org/stable/auto_examples/preprocessing/plot_map_data_to_normal.html#sphx-glr-auto-examples-preprocessing-plot-map-data-to-normal-py
