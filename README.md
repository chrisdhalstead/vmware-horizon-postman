# vmware-horizon-postman
Postman Collection for VMware Horizon REST API  
*REST API for VMware Horizon 7.10 and later*

## Usage

1. Install Postman from https://www.getpostman.com/
2. Either click the "Run in Postman" button (preferred) or Import the appropriate Postman JSON collection file into Postman 
3. Edit the collection - enter the following on the Variables Tab:

	- Horizon Server FQDN
	- Username
	- Password	
	- Domain
4. Click Update to save the variables
5. Run the Login request to get the JSON Web Token - you can now run the other requests in the collection until the JWT expires.
6. Make sure all requests are set to "Inherit Auth From Parent" under the authorization tab.

## Horizon Versions
Download the collection for your installed version of Horizon

#### Horizon 8 (2111)

- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/11e3fac5415ffa9f73a7?action=collection%2Fimport)
- Note: starting with the Horizon 2111 Collection the server name needs to include /r
- API Documented here:  [https://developer.vmware.com/apis/1189](https://developer.vmware.com/apis/1189)  
  Updated 6/6/22

#### Horizon 8 (2006)

- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/b927097517849cd252a5)
- API Documented here:  https://code.vmware.com/apis/1007  
  Updated 8/11/20

#### Horizon 7.12

- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d39d93044c904d9f1f8a?action=collection%2Fimport)
- API Documented here: https://code.vmware.com/apis/919/view-rest-api  
  Updated 3/17/20


#### Horizon 7.11

- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d39d93044c904d9f1f8a)
- API Documented here: <https://code.vmware.com/apis/732/view-rest-api>  
Updated 12/12/19


#### Horizon 7.10

- Click the following button to run this collection in Postman: [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/0bd9b80c00d4144abb75)
- API Documented here: <https://code.vmware.com/apis/697/view-rest-api>   
  Updated 10/14/19

  

  


## Feedback

Chris Halstead -Senior Staff Technical Product Manager, VMware  
Email: chalstead@vmware.com  
Twitter: @chrisdhalstead