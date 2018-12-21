#time from seconds
#python 2.7

import time

def secToTime(sec):
    if sec < 60:
        time = "Completed in {} sec".format(int(sec))
        return time
    else:
        minutes = sec//60
        sec = sec - (minutes*60)
        if minutes < 60:
            time = "Completed in {} min {} sec".format(int(minutes), int(sec))
            return time
        else:
            hour = minutes//60
            minutes = minutes - (hour*60)
            time = "Completed in {} hr {} min {} sec".format(int(hour), int(minutes), int(sec))
            return time

start = time.time()

print "hello"
print"this is a test"

end = time.time()
totalTimeSec = (end-start)
totalTime = secToTime(totalTimeSec)
print totalTime

