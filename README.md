Monitor OPNsense via API with Zabbix

The current OPNsense template for Zabbix is no longer functional. I am developing a new template that leverages the OPNsense API to retrieve all necessary data. The initial steps involve creating a template that connects to the API and monitors the basic status.

Warning: This version is a very early proof of concept. Do not use it in a production environment!

For those interested in experimenting with this:
	1.	Import the Template: Begin by importing the template into Zabbix.
	2.	Configure Macros: Set the following macros:
	•	$KEY
	•	$ROUTER_URL
	•	$SECRET
To obtain the required values, you need to create an API key in your OPNsense system.
