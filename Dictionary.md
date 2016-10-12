This is the dictionary
# DFD Dictionary

## Entities
**Developer** - Person responsible for all the coding the main software packages and preparing for the license scan.    
**Manager** - Person responsible for the overall project and requests information from the the Package and policy DB's

## Datastores
**NIST Known Vulnerability DB** - Repository of known vulnerabilities maintained by the U.S. Government for checking the software package.  
**Software Project License and Vulnerability Policy** - Database that contains Policy documents for associated software packages.    
**OSS Package License and Vulnerability Database** - Database that stores software package, license and vulnerability information.    

## Processes
**Manage Software Packages** - Process that handles the software packages submitted by developer and prepares them for license scanning. Also checks NIST DB for vulnerabilities. Returns information to developper and OSS Package Database.  
**Scan for Licenses** - Process that scans submitted software for OSS licenses.  
**Retrieve Full Software Package & License Information** - Process that retrieves all software and license information for a packags. Can be requested by the Manager or Developer.   
**Retrieve All Policy Documents for Current Project** - Process where Manager or Developer requests OSS policy documents for current project.    
**Modify or Add to OSS Policy Documents DB** - Process where Manager submits to contripute or modify OSS policy documents.    
 
## Data Flows
**Software Package** - The package of OSS software that the Developer submits for scanning.  
**Software Package Name** - How the software package can be identified  
**Known Software Vulnerabilities Results** - Information submitted from NIST regarding known vulnerabilities in a software Package.  
**Software Package License Results** - Results of scan for license for this particular software package.  
**Software Package License & Vulnerability Results** - Information for OSS software license and vulnerability checks that is submitted to database  
**Request OSS Package Licenses and Vulnerability for Project** - A request from a manager or a developer to the OSS Package Database for information on License and vulnerbility  
**Results of Request for License and Vulnerability for Project** - Information returned to the Developer or Manager from the request submitted to OSS Database.  
**Project Policy Document Request** - Request from a Manager or Developer for the policy documents regarding the software project, sent to the OSS Policy Document Database.  
**Results of OSS Policy Document Request** - The results concerning the policy documents of a software package, retrieved through a query to the OSS Policy Document Database.
**Request to Modify Policy Documents** - 
