# OpenCvTimelapse
Camera TimeLapse

Create timelapse from LAN/WIFI/USB cameras.

# Dependencies

OpenCv3.2 (http://opencv.org/)

python-crontab (pip install python-crontab)



# Usage
usage: main.py [-h] -u USERNAME -p PASSWORD -t PROTOCOL -c CAMERAPATH -l
               LENGTH -e EVENTLAST [-n CORRECTION] [-f FPS]

optional arguments:
  -h, --help     show this help message and exit
  -u USERNAME    Camera username
  -p PASSWORD    Camera password
  -t PROTOCOL    Type of stream (ex:rtsp, http)
  -c CAMERAPATH  Camera path (ex:'192.168.1.75/live/ch0')
  -l LENGTH      Length of the output video (in seconds)
  -e EVENTLAST   How long will the event last (in hours)
  -n CORRECTION  How long will the event last (in hours)
  -f FPS         frame per seconds
