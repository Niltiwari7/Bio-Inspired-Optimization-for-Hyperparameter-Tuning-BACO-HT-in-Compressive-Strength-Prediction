# Capctone
Capctone all ml algo

Here's a table categorizing **ensemble** and **non-ensemble** machine learning algorithms which we have implemented  comparative analysis:

| **Category**              | **Algorithm**                                                                                     | **Type**            | **Key Features**                                                                                             |
|---------------------------|-------------------------------------------------------------------------------------------------|---------------------|-------------------------------------------------------------------------------------------------------------|
| **Non-Ensemble Algorithms** |                                                                                                 |                     |                                                                                                             |
|                           | **Linear Regression**                                                                           | Regression          | Simple model, assumes linear relationship between features and target.                                     |
|                           | **Ridge Regression** / **Lasso Regression**                                                     | Regression          | Adds regularization to linear regression to reduce overfitting.                                            |
|                           | **Support Vector Regressor (SVR)**                                                              | Regression          | Effective for high-dimensional data, uses kernels for non-linear patterns.                                 |
|                           | **K-Nearest Neighbors (KNN)**                                                                   | Instance-Based      | Simple, works well for small datasets, distance-based prediction.                                          |
|                           | **Decision Tree (DT)**                                                                          | Tree-Based          | Splits data based on feature thresholds, interpretable but prone to overfitting.                           |
|                           | **Multivariate Polynomial Regression**                                                          | Regression          | Captures non-linear relationships by including polynomial features.                                        |
|                           | **Neural Network (NN)**                                                                         | Neural Network      | Highly flexible, works for non-linear relationships, requires significant computational resources.         |
|                           |                                |
|                           | **Data Envelopment Analysis (DEA)**                                                             | Linear Programming  | Measures the efficiency of decision-making units, not predictive but useful for comparisons.               |
| **Ensemble Algorithms**    |                                                                                                 |                     |                                                                                                             |
|                           | **Random Forest (RF)**                                                                          | Bagging             | Combines multiple decision trees using bootstrapping for stability and accuracy.                           |
|                           | **Extra Trees (ET)**                                                                            | Bagging             | Variant of RF with more random splits for higher variance reduction.                                       |
|                           | **Bagging Regressor**                                                                           | Bagging             | General framework for bagging with customizable base learners.                                             |
|                           | **Gradient Boosting Regression Tree (GBRT)**                                                   | Boosting            | Combines weak learners sequentially to minimize residual errors.                                           |
|                           | **Extreme Gradient Boosting (XGBoost)**                                                        | Boosting            | Optimized gradient boosting with regularization and GPU support.                                           |
|                           | **LightGBM (Light Gradient Boosting Machine)**                                                 | Boosting            | Faster than XGBoost, handles large datasets with high performance.                                         |
|                           | **CatBoost**                                                                                   | Boosting            | Gradient boosting optimized for categorical data.                                                          |
|                           | **AdaBoost**                                                                                   | Boosting            | Sequentially trains models by focusing on incorrectly predicted instances.                                 |
|                           | **Stacking Regressor**                                                                          | Stacking            | Combines multiple base models (e.g., RF, XGBoost) with a meta-learner for improved predictions.            |
|                           | **Voting Regressor**                                                                            | Voting              | Combines predictions of multiple models by averaging.                                                      |
|                           | **Genetic Expression Programming (GEP)**                                                       | Evolutionary        | Applies genetic algorithms to evolve predictive models.                                                    |
|                           





#### All the dependency requirement
```markdown
# Installed Packages and Versions

| Package                | Version   |
|------------------------|-----------|
| absl-py                | 2.1.0     |
| anfis                  | 0.3.1     |
| anyio                  | 3.5.0     |
| argon2-cffi            | 20.1.0    |
| astor                  | 0.8.1     |
| attrs                  | 22.1.0    |
| backcall               | 0.2.0     |
| beautifulsoup4         | 4.11.1    |
| bleach                 | 4.1.0     |
| catboost               | 1.2.7     |
| category-encoders      | 2.6.4     |
| certifi                | 2024.2.2  |
| cffi                   | 1.15.1    |
| charset-normalizer     | 3.3.2     |
| click                  | 8.1.8     |
| cloudpickle            | 2.2.1     |
| colorama               | 0.4.6     |
| cycler                 | 0.11.0    |
| debugpy                | 1.5.1     |
| decorator              | 5.1.1     |
| defusedxml             | 0.7.1     |
| easyocr                | 1.7.1     |
| entrypoints            | 0.4       |
| fastjsonschema         | 2.16.2    |
| fonttools              | 4.38.0    |
| gast                   | 0.5.4     |
| google-pasta           | 0.2.0     |
| graphviz               | 0.20.1    |
| grpcio                 | 1.42.0    |
| h5py                   | 2.10.0    |
| idna                   | 3.4       |
| imageio                | 2.31.2    |
| importlib-metadata     | 4.11.4    |
| importlib-resources    | 5.12.0    |
| imutils                | 0.5.4     |
| ipykernel              | 6.15.2    |
| ipython                | 7.31.1    |
| ipython-genutils       | 0.2.0     |
| jedi                   | 0.18.1    |
| Jinja2                 | 3.1.2     |
| joblib                 | 1.3.2     |
| jsonschema             | 3.0.2     |
| jupyter_client         | 7.4.9     |
| jupyter_core           | 4.11.2    |
| jupyter-server         | 1.23.4    |
| jupyterlab-pygments    | 0.1.2     |
| kaggle                 | 1.6.17    |
| keras                  | 2.11.0    |
| Keras-Applications     | 1.0.8     |
| Keras-Preprocessing    | 1.1.2     |
| kiwisolver             | 1.4.5     |
| lightgbm               | 4.5.0     |
| Markdown               | 3.5.2     |
| MarkupSafe             | 2.1.1     |
| matplotlib             | 3.5.3     |
| matplotlib-inline      | 0.1.6     |
| mistune                | 0.8.4     |
| nbclassic              | 0.5.2     |
| nbclient               | 0.5.13    |
| nbconvert              | 6.4.4     |
| nbformat               | 5.5.0     |
| nest-asyncio           | 1.5.6     |
| networkx               | 2.6.3     |
| ninja                  | 1.11.1.1  |
| nltk                   | 3.8.1     |
| notebook               | 6.5.2     |
| notebook_shim          | 0.2.2     |
| numpy                  | 1.21.6    |
| opencv-python          | 4.9.0.80  |
| opencv-python-headless | 4.9.0.80  |
| packaging              | 22.0      |
| pandas                 | 1.3.5     |
| pandocfilters          | 1.5.0     |
| parso                  | 0.8.3     |
| patsy                  | 1.0.1     |
| pickleshare            | 0.7.5     |
| Pillow                 | 9.5.0     |
| pip                    | 24.0      |
| plotly                 | 5.18.0    |
| prometheus-client      | 0.14.1    |
| prompt-toolkit         | 3.0.36    |
| protobuf               | 3.20.3    |
| psutil                 | 5.9.0     |
| pyclipper              | 1.3.0.post5 |
| pycparser              | 2.21      |
| pygad                  | 3.4.0     |
| Pygments               | 2.11.2    |
| pyparsing              | 3.1.2     |
| pyreadline             | 2.1       |
| pyrsistent             | 0.18.0    |
| python-bidi            | 0.4.2     |
| python-dateutil        | 2.8.2     |
| python-slugify         | 8.0.4     |
| pytz                   | 2024.2    |
| PyWavelets             | 1.3.0     |
| pywin32                | 305.1     |
| pywinpty               | 2.0.10    |
| PyYAML                 | 6.0.1     |
| pyzmq                  | 23.2.0    |
| regex                  | 2024.4.16 |
| requests               | 2.31.0    |
| scikit-fuzzy           | 0.5.0     |
| scikit-image           | 0.19.3    |
| scikit-learn           | 1.0.2     |
| scipy                  | 1.7.3     |
| seaborn                | 0.12.2    |
| Send2Trash             | 1.8.0     |
| setuptools             | 65.6.3    |
| shapely                | 2.0.3     |
| six                    | 1.16.0    |
| sniffio                | 1.2.0     |
| soupsieve              | 2.3.2.post1 |
| statsmodels            | 0.13.5    |
| tenacity               | 8.2.3     |
| tensorboard            | 1.14.0    |
| tensorflow             | 1.14.0    |
| tensorflow-estimator   | 1.14.0    |
| termcolor              | 2.2.0     |
| terminado              | 0.17.1    |
| testpath               | 0.6.0     |
| text-unidecode         | 1.3       |
| threadpoolctl          | 3.1.0     |
| tifffile               | 2021.11.2 |
| torch                  | 1.13.1    |
| torchvision            | 0.14.1    |
| tornado                | 6.2       |
| tqdm                   | 4.67.1    |
| traitlets              | 5.7.1     |
| typing_extensions      | 4.5.0     |
| urllib3                | 2.0.7     |
| wcwidth                | 0.2.5     |
| webencodings           | 0.5.1     |
| websocket-client       | 0.58.0    |
| Werkzeug               | 2.1.2     |
| wheel                  | 0.42.0    |
| wrapt                  | 1.14.1    |
| xgboost                | 1.6.2     |
| zipp                   | 3.7.0     |
```

You can copy and paste this into a Markdown file (e.g., `packages.md`) for sharing or documentation.