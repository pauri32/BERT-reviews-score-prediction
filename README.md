# BERT-reviews-score-prediction
Prediction of Amazon's reviews rating using a BERT model.

Structure of the project:
* **bertconfig**: Configuration of the pre-trained BERT model, downloaded from Hugging Face ([link](https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip)).
* **amazon-cell-phones-reviews**: Dataset from Griko Nibras shared on Kaggle ([link](http://https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews?select=20191226-reviews.csv)).
* **nlp-project.ipynb**: Notebook with the project.

## How to run the code

1) Download the files, including the *bertconfig* and *amazon-cell-phones-reviews* directories. **ATTENTION:** To complete the *bertconfig* directory it is required an extra file that has to be downloaded from the ([link](https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip)), as it exceeds the size limits of GitHub.

2) Open the notebook with a Python environment. It is recommended to open it using Kaggle notebooks, as Conda is installed by defult and does not require any further installation. Kaggle notbooks was the cloud platform used for this development.

3) Check the installation of the packages listed in the first cell.

4) Run the cells sequentially, preferably using an accelerator, such as a GPU.


## How to run the code

This project was created using Kaggle notebooks: ([BERT Amazon's reviews prediction](https://www.kaggle.com/paurodrguezinserte/reviews-prediction))


*Project developed for the NLP course of Intelligent Systems (Universidad Politécnica de Madrid)*
