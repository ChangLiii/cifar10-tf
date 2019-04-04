# cifar10-tf
12/01/2018 cifar10 classification homework

Step1:
Modify input and output file paths according to your local paths.

Step2:
Do data preprocessing work in utils.py. Run the script with ‘python utils.py’. After this, training set, validation set, and test set should be saved in npy form.

Step3:
Experiment with hog+svm classifier. Change all the file path in the script if needed, and then run the script with ‘python hog_svm.py’.

Step4:
Experiment with both deep learning methods. Six networks (from two methods) are implemented in network.py. Modify the string net_name in config.py to test on different networks. You can also choose a different GPU or tune the hyper-parameters in config.py. After this, run “python main.py”, a model will be trained and tested.
