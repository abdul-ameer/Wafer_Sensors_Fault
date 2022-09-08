# What is Wafer sensors ??

The inputs of various sensors for different wafers have been provided. In electronics, a wafer (also called a slice or substrate) is a thin slice of semiconductor used for the fabrication of integrated circuits. The goal is to build a machine learning model which predicts whether a wafer needs to be replaced or not(i.e., whether it is working or not) based on the inputs from various sensors. There are two classes: +1 (working condition) and -1 (Not working to replace)


# Architecture

The pipeline of a project below image

![image](https://user-images.githubusercontent.com/67822092/129449507-c939db3b-b696-4650-b2be-5c9d4ef9814d.png)

# Demo

- This repository represents **" Wafer Fault in Sensors "**.
- With the help of this project we can detect the Wafer Fault on  **Different Sensors**.
- "-1" represents Good "1" represents Bad Wafer check below image
 
![Screenshot_20210816_152230_2](https://user-images.githubusercontent.com/67822092/129545886-131db174-953a-48d8-9881-c718b94d0c96.jpg)


  
## 📝 Description

- In this project we have used **KMEANS**, **RANDOM FOREST** and **XGBOOST** for Fault Detection.

## ⏳ Dataset
- Download the dataset for custom training
- https://github.com/ameerkings123/Wafer_Sensors_Fault/tree/main/Training_Batch_Files
- Download the file and Place it into **" Training_Batch_Files/ ".** folder.

## :desktop_computer:	Installation Setup
1.Clone or download the repo.<br>
2.Open command prompt in the downloaded folder.<br>
3.Create a virtual environment

```bash
$ pip install virtualenv
```
```bash
$ virtualenv environment_name
```
Install dependencies :-
```bash
$ pip install -r requirements.txt
```
Run the application:
```bash
python main.py
```

### :book: Please Go through [LLD Documents](https://github.com/ameerkings123/Wafer_Sensors_Fault/tree/main/LLD) for more info.


## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25> 
- ABDUL AMEER NABILLA





