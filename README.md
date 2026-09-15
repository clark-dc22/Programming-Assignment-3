# Programming-Assignment-3

## Introduction
 This programming assignment focuses on Python Data Analysis (Panda), specifically on loading CSV dataset, selecting rows and columns with the use of indexing, and extracting a specific subset of data without modifying the original data frame. 

## Intended Learning Outcomes
1. load a CSV dataset into a Pandas DataFrame;
2. select rows and columns using positional and label-based indexing;
3. filter records using conditions on a DataFrame column; and
4. extract a well-defined subset of data without changing the source data.

## Problem A: Positional and Label-Based Slicing
a. Display the shape and complete list of column names of cars.
- This code shows the size of the list by displaying the rows and columns of the list and the name of each column in the list.

<img width="512" height="95" alt="image" src="https://github.com/user-attachments/assets/9a7e093c-177b-40e6-b2a4-7507ca790d00" />

- Output:

<img width="707" height="45" alt="image" src="https://github.com/user-attachments/assets/e5310b48-adc9-47cc-9ac8-566c317b4ace" />

b. Using positional slicing, create cars 6 to 10 containing rows 6 through 10 of the dataset, where the first data row is row 1.
- This code prints only cars from 6 to 10 in the dataset.

<img width="233" height="61" alt="image" src="https://github.com/user-attachments/assets/113e58b9-fe19-4ade-81df-d27acf7042b4" />

- Output:

<img width="519" height="179" alt="image" src="https://github.com/user-attachments/assets/b04f54e3-a4d7-4e41-837e-74ca3b31f17d" />

c. From cars 6 to 10, display only the columns Model, mpg, cyl, hp, and gear, in that order.
- This code displays cars from 6 to 10 with specific columns only.

<img width="538" height="62" alt="image" src="https://github.com/user-attachments/assets/ad47b70a-c936-4323-9ef3-a26e9822c1b8" />

- Output:

<img width="252" height="180" alt="image" src="https://github.com/user-attachments/assets/f127cf75-e03f-40f5-bddb-d2f1c8269ca8" />

## Problem B: Model Lookup
Use Boolean indexing on the Model column to answer both requests.

a. Display the complete row for Toyota Corolla.
- This code displays the complete row for Toyota Corolla where it displays only a specific row.
<img width="505" height="61" alt="image" src="https://github.com/user-attachments/assets/b61460db-fde4-4739-912c-4006e78aeb63" />

- Output:

<img width="540" height="54" alt="image" src="https://github.com/user-attachments/assets/6719fb1d-c9fc-4274-8742-e820cfbf4b31" />

b. For Pontiac Firebird, display only Model, mpg, hp, and wt.
Store the two results in toyota and pontiac, respectively. Do not use a hard-coded row number to locate either model.

- This code displays a specific column, Pontiac Firebird, and specific rows which are model, mpg, hp, and wt.

<img width="647" height="70" alt="image" src="https://github.com/user-attachments/assets/f7fd4d2e-03c4-4e1a-ad2b-a57bd59265f0" />

- Output:

<img width="247" height="55" alt="image" src="https://github.com/user-attachments/assets/5d0b0744-29fe-4152-8980-fa5b27bec19d" />

## Problem C: Multi-model Subsetting
Create a DataFrame named selected cars containing only the records for three models: Datsun 710, Lotus Europa, and Ferrari Dino. For these records, retain only Model, mpg, cyl, hp, and gear. Select the rows by their model values rather than by row numbers. Display selected cars and its shape.

- This code displays specific columns which are Datsun 710, Lotus Europa, and Ferrari Dino. It also displays specific rows which are model, cyl, hp, gear.

<img width="486" height="116" alt="image" src="https://github.com/user-attachments/assets/9df7435b-4648-489b-9a32-ddd22318c25a" />

- Output:

<img width="267" height="136" alt="image" src="https://github.com/user-attachments/assets/69174223-b6f7-46dc-84a3-b28aa4dafee3" />







