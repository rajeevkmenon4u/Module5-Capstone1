# Module5-Capstone1(Will the Customer Accept the Coupon?)
This is the first Practical Project Part of AI &amp; ML Course
# Link to the Project ()
## Brief summary of the data provided
  Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the 
  coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor 
   passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?
   Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to 
   them? How would you determine whether a driver is likely to accept a coupon?
## Data Analysis
   ###### Analysing the data and identfying the anamolies/ missing data 
     Below are the list of columns that has maximum missing data
     + car---:12576
     + CoffeeHouse---:217
     + Restaurant20To50---:189
     + CarryAway---:151
     + RestaurantLessThan20:---130
     + Bar:---107
   ###### Graphical Representation
    ![image](https://github.com/user-attachments/assets/8775386f-a448-4b86-a5d4-d1038259f171)
   #### Results / steps for Missing data
       Column Car has the maximum missing data as it is not used anywhere in the analysis we are ignoring the data
       Rest of the columns has the same ratio of missing data, hence it will not impact our analysis
       
       CoffeeHouse:---0.017108
       Restaurant20To50:---0.014901
       CarryAway:---0.011905
       RestaurantLessThan20:---0.010249
       Bar:---0.008436

## Various Scenarios that are considered for Analayis 
# 1. What proportion of the total observations chose to accept the coupon?
###### Analysis-Findings
        
      Y:---coupon	
      0:---0.431567
      1:---0.568433
### Hypothesis      
    Based on the analysis we can see that 57 % accepted and 43% rejected

###### Graphical Representation
# 2. bar plot to visualize the coupon column
###### Analysis-Findings
  
| coupon        | Y             | Coount  |
| ------------- |:-------------:| -----:|
| Bar           | 0             |  1190 |
|               | 1             |   827 |
| Carry out & Take away | 1      |   1760|
|  |   0     |   633|
|  Coffee House	 | 0      |   2001|
| | 1      |   1995|
| Restaurant(20-50)	 |   0     |   834|
|  	 |1      |   658|
| Restaurant(<20) |   1     |   1970|
|  	 |0      |   816|

###### Graphical Representation
![image](https://github.com/user-attachments/assets/a8ec9a5f-24ba-4950-a884-ebc1b8680e02)
![image](https://github.com/user-attachments/assets/f95ac9a5-b627-4c6a-ab54-d624f40a4a0b)

### Hypothesis 
  1. Maximum acceptance is for "coffehouse" and "Resturant<20"
  2. 3rd place if "Carry out & Takeaway"
  3. For CoffesHouse the Rejection rate is also high 

# 3. Use a histogram to visualize the temperature column.
###### Analysis-Findings
  Of the overall coupon data of 12K, Temp 80 contibuties to 6.5k of the data, 4K data for Temp55 and remainik 2k Data to Temp30
     Temperature	
      30	0.531088
      55	0.536719
      80	0.600337

###### Graphical Representation
![image](https://github.com/user-attachments/assets/1f332d0f-d7f1-400a-846f-8ff63cae3b55)
![image](https://github.com/user-attachments/assets/571bbbdd-930a-47d8-8e3e-ae6d861d1230)
![image](https://github.com/user-attachments/assets/29ff00a9-dad1-4244-b10d-17501ed2af3d)
### Hypothesis 
  1. Top 3 acceptance of coupons cateogry ( All temp 80)
      1. Coffee house
      2. Restaurant(<20)
      3. Carry out & Take away "Carry out & Takeaway"
  2. Top 3 Rejection of coupons cateogry
      1. Coffee house - Temp 80
      2. Restaurant(<20)  - Temp 55
      3. Bar - Temp 55
     
# 4. 
###### Analysis-Findings
###### Graphical Representation
### Hypothesis 
# 5. 
###### Analysis-Findings
###### Graphical Representation
### Hypothesis 

## Results / Observation
