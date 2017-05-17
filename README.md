# Date-of-birth-assigment
Here is the my Birth of date assignment
import calendar
from datetime import datetime
now=datetime.now()
yenow=now.date()
yean=list(str(yenow))
year=int(yean[0]+yean[1]+yean[2]+yean[3])
age=input('Enter your age: ')
yer=int(year)-int(age)
man=input('Enter the month: ')
dy=input('Enter the date of the month: ')
cal=calendar.weekday(int(yer),int(man),int(dy))
day=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']
month=['january','february','march','april','may','june','july','august','september','october','november','december']
print('You where born on ',day[cal], month[int(man)-1], yer)


