# Rock vs Mine Prediction

## Description
The dataset has 208 rows with 61 columns.

All the columns values are float64 except the target variable which is object

Target varible has unique `'R'` -> Rock and `'M'` -> Mine

## Project Structure
project/

├── data/ # Dataset

├── notebooks/ # Jupyter notebooks

├── src/ # Source code

├── requirements.txt # Dependencies

└── README.md # This file

## Results
1. *Accuracy Score* - 88%
2. *Confusion Matrix*
	- 22 correctly predicted mines
	- 15 correctly predicted rocks
	- 4 mines predicted as rocks
	- 1 rock predicted as mine
