# BERT-reviews-score-prediction
Prediction of Amazon's reviews rating using a BERT model.

Structure of the project:
* **bertconfig**: Configuration of the pre-trained BERT model, downloaded from Hugging Face ([link](https://huggingface.co/google/bert_uncased_L-12_H-768_A-12)).
* **amazon-cell-phones-reviews**: Dataset from Griko Nibras shared on Kaggle ([link](http://https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews?select=20191226-reviews.csv)).
* **nlp-project.ipynb**: Notebook with the project.

## How to run the code

1) Download the files, including the *bertconfig* and *amazon-cell-phones-reviews* directories.

2) Open the notebook with a Python environment. It is recommended to open it using Kaggle notebooks, as Conda is installed by defult and does not require any further installation. Kaggle notbooks was the cloud platform used for this development.

3) Check the installation of the packages listed in the first cell.

4) Run the cells sequentially, preferably using an accelerator, such as a GPU.


Project developed for the NLP course of Intelligent Systems (Universidad Politécnica de Madrid)
