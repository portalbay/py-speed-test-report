# py-speed-test-report
A short python script to check internet speed, runs from cronjob on linux.


### Cronjob
10 * * * * /usr/bin/python /home/pi/code/py-speed-test-report/speed-test-run.py >> /home/pi/code/py-speed-test-report/report/speedtest.csv  2>&1
