**Motion Detection with OpenCV and Twilio WhatsApp Integration**

This project implements a real-time motion detection system using OpenCV in Python. It captures video input from a webcam, detects motion by analyzing frame differences, and provides notifications through audio alerts, visual cues, and WhatsApp messages.

**Features
**
Real-Time Motion Detection: Detects motion in video frames using frame differences and thresholds.

Audio Alert: Plays a sound when motion is detected.

Visual Feedback:

Displays current date and time on the video feed.

Blinking red overlay on motion detection.

Saves screenshots of motion events with highlighted regions.

WhatsApp Notifications: Sends a message via WhatsApp when motion is detected.

Logging: Logs motion detection events, including pixel count and standard deviation, to a file.


- **USAGE**
  
Run the program:

python motion_detection.py

On motion detection:

A red blinking overlay will appear on the video feed.

An audio alert will play.

A WhatsApp notification will be sent.

A screenshot of the motion event will be saved in the motion_output directory.

The event will be logged in motion_output/motion_detection.log.

Press ESC to exit the application.

