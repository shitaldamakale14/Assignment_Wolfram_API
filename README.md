This is an assignment work
	Wolfram Alpha API spews a lot of schematic output.
	This api is a simple proxy around the Wolfram API.
	It extracts the most relevant data from the result and
	presents it in json or xml formats. 

1 GitHub link 
	https://github.com/shitaldamakale14/Assignment_Wolfram_API.git

2 cd directory

3 npm install to install dependencies 

4 run this using npm start
 
5 To execute in postman 
	GET http://localhost:8000/api/v1/query?input=When was nelson mendela born?&format=xml
	
	Header 
		Authorization: Bearer 01c46413-3cfb-4603-b526-1b4dfebea7d5

  Returns the result for your input query as either json or xml.

