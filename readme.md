## BLSTM for Estimating cooking time for a given recipe

Please install the required packages before running the code

- tensorflow (Keras libraries)
- scikit-learn
- pandas
- plotly

This zip files contains 4 ```.ipynb```  files according to the list below 

- ```vec50&main_eval.ipynb``` consists of initial data virtualizations, classification models for Doc2vec-50 inputs data, diagnostic graphs during hyperparameter tuning, and classification reports.

- ```vec100_eval.ipynb``` consists of classification models for Doc2vec-100 inputs data, and diagnostic graphs during hyperparameter tuning, and classification reports.

- ```chi2.ipynb``` consists of initial classification models for ```.npz``` inputs data, 100-best feature selection, diagnostic graphs during hyperparameter tuning, and classification reports.

- ```chi2.ipynb``` consists of initial classification models for ```.npz``` inputs data, 300-best feature selection, diagnostic graphs during hyperparameter tuning, and classification reports.


The zip file also contains the ```.csv``` ouput files in the ```./csv_result``` directory, where they are format as follow


``` Python
<Model>_y_pred_<feature extraction/selection methods>
```