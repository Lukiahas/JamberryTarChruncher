# JamberryTarCruncher
If you work for Jamberry Nails, or have a significant other that does, you probably know what a TAR is. This will take the TAR and tell you your bonus. 

Simply have the Export.csv file in the same folder and run the EXE. Press Enter to exit. It will try to use the newest .csv file in the folder. 

If you're more advanced, you can run it from the command line and give it a file name of another csv file as an argument. In addition you can also pass in a rank you want it to calculate to see possible earnings if you advance one more rank or something. 

Command line usage: JamberryTarCruncher.exe ({file_name} ({rank}))   
	* {file_name} = location of CSV file. eg ExportJuly.csv   
	* {rank} = A number between 1 and 13 where 1 is Consultant and 13 is Elite Executive. 
	
example: JamberryTarCruncher.exe ExportSept.csv 12

Rank:						# to pass in:
Consultant					1
Advanced Consultant			2
Senior Consultant			3
Lead Consultant				4
Senior Lead Consultant		5
Premier Consultant			6
Team Manager				7
Senior Team Manager			8
Executive					9
Senior Executive			10
Lead Executive				11
Premier Executive			12
Elite Executive				13
