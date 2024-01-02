This project analyzes 911 response data from Montgomery County, Pennsylvania, from 2016 until 2019, inclusive.

The list of possibilities for analysis with this dataset is limitless. I decided to choose pointers that I felt would allow for good data-driven operational decisions.

The columns of the main dataset are as follows:
'lat': The lattitudinal coorindates of the call
'lng': The longitudinal coordinates of the call
'desc': the full address, date of call, and time of call, concatenated
'zip': The zip code in which the call occured
'title': Lists the primary call type (i.e. FIRE/EMS/TRAFFIC), followed by the SECONDARY call type (i.e. CARDIAC EMERGENCY)
'timeStamp': The date/time when call was dispatched
'twp': The township in which the call occured.
'addr': The address of the incident
'e': The count of incident. This is "1" for each incident
'calltype': This is the primary call type category of the incident (EMS, FIRE, or TRAFFIC)
'year': The year in which the incident occured
'month': The year in which the incident occured
'day': The day in which the incident occured
'hour': The hour in which the incident occured (0=12:00-12:59 AM, 23= 11:00-11:59 PM)
'date': The date, in format YYYY-MM-DD
'dayofweek' The day of the week (i.e. "Monday" or "Tuesday")
'calltype2': The secondary call type category of the incident (i.e. "CARDIAC ARREST" or "FIRE ALARM")


THE FOLLOWING WILL BE EXPLORED:

-Trend of Call Count Per Year From 2016-2019 (TOTAL, EMS, FIRE, TRAFFIC)

-Most Prevalent Call Categories Overall (most relevant for EMS)

-Most Prevalent Call Categories in Particular Townships (most relevant for EMS)

-Average Daily Call Count By Month Over the Course of a Year (FIRE, EMS, TRAFFIC)

-The Average Number Of Daily Calls By Month Over The Course OF A Year (EMS, FIRE, TRAFFIC)

    - In other words, was a month consistently correlated with higher or lower daily call count?
    - An example might be: Did Traffic incidents increase in the winter months due to bad weather?
    
-Townships With Highest Call Volume (EMS, FIRE, TRAFFIC)

-Average Hourly Call Count Based on the Hour of the Day (All calls, EMS, FIRE, TRAFFIC)

-Average Hourly Call Count Based on the Day of the Week (All calls, EMS, FIRE, TRAFFIC)

-Correlation between Day or hour of week and Specific call type (most relevant for EMS)

  -For instance:
    -Were there were more FALL-related EMS calls during a particular hour of the week? (between 8-9 am on a 
     Sunday?)
    -Were there more OVERDOSE-related calls on Saturdays?
    
-Most prevalent secondary call types in each jurisdiction (most relevant for EMS)
