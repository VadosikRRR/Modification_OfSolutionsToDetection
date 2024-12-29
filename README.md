# Modification of solutions to the detection problem

## Requirements

- numpy               >=1.23.0
- numpy               <2.0.0; sys_platform == "darwin"
- matplotlib          >=3.3.0
- opencv-python       >=4.6.0
- pillow              >=7.1.2
- pyyaml              >=5.3.1
- requests            >=2.23.0
- scipy               >=1.4.1
- torch               >=1.8.0
- torch               >=1.8.0; sys_platform == "win32"
- torchvision         >=0.9.0
- tqdm                >=4.64.0
- psutil              5.9.3
- py-cpuinfo          9.0.0
- pandas              >=1.1.4
- seaborn             >=0.11.0
- ultralytics-thop    >=2.0.0

## Guide

It is recommended to use kaggle with GPU, google colab with GPU or computer with GPU.

### How to install and run

### On kaggle:

Create or sing in an account on kaggle.
Download "ModificationOfSolutionsToDetection.ipynb" from notebook folder in GitHub.
Create new notebook and import "ModificationOfSolutionsToDetection.ipynb".
Add dataset "Animals Detection Images Dataset", URL = "https://www.kaggle.com/datasets/antoreepjana/animals-detection-images-dataset".
Run the first cell (for kaggle). After run all after three.

### On Google colab:

#### Step 1: Download kaggle.json.

Create or sign in an account on kaggle.
Go to the "settings" section.
Find "Api" and click "Create new token".

#### Step 2: Notebook preparation.

Create or sing in account on google.
Download "ModificationOfSolutionsToDetection.ipynb" from notebook folder in GitHub.
Create new notebook and import "ModificationOfSolutionsToDetection.ipynb".

#### Step 3: Run notebook.

Run the second cell (for google colab). After run all after three.

### On computer:

#### Step 1: Download kaggle.json.

Create or sign in an account on kaggle.
Go to the "settings" section.
Find "Api" and click "Create new token".

#### Step 2: Clone the repository:

```bash
git clone https://github.com/VadosikRRR/Modification_OfSolutionsToDetection.git
```

#### Step 3: install kaggle and send kaggle.json.
Open ModificationOfSolutionsToDetection in notebook folder.
Run the third cell.
It will give you an error. Move kaggle.json to the specified path.

#### Step 4: Run notebook
Run the third cell again. After run all after three.