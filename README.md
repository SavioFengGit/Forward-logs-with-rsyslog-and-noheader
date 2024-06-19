# Forward-logs-with-rsyslog
Let's see how to forward logs with rsyslog without header

## Introduction of rsyslog
Rsyslog is an open-source utility used in UNIX and Unix-like computer systems to forward log messages over an IP network. In other words, rsyslog is a fast and flexible system for log processing. Initially born as a standard log daemon, it has evolved into a versatile tool capable of accepting input from various sources, transforming them, and sending the results to different destinations. This includes advanced features like filtering and support for TCP and UDP protocols for log message transport.

<br>
<img src="rsyslog.png" width=30% height="auto"><br><br>

## Install rsyslog
Use the command to install rsyslog:
 - sudo apt-get install rsyslog

## Set the file rsyslog.config 
In the /etc/rsyslog.d folder, insert the rsyslog.conf file that you find on this repository

## Restart rsyslog and check the status
 - sudo systemctl restart rsyslog
 - sudo systemctl status rsyslog

<br><br>

#Author
<b>Xiao Li Savio Feng</b>
