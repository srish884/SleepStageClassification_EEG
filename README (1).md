
# Sleep stage classification from polysomnography (PSG) data




## Dataset Used

The dataset used in this project can be easily accessed and downloaded from the link given below:

https://www.physionet.org/content/sleep-edfx/1.0.0/#files-panel
##  Summary

Polysomnography (PSG) data is a valuable source of information for sleep stage classification. PSG is a type of sleep study that records physiological signals during sleep, such as EEG, EOG, EMG, and ECG. These signals can be used to classify sleep stages based on the characteristic patterns of activity seen in each stage.

There are several approaches to sleep stage classification using PSG data, ranging from simple rule-based methods to more complex machine learning algorithms. One popular approach is to use spectral features extracted from the EEG signals to train a classifier, such as a support vector machine (SVM) or a random forest classifier.

The first step in the process is to preprocess the PSG data. This typically involves filtering the signals to remove noise and artifacts, as well as segmenting the data into epochs of fixed duration (e.g., 30 seconds) that correspond to different sleep stages. The next step is to extract features from the segmented data, such as the power spectral density (PSD) of the EEG signals in specific frequency bands. These features are then used to train a classifier to predict the sleep stage for each epoch.

There are several metrics that can be used to evaluate the performance of a sleep stage classifier, such as accuracy, sensitivity, specificity, and Cohen's kappa. However, it's important to note that the choice of metric may depend on the specific application and the goals of the study.

Overall, sleep stage classification from PSG data is an important task in sleep medicine, as it provides valuable information about the quality and quantity of sleep in patients with sleep disorders, as well as in healthy individuals.





