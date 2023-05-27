STEPS:
 - 1: Create JsonServer
 - 2: Open NodeJS command prompt
 - 3: Use cd /d to move to JsonServer folder
 - 4: Check version: "npm -v"
 - 5: Create virtual: "npm -init" next next yes
 - 6: Create Json virtual server: "npm install i json-server"
 - 7: New a file .json in folder: "products.json"
 - 8: Run file .json above: "json-server --watch products.json"
	+ Tips:
		- Add one line code in package.json in script: "start": "json-server --watch products.json",
		-> Now, to run file .json above: "npm start"  
		
Guide Postman:
 - GET: get value, show value
 - POST: create new value
	+ Body -> raw -> Json
 - DELETE: delete old value
	+ Params
 - PUT: change value
	+ Body -> x-www-form-urlencoded -> key  
	
Create variable:
 - Project -> Edit -> Variables
	+ How to use that variables: "{{var}}
 - beside:
	+ Create global variable: [Evironment quick look]  
	
Tests:
 - Eg: console.log('gia tri bien', pm.variables.get("demo_url"));
