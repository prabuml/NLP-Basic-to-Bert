# NLP-Basic-to-Bert


The Repository compares different model for the text classification 

### Dataset Set:

The dataset used here is stolen from kaggle dataset.[Link](https://www.kaggle.com/bittlingmayer/amazonreviews)
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


###
| Notebooks  | Functionality |
| ------------- | ------------- |
| Extract_data.ipynb  | Download the data from kaggle data  |
| Basic_Data_analyst.ipynb  | Perform the basic text data analysis   |
| LinearSVM_Basic.ipynb  | Experiment with basic linear svm model  |
| LinearSvm_Glovefeatures.ipynb  | Experiment with linear svm model with glove features  |
| LinearSVM_Bert.ipynb  | Experiment with linear svm model with bert features  |
| Basic_lstm_glove_features.ipynb  | Experiment with basic lstm model with glove features  |
| Ulmfit.ipynb  | Experiment with ulmit model  |
| Bert.ipynb  | Experiment with bert model  |



 




