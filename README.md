# cgiProject 
I used Spring Boot and Gradle for this project.   
I developed this project on Intellij Ultimate.  
Front-end should run on localhost:8080   
Back-end runs on localhost:8090 
Open front-end and back-end separately. 
Before trying to run the project should type "npm install" in terminal, 
so that all packeges are installed.
To run back-end. Run Gradle Task bootrun. 
To run front-end. Go to app directory in front end and type command "npm run serve" in the terminal.  
Should definetley Enable Annotation Processing because project uses Lombok. 
When my project calls python script in FileStorageService.java class  in method randomGuesser, 
there is ProcessBuilder that in first argument needs to now path to your python.exe file and 
also where randomGuesser.py script is located on your machine. 
Currently there are my machines paths but they should be replaced. 
Should also watch whether your IDE supports python files. 
In intellij I installed Python plugin and to cgi.main module I added also Python SDK. 

