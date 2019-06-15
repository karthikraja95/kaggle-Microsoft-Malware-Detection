# Microsoft Malware Detection

## Problem Statement:

In the past few years, the malware industry has grown very rapidly that, the syndicates invest heavily in technologies to evade traditional protection, forcing the anti-malware groups/communities to build more robust softwares to detect and terminate these attacks. The major part of protecting a computer system from a malware attack is to <b> identify whether a given piece of file/software is a malware.</b>

## Data:

Microsoft has been very active in building anti-malware products over the years and it runs it’s anti-malware utilities over 150 million computers around the world. This generates tens of millions of daily data points to be analyzed as potential malware. In order to be effective in analyzing and classifying such large amounts of data, we need to be able to group them into groups and identify their respective families. 

This dataset provided by Microsoft contains about 9 classes of malware. 

Source: https://www.kaggle.com/c/malware-classification

## Business Objectives & Constraints:

1. Minimize multi-class error.
2. Multi-class probability estimates.
3. Malware detection should not take hours and block the user's computer. It should fininsh in a few seconds or a minute.

### There are nine different classes of malware that we need to classify a given a data point => Multi class classification problem    

## Performance Metric:

Source: https://www.kaggle.com/c/malware-classification#evaluation

Metric(s):

1. Multi class log-loss
2. Confusion matrix
