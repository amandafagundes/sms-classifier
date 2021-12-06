## SMS Classifier

The dataset used in this project consists of 5.574 text messages, where 747 are spam. Applying pre-processing techniques and using TF-IDF representation, the text vectors are used as input for three different classification models: Random Forest, Linear Regression and SVM which were tunned using the ``GridSearchCV`` method.

In the end, the SVM model achieved the best performance, with 98% of accuracy and 93% for F1-Score.

The PDF file is a mini paper where the methodology is explained.

### Running the code

To execute the developed code, you need to have the Jupyter Notebook installed on your machine and then, inside the repository folder, run the ``jupyter notebook`` command.

Most libraries used in this project are present at Anaconda and Google Colab environments.