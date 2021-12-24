
# Why we need data visualization?

It is an important skill that is used in many parts of the data analysis process and it is used to communicate our data findings.
There is two types of data visualization techniques

## Exploratory data visualization

It generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed.

## Explanatory data visualization 
                                           
These techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

## Project Details
                                                    
### 1.Dataset

I chose the Ford GoBike dataset provided by the Udacity.It has 183412 shared bike's information including start_time, end_time start station id, start station name ,end station id,end station name,bike id,user type,member birth year, member gender, bike share for all trip and other attributes.

### 2.Explore the data

Explore the data through jupyter notebook where the dataset is presented visually and programmatically.

### 3. Document the story

Organized the data findings to convey a story to an audience.

### 4.Communicate the findings

Created the slide deck with data findings to present the story to an an audience.

## Summary of Findings

1.Bike Ride Duration Time: The origianl duration data was skewed to right - bike durations range from less than 1 minute to 1409 minutes with median at around 8.5 min and mean at around 11.73 min. We need to do some data transformation to make data visualization and data analysis easier.I used log transformation.

2.Bike ride trends and User types:

* Thursday, 5:00 PM has the highest biker counts across 7 days, 24 hours.

* As compared to female bikers, Male bikers rented more bikes.

* 8:00 AM and 5:00 PM has the most 'Subscriber' and 'Customer' bikers as compared to other hours.

3.Bike Ride Durations for Different Age Group Across DayofWeek and Hour: 

* By looking at both pointplots , we can tell that there are more younger bikers (age < 40) across 7 days and 24 hours. 

* Bikers (Subscribers) has wide range of age and highest no. of bikers were of 31 years old. Age spread across 40-55 ages.

* Bikers(Customers) are the younger than subscribers and has narrow range of age.Large no. of customers has age of 30 years.

* Subscribers ride much shorter/quicker trips as compared to customers on each day of the week. Both user types have an obvious increase of trip duration on Saturdays and Sundays , especially for customer riders. Subscribers usage seems to be more stable and has very consistent average duration Monday through Friday than customers overall.

## Key Insights for Presentation

1.The distribution of biking durations is skewed. After log transformation and outliner removing, we may visualize and interpret data better.

2.Rush hours,days,user types were analyzed.

3.Common age of bikers were also analyzed.
                                         
