# Homebridge example

Homebridge install with example config for using the FritzBox to enable guest wifi on your iOS device.

## supervisord
Homebridge will be run via supervisord. Change paths in supervisor.conf before running it. 
Link supervisor.conf to "/etc/supervisor/conf.d/homebridge.conf". 

## Logs
Logs will be written to log directory. Supervisor will truncate files every 1 MB and keeps 10 backups as configured in supervisor.conf
