# FIRE-DETECTION-USING-WSN

# Abstract
Fire detection systems are currently the most crucial element of any building design. Recently, there have been numerous
reports of fire incidents. This may frequently be the outcome of carelessness on the part of people. Consider a few instances, such as
petrol stations, cracker shops, residences, and primarily workplaces,
etc. Approximately 4,000 fire accidents are reported in a single year.
This work introduces a fire sensor-based automatic fire detection
system after accounting for all of these aspects. Our suggested
solution operates differently than the current fire detection system,
which locates the fire using a fire sensor. The current systems
contain fire alarms and warnings that sound an alarm when a fire
is discovered in a small area.The suggested system has a fire alarm,
notifies us via our mobile devices, and enables mail to be sent to an
email address that is attached. This mail will contain details about
the accident-prone location as well as the information needed to
alert the fire station of the incident. This fire detection system will
be more reliable and safe when compared to the current
conventional fire alarm systems.
# INTRODUCTION
The Internet of Things (IoT) is a network made up of
physical devices with sensors built in and connected to a
cloud where data is transferred with the aid of a gateway,
which makes it easier for data connected over the internet to
communicate. Early warnings from fire detection systems
are intended to allow for a safe exit of residents or visitors
from the building. Protection of the safety of emergency
response personnel is greatly aided by early discovery.
Because management efforts are started while the fireplace
is still small, there will be less property loss and a shorter
time required for the operation. In this project, we made use
of a few sensors to alert people to the fire and get them to act
before any damage is done.

# PROPOSED SYSTEM
1. Online Simulation :
It includes an Arduino Board at the Control/Monitor
room, and a remotely located Arduino Board in the forest.
Gas and temperature sensors detect conditions and pass
values to the remote Arduino, which routes the data to the
Monitor room. If the fire is localised, a Fire Warning at said
location is issued; if the fire is widespread, a High Risk Alert
is issued along with a fire alarm. Includes PIR sensors to
warn life forms to keep away ONLY in case of danger.
2. Implementation using hardware:
The fire detector and alarm project uses a fire sensor to
detect fire and instantly sound an alarm once detected. It
uses temperature sensor, PIR sensor, Ultrasonic sensor etc to
detect fire causing elements nearby and it will measure the
distance between the fire to the sensor. When the fire or
cautious smoke is detected, the sensors used here become
alert and it will switch on the buzzer to notify nearby people
in an apartment or home or organisation. It also switches on
the DC motor connected using the relay switch which it
makes to spray the water on the fire using the DC pump
motor. The overall real-time data of every second will store
into the Thingspeak cloud which we connected using Node
MCU (ESP8266) wifi module. We can see all the data there
by graphs for each of the sensors.

# Implementation using hardware:
This is an automated fire detection system, which on
detecting fire, will take proactive measures of alerting the
respective personnel, in addition to raising the alarm like a
conventional fire detection system. It is implemented using
the components like Node MCU, Fire sensor Buzzer. All
components are interfaced with the NodeMCU and works by
automation as per uploaded code. When fire is detected
within the deployed area, the notification regarding the fire
accident will be sent on our mobile screen, with the
specifications of the accident location will be sent to the fire
station along with the alarm buzzing, alerting the people
around. With this system, we can overcome the problem
which is in the existing system. The fire sensors are
deployed in small black boxes around the space to be
monitored. If any fire is detected by the sensor, it sends the
information to the Nodemcu.
