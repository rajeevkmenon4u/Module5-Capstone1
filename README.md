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

# 3. 
###### Analysis-Findings
###### Graphical Representation
# 4. 
###### Analysis-Findings
###### Graphical Representation
# 5. 
###### Analysis-Findings
###### Graphical Representation


## Results / Observation
