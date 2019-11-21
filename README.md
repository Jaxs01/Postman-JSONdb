# Postman-JSONdb
some simple End to End tests with installed Node.js and Postman
//download https://nodejs.org/en/download/ 
//create a db.json .... cmd ->Start server  json-server --watch db.json
{
	"posts": [
		{
			"id": 1,
			"title": "Updated Title",
			"author": "Updated Author"
		}
	],
	"comments": [
		{
			"id": 1,
			"body": "some comment",
			"postId": 1
		}
	],
	"profile": {
		"name": "typicode"
	}
}

//http://localhost:3000/

//E2E ...
get all date in DB
Create a new Record
get Record
change Record
get Record
delete Record
get all date in DB
