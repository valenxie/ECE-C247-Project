# ECE-C247-Project
This project aims to evaluate and compare the performance of Convolutional Neural Network (CNN), Convolutional Recurrent Neural Network (CRNN), and Transformers when classifying electroencephalography (EEG) data based on four different motor imagery tasks, which are the imagination of movement of the left hand (class 1), right hand (class 2), both feet (class 3), and tongue (class 4) [1]. In each model, we tested whether training all subjects instead of only one subject will improve the classification accuracy for that subject. We found out that the performance of CNN and CRNN is similar while the test accuracy of the Transformer is much lower. Additionally, we evaluated the classification accuracy as a function of time on three models. We divided the time period into 2 groups based on the data visualization since the image is relatively identical after the 500 time period, and then evaluated the accuracies with different group increments. Among the first 500 time periods, all models generated the best results around the same period, while this period varies among the last 500 time periods.
