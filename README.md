# Job_Specification_Template
Notes on how to specify Engineering Job requirements for communicating to 3D party contractors

## Basic Requirements for Process Control Job Specification

### 1.	Statement of Work
-	List all sensors / valves or other process equipment that need to be controlled.
-	IO or DAQ devices required. – Konrad or Myself can advise as to available options given the above specification. Konrad can also supply DAQ and IO Equipment as part of their quote if you are looking for a turnkey solution.
-	Detail the type of data logging that is required:
o	Which sensors,
o	Recorded/Displayed in which Units,
o	Over which timeframes,
o	Sample rates required,
o	Log File types required.
-	Any specifics regarding the Human Machine Interface, I.E. Which sensor readings should be displayed, what controls should be available for the user. Requirements for safety critical steps like emergency stops.
-	As much detail about the process, or the steps required for the process, including which elements should be manually controlled and when, and which should be automated. A state diagram is an exceptionally useful tool for communicating these requirements, but a written list of process steps may be sufficient depending on the complexity of the process.
-	As much detail as possible regarding any 3D party equipment, Ovens, specialised sensors with their own controllers etc. which will need to interface with the software. Manuals and Driver/Proprietary software delivered with this kind of equipment is invaluable.
-	Specific deliverables required and the timeframe for delivery.

### 2.	Electrical Schematic
-	Myself of Konrad can assist you with this given the list of process equipment that you generate if you are not able to generate this yourself.

### 3.	P&ID Diagram
-	Myself or Konrad may be able to assist with this, but this is not my area of expertise. This diagram is less useful for our purposes of developing the software solution, however it is really useful to establish early a naming convention for the process equipment, as this can be referenced throughout the rest of the specification. E.g. (“Wait for Temp sensor 2 = 30degC then open Valve 3”) Is an example of a clear step in a process that might be automated, it is much easier to coordinate development work if this diagram is created early in the process.

This is the minimum amount of information they will require to be able to generate an accurate quote. I am unable to advise on their costs, you should contact them once we have generated the above information. The methods they use for communicating development timelines should be agreed upon during the quoting process, but your expectations on deliverables should be noted in the statement of work. Depending on the complexity of the project, they may require access to specific equipment and in these cases delays in getting that equipment to them could leads to delays in the timeline for deliverables.

