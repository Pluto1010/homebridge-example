# Homebridge example

Homebridge install with example config for using the FritzBox to enable guest wifi on your iOS device.

## supervisord
Homebridge will be run via supervisord.

## Logs
Logs will be written to log directory. Supervisor will truncate files every 1 MB and keeps 10 backups as configured in supervisor.conf

# Install
Install recent version of NodeJS and supervisord.
Run `npm install` inside project directory to download all dependencies listed in `package.json`.
Change paths in supervisor.conf and config.json before running it. See homebridge documentation for details.
Link supervisor.conf to "/etc/supervisor/conf.d/homebridge.conf". 

