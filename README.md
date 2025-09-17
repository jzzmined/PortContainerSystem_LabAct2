Port Container Management System

A Java console-based program that simulates port operations using stack (for containers) and queue (for ships). It allows storing containers, viewing them, registering arriving ships, viewing waiting ships, and loading containers onto ships.

How to Run the Program

Open a terminal or command prompt.

Compile the program:

  javac PortContainerManagement_LabAct.java

Run the program:

  java PortContainerManagement_LabAct

Example Input/Output

Menu:

=== Port Container Management System ===

[1] Store container (push)
[2] View port containers
[3] Register arriving ship (enqueue)
[4] View waiting ships
[5] Load next ship (pop container + poll ship)
[0] Exit

Sample Run:
Enter Container ID: C001
Enter Description: Electronics
Enter Weight (kg): 2000
Stored: C001 | Electronics | 2000kg

Enter Ship Name: MV Pacific
Enter Name of the Captain: Capt. Cruz
Registered: MV Pacific | Capt. Cruz

Loaded: C001 | Electronics | 2000kg → MV Pacific | Capt. Cruz
Remaining Containers: 0
Remaining Ships Waiting: 0
