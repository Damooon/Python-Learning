# This is the practice of date and time

from datetime import datetime
now = datetime.now()
print '%s/%s/%s %s:%s:%s' % (now.month,now.day,now.year,now.hour,now.minute,now.second)
