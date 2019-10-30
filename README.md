# Team Project

## Validating Deep Neural Networks for Online Decoding of Motor Imagery Movements from EEG Signals
- **Article**: https://www.mdpi.com/1424-8220/19/1/210/htm
- **Github**: https://github.com/gumpy-bci/gumpy-deeplearning/tree/master/models
- **Data**: http://gumpy.org/
- **Summary**: Decoding motor imagery.  Used three deep learning models 1) A long short-term memory (LSTM); (2) a spectrogram-based convolutional neural network model (CNN); and (3) a recurrent convolutional neural ne$twork (RCNN).  Did not use feature engineering.
- **Preprocessed**: Gumpy gives a the data!  It also gives a lot of code to preprocess
- **Notebook**: https://colab.research.google.com/drive/12YtbtCF7jbqUk_Rtz38ZkS-94V-EtGGP 
- **Cons**: None so far!
- **Pros**: Seems like a great paper!  Very clear and has all the data, code.

### Notes:

Preprocessing consists of: 
- Band-pass filtering the data in frequency range from %.1f Hz to %.1f Hz
- Segmentation of trials
- Concatenating data for training and create labels
- Runs an automated statistical thresholding for EEG artifact rejection
