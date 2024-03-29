# Project: Investigate a Dataset - No-show Appointments
* Table of Contents
* Introduction
* Data Wrangling
* Exploratory Data Analysis
* Conclusions

# Question(s) for Analysis
* Which gender missed the highest percentage of appointments?
* Which days of the week have the highest percentage of missed appointments?
* Which age group has the highest percentage of missed appointments?

  ```
  import pandas as pd
  import matplotlib.pyplot as plt
  import numpy as np
  import seaborn as sns
  ```

  ```
  df = pd.read_csv("noshowappointments-kagglev2-may-2016.csv")
  df
  ```

  <img width="1116" alt="Screenshot 2024-02-24 at 12 26 21 AM" src="https://github.com/barnascript/missed_appointments/assets/142545558/ea397654-29c1-4e60-b07e-baa87f0ac4a8">

  ```
  df.shape
  (110527, 14)
  ```

  ```
  df.describe()
  ```

  ```
  # Check info on data such as index, column names, non-null counts, and data types
  df.info()
  ```
  <img width="1112" alt="Screenshot 2024-02-24 at 9 21 36 AM" src="https://github.com/barnascript/missed_appointments/assets/142545558/fa074e26-8103-4237-bf14-7138ef0c6431">


  ```
  df.isnull().sum()
  ```

  Check for the remainer of the code here  ~ https://github.com/barnascript/missed_appointments/blob/main/Missed%20Appointments.ipynb
