[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/LOuMvgtV)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11524743&assignment_repo_type=AssignmentRepo)
# MAST30034 Project 1 README.md
- Name: `William Conlon`
- Student ID: `1168993`

**Research Goal:** My research goal is finding what the most profitable trips for taxi drivers to take are.

**Timeline:** The timeline for the research area is from July to December 2022.

To run the pipeline, please visit the `notebooks` directory and run the files in order:
1. `Get_Data_Yellow.ipynb`: This downloads the raw TLC data into the `data/raw` directory.
2. `Yellow_Preprocessing.ipynb` and `Weather_Preprocessing.ipynb`: These notebook details all preprocessing steps for the TLC and weather data and outputs it to the `data/landing` directory.
3. `Yellow_Feature_Engineering.ipynb`: This notebook creates features for the TLC data abnd outputs it to the `data\curated` directory.
4. `Analysis.ipynb`: This notebook is used to conduct analysis on the curated data.
5. `Model.ipynb`: The notebook is used for creating and analysing the model.
