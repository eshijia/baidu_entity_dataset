# Dataset for Entity Search

The dataset comes from [Baidu Cup' 16](http://nlpcc.baidu.com). It consisits of four kinds of entity search datasets, i.e., tvShow, movie, restaurant, and celebrity.

- .ENTITYSET.txt: This file contains all entity candidates for a specific entity type. One entity per line.
- .TRAINSET.txt: This file contains 100 training samples. Each line is a entity search query with ~100 entity candidates. Part of them are correct (denoted with 1), and the others are incorrect (denoted with 0). 
- .GROUNDTRUTH.txt: This file contains the test data. The file format is same as the training set.

The file encoding is gb18030. 