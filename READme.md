# Readme: Quest / Westgate Robotics

## Usage Instructions

### Torque Lesson
1. [torque_segments_no_server_embed.html](https://github.com/roubaix-rider/robotics/blob/main/torque_segments_no_server_embed.html) is the file that will be used in the classroom setting.  The file will be downloaded from a browser using the following URL: [https://htmlpreview.github.io/?https://raw.githubusercontent.com/roubaix-rider/robotics/refs/heads/main/torque_segments_no_local_server.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/roubaix-rider/robotics/refs/heads/main/torque_segments_no_local_server.html).<br><br>
2. [torque_clips.html](https://github.com/roubaix-rider/robotics/blob/main/torque_clips.html) can be used for development and testing.  In particular, to tweak the start and stop times of the video clips used. A local HTTP server needs to be running on your machine to make this work properly.  To run a Python3 web server enter the following Terminal commands (MacOS)...
```sh
  $ python3 -m http.server 8000
```
> Then enter the following on your web browser: 
> [http://localhost:8000/torque_clips.html](http://localhost:8000/torque_clips.html)