
## Code
* All of the main code for the project can be found in `main.ipynb`
* The following models can be found in the file:
    1. 0R Classifier
    2. K Nearest Neighbours (KNN)
    3. Support Vector Machine (SVM)
    4. Extreme Gradient Boosting (XGB)
    5. Random Forest (RF)

### How to Run
1. Run the following code sections. This is because the models are using and sharing helper functions from these sections.
  * Imports and Constants
  * Utility Functions
  * Preprocessing
  * Evaluation
2. Choose a model to be run and run that cell
   * Note that models will run slower if `CROSS_VAL` in the "Imports and Constants" section is set to `True`
3. Results for whatever model you run can be found in `csv_results` - the filename is printed at the end of any model's execution
4. You can also run the code blocks for Hyperparameter Tuning for the following models if wanted.
   * SVM
   * XGB
   * RF


## Kaggle Results
* Can be found in `/csv_results`
* Che naming convention of result files can be found in `get_filename` in the "Utility Functions" section of `main.ipynb`