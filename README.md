# Temporal_conflicts
## 1. Introduction
Although calendar scenarios are a very common application, and conflicts between events are very often, there is no available dataset of conflicting events and their resolutions. Therefore, we created this dataset -- Temporal_conflicts, which contains 1) events.npy -- the events of five users during one year, and 2) TIs.npy -- the conflicting events and their resolutions.  

## 2. Dataset
### 2.1 User background
Temporal_conflicts invovles 5 participants, including 4 males and 1 female. Table 1 belows gives participant information

### # Table 1. participant information

| User        | Age   |  Sex  |        Profession| Hobbies  |   Educational background| 
| --------   | -----:  | :----:  |      :----:  | :----:  |         :----:  |
|1	|28	|M	|PhD student	    |Movies	     |Postgraduate |
|2	|29	|M	|IT engineer	    |Animation	 |Bachelor|
|3	|33	|M	|SIPI engineer	  |Cooking	   |Bachelor|
|4	|28	|M	|PhD student    	|Basketball	 |Postgraduate|
|5	|20	|F	|College student	|Esports	   |High school|

### 2.2 data  
event = [uuid, event type, activity, start time, duration, flexibility, host, participant, location, periodicity, flag]
ti = [uuid_e1, uuid_e2, temporal class, commuting time, user_action_1, user_action_2, user_action_3, user_action_4]


| User  | No. events   |  No. tis |
| ----  | :-----:  | :----:  | 
|1	|4383	|756	|
|2	|3359	|489	|
|3	|3565	|579	|
|4	|5110	|835	|
|5	|3984	|667	|
