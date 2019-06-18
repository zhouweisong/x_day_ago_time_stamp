import dateutil.parser
from datetime import datetime,date,timedelta
import time

def x_day_unix(x):
    date_time_object = datetime.now()+timedelta(days= -x)
    x_day_date_tuple = date_time_object.timetuple()
    x_day_date_second = time.mktime(x_day_date_tuple)
    x_day_date_millisecond = int(x_day_date_second * 1000 + date_time_object.microsecond / 1000)
    return x_day_date_millisecond
