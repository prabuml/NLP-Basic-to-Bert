# NLP-Basic-to-Bert


The Repository compares different model for the text classification 

### Dataset Set:

The dataset used here is stolen from [kaggle dataset](https://www.kaggle.com/bittlingmayer/amazonreviews)
This dataset comprises of millions of amazon reviews with sentiment labels. 
The dataset is restricted to 50000 in train and test data in the study to get quicker result in google colab.  
		

### Summary of different models with accuracy 
| Model  | Accuracy |
| ------------- | ------------- |
| Linear SVM with tfidf features  | 89%  |
| Linear SVM with glove featues  | 83%  |
| Linear SVM with bert features  | 88%  |
| LSTM with glove featues  | 90%  |
| Ulmfit  | 93%  |
| Bert  | 95%  |



| Notebooks  | Functionality |
| ------------- | ------------- |
| Extract_data.ipynb  | Downloads the data from kaggle data  |
| Basic_Data_analyst.ipynb  | Performs the basic text data analysis   |
| LinearSVM_Basic.ipynb  | Experiments with basic linear svm model  |
| LinearSvm_Glovefeatures.ipynb  | Experiments with linear svm model with glove features  |
| LinearSVM_Bert.ipynb  | Experiments with linear svm model with bert features  |
| Basic_lstm_glove_features.ipynb  | Experiments with basic lstm model with glove features  |
| Ulmfit.ipynb  | Experiment with ulmit model  |
| Bert.ipynb  | Experiments with bert model  |


### Setup
Can be directly run in google colab or laptop or cloud </br>
Required Libraries are installed in Notebook

### References
https://github.com/alohia/pytorch_playground <br />
https://github.com/SudalaiRajkumar/DHS2019_HackSession_NLP <br />
https://www.kaggle.com/bminixhofer/simple-lstm-pytorch-version <br />
https://github.com/prrao87/tweet-stance-prediction <br />
 




