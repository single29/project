# project1
python class final project
1. Introduction
 - This project is designed to help maintenance of hundreds of Brocade Fabric Switches inside VMware R&D engineering department.
These switches are spread over 3 datacenters . They connect Storage arrays and thousands of servers. As maintenance of these Fabric switches manually become incredibly time consuming especially during the firmware upgrade that an interactive response is needed.
 
2. Requirements
 - Need these module: Fabric, paramiko, pexpect. Csv.

List all the Python modules that need to be installed. If some of these modules need a specific version, please indicate so. You can also list any other conditions that are needed to run the program.
 
 
3. Description of the Python program.
#1
Based on the decision which firmware version we need for our switches, the python program check every switch and put their hostname/IP and firmware version in a csv file.
#2
Set up proper firmware repository and download the target version.
#3
Modify the Python program to point to the right file
#4
Use paramiko or pexpect module to interactively answer the questions such as Yes/No in the middle of the upgrade, and report the error back should the upgrade process get stuck


 
 
4. Screenshots of the program output  - If you are using a specific hardware and cannot obtain screenshot, please enclose appropriate photographs
 
 
5. Conclusion -  Describe in brief the problem you solved, the program you wrote and obtained output.
 
 
6. Python program  - If the program is one file, please add it as one of the pages in the report. If the code is large and spans more than one file, enclose a separate zip file.
