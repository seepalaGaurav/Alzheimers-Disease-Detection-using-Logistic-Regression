# Alzhiemers-Disease-Detection-using-Logistic-Regression

STEP-1:
Open the MATLAB code files to train the models by selecting the duseased cluster(inside IMAGES DATABASE folder).
They are:
1)data_train_Alzheimer_MildDemented
2)data_train_Alzheimer_ModeratedDemented
3)data_train_Alzheimer_VeryMildDemented
4)data_train_Alzheimer_NonDemented

Reference image 1:
![data train image](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/b800d558-4e6c-4b72-8404-55169bc2e1ef)

STEP-2:
As a result .mat files are generated(inside IMAGES DATABASE folder).
They are:
1)Alzheimer_MildDemented
2)Alzheimer_ModeratedDemented
3)Alzheimer_VeryMildDemented
4)Alzheimer_NonDemented

STEP-3:
Now execute 'Train_final_save_Alzheimer' (inside IMAGES DATABASE folder) to combine all the .mat files into single file named 'Alzheimer_Training_Data'

STEP-4:
Execute "Detect_model_Grayscale"(outside IMAGE DATABASE).

Select the image from IMAGE DATABASE.
![Detect Model](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/99084a79-f4a0-4a18-a904-6eeb18be4b27)

Here I took MildDemented
![dataset](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/a743158a-3b0b-46df-b36d-34a8cf76db3d)

Here I chose 2nd image.
![data selection](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/d3597328-4b09-4bef-a514-c9b5ac767019)

The prompt will ask to select the disease cluster.
![data train image](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/b571f803-55eb-4dbb-91cb-7612f5503bd8)

After that the prompt will ask for the training percentage.
![training presentage](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/7ceadd7f-83dd-427b-9a31-63612d496846)

Finally the will find the disesse name correctly.
![result1](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/52a16e6d-ccd0-4bdf-ac94-75ac15f3db82)

The result metrics will be displayed
![metrics](https://github.com/SVSG21/Alzhiemers-Disease-Detection-using-Lohistic-Regression/assets/85582946/0f08900c-a05f-4fdd-a7dc-84b737c541f1)










