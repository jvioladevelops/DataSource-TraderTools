# DataSource-TraderTools
A traders best friend application:

EURUSD:

Sunday Open 16:00 - Friday Close 16:00
Closed for 48 hours every week from Friday 16:00 to Sunday 16:00. Open for 5 straight days then closed for 5 straight days not including holidays.

** Correction it looks like the data is closing at 16:00 on Fridays and Opening at 17:00 Sundays but the market goes from 5-5

On the half hour there will be 48 half hour slots every day and 48*5 = 240 half hour slots per week. 
 
If the last time slot for a day is 16:00 then we know it is a weekend. 
If the starting time slot for a day is 16:00 then we know it is a Sunday. 

We should figure out this holiday situation and figure how we can account for that in our data. 

-Writing new code 08/10
*loading in minute data want to write some more code tonight to find max movement in given time frame
I am thinking maybe it will be better if instead of having the max it was a range like the the top 10 max in a 30 day period or something

road blocks
...
Made some changes 

Here we go
