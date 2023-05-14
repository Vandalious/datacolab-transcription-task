# DataCoLab Interview Task

This repository is for DataCoLab interview purposes-only.

The main notebook and the finalized dataframe are `main.ipynb` ~~and `to_fill_finalized.csv`~~ respectively.

~~The `topic_classification_BERT.ipynb` notebook was an attempted BERT training on Colab.~~


## UPDATE

The model used for predicting the topics has been now been updated to BERT. The training is done using `Hugging Face`'s Trainer API. The main notebook have now been updated to show the results of the BERT's predictions in the final cell, which can be compared with the `RandomForest` one. The performances are very close but by reducing the `Sigmoid Threshold` (explained in the BERT notebook), you can observe better results for predictions.

The `topic_classification_BERT.ipynb` notebook contains the full training code and predictions.

 **The final and best dataframe is now `to_fill_finalized_BERT.csv`**.
