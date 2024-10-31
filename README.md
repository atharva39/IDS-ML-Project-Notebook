# Intrusion Detection System (IDS) Project

## Overview
This project implements an Intrusion Detection System using machine learning techniques. It allows users to customize the dataset for training the model.

## Requirements
Make sure to install the required packages before running the project. You can do this by using the following command:

```bash
pip install -r requirements.txt # Windows
```
```bash
pip3 install -r requirements.txt # macOS
```

## How to Run the Code
Change Features File (Cell 1)
Edit the features.txt file path in Cell 1 to match the location of your dataset's features file.

Edit Columns (Cell 2)
Modify the column names in Cell 2 according to your dataset's structure. Ensure that the columns you specify match those in your dataset.

Read Training Attack Types (Cell 3)
In Cell 3, read the training_attack_types file as per your dataset. Adjust the file path if necessary.

Create a Dictionary (Cell 4)
In Cell 4, create a dictionary based on your dataset's attack types. This dictionary will be used to map attack types to their respective labels.

Change Dataset (Cell 5)
In Cell 5, specify the dataset you want to use for training. Ensure the dataset is in the correct format and accessible by the script.

## How to Execute the Code
To execute the code, follow these steps:

Open the Jupyter Notebook or Python script where your IDS implementation resides.
Run each cell in order, starting from Cell 1 through Cell 5, making sure to adjust any parameters as specified in the previous section.
Monitor the output for any errors or logs to ensure everything runs smoothly.
