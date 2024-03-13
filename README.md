# KINETIC-Implementation

As a Part of Kinetic Implementation Team, Upgraded Epicor ERP From E10 to KNETIC.

**Screen UI Fixes :**

Since Epicor Introduced New UI Fields in Kinetic and DB Fields , this caused Overlap in the Exisiting Customization.

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/5cf55e41-6f1d-41f3-86e0-5a9eefe2ec57)
* Created  a New Customization on top of previous Customization Layer.
* Re-Aligned the Fields.

**RMA Dispositon Automation:**

Automated the  RMA Transaction to Scrap the part using DMR Dispositions and update the SerialNumber status to be scrapped.

1.Created  a New RMA Disposition.
2.New DMR Actn.
3.Updated the SerialNumber Transaction.

**High-Level Design:**

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/ac258b57-40a8-4231-a240-82f3d953ebb3)

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/3e1295c5-5612-4cdb-ba06-e108f32fda16)

**Leveraged KINETIC Functions for Automation:**

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/1b9db631-5f06-4e86-9e9c-85579cec7f01)
![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/006807bb-d629-4145-ac7a-2b330d20ba61)




**ShipHold:**

purpose of these ship holds is to prevent a specific Part number, Lot number, or Serial Number/range of serial numbers from being shipped to one or more particular country(s). 
A ship hold may be implemented at any time, although an upcoming hold is typically known days or weeks in advance. 

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/86e4924d-dca5-4340-a997-207705d9b077)


**Lookup Table:**

used Lookup Table to store the Information of the parts,countrynum that needs to be blocked during the shipment.

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/5a8c2d79-5249-41c8-8c6f-24ea7ab9d89f)


**MethoDirective:**:
1.Used Conditional Widgets
2.Variables
3.Linq queries
4.Exception Message 
5.DropShip

![image](https://github.com/MuraliDharanGopalakrishnan/KINETIC-Implementation/assets/102019076/7aa83346-c462-4fb7-bcb1-37a7c623a0e6)




