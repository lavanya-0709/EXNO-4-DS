# EXNO:4-DS
# AIM:
To read the given data and perform Feature Scaling and Feature Selection process and save the
data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Scaling for the feature in the data set.
STEP 4:Apply Feature Selection for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE SCALING:
1. Standard Scaler: It is also called Z-score normalization. It calculates the z-score of each value and replaces the value with the calculated Z-score. The features are then rescaled with x̄ =0 and σ=1
2. MinMaxScaler: It is also referred to as Normalization. The features are scaled between 0 and 1. Here, the mean value remains same as in Standardization, that is,0.
3. Maximum absolute scaling: Maximum absolute scaling scales the data to its maximum value; that is,it divides every observation by the maximum value of the variable.The result of the preceding transformation is a distribution in which the values vary approximately within the range of -1 to 1.
4. RobustScaler: RobustScaler transforms the feature vector by subtracting the median and then dividing by the interquartile range (75% value — 25% value).

# FEATURE SELECTION:
Feature selection is to find the best set of features that allows one to build useful models. Selecting the best features helps the model to perform well.
The feature selection techniques used are:
1.Filter Method
2.Wrapper Method
3.Embedded Method

# CODING AND OUTPUT:
## Feature scaling:
![image](https://github.com/user-attachments/assets/c663fdde-b378-4fc6-b11b-cb700f7dea39) 
![image](https://github.com/user-attachments/assets/0cb19f5b-fad4-43e3-ad6b-aad1e16e0758)
![image](https://github.com/user-attachments/assets/244bc0eb-71ed-468d-9c98-90c5f71d1437)
![image](https://github.com/user-attachments/assets/3b10ce06-8688-4b93-8463-23f7a8812156)

## Standard scaling:
![image](https://github.com/user-attachments/assets/fef6e23b-e187-4d48-9972-bc1c6c6e5f35)
![image](https://github.com/user-attachments/assets/d138918d-036f-4484-b110-4f38ab369393)

## Min max scaling:
![image](https://github.com/user-attachments/assets/fc3e73d8-513c-42fb-8f57-703ff95e5cd0)

## Maximum absolute scaling:
![image](https://github.com/user-attachments/assets/018cf1d3-df68-4ee9-b321-86518569068b)
![image](https://github.com/user-attachments/assets/74e5eab8-9555-457a-9256-efa47794289b)

## Robust scaling:
![image](https://github.com/user-attachments/assets/8ba51c93-5662-48ce-b88a-5cd932193609)
![image](https://github.com/user-attachments/assets/57802f0e-3081-4a15-b093-ebce2cf90b47)

## Feature scaling:
![image](https://github.com/user-attachments/assets/ed3e7031-c8a9-4847-a762-d38567941cab)
![image](https://github.com/user-attachments/assets/8260f962-dfa2-4bc5-9cb8-589ad59a7109)
![image](https://github.com/user-attachments/assets/00e76a7b-47ee-4329-802d-0ea9cd534d67)
![image](https://github.com/user-attachments/assets/cbe0a16b-bebb-40b0-a4e6-893e0137bfb2)
![image](https://github.com/user-attachments/assets/b617110b-157a-471e-b00c-0d3e9420a5b3)
![image](https://github.com/user-attachments/assets/fa2673c6-929d-48a7-8e17-87a53541d4f1)

## Filter method:
![image](https://github.com/user-attachments/assets/9bb44b3f-eff9-4582-9663-7ef80797b7f8)
![image](https://github.com/user-attachments/assets/e44b85bf-ab8d-4eaf-bfea-40b2f54a7563)
![image](https://github.com/user-attachments/assets/e2f42589-05ef-463c-be94-668f17f9445d)

## Model:
![image](https://github.com/user-attachments/assets/ea29f6a3-9dff-44c1-84c5-77b2fc62b581)
![image](https://github.com/user-attachments/assets/722e27ab-0ffa-4018-bb8b-aa224f53fdb5)

## Fisher square:
![image](https://github.com/user-attachments/assets/2133ef19-c2b0-4809-b13f-680ca25c1d6e)
![image](https://github.com/user-attachments/assets/6fc86b26-8321-48a3-8c13-6d3cc721f2d6)
![image](https://github.com/user-attachments/assets/8d7a0f62-91a3-4c8a-978f-54729dd1f3f2)

## Anova:
![image](https://github.com/user-attachments/assets/998e3c58-0e4a-43da-a48f-8c95acdc03d9)

## Wrapper method:
![image](https://github.com/user-attachments/assets/5c84fb4c-131b-4c37-b52a-0bcecbcd901f)
![image](https://github.com/user-attachments/assets/e52d69f9-fd6b-4f08-a22f-8a66b0a03201)
![image](https://github.com/user-attachments/assets/5f2f18ef-21da-41a9-9a75-27d43486221a)
![image](https://github.com/user-attachments/assets/39ee3e5d-f3c9-430e-a035-044801a9ec5a)
![image](https://github.com/user-attachments/assets/3257bad1-1d6c-43b4-995c-17f7dacca3ae)

# RESULT:
Thus the program was verified successfully.
