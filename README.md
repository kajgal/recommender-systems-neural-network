# Neural Network Recommenders

Neural network recommenders with data pre-processing on real buisness hotel data.

Most of the code belongs to **[Piotr Zioło](https://github.com/PiotrZiolo)**, who teaches "Recommendation Systems" in the summer semester 2021/2022. My contribution was to complete the tasks in the indicated places.

---

### Project contains:

:heavy_check_mark: **Cases of data pre-processing that can be found in real business projects**

---

### Requirements:

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8.
2. Install [Visual Studio Code](https://code.visualstudio.com/docs/?dv=win) for comfortable working with jupyter notebooks
3. Open CMD and go to project folder where you can find env.yaml file - it contains information required to correctly create environment
4. Prepare your conda environment (instructions given for Windows 64bit)
```
conda env create --file env.yaml -n rs-nn-env python=3.8.0
```
5. Activate your newly created environment
```
conda activate rs-nn-env
```
6. Open main folder with Visual Studio Code
7. Install two extensions in Visual Studio Code: "Jupyter" and "Python"
8. Open desired .ipynb file and in the top-right side click "Select kernel" and choose your environment "rs-cb-env"
9. If Visual Studio Code will ask you to install ipykernel package, allow it and you are ready to go!
10. Start playing with the code!
---

### Package structure:

```
project_1_data_preparation.html
project_1_data_preparation.ipynb
project_2_recommender_and_evaluation.html
project_2_recommender_and_evaluation.ipynb
|   
+---data
|   \---hotel_data
|           hotel_data_interactions_df.csv
|           hotel_data_original.csv
|           hotel_data_preprocessed.csv
|           
+---data_preprocessing
|    | 	dataset_specification.py
|    |  data_preprocessing_toolkit.py
|    |  people_identifier.py
|
+---evaluation_and_testing
|   |   evaluation_measures.py
|   |   testing.py        
|           
+---recommenders
    |   amazon_recommender.py
    |   netflix_recommender.py
    |   recommender.py
    
```

Data, data_preprocessing, evaluation_and_testing, recommenders folders mostly contains pre-prepared code by mentioned author.

Main content is in project_1_data_preparation.ipynb and project_2_recommender_and_evaluation.ipynb notebooks.

---

### Results

![Results](./img/performance.png)

---
