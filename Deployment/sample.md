# Crystal Reports Ninja. Version 1.0.0.0
Copyright(c) 2017 Rainforest Software Solution http://www.rainforestnet.com
CrystalReportsNinja Arguments Listing
---------------------------------------------------
-U database login username
-P database login password
-F Crystal reports path and filename (Mandatory)
-S Database Server Name (instance name)
-D Database Name
-O Crystal reports Output path and filename
-E Export file type.(pdf,doc,xls,rtf,htm,rpt,txt,csv...) If print to printer sim
ply specify "print"
-a Parameter value
-N Printer Name (Network printer : \\PrintServer\Printername or Local printer :
printername)
-C Number of copy to be printed
-l To write a log file. filename ninja-yyyyMMddHHmmss.log
---------------------------------------------------

Example: C:\> CrystalReportsNinja -U user1 -P mypass -S Server01 -D "ExtremeDB"
-F c:\test.rpt -O d:\test.pdf -a "Supplier Name:Active Outdoors" -a "Date Range:
(12-01-2001,12-04-2002)"
Learn more in http://www.rainforestnet.com/crystal-reports-exporter/

## test samples

F:\TFS\CrystalReportsNinja\Deployment>CrystalReportsNinja -?

CrystalReportsNinja -D THI -F "C:\Users\ecervantes\Downloads\<CRYSTAL REPORT>" -E <OUTPUT EXTENSION> -a "<VARIABLE NAME: VALUE>" -a "<VARIABLE NAME: VALUE>"





