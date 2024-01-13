## Installation

We need to set up our local environment to programming using python , here :

- Install and navigate through the Anaconda [Anaconda Installer](https://www.anaconda.com/download/) .

- Setup and manage the environments.

  ```conda create -n env_name```

   To access this environment through the command line : ```conda activate env_name```

   To check for the Python packages : ```conda list```

- Download Python packages in Anaconda Terminal (we can use pip or conda interchangeably).

  ```pip install pandas```

   ```pip install numpy```

   ```pip install matplotlib```

   ```pip install seaborn```

  **OR**

  Install multiple packages at the same time. For example, the command below will install all three packages simultaneously.

  ```conda install pandas numpy matplotlib seaborn```

- Install Jupyter Notebooks.

  ```conda install jupyter notebook```

## Coding

-  Python Integrated Development Environment (IDE) : Jupyter Notebooks.

   **Packeges used**
   
* **pandas - numby** : used for data manipulation.
* **matplotlib - seaborn** : used for data visualization.

**NOTE** : to run the slid deck in Jupyter Notebooks : 

```!jupyter nbconvert Explanatory_Analysis_Slide_Deck.ipynb --to slides --post serve --no-input --no-prompt```


## About The Dataset

- There are **183,412** observations and **16** features.
- Data source stored as ZIP file and can be accessed through this link : [Dataset](https://github.com/hayasalman/Ford-GoBike-System-Data-Analysis/blob/main/fordgobike_tripdata.zip)




