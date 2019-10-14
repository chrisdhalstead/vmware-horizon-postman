# vmware-horizon7-postman
Postman Collection for VMware Horizon 7 REST API

10/14/2019

REST API for VMware Horizon 7.10 and later

Documented here: https://code.vmware.com/apis/697/view-rest-api

Enter the following on the Variables Tab:

	Horizon Server FQDN
	
	Username
	
	Password
	
	Domain

Usage:

Import the JSON collection file into Postman - https://www.getpostman.com/

Enter the variables, click update then run the Login request to get the JSON Web Token - you can now run the other requests in the collection until the JWT expires.

Chris Halstead
chalstead@vmware.com
@chrisdhalstead