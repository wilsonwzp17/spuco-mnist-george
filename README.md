# SpuCoMNIST assignment

This is my BigML coding assignment using [SpuCo](https://github.com/BigML-CS-UCLA/SpuCo). I started from
the official [SpuCoMNIST clustering quickstart](https://github.com/BigML-CS-UCLA/SpuCo/blob/master/quickstart/spuco_mnist/spuco_mnist_cluster.ipynb)
for the one-epoch ERM inference, the class-wise k-means on logits and the group-balanced retraining, and
from the [group-balance quickstart](https://github.com/BigML-CS-UCLA/SpuCo/blob/master/quickstart/spuco_mnist/spuco_mnist_group_balance.py)
for the 20-epoch SGD settings. The one-epoch model makes the clusters; the 20-epoch ERM is only a
baseline. The notebook works through seed 0 first, then repeats the comparison over 5 seeds and uses
the true groups as a reference.
