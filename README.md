# Sorting Line - Standard for Schneider platform
The code deployed here is meant for a standard Sorting Line with the supported options.

## Files
Normally, 2 files exist in the repo:<br>
*	<b>.sta file</b>, Unity Pro Archived File --> back-up of project
*	<b>.stu file<b/>, Unitu Pro File --> project file

In normal circumstances, open the .stu file and proceed to installing step. Otehrwise use .sta file to recover project.

## Installing
Before installing, check if there is an SD-Card inside the PLC, otherwise data will not be retained!<br>
*	Open Virtual Machine "Windows 10 - Schneider M580 Safety"
*	Open "Control Expert"
* 	Unity Pro L: Open project --> .stu/a file from this repo, can be found in PLC
* 	Unity Pro L: PLC --> Set Address --> Ethernet is baler standard: 192.168.1.15
*	Unity Pro L: PLC --> Connect --> try to make connection to PLC (by USB or Ethernet) 
*	Unity Pro L: Once connected --> Transfer project to PLC
* 	Unity Pro L: Click on pop-up windows (differences) on Run and select ok
* 	After downloading code to PLC, data is automatically stored to SD PLC card
<br>
After downloading, the interface in Unity Pro should indicate ONLINE, check if the Card message indicates OK. If not, check the SD-Card.
