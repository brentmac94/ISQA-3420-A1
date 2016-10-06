#Data Dictionary

##Entities##
**Developer** - Person responsible for all the coding the main software packages and preparing for the license scan.

**Manager** - Advisor for the software packages. 

##Datastores##
**NIST Vulnerability DB** - Database that contains any known vulnerabilities in the software package.

**Software Project License and Vulnerability Policy** - Database that contains Policy documents for associated software packages

**Software Package & License Info** - Database that stores software package, license and vulnerability information.

##Processes##

**Retrieve associated policies for corresponding software project** - Process that retrieves  policy request information for corresponding software projects based on Developer and Manager request.

**Checked for OSS Components** - Process that checks for open source software in the file.

**Policy documents submitted or modified** - Process where Manager submits or modifies policy documents.

**Retrieve full list of Projects and Corresponding License Info** - Process that retrieves requested information from the Software Package & License Info per Manager request.

**Scan for Licenses** - Process that scans for any licenses that can be found in the program. 

##Data Flows##

**Software Package** - Multiple code files that make up a software. 

**OSS Licenses** - Open Source Software Licenses. These include Open source, MIT, Apache licences, etc.

**Software Package Name** - Name of software package/collection of files.

**Known OSS Vulnerability Issues** - Documented Open Source Software Package vulnerabilities.
 
**Project and Info Request**- Process where manager requests package for corresponding license info. 

**Project, License and Vulnerability Response** - Response to manager for package, license & vulnerability information.

**Project, License and Vulnerability Request** - Request from manager for package, license & vulnerability information.

**Known Vulnerability Issues** -  Data returns any known vulnerabilities in the software package.

**Associated Software Policies** - Software policies that correspond with their respective software projects.

**Software Project Policy Request** - Request associated policy information for respective software projects.

**Updated Policy Document** - Most up to date policy document submitted by Manager.

**Current Policy Document** - Policy that is returned from the Software Project License and Vulnerability Policy database.

**Software Package License and Vulnerability Policy** - Database that stores all Software Project License and Vulnerability Policy information.



