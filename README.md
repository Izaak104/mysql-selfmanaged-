# mysql-selfmanaged-



•	Log In to Google Cloud Platform (GCP – www.console.cloud.google.com)

•	Select and click on Compute Engine

•	Select and click on VM Instances to begin the process of creating the virtual machine

•	Click on Create Instance

•	Under Name, give your virtual machine a name of your choice, but one that is easily recognizable

•	Under Region and Zone, verify that it shows us-central1(Iowa) and us-central1-a respectively

•	Under machine configuration, ensure that E2 is selected within the drop-down menu

•	Under machine type, select e2-micro to get the most reasonable and affordable price

•	Under Boot Disk, select and click on CHANGE to setup a public image by choosing an operating system for the virtual machine

•	Under operating system, click the drop-down menu and select Ubuntu

•	Under version, select Ubuntu 18.04 LTS

•	Under Boot disk type, make sure it shows “Balanced persistent disk”

•	Click select to complete the public image process and return to creating the virtual machine.

•	Regarding the Identity and API access section

o	Select allow default access under Access scopes
o	Check the box on the left of Allow HTTP traffic and Allow HTTPS traffic respectively
•	Select and click “CREATE” at the bottom of the page to create the virtual machine

•	When the virtual machine is created, click SSH to log unto the virtual machine

•	While in the virtual machine, firstly run the following commands

o	“sudo apt-get update” to ensure that the new virtual machine is up-to-date with the necessary programs needed to run the program.
o	“python3” to determine which version of python is being run on the system
•	Press control + C (Ctrl C) to exit python3

•	Run sudo apt install mysql-server mysql-client (To install MySql)




