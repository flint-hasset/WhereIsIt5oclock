# WhereIsIt5oclock
Given your location, calculates where it is 5oclock based on strict longitude (not time zone)
Think of it as 'Solar 5pm'

## This assumes wherever your starting point is has the 'correct time', and all other places on earth have 'true times' based on their global position, rather than their local time zone. 

Known Issues:
1. Cannot be run outside out your current time zone (or whatever datetime.now returns)
2. Returns whatever named place exists on the proper calculated longitude, but searches North first, then South, so not necessarily closest place. 
3. Identifies any named place, not necessarily a city. 
