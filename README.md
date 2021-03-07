# Python_hw1
for part.1, no significant change as the origial code imports the csv file into the list by labeling each data by it's 
weather type. 

Only 2 new lines are added at the end. which is 

```bash
if row['TEMP'] == '-99.000' or row['TEMP'] == '-999.000':
            data.pop()
```

this allows data with false content getting removed from the list.
