# py-speed-test-report
A short python script to check internet speeds, runs from cronjob on linux.


### Cronjob
10 * * * * /usr/bin/python /home/pi/code/bandwidth_monitor/speed-test-run.py >> /home/pi/code/bandwidth_monitor/report/speedtest.csv  2>&1
