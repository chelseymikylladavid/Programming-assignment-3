# 🚗 Pandas Data Analysis Project

## 📌 Project Overview

This project demonstrates data analysis using **Python** and
**Pandas**.\
The dataset `cars.csv` contains information about different car models,
including attributes such as cylinders (`cyl`) and gears (`gear`).

The analysis is divided into two Jupyter Notebooks:\
- **David_Pandas-P1.ipynb** → Basic data exploration and filtering\
- **David_Pandas-P2.ipynb** → Extended analysis and advanced queries

------------------------------------------------------------------------

## 📂 Files in this Repository

-   `cars.csv` → The dataset used in this project\
-   `David_Pandas-P1.ipynb` → Notebook with initial analysis\
-   `David_Pandas-P2.ipynb` → Notebook with further analysis\
-   `README.md` → Project documentation

------------------------------------------------------------------------

## ⚙️ Requirements

Make sure you have the following installed:\
- Python 3.x\
- Jupyter Notebook or JupyterLab\
- Pandas library

You can install dependencies with:

``` bash
pip install pandas jupyter
```

------------------------------------------------------------------------

## ▶️ How to Run

1.  Clone or download this repository\

2.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

3.  Open `David_Pandas-P1.ipynb` or `David_Pandas-P2.ipynb`\

4.  Run the cells step by step to explore the dataset

------------------------------------------------------------------------

## 📊 Example Usage

Filtering cars by model:

``` python
selected_models = ['Mazda RX4 Wag', 'Ford Pantera L', 'Honda Civic']
result = f[f['Model'].isin(selected_models)][['Model', 'cyl', 'gear']]
print(result)
```

------------------------------------------------------------------------

## ✨ Author

Created by **David** -- Pandas Practice Project
