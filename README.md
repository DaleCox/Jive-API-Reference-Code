Jive-API-Reference-Code
=======================

Reference code for Jive API ver 3.3

The code contained in this repository will not compile without a little bit of work, this was done on purpose as the provided code is meant to provide an example on how to interact with the API in C#.  

All reference code should work in .NET 4.0

For the Data Objects, I used the provided JSON object from the API documentation ( https://developers.jivesoftware.com/api/v3/cloud/rest/PersonEntity.html ) and the output from this web site http://json2csharp.com/ to create them. 
	I refactored the objects to make the object more efficient. 
	
For Multipart Form Posts I leveraged code from: http://www.paraesthesia.com/archive/2009/12/16/posting-multipartform-data-using-.net-webrequest.aspx

Link to Jive API Documentation - https://developers.jivesoftware.com/api/v3/cloud/rest/ 
	
The account that was used was not federated. For discussion on the API using .NET please see https://community.jivesoftware.com/docs/DOC-82646