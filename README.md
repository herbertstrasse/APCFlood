# APCFlood

APC Injection technique based off of Sektor7's terrific [Malware Development Intermediate Course](https://institute.sektor7.net/rto-maldev-intermediate).

This script has been modified in the following ways:

* Injects shellcode into the APC queues of multiple threads to increase chances of successful execution 
* Target process defined by the user at command line position 1 (rather than hardcoded)
* Uses CreateProcess to start a new instance of target process, ensuring a target is running

  Compile with included batch script. 
