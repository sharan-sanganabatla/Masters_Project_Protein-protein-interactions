To run this project, you must need a dataset specified in the format of begin.csv I.e.,

Human sequence.        Pathogen Sequence.          Interaction


Any dataset in this format can be given as input to preprocessing.ipynb file which generates required files. Then you can use generate_datasets.ipynb and 5F_CROSSVAL_DATA_GENERATOR.ipynb to generate multi-dimensional files for both test and training set as well as 5 Fold cross_validation data.


Make sure to include these files in the same folder of the code or adjust the path of these files inn the code before executing the models.

The sample Influenza data used for the project is present in the Data folder.

When all the above are followed, you can directly execute the models with the desired dataset.




