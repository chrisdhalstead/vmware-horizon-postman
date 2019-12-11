# vmware-horizon7-postman
Postman Collection for VMware Horizon 7 REST API

12/12/2019

REST API for VMware Horizon 7.10 and later


## Horizon 7.11


- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/de27a9ea33f1752e6092)
- Documented here: [https://code.vmware.com/apis/732/view-rest-api](url)


## Horizon 7.10


- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0bd9b80c00d4144abb75)
- Documented here: [https://code.vmware.com/apis/697/view-rest-api](url)



## Usage:

1. Install Postman from https://www.getpostman.com/

2. Either click the "Run in Postman" button (preferred) or Import the appropriate JSON collection file into Postman 

3. Edit the collection - enter the following on the Variables Tab:

	- Horizon Server FQDN
	- Username
	- Password	
	- Domain

4. Click Update to save the variables

5. Run the Login request to get the JSON Web Token - you can now run the other requests in the collection until the JWT expires.

## Feedback


Chris Halstead  
chalstead@vmware.com  
@chrisdhalstead
