# JamberryTarCruncher
If you work for Jamberry Nails, or have a significant other that does, you probably know what a Team Activity Report (TAR) is. This will take the TAR and tell you your bonus. 

Simply download your TAR and the JamberryTarCruncher.exe file and have them in the same folder and double click on the JamberryTarCruncher.exe file. Press Enter to exit. It will try to use the newest .csv file in the folder. 

To Download your TAR, go to "Volume & Earnings" and click "Team Activity Report".  Be sure you select the month you want and "Entire Downline" for the "Number of Downline Levels to Display". Then click "Export to Excel/CSV".

Supported OSs: Windows, (Darwin) Mac OSX, Linux, and FreeBSD. Simply download the one you need for your system.

If you're more advanced, you can run it from the command line and give it a file name of another csv file as an argument. In addition you can also pass in a rank you want it to calculate to see possible earnings if you advance one more rank or something. 

Command line usage: JamberryTarCruncher.exe ({file_name} ({rank}))   
	* {file_name} = location of CSV file. eg ExportJuly.csv   
	* {rank} = A number between 1 and 13 where 1 is Consultant and 13 is Elite Executive. (See below)
	
example: JamberryTarCruncher.exe ExportSept.csv 12

#### Discaimer:
The amount that this program returns is an estimateion. Your actual payout will differ. 
The Fast Start Bonus (FSB) seems to be the biggest delta. When trying to cacluate the correct FSB, the program needs to know who is in their Fast Start period and the TAR does not always list that value correctly. ("Type" Column [AB] in the TAR)

---

Rank: | # to pass in:
--- | ---
Consultant | 1
Advanced Consultant | 2
Senior Consultant | 3
Lead Consultant | 4
Senior Lead Consultant | 5
Premier Consultant | 6
Team Manager | 7
Senior Team Manager | 8
Executive | 9
Senior Executive | 10
Lead Executive | 11
Premier Executive | 12
Elite Executive | 13
