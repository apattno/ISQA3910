This is the dictionary
# DFD Dictionary

## Entities
**Developer** - Person responsible for all the coding the main software packages and preparing for the license scan.  
**Manager** - Person responsible for the overall project and requests information from the the Package and policy DB's

## Datastores
**NIST Known Vulnerability DB** - Repository of known vulnerabilities maintained by the U.S. Government for checking the software package. **Software Project License and Vulnerability Policy** - Database that contains Policy documents for associated software packages  
**Software Package & License Info** - Database that stores software package, license and vulnerability information.  

## Processes
**Retrieve associated policies for corresponding software project** - Process that retrieves policy request information for corresponding software projects based on Developer and Manager request.  
**Checked for OSS Components** - Process that checks for open source software in the file.  
**Policy documents submitted or modified** - Process where Manager submits or modifies policy documents.  
**Retrieve full list of Projects and Corresponding License Info** - Process that retrieves requested information from the Software Package & License Info per Manager request.  
**Scan for Licenses** - Process that scans for any licenses that can be found in the program.
