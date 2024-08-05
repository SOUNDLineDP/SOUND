# SOUND
To optimize efforts in Software Quality
 Assurance activities, we propose a novel Code-line-level defect prediction (CLDP) method,
 Spectrum infOrmation and caUsality aNalysis based coDe-line
level defect prediction (SOUND).

This is the source code for the paper "Boosting Code-line-level Defect Prediction with
 Spectrum Information and Causality Analysis".

## Datasets
[`/dataset`](/dataset/) stores all 19 projects.

The file-level datasets (in [`/dataset/File-level`](/dataset/File-level/)) contain the following columns:
- `File` : A file name of source code
- `Bug` : A label indicating whether source code is clean or defective
- `SRC` : A content in source code file

The line-level datasets (in [`/dataset/Line-level`](/dataset/Line-level/)) contain the following columns

- `File` : A file name of source code
- `Line_number` : A line number where source code is defective
- `SRC` :  A content in source code line
## Environment Setup
1. clone the github repository by using the following command:

```
git clone https://github.com/SOUNDLineDP/SOUND.git
```
2. use the following command to install required libraries in conda environment:

```
 conda env create -f requirements.yml
 conda activate causal_research
```
## Experiment

