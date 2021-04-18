# Hoover-application

Minimum Requirement for Running the application
------------------------------------------------
Java 8 is installed and JAVA_HOME is set in environment variables


Instructions to run the Hoover Application
--------------------------------------------
This Application can be run either directly from command prompt or using the .bat file 

1. Run the application directly from command prompt: 
	- In the command prompt browse to the directory where the 'hoover' project is extracted
	- Enter the below command to run the application with input fil. If the input file is absent, a default one will be used.
		java -jar jar/hoover-1.0-jar-with-dependencies.jar <input file path>
		eg: java -jar jar/hoover-1.0-jar-with-dependencies.jar "C:\Sumathi\Interview\hoover\src\main\resources\data\input2.txt"
	
	
2. Running from .bat file using command prompt (either hoover_linux.sh or hoover_win.bat)
	- In the command prompt browse to the directory where the 'hoover' project is extracted
	- execute the .bat or .sh as below 
		C:\Sumathi\Interview\hoover>hoover_win.bat
