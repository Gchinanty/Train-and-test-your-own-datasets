# Train-and-test-your-own-datasets
This is a guidance about how to train and test your own datasets in CaffeNet and other neural network.
# Step one
Prepare your own train and test datasets.
1. You can download from http://www.image-net.org/.
2. Just gather your own datasets by yourself.
# Step two
Convert your datasets to lmdb format.
You can bash the following two scripts on the root of caffe. 
  1.  sh ./examples/myfile/create_filelish.sh
  2.  sh ./examples/myfile/create_lmdb.sh
# Step three
Calculate the mean of the datasets.
You can execute the following shell commond.
